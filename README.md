# Rime 输入法配置

个人Rime配置集合，包含虎码（Tiger/Tigress）和魔然码（Moran）两种高效的形码输入法方案。

## 📋 项目概述

这是一个基于Rime输入法引擎的个性化配置项目，主要包含：

- **虎码输入法**：高效的中文形码输入方案
- **魔然码输入法**：基于自然码的双拼+形码辅助输入方案
- 丰富的词库和个性化配置

## 🚀 快速开始

### 安装要求

- Rime输入法引擎（小狼毫、鼠须管等）
- 支持Rime的操作系统（Windows/macOS/Linux）

### 部署步骤

1. 将本仓库克隆到Rime用户配置目录
2. 重新部署Rime输入法
3. 选择需要的输入法方案

## 📁 项目结构

```
Rime/
├── default.custom.yaml      # 默认配置，启用所有输入法方案
├── user.yaml                # 用户个性化设置
├── weasel.yaml              # 小狼毫外观配置
├── tiger/                   # 虎码相关配置
│   ├── tiger.schema.yaml    # 虎码方案定义
│   ├── tiger.dict.yaml      # 虎码词库
│   └── tiger.custom.yaml    # 虎码个性化配置
├── tigress/                 # 虎码变体配置
│   ├── tigress.schema.yaml
│   ├── tigress.dict.yaml
│   └── tigress.custom.yaml
├── moran/                   # 魔然码配置
│   ├── moran.schema.yaml   # 主方案
│   ├── moran_aux.schema.yaml # 辅助方案
│   ├── moran_fixed.schema.yaml # 固定方案
│   ├── moran_bj.schema.yaml   # 北京方案
│   ├── moran_sentence.schema.yaml # 句子方案
│   └── 多个词库文件
├── lua/                     # Lua脚本扩展
│   ├── moran.lua           # 魔然码核心逻辑
│   ├── calculator_translator.lua # 计算器功能
│   └── 其他功能脚本
├── opencc/                  # 简繁转换配置
├── icons/                   # 输入法图标
└── etc/                     # 其他资源文件
```

## 🔧 可用输入法方案

### 虎码系列
- **tiger** - 标准虎码输入法
- **tigress** - 虎码变体方案

### 魔然码系列
- **moran** - 标准魔然码
- **moran_aux** - 辅助魔然码
- **moran_fixed** - 固定魔然码
- **moran_bj** - 北京魔然码
- **moran_sentence** - 句子魔然码

### 其他方案
- **PY_c** - 拼音输入法
- **easy_english** - 英文输入

## ⚙️ 个性化配置

### 字体设置
当前配置使用以下字体：
- TX-02
- 汉仪花冠
- 霞鹜文楷等宽GB屏幕阅读版

### 功能特性
- ✅ Emoji表情支持
- ✅ 简繁转换
- ✅ 计算器功能
- ✅ 多种输入模式
- ✅ 智能候选过滤

## 🔄 更新维护

本项目基于开源输入法方案进行个性化定制，会定期同步上游更新：

- 虎码：基于官方虎码方案
- 魔然码：基于rimeinn/rime-moran项目

## 📖 使用说明

### 输入法切换
使用 `Ctrl+` 或 `F4` 键切换不同输入法方案

### 特殊功能
- 计算器：输入数学表达式自动计算
- Emoji：输入关键词显示相关表情
- 简繁切换：支持简繁体转换

## 🤝 贡献

欢迎提交Issue和Pull Request来改进这个配置集合。

## 📄 许可证

本项目配置基于多个开源输入法方案，具体许可证请参考各方案的原始授权。

---

*最后更新：2025年12月*