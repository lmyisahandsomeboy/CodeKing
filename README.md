
# CodeKing 使用文档

## 项目简介

**CodeKing** 是一个基于 Qt 的图形界面程序，主要功能包括：

- 代码编辑（Code Editor）
- 词法分析（Lexical Analyzer）
- 语法分析（Syntax Analyzer）
- 语义分析（Semantic Analyzer）
- 语法高亮（Syntax Highlighter）
- 符号表管理（Advanced Symbol Table）
- 四元式优化（Quadruple Optimizer）

## 功能模块

- **代码编辑器**：支持基本的代码编辑与高亮显示。
- **词法分析**：对输入代码进行词法分析，输出 Token 流。
- **语法分析**：对 Token 流进行语法分析，生成语法树或报错。
- **语义分析**：进行类型检查、作用域分析等。
- **符号表**：高级符号表管理，支持变量、函数等符号的存储与查询。
- **四元式优化**：对中间代码进行优化处理，提高执行效率。

---

## 依赖环境

- **Qt 5.x 或 6.x**（需包含 Qt Widgets 模块）
- **C++17** 标准支持

---

## 文件结构

- `codeeditor.*`：代码编辑器相关
- `lexicalanalyzer.*`：词法分析器
- `syntaxanalyzer.*`：语法分析器
- `semanticanalyzer.*`：语义分析器
- `syntaxhighlighter.*`：语法高亮
- `advanced_symbol_table.*`：高级符号表
- `quadruple_optimizer.*`：四元式优化
- `mainwindow.*`：主窗口及 UI
- `mainwindow.ui`：主界面设计文件
- `CodeKing_zh_CN.ts`：中文翻译文件

---

## 构建与运行

1. **安装 Qt 环境**  
   推荐使用 Qt 5.12 及以上版本，确保包含 Qt Widgets 模块。

2. **打开项目**  
   使用 Qt Creator 打开 `CodeKing.pro` 工程文件。

3. **编译项目**  
   选择合适的构建套件（如 MSVC、MinGW），点击“构建”按钮。

4. **运行程序**  
   编译完成后，点击“运行”按钮启动程序。

---

## 国际化

- 项目内置中文翻译（`CodeKing_zh_CN.ts`），可根据系统语言自动切换。

---

## 许可证

请根据实际项目情况补充许可证说明。

---

如需进一步开发或定制功能，请参考各模块源代码及头文件。

---
