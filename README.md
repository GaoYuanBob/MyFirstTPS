# MyFirstTPS
## MiniGTA

### 操作设置
* PC
  * WASD移动
  * 左`Shift`加速
  * `F`进行物品拾取
  * 鼠标滚轮装备/切换武器；`E`装备/卸下武器
  * 鼠标右键瞄准；左键射击
  * `Space`跳跃
* Phone：
  * 略

### 参考资料
1. UE4官方文档：
    * [Scalability Reference](https://docs.unrealengine.com/en-US/Engine/Performance/Scalability/ScalabilityReference/index.html)
1. [User Interface Development：1 - 18](https://www.youtube.com/playlist?list=PLL0cLF8gjBprIHm0yo-Vj9oBwi2-gAIEd)
2. [Create Game From Scratch UE4 TPS Game Series：1 - 24](https://www.youtube.com/playlist?list=PLM6ZWbxOgIqsCb3dUJRdYoUbyi_zFCOjs)


### Version History
* 2020.6.5
  * Sprint功能修改，射击/切换武器/装备卸下武器/下蹲 会自动 UnSprint
  * 修改UI显示，在 sprint 状态下，不显示界面中心瞄准的图标
  * 修复 Jump，现在下蹲时可以jump；手持武器时可以 jump，不可以射击

* 2020.6.4
  * UI界面开发

* 2020.6.3
  * 完成NPC射击主角，爆头
  * 添加NPC Spawn Sensing
  * 完成鼠标右键 ZoomIn、ZoomOut
  * NPC AimOffSet 设置
  * NPC ScanEnemy，视野内没有Player的时候，StopFire并且寻找 Player
  * NPC Sense Player，根据其他NPC来找player
  * NPC 死亡效果

* 2020.6.2
  * 完成武器射击Projectile
  * 修复SwapWeapon，Qquip/UnEquip Weapon时开枪的bug
  * 完成头部Capsule，实现爆头
  * 完成NPC被击中掉血
  * 完成NPC 的 Patroling，以及被击中后 跟随玩家

* 2020.6.1
  * 修复双武器切换Bug
  * 添加LineTrace实现射击效果
  * 实现双武器弹药消耗，以及Reload功能
  * 有/无武器时的Crouch功能
  * 修复换弹动画最后一点可以开枪的bug
  * 添加射击时枪口MuzzleFlash效果

* 2020.5.29 
  * 完成靠近武器（Pickups）的高亮显示（PostProcessVolume）
  * 完成第一次 Android 打包，以及手机联调（Launch）
  * 完成装备武器的时候的视角变换

* 2020.5.28 武器配置初步完成
  * 完成两个武器的模型，武器上身效果，换武器的工作（现在只能换一个武器）
  * 完成靠近武器的 Text 的显示（Rifle_Child 中配置 Itemclass，然后设计 UI）
  * 完成 Idle Walk Run 之间的自然过渡