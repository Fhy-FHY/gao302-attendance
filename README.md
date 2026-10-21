# 高三2组出勤表

移动端优先的班级考勤单页应用，纯静态 HTML，无需后端。

## 功能

- 卡密门禁（默认卡密 `2008`，在 `index.html` 的 `KEYS` 数组中修改）
- 日期切换、按日期记录考勤（出勤 / 迟到 / 请假 / 缺席）
- 实时统计：应到、出勤、迟到、请假、缺席
- 姓名搜索、全部出勤、清空今日、重置预设名单
- 导出 Excel（.xlsx，纯前端生成）与 CSV
- 数据保存在浏览器 localStorage，关闭页面不丢失

## 本地预览

双击 `index.html`，或：

```bash
python -m http.server 8080
# 打开 http://localhost:8080
```

## 线上地址

GitHub Pages：本仓库 Settings → Pages 已开启，访问地址见仓库描述。

## 修改名单

编辑 `index.html` 中的 `NAMES` 数组，或在页面上直接增删改后刷新。
