# statistics

# 文件统计工具

## 项目简介

文件统计工具是一个基于 JavaFX 的桌面应用程序，旨在帮助用户快速获取指定文件夹中的文件信息和统计数据。用户可以通过简单的图形界面选择文件夹、过滤文件类型、选择统计方法和导出格式，以便轻松管理和分析文件数据。

## 背景

随着数字化时代的发展，文件的存储与管理变得愈发重要。特别是在需要分析大量文件时，手动统计和处理信息往往效率低下。文件统计工具旨在为用户提供一个高效、易用的解决方案，帮助他们快速获取所需的文件统计信息，提升工作效率。

## 特性

- **文件夹选择**：用户可以通过图形界面选择要统计的文件夹，方便快捷。
- **文件类型过滤**：支持多种常见文件格式（如 JPG、PDF、DOCX 等），用户可以选择特定文件类型进行统计。
- **多种统计方法**：提供不同的统计方式，包括：
  - 文件夹统计：统计文件夹内所有文件的信息。
  - 文件统计：仅统计特定类型的文件。
  - 详细信息统计：获取每个文件的详细信息（如大小、创建时间等）。
- **导出方式选择**：用户可以选择不同的导出格式：
  - 格式化输出：以易读的格式输出统计信息。
  - 深度优先：按照文件夹结构深度优先输出。
  - 广度优先：按照文件夹结构广度优先输出。
- **友好的用户界面**：基于 JavaFX，提供直观、易用的界面设计。

## 技术栈

- **Java**：编程语言
- **JavaFX**：用于构建用户界面的框架
- **Maven**：项目管理和构建工具
- **Git**：版本控制

## 安装

### 前提条件

确保您的计算机上安装了以下软件：

- Java JDK 8 或更高版本
- Maven（用于构建项目）

### 安装步骤

1. **克隆仓库**：

   ```bash
   git clone https://github.com/您的用户名/文件统计工具.git
