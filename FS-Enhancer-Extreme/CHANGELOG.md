# v1.0.0
## 🎉第一个正式版发布🎉

> 主要
- [ca0f544](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/ca0f544e655e4c8804d37ccc38cacf276a28fa2c)
  - 添加@yu13140的WebUI,当前版本存在大量bug,并且我不是作者无能为力,还请见谅,tseed完成重写后立即重写WebUI.
- [9d4e333](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/9d4e33358b6974348c6de5a141fd2e0337001a9c) [d794f0f](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/d794f0f156d6b617704a447be0a1be66600edc55)
  - 将后台服务使用Rust语言重写
- [d961929](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/d961929483b633f5086a70c9e8d33d44d532eb31) [db15dff](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/db15dff76f1153660e0e9c854a31f31a82accddb)
  - 修复KitsuneMask兼容问题
- [ed3d94d](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/ed3d94d907aea540ae43bb58a9832a6872b02da7)
  - 放弃OverlayFS
- [79958ea](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/79958ea221375d78000193855663e9c7854de5e0) 
  - 解耦 tseed 和 util_functions.sh 以便使用Rust语言重写
  - 为 TrickyStore 1.4.1 添加 verifiedboothash 缓存
  - 避让 Enginex0 的 TEESimulator 分支
  - 为抓取有效密钥后端功能修复来源C
  - 为所有日志添加等级
- 优化安装流程
  - [8b9bc36](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/8b9bc3691a6edd6f2e454797eb9028d43e9f35b3)
    - 修复因Magisk更新模块重新打包导致的安装失败
    - 将备份配置文件改为只备份Keybox
  - [d794f0f](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/d794f0f156d6b617704a447be0a1be66600edc55)
    - 为 OnePlus 添加 com.coloros.sceneservice
  - [d3a25ab](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/d3a25ab10224228c5d7569326bba4f4abf3df575)
    - 更换校验和哈希算法
  - [6514d6f](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/6514d6f02d8685d37b9672a986323fd05b42d591)
    - 加入黑名单模式
- [4477ab2](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/4477ab2b73de24b28f50ace9b753bd54565b67f0)
  - 移除 TrickyStore 模块卡片上的动作按钮
- [8deeb9b](https://github.com/XtrLumen/FS-Enhancer-Extreme/commit/8deeb9b16ab37a7d11452298e89080c09c39c6c0)
  - 扩充冲突模块列表
- 修复大量bug

> 杂项
- 添加版权声明
- 编辑模块描述
- 详细的多语言README

> 仓库
- 删除CHANGELOG

## === Guards the peace of Misty Lake ===