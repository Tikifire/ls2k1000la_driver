# ls2k1000la_driver [DEPRECATED]

⚠️ **仓库已弃用（Deprecated）**

本仓库已不再维护，项目已整体迁移至新的仓库

👉[LoongsonLab/gmac_driver](https://github.com/LoongsonLab/gmac_driver)

👉[LoongsonLab/ahci_driver](https://github.com/LoongsonLab/ahci_driver)

下面是原有仓库说明

---

仓库内提供c和rust语言实现的ahci和gmac设备驱动，适配龙芯2k1000la板卡

驱动开发时测试操作系统为RT-Thread，网络栈使用lwip，c直接和OS一起编译，rust编译为库后再链接，通过cbingen和ffi实现调用

由于时间有限，驱动代码还不够完善，欢迎提交issue与pr进行反馈🚀
