# Color Pick Master 🎨

<div align="center">

![Color Pick Master Icon](https://github.com/muscccm/Color-Pick-Master/blob/main/PixPin_2025-06-27_02-47-07.png?raw=true)

**一个强大的图片配色提取工具**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![PyQt6](https://img.shields.io/badge/PyQt6-6.0+-green.svg)](https://www.riverbankcomputing.com/software/pyqt/)

</div>

## 📖 简介

Color Pick Master 是一个专业的图片配色提取工具，采用先进的 K-means 聚类算法，能够智能识别图片中的主要颜色并生成精美的配色方案。无论您是设计师、开发者还是艺术爱好者，这款工具都能帮助您快速获取图片的颜色信息，提升工作效率。

## ✨ 主要功能

### 🎯 核心功能
- **智能颜色提取**：使用K-means聚类算法精准提取图片主要颜色
- **多格式支持**：支持PNG、JPG、JPEG、GIF、BMP、TIFF、WEBP、ICO等多种图片格式
- **实时颜色预览**：悬停即可查看颜色的HEX、RGB值和占比信息
- **一键颜色复制**：点击复制HEX值，按住Shift点击复制RGB值
- **配色数量可调**：支持提取3-15种主要颜色

### 🚀 高级功能
- **批量处理**：同时处理多张图片，提高工作效率
- **配色板导出**：将提取的颜色导出为精美的配色板图片
- **拖拽导入**：支持直接拖拽图片文件到程序窗口
- **选择性导出**：可选择特定图片进行配色导出
- **主题切换**：支持暗色/亮色主题，适应不同使用环境

### 🎨 用户体验
- **现代化界面**：采用PyQt6构建的现代化用户界面
- **响应式设计**：界面自适应不同屏幕尺寸
- **智能提示**：详细的操作提示和状态反馈
- **无损处理**：所有操作不会修改原始图片文件

## 🖼️ 软件界面

![Color Pick Master 界面展示](https://github.com/muscccm/Color-Pick-Master/blob/main/PixPin_2025-06-27_02-46-58.png?raw=true)

## 🔧 安装与使用

### 系统要求
- Windows 10/11
- 无需安装Python环境（独立可执行文件）

### 快速开始
1. 下载最新版本的 `Color Pick Master.exe`
2. 双击运行程序
3. 拖拽图片到程序窗口或点击"上传图片"按钮
4. 悬停在颜色条上查看颜色信息
5. 点击颜色条复制颜色值
6. 选择图片后点击"导出配色"生成配色板

### 详细操作指南

#### 📥 导入图片
- **方法一**：直接拖拽图片文件到程序窗口
- **方法二**：点击"上传图片"按钮选择文件
- **支持格式**：PNG、JPG、JPEG、GIF、BMP、TIFF、WEBP、ICO

#### 🎨 颜色操作
- **查看颜色信息**：将鼠标悬停在颜色条上
- **复制HEX值**：左键点击颜色条
- **复制RGB值**：按住Shift键 + 左键点击颜色条
- **调整颜色数量**：在右下角选择3-15种颜色

#### 📊 选择与导出
- **选择图片**：点击图片进行选中/取消选中
- **全选操作**：点击"全选"/"取消全选"按钮
- **导出配色**：选择图片后点击"导出配色"按钮
- **保存位置**：选择文件夹，程序将自动生成配色板文件

## 🎯 使用场景

### 🎨 设计师
- **网页设计**：提取网站主题色彩
- **UI设计**：获取应用界面配色方案
- **平面设计**：分析优秀作品的色彩搭配
- **品牌设计**：提取Logo和品牌形象的主要颜色

### 💻 开发者
- **前端开发**：快速获取设计稿的准确颜色值
- **主题开发**：分析流行应用的配色方案
- **CSS样式**：直接获取可用的颜色代码

### 🎭 艺术爱好者
- **色彩分析**：学习大师作品的用色技巧
- **搭配灵感**：从喜欢的图片中获取配色灵感
- **作品创作**：为绘画、摄影作品寻找色彩参考

## 🛠️ 技术特性

### 核心算法
- **K-means聚类**：采用scikit-learn的K-means算法进行颜色聚类
- **智能优化**：自动缩放图片以提高处理速度
- **精确计算**：准确计算每种颜色的占比

### 技术架构
- **GUI框架**：PyQt6 现代化界面框架
- **图像处理**：PIL/Pillow 强大的图像处理库
- **数据处理**：NumPy 高效的数值计算
- **机器学习**：scikit-learn 专业的聚类算法

### 性能优化
- **多线程处理**：避免界面卡顿，提供流畅体验
- **内存优化**：智能管理图片内存占用
- **批量处理**：高效处理多张图片

## 📋 更新日志

### v1.2.0 (最新版本)
- ✨ 新增批量处理功能
- ✨ 新增配色板导出功能
- ✨ 新增主题切换功能
- 🔧 优化颜色提取算法
- 🔧 改进用户界面体验
- 🐛 修复已知问题

### v1.1.0
- ✨ 新增Shift+点击复制RGB功能
- ✨ 新增拖拽导入支持
- 🔧 优化颜色显示效果
- 🔧 改进错误处理机制

### v1.0.0
- 🎉 首个正式版本发布
- ✨ 基础颜色提取功能
- ✨ HEX颜色复制功能
- ✨ 现代化用户界面

## 💖 支持作者

如果这个工具对您有帮助，欢迎支持作者继续开发更多实用工具！

### 💳 打赏方式

<div align="center">

#### 微信支付
<img src="https://github.com/muscccm/Excel-Column-Extraction-Tool/blob/main/WC.png?raw=true" width="200" alt="微信支付二维码">

#### 支付宝
<img src="https://github.com/muscccm/Excel-Column-Extraction-Tool/blob/main/AP.png?raw=true" width="200" alt="支付宝二维码">

#### PayPal
[点击这里通过PayPal支持](https://paypal.me/muscccm?country.x=C2&locale.x=zh_XC)

</div>

您的支持是我继续创作的动力！💪

## 📝 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 🤝 贡献

欢迎提交问题和功能请求！如果您想贡献代码，请先创建一个 issue 讨论您想要添加的功能。

## 📧 联系方式

如有问题或建议，请通过以下方式联系：
- 创建 GitHub Issue
- 通过打赏页面留言

---

<div align="center">

**让颜色提取变得简单而美好** ✨

Made with ❤️ by muscccm

</div> 

