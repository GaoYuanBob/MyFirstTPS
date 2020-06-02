# MyFirstTPS
MiniGTA

当前设置：
1. 下蹲或者手持武器状态，不能 junmp
2. SwapWeapon，Equip/UnEquipWeapon，Sprint 时不能 Fire


2020.6.2
* 完成武器射击Projectile
* 修复SwapWeapon，Qquip/UnEquip Weapon时开枪的bug


2020.6.1
* 修复双武器切换Bug
* 添加LineTrace实现射击效果
* 实现双武器弹药消耗，以及Reload功能
* 有/无武器时的Crouch功能
* 修复换弹动画最后一点可以开枪的bug
* 添加射击时枪口MuzzleFlash效果
    * 有一个不知道怎么复现的bug，**以后再说**。。

2020.5.29 
* 完成靠近武器（Pickups）的高亮显示（PostProcessVolume）
* 完成第一次 Android 打包，以及手机联调（Launch）
* 完成装备武器的时候的视角变换

20202.5.28 武器配置初步完成
* 完成两个武器的模型，武器上身效果，换武器的工作（现在只能换一个武器）
* 完成靠近武器的 Text 的显示（Rifle_Child 中配置 Itemclass，然后设计 UI）
* 完成 Idle Walk Run 之间的自然过渡