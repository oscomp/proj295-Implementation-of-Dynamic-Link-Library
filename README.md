# proj295-Implementation-of-Dynamic-Link-Library
基于NXOS内核的动态链接库实现

## 项目描述
NXOS是一个开源操作系统内核，由BookOS操作系统社区开发。本项目需要参赛选手为基于NXOS内核的操作系统BookOS支持动态链接库，从而节省磁盘以及内存占用。本项目基于RISCV架构实现动态链接，需要选手熟悉RISCV架构，以及熟悉ELF可执行文件。

## 预期目标
- 阅读理解目标系统和RISCV架构特性，实现RISCV架构的动态链接库支持。
- 在RISCV架构的QEMU模拟器上完成功能调试，形成开发和测试文档。

## 特征
- BookOS是一个拥有基础库，libc的操作系统，可以运行shell程序，lua脚本等应用。
- NXOS是一个支持多核，多进程，多线程，虚拟内存管理，文件系统，网络的操作系统，可以学习一个基础操作系统的实现。
- NXOS拥有自己的编程API，类似于Win32 API。
- NXOS由BookOS社区维护，有社区文档以及比赛交流群，可以为学生答疑。
- 支持各种硬件
  - 基于目前量产的处理器和开发板：
    - D1/D1s哪吒开发板（基于平头哥C906 RV64 CPU）
    - K210开发板（基于K210处理器 RV64 CPU）
    - SiFive Unmatch开发板（基于U740/U540 RV64 CPU）
    - 树莓派4B开发板（基于AARCH64处理器）
  - 基于QEMU模拟器的处理器：
    - QEMU X86模拟器
    - QEMU RISCV64模拟器
    - QEMU AARCH64模拟器
   
## 已有参考资料
- BookOS开源代码：https://gitee.com/BookOS/BookOS
- NXOS开源代码：https://gitee.com/BookOS/nxos
- Elf 文件格式

## 赛题分类
系统调试/支撑库的设计

## 参赛要求
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求

## 难度
中等

## License
Apache 2.0 License

## 所属赛道
2025全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师
姓名：胡自成
单位：BookOS开源社区
github ID： https://github.com/hzcx998
Gitee ID： https://github.com/hzc1998
email： 2323168280@qq.com
