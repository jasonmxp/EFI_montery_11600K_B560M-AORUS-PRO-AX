# EFI_montery_11600K_B560M-AORUS-PRO-AX

  CPU      11th Gen Intel Core i5-11600K @ 3.90GHz 六核
  主板      技嘉 B560M AORUS PRO AX ( LPC Controller - 4387 )
  显卡      AMD Radeon RX 560 ( 4 GB / 蓝宝石 )
  内存      16 GB ( 4133hz  8G*2 )
  SSD      inter760P 256G ( 512 GB / 固态硬盘 )
  声卡      ALC897
  网卡      英特尔 Ethernet Controller  I225-V / 技嘉
  无线      BCM94360CD(板载AX200)

☑有线-启动参数e1000=0即可免驱
☑蓝牙、无线、显卡（跨设备复制粘贴“连续互通”、隔空投送）-----免驱
☑声卡-layout-id=12
☑USB（定制）
☑iMessage、FaceTime、睡眠唤醒


20220729更新：
ax200更换为BCM94360CD，移除相关无线网卡驱动
I225-v网卡名称显示??修复（移除仿冒信息，启动参数直接增加e1000=0）

20220801更新：
调整kext加载顺序，将USB相关驱动前移
<img width="879" alt="image" src="https://user-images.githubusercontent.com/62681833/182175855-241936c8-4f34-4c53-8fb2-e7cbae836a41.png">
