# Trae Theme

一个为VS Code设计的主题，基于Trae编辑器的配色方案。

## 特点

- 🌙 暗色主题 - 舒适的深色背景配合精心调配的语法高亮
- ☀️ 亮色主题 - 清晰的浅色背景适合日间使用
- 🎨 精确的语法高亮 - 完美还原Trae编辑器的代码配色
- 🎯 优化的对比度 - 确保长时间编码的舒适度

## 安装

有两种安装方式：

1. 从VSIX文件安装：
   - 下载最新的`trae-theme-x.x.x.vsix`文件
   - 在VS Code中，选择"从VSIX安装..."
   - 选择下载的文件进行安装

2. 从源码安装：
   ```bash
   git clone https://github.com/xiaoguan521/trae-theme.git
   cd trae-theme
   vsce package
   code --install-extension trae-theme-x.x.x.vsix
   ```

## 使用

1. 打开VS Code的命令面板 (Ctrl+Shift+P / Cmd+Shift+P)
2. 输入"颜色主题"并选择"首选项：颜色主题"
3. 选择以下主题之一：
   - "Trae Dark" - 暗色主题
   - "Trae Light" - 亮色主题

## 版本历史

- 1.1.0
  - 添加亮色主题支持
  - 优化包大小
- 1.0.0
  - 首次发布
  - 实现暗色主题

## 贡献

欢迎提交Issue和Pull Request来帮助改进这个主题。

## 许可

MIT License - 查看 [LICENSE](LICENSE) 文件了解详情。 