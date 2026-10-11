# 主页维护

这是 `MIAOKATZE/MIAOKATZE` 的公开 GitHub Profile README。根目录的 `README.md` 显示在个人主页。

布局为矮横幅、个人主页入口、三列模组展示及一段 Star 邀请。详细模组宣传由 https://miaokatze.com/ 承载。

## 当前素材与尺寸

- `assets/profile/brand.svg`：新设计的猫猫工坊横幅，600 × 108，README 中显示宽度为 520px。
- `assets/profile/homepage.svg`：个人主页胶囊按钮，280 × 42，显示宽度为 260px。
- `assets/profile/star-*.svg`：青、紫、铜金三色 Star 按钮，136 × 30，显示宽度均为 120px。
- `assets/gt-*.png`：三个模组原有标题图，保持原图与透明背景，显示宽度均为 180px。
- `assets/` 下其余旧装饰素材保留，当前 README 不再引用。

## 内容维护

- 头图与个人主页按钮均链接到 https://miaokatze.com/，入口保持在模组展示之前。
- 使用一个 HTML 表格，第一行只放三个项目标题图，第二行放对应的简介、下载、Wiki、反馈与 Star 入口。标题图保持同一排；移动端允许横向滚动。
- 标题图、项目名称与 Star 按钮进入对应仓库。Star 按钮不能直接替访客标星，说明需点击 GitHub 原生 Star。
- 项目简介以各项目 README 为准；兼容版本与发行版本不在主页重复维护。
- SVG 使用自包含图形，不引入脚本、外部字体或远程图片。README 使用 GitHub 支持的 HTML 属性，不依赖自定义 CSS。

## 验收

检查 Markdown / HTML 结构、SVG 解析、图片路径与显示尺寸。核对个人主页、仓库、Releases、Wiki 和 Issues 的链接。使用 GitHub Markdown 渲染结果确认表格保留三列、三张标题图位于同一行，且按钮仍为可点击链接。发布后如可用，检查 GitHub 页面实际显示与移动端横向滚动。
