# 湖院实验通 (HZC LibTong)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Chrome-red.svg)

> 专为湖州学院实验室准入考试设计的题库搜索工具

## 01 功能简介

湖院实验通是一款Chrome扩展，可在指定网站上提供悬浮式题库搜索功能，帮助用户快速查找实验室安全准入考试的相关题目和答案。

### 核心功能

- **智能搜索**：支持关键词模糊匹配，实时显示题目、选项和答案
- **自动提取**：可自动识别当前页面题目并搜索答案
- **快速刷题**：自动随机选择答案并跳转下一题
- **自动考试**：自动匹配题目并选择正确答案
- **简洁界面**：现代化设计，提升用户体验

## 02 安装步骤

1. 下载项目到本地 ([点我快速下载](https://github.com/Whale-Yu/HZC-LibTong/releases/download/V1.0/HZC_LibTong.zip))
2. 打开 Chrome 浏览器，进入 `chrome://extensions/`
3. 开启开发者模式
4. 点击"加载已解压的扩展程序"
5. 选择项目中的 `HZC_LibTong` 文件夹（至最里面的文件夹为止）

注：edge浏览器步骤类似
## 03 使用方法

1. 访问目标网站: `https://zysys.zjhzu.edu.cn/`
2. 页面右上角会出现悬浮窗
3. 输入关键词进行搜索，或使用自动功能



## 04 技术架构

- 基于 Chrome Extension Manifest V3
- 使用 JavaScript、HTML 和 CSS 实现
- JSON 格式存储题库数据

## 05 项目结构

```
HZC_LibTong/
├── HZC_LibTong/           # Chrome扩展主目录
│   ├── manifest.json      # 扩展配置文件
│   ├── content.js         # 主要功能实现
│   ├── floating.css       # 悬浮窗样式
│   ├── questions.json     # 题库数据
│   ├── instructions.html  # 使用说明
│   └── icon.png           # 扩展图标
└── README.md              # 项目说明文档
```

## 06 免责声明

本扩展仅用于教育目的，帮助学生复习实验室安全知识。 请遵守相关法律法规和学校规定，合理使用本工具。


## 07 支持与反馈

如果您发现任何问题或有改进建议或者题库更新，请联系开发者：
- 蟹老板 (v：tinyfisher19)

## 08 打赏支持

如果本工具对您有帮助，欢迎打赏支持开发：
![img.png](img.png)

## 09 参考

本项目多选题的逻辑参考了以下开源项目，感谢原作者的开源贡献：
- [湖州学院实验室准入考试辅助脚本](https://gitee.com/himwei/huzhou-university-laboratory-test)

## 10 许可证

本项目采用 MIT 许可证，详情请参见 [LICENSE](LICENSE) 文件。
