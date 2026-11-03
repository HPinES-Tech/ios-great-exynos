# iOS Great Exynos Project

**Apple's iOS running on a Samsung Galaxy Note8.**

`Fork of dipa-studio/ios-sweet`

This project ports Apple's open-source XNU kernel to the Samsung Galaxy Note8 (`greatlte`, Samsung S5E8895 / Exynos 8895). On top of it runs the **unmodified iOS userland**: launchd, the system daemons, backboardd, SpringBoard and the stock apps.

> Experimental bring-up, not a usable phone OS. Many things are missing or stubbed (see below), and Apple's security model is mostly switched off. It installs into the `userdata` partition and so **erases Android's user data**.

# XNU Kernel Port
|kernel|generation|status|branch|
|:---:|:---:|:---:|:---:|
|xnu-4570|iOS 11|Unplanned||
|xnu-4903|iOS 12|Unplanned||
|xnu-6153|iOS 13|Unplanned||
|xnu-7195|iOS 14|Unplanned||
|xnu-8020|iOS 15|Unplanned||
|xnu-8796|iOS 16|Planned|[View](https://github.com/HPinES-Tech/ios-great-exynos/tree/xnu-8796)|
|xnu-10063|iOS 17|Unplanned||
|xnu-11417|iOS 18|Unplanned||
|xnu-12377|iOS 26|Unplanned||
|xnu-13432|iOS 27|Unplanned||

Status definitions:
- `Planned`: No source-code modifications have been made.
- `Working-on`: Source-code modifications are in progress.
- `Untested`: Implementation is complete but has not been verified.
- `Completed`: Fully verified and usable.
