什么是 Omege UOS?
================

Omege UOS 是由**一位7岁小学生**从零开始独立开发的操作系统。

它主要由 C 语言编写，其次是汇编语言与 Rust。
注意：**本系统默认开启 Secure Boot**
（技术说明：此处“开启”指系统内核会强制校验自身完整性，与主板 Secure Boot 设置无关。即使主板未开启 Secure Boot，本系统也会执行自制的校验。）

我该如何编译？
============

如果您需要编译，需要安装以下：
GCC 编译器
一个 Linux 操作系统
CMake 编译系统
rustup
另见 [README 文档](https://github.com/deeplearning-corporation/OmegeUOS/blob/main/README.md)
