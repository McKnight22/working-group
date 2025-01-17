# 文章分类索引

## android-review 进展

- [第一期：2022/10/13][40]
- [第二期：2022/10/27][41]

## 安卓（Android）

- [AOSP 的版本管理][1]
- [AOSP 内核的版本管理][2]
- [编译一个 RISC-V 的 Android 内核][3]
- [第一个 RISC-V 上的“Android 最小系统”][5]
- [Create a minimal Android system for RISC-V][31]
- [RISC-V Gets an Early, Minimal Android 10 Port Courtesy of PLCT Lab, Gareth Halfacree - https://abopen.com/, 20201127][32]
- [AOSP-RISCV 的开源仓库在 Gitee 上新建了镜像][6]
- [AOSP Build 背后涉及的相关知识汇总][7]
- [AOSP Soong 创建过程详解][8]
- [envsetup.sh 中的 lunch 函数分析][9]
- [代码走读：对 soong_ui 的深入理解][10]
- [Case analysis:prebuilt-elf-files][11]
- [如何为 AOSP 的 lunch 新增一个菜单项][12]
- [Android NDK 的构建分析][13]
- [GDB 调试 Android 模拟器][15]
- [AOSP 12 移植 RISCV64 过程中针对 RenderScript 的适配方案分析][16]
- [AOSP RISC-V 移植工作中 setjmp 相关函数实现总结][17]
- [Bazel 和 AOSP 介绍][18]
- [BIONIC 中对 IFUNC 的支持][20]
- [搭建 CTS 环境][21]
- [Andorid Build System 研究心得][33]
- [为 AOSP 添加一个 module][34]
- [学习笔记：Android Init Language][35]
- [学习笔记：Android Early Init Boot Sequence][36]
- [学习笔记: VNDK 基本概念][37]

## 编程语言与编译技术

- [制作一个针对 RISC-V 的 LLVM/Clang 编译器][4]
- [GNU IFUNC 介绍（RISC-V 版）][19]
- [Call Stack (RISC-V)][22]
- [Stack Unwinding - Overview][23]
- [Stack Unwinding 之基于 Frame Pointer][24]
- [制作交叉工具链 riscv-gnu-toolchain][25]
- [Stack Unwinding 之基于 Call Frame Information][26]
- [用于栈回溯的一些库][28]
- [学习笔记: Symbol Versioning 基本使用][38]


## Linux

- [聊一聊 Linux 上信号处理过程中的信号栈帧][27]
- [和 ptrace 有关的一些笔记][29]
- [在 QEMU 上运行 RISC-V 64 位版本的 Linux][30]
- [Linux 设备模型之 kobject 和 kset][42]
- [学习笔记：编写一个内核模块][43]
- [Linux 中的 sysfs][44]
- [Linux 驱动模型之三剑客][45]

## 开发工具

- [尝试运行第一个支持 RISC-V 的 QEMU 版本（v2.12.0）][14]


[1]: ./20200911-platform-version.md
[2]: ./20200915-android-linux-version.md
[3]: ./20200929-build-riscv-android-kernel.md
[4]: ./20201009-create-clang-riscv.md
[5]: ./20201120-first-rv-android-mini-system.md
[6]: ./20201215-opensrc-on-gitee.md
[7]: ./20201230-android-build-sum.md
[8]: ./20210111-soong-process.md
[9]: ./20211026-lunch.md
[10]: ./20211102-codeanalysis-soong_ui.md
[11]: ./20220226-case-prebuilt-elf-files.md
[12]: ./20220315-howto-add-lunch-entry.md
[13]: ./20220402-understand-how-ndk-built.md
[14]: ./20220406-qemu-riscv-2.12.md
[15]: ./20220412-howto-gdb-android-emulator.md
[16]: ./20220509-renderscipt-adaptation-analysis-in-android12-riscv64-porting.md
[17]: ./20220511-aosp-riscv-setjmp.md
[18]: ./20220615-introduce-bazel-for-aosp.md
[19]: ./20220621-ifunc.md
[20]: ./20220623-ifunc-bionic.md
[21]: ./20220705-build-the-cts.md
[22]: ./20220717-call-stack.md
[23]: ./20220719-stack-unwinding.md
[24]: ./20220719-stackuw-fp.md
[25]: ./20220721-riscv-gcc.md
[26]: ./20220721-stackuw-cfi.md
[27]: ./20220816-signal-frame.md
[28]: ./20220819-libunwind.md
[29]: ./20220829-ptrace.md
[30]: https://zhuanlan.zhihu.com/p/258394849
[31]: https://plctlab.github.io/aosp/create-a-minimal-android-system-for-riscv.html
[32]: https://abopen.com/news/risc-v-gets-an-early-minimal-android-10-port-courtesy-of-plct-lab/
[33]: ./20220905-aosp-build-system.md
[34]: ./20220908-add-app-in-aosp.md
[35]: ./20220915-andorid-init-language.md
[36]: ./20220916-android-early-boot-sequence.md
[37]: ./20220923-vndk.md
[38]: ./20221008-symbol-version.md
[40]: ./android-review/20221013.md
[41]: ./android-review/20221028.md
[42]: ./20221029-kobject-kset.md
[43]: ./20221101-write-lkm.md
[44]: ./20221101-sysfs.md
[45]: ./20221102-bus-device-driver.md