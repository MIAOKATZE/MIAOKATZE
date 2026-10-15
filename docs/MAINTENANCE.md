# 主页维护

这是 `MIAOKATZE/MIAOKATZE` 的公开 GitHub Profile README。根目录的 `README.md` 显示在个人主页。

布局为简短介绍、个人主页按钮、四张并排的模组卡片及一段 Star 邀请。详细模组宣传由 https://miaokatze.com/ 承载，不使用顶部装饰横幅。

## 当前素材与尺寸

- `assets/profile/homepage.svg`：个人主页主按钮，280 × 42，显示宽度 260px。
- `assets/gt-*.png`：四个模组原有标题图，保持原图与透明背景，统一显示高度 60px，宽度按原始比例缩放；猫猫蓝图来自 `GT-Miao-Blueprint/README/GTMB.png`。
- `assets/profile/project-*.svg`：项目仓库按钮，176 × 30，显示宽度 176px。
- `assets/profile/action-download.svg`、`action-wiki.svg`、`action-issues.svg`：四个项目共用的下载、Wiki 与反馈按钮，54 × 26。
- `assets/profile/star-*.svg`：四色 Star 按钮，176 × 28，显示宽度 176px。
- 青色、紫色、铜金色、蓝色分别对应无线电网、趣味道具、蒸汽重生和猫猫蓝图；项目仓库按钮使用深色背景，Star 按钮使用对应的浅色背景。
- 旧横幅及其余未引用的装饰素材保留，无需在文案更新时修改。

## 内容维护

- 个人主页按钮保持在模组展示之前，链接到 https://miaokatze.com/。
- 使用一个只有一行、四个单元格的 HTML 表格，每列宽度为 25%，每个单元格容纳一张完整的模组卡片。简介使用正文大小的 `span`，单元格使用 `nowrap="nowrap"`，保持简介和操作按钮不换行，并为标题图及按钮保留足够宽度。四张标题图同排，单元格顶部对齐；窄屏允许表格横向滚动。
- README 中所有超链接均由 SVG 按钮承载。标题图作为静态展示，不链接到仓库。
- 项目按钮与 Star 按钮进入对应仓库。下载、Wiki、反馈按钮分别链接到 Releases、Wiki 和 Issues。
- 猫猫蓝图未启用 GitHub Wiki，其 Wiki 按钮链接到项目 README 提供的完整指南 https://miaokatze.com/wiki?mod=gtmb。
- Star 按钮不能直接替访客标星，页尾说明需点击 GitHub 原生 Star。
- 项目简介以各项目 README 为准；兼容版本与发行版本不在主页重复维护。
- SVG 使用自包含图形，不引入脚本、外部字体或远程图片。README 使用 GitHub 支持的 HTML 属性，不依赖自定义 CSS。

## 验收

检查 Markdown / HTML 结构、SVG 解析、图片路径及显示尺寸，确认所有链接都包含按钮图片。核对个人主页与各项目的仓库、Releases、Wiki 或完整指南、Issues 目标地址。检查 GitHub 渲染结果保留一行四列、四张标题图和各自按钮；如浏览器可用，检查实际显示与窄屏横向滚动。
