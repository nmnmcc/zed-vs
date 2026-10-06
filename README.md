# Visual Studio Theme for Zed

将 **Visual Studio IDE** 的配色带到 Zed。这个插件提供 Visual Studio 风格的 **Dark** 和 **Light** 两套主题，包含编辑器、解决方案侧栏、标签栏、面板、状态栏、终端、差异视图和语法高亮。

配色取自 Visual Studio 的 IDE 色彩语义：深色主题使用 Visual Studio 常见的蓝色关键字、青绿色类型、黄色方法、橙色字符串和绿色注释；浅色主题使用 Visual Studio 的经典蓝色关键字、红色字符串和绿色注释。主题文件是 Zed 原生格式，不依赖其他编辑器主题或扩展。

## 安装

1. 将此仓库作为本地扩展安装，或在 Zed 的 Extensions 面板中安装发布后的 **Visual Studio Theme**。
2. 打开命令面板（`cmd-shift-p` / `ctrl-shift-p`），执行 **theme selector: toggle**。
3. 选择 **Visual Studio Dark** 或 **Visual Studio Light**。

本地开发时，可在 Zed 中使用 `zed: install dev extension`，然后选择此仓库目录。

## 主题细节

- **Visual Studio Dark**：以 VS 2019/2022 深色 IDE 为基准，编辑器背景 `#1E1E1E`，状态栏使用 Visual Studio 蓝 `#007ACC`。
- **Visual Studio Light**：以 Visual Studio Light IDE 为基准，编辑器背景 `#FFFFFF`，工具窗背景 `#F3F3F3`，焦点蓝 `#0066BF`。
- 为适配 Zed 的蓝色状态栏，按钮选中时使用深色主题白色、浅色主题黑色的强调色，悬停、按下和选中背景采用中性灰。Zed 的按钮文字和图标共用全局强调色，因此其他强调文字和图标也会使用这些颜色。
- 两套主题都包含完整的 ANSI 终端色板、Git 状态色、诊断色、协作光标，以及 Zed 的 bracket/document highlight。

## License

本仓库使用 [Unlicense](https://unlicense.org)，将主题适配代码尽可能释放到公共领域，允许自由使用、修改、发布和再分发。
