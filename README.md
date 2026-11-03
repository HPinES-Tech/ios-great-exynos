# iOS Great Exynos Project

**Apple's iOS running on a Samsung Galaxy Note8.**

`Fork of dipa-studio/ios-sweet`

This project ports Apple's open-source XNU kernel to the Samsung Galaxy Note8 (`greatlte`, Samsung S5E8895 / Exynos 8895). On top of it runs the **unmodified iOS userland**: launchd, the system daemons, backboardd, SpringBoard and the stock apps.

> Experimental bring-up, not a usable phone OS. Many things are missing or stubbed (see below), and Apple's security model is mostly switched off. It installs into the `userdata` partition and so **erases Android's user data**.

# XNU Kernel Port
|kernel|version|status|branch|
|:---:|:---:|:---:|:---:|
|xnu-8796|iOS 16|unusable|[View](https://github.com/HPinES-Tech/ios-great-exynos/tree/xnu-8796)|
