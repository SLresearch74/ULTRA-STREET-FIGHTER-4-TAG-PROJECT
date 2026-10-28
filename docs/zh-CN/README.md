[English](../../README.txt) · [语言](../README.md)

# USF4 TAG! — 安装与游玩指南

**Pre-alpha v0.1 · 版本 0.1.0 · 简体中文**

## 开始前

需要你自己的 Windows 版 **Steam Ultra Street Fighter IV** 安装，以及 **PowerShell 5.1**、**.NET Framework 4.7.2 或更高版本**。Setup 会检查受支持的 Steam 构建及必要原文件。若尚未安装已测试版本的 Simp，需要联网获取。

这是单角色战斗预览版，支持 **42 名角色**。组队／换人玩法仍是独立项目；**Hugo 与 Hakan 暂缓**。额外 **50% 眩晕值减免**目前仅在 **离线标准 Ultra Training** 生效。

启动器界面仍为英文，以下保留按钮的实际英文名称。角色与招式名也沿用英文原文，避免地区命名混淆。

## 安装

1. 正常退出 USF4 与 Simp。将 **完整 ZIP 解压**到一个文件夹。
2. 运行 **USF4TAG-PreAlpha-0.1.0-Setup.exe**。
3. 如有提示，选择包含 **SSFIV.exe** 的 Steam 游戏文件夹。
4. 点击 **Install Pre-Alpha**，等待 **Installation complete**。

Setup 自动安装模组并配置已测试版本的 Simp。已有完全匹配的副本会被复用，否则从来源下载并校验。下载不可用时，可选择已有的已测试副本，或取消。已安装的不同 Simp 版本会保留，不会被覆盖。删除下载的安装器后，桌面快捷方式仍然有效。

## 游玩

1. 打开桌面 **USF4 TAG Pre-Alpha**，点击 **Launch USF4**。
2. 在游戏 **主菜单** 等待，暂不进入 Training。
3. 返回启动器，点击 **Load Pre-Alpha**。
4. 在 Simp 选择 **tag_pre_v0100**，点击 **Launch**。
5. 保持启动器打开，直到出现 **Patching complete** 提示。
6. 回到游戏，进入 **标准 Ultra Training**。请选择标准 Ultra 角色，不要选择 Omega 或早期版本角色。

补丁完成后，启动器自动启用 Training 眩晕规则。用角色的浮空启动技命中后 **按住上** 追击。普通技空中连锁须以 **轻或中攻击** 起手，重攻击收尾。[42 名角色完整改动](ROSTER_CHANGES.md) 列出各启动技、输入及例外。

## 游玩原版 USF4

正常退出 USF4 与 Simp。选择 **Play Normal USF4**，或在 Simp 关闭后从 Steam 重新启动游戏。原文件与存档保留。

## 更新与问题报告

- **Manage → Check for updates：** 选择更新后，下载并校验新发布的安装器。安装前正常关闭 USF4 与 Simp。
- **Manage → Open logs：** 打开本地错误与操作报告。
- **Manage → Report a bug：** 显示诊断预览，再打开预填的 GitHub issue。请在 GitHub 审核并提交；不会自动上传原始日志或文件。

## 修复与卸载

关闭 USF4 与 Simp 后，使用 **Manage → Repair installation** 或 **Manage → Remove Pre-Alpha**。受管理更新／修复会保留恢复副本。无关或被修改文件会保留，可能需要你自行处理。

## 内容与支持

下载包含安装器、说明、[角色改动](ROSTER_CHANGES.md)、翻译、**CREDITS.txt**、**THIRD_PARTY_NOTICES.txt**、**LICENSE.txt** 与完整性校验文件 **SHA256SUMS.txt**。安装器包含永久启动器、运行组件和战斗补丁；不包含游戏本体或 Simp 可执行文件。

[GitHub 项目](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT) · [报告问题](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/issues)
