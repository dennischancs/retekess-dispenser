### Retekess TH017 自动药物分配器 APP 使用说明书

🇺🇸 [English](https://github.com/dennischancs/retekess-dispenser/blob/main/README.md) | 🇫🇷 [Français](https://github.com/dennischancs/retekess-dispenser/blob/main/README-FR.md) | 🇩🇪 [Deutsch](https://github.com/dennischancs/retekess-dispenser/blob/main/README-DE.md) | 🇮🇹 [Italiano](https://github.com/dennischancs/retekess-dispenser/blob/main/README-IT.md) | 🇪🇸 [Español](https://github.com/dennischancs/retekess-dispenser/blob/main/README-ES.md) | 🇷🇺 [Русский](https://github.com/dennischancs/retekess-dispenser/blob/main/README-RU.md) | 🇵🇹 [Português](https://github.com/dennischancs/retekess-dispenser/blob/main/README-PT.md) | 🇯🇵 [日本語](https://github.com/dennischancs/retekess-dispenser/blob/main/README-JP.md) | 🇨🇳 [简体中文](https://github.com/dennischancs/retekess-dispenser/blob/main/README-CN.md)

---

## 1. APP下载与安装

通过以下方式在您或您的护理人员的智能手机上下载并安装iDispenser APP:

<img src="./assets/app_qr_code@4x.webp" alt="app_qr_code" width="67%" />

- iOS用户:访问App Store
- Android用户:访问Google Play或直接下载

---

## 2. 账户注册

如果您是首次使用iDispenser,请创建账户:

1. 打开iDispenser APP并点击"注册"
2. 同意隐私政策条款和条件
3. 输入有效的电子邮箱地址或手机号码进行验证
4. 获取验证码并输入
5. 创建密码并登录

---

## 3. Wi-Fi连接设置

### 设备进入AP模式

<img src="./assets/1.svg" alt="1"  width="40%"  />

1. 在设备的主页时钟模式下,长按设备的"+"按钮3秒进入Wi-Fi AP模式；
2. 此时扬声器会播报"AP Mode"语音,LED灯开始闪烁；
3. 如果3分钟内没有操作,设备将自动退出AP模式并返回主页时钟模式；
4. 再次长按设备的"+"按钮3秒可退出AP模式。

**注意:** 需要开启蓝牙和位置服务才能将药物分配器与移动设备配对。

---

## 4. 设备配对方式

### 方式一:自动扫描(Auto Scan)

1. 打开iDispenser APP,点击APP主页上的"添加设备"(Add Device)
2. 等待自动扫描在"发现设备"(Discovering Devices)部分找到药物分配器
3. 当要连接的药物分配器出现时,点击"去添加"(Go to Add)
4. 输入Wi-Fi网络名称和密码,然后点击"下一步"(Next)
5. 等待移动设备和药物分配器连接

### 方式二:手动添加(Add Manually)

1. 打开iDispenser APP,点击APP主页的"⊕"按钮进入"添加设备"页面
2. 选择 Others → Others(Wi-Fi)
3. 点击要连接的药物分配器
4. 确保药物分配器已插电并处于AP模式,然后点击"下一步"

<img src="./assets/5@4x.webp" alt="5" width="60%" />

5. 输入Wi-Fi密码(与手机Wi-Fi密码相同),点击"下一步"

<img src="./assets/6@4x.webp" alt="6"  width="25%" />

6. 进入AP模式页面,点击"下一步"

<img src="./assets/7@4x.webp" alt="7"  width="85%"  />

7. 点击"去连接"(Go to Connect),选择匹配的Wi-Fi SSID

<img src="./assets/8@4x.webp" alt="8"  width="85%" />

8. 前往手机的Wi-Fi设置,从列表中选择"TH017-XXXX"连接分配器
9. 返回APP,等待移动设备和药物分配器连接
10. 连接成功后,点击"完成"(Done)
11. AP连接成功后,点击"返回"回到"添加设备"页面

### 连接成功标识

Wi-Fi连接成功后,设备的显示屏上会显示"<img src="./assets/2.svg" alt="2"  width="3%" />"符号。

<img src="./assets/9@4x.webp" alt="9" width="85%" />

### 连接失败排查

如果Wi-Fi连接失败,请检查以下方面:

1. Wi-Fi的SSID和密码是否正确？
2. 您的Wi-Fi是否为5GHz？请将其设置为2.4GHz。
3. 重置设备:长按设备的"+"按钮重新进入AP模式,重新连接Wi-Fi。

**重要提示:** 一旦药物分配器连接到移动设备,分配器上显示的时间将与移动设备的时间同步。如果移动设备移动到不同的时区,药物分配器的时间不会改变,除非重新配对。

---

## 5. APP操作指南

<img src="./assets/21@4x.webp" alt="21@4x" width="25%" />

### 5.1 设置用药计划

首次通过APP操作药物分配器时,需要设置用药计划:

1. 在仪表盘(Dashboard)上,点击"设置"(Setup)
2. 点击"每日剂量"(Doses per day)选择每天的剂量次数
3. 点击"保存"(Save)保存剂量选择

**注意:** 您可以打开"解锁周期长度"(Unlock Cycle Length)来自定义日周期,如果预设的日周期不符合您的需求。

4. 选择闹钟时间段来设置闹钟
5. 为选定的闹钟时间段设置时间,如需要可添加备注

**注意:** 不能重复设置相同的闹钟时间。

6. 设置完所有闹钟后,会出现弹窗。在弹窗中点击"确定"(Okay)。分配器将自动旋转托盘回到起始位置
7. 将出现另一个弹窗,提示您的托盘已准备就绪。在弹窗中点击"确定"

### 5.2 仪表盘概述(Dashboard Overview)

#### 下次剂量(Next Dose)

<img src="./assets/22@4x.webp" alt="22@4x" width="15%" />显示下次剂量的时间、剂量编号、总剂量数、下次剂量的备注,以及提前服药的选项

#### 日周期(Day Cycle)

<img src="./assets/23@4x.webp" alt="23@4x" width="15%" />显示当前选择的日周期

#### 活动槽位(Active Slots)

<img src="./assets/24@4x.webp" alt="24@4x" width="15%" />显示正在使用的药盒数量(例:21个活动槽位)

#### 结束时间(Ends)

<img src="./assets/25@4x.webp" alt="25@4x" width="15%" />显示药物分配器需要重新装填的日期

#### 剩余剂量(Doses Left)

<img src="./assets/26@4x.webp" alt="26@4x" width="15%" />显示还有多少剂量需要服用(例:21剂剩余)

#### 插头图标

<img src="./assets/28.svg" alt="28" width="8%" /> 表示药物分配器已插上电源线

**注意:** 如果药物分配器拔掉电源,插头图标将从仪表盘消失。

### 5.3 用药提醒

当到了服药时间:

1. 下次剂量窗口将变为红色
2. 闹钟将响起(如果分配器未静音)
3. 点击"静音此闹钟"(Mute this alarm)关闭闹钟
4. 服药后,下次剂量窗口将恢复为蓝色,并显示计划中的下一剂量
5. 药物分配器内置传感器,可以感知何时从药盒中倒出药物

#### 提前服药

要在设定时间之前服药:
1. 点击"提前服用"(Take in advance)
2. 弹窗将出现确认您的选择,点击"确定"
3. 与计划时间一样,下次剂量窗口将变红,闹钟将响起
4. 然后可以正常服药

**注意:** 如果您试图提前一天服药,"提前服用"按钮将不起作用。

<img src="./assets/29@4x.webp" alt="29@4x" width="25%" />

### 5.4 活动概述(Activity Overview)

活动界面显示用户何时服药的记录:

- **绿色符号:** 按时服药
- **黄色符号:** 延迟服药
- **红色符号:** 错过服药

您可以点击时间旁边的备注图标来查看该特定剂量的备注。

#### 服药时间判定

- **按时:** 在设定的闹钟持续时间内服药
- **延迟:** 在闹钟持续时间后但在下次闹钟前服药
- **错过:** 从未服药且下次闹钟已响起

闹钟持续时间默认设置为30分钟,但可以调整(请参阅"设置概述"部分)。

**注意:** 记录将在14天后开始删除。

<img src="./assets/210@4x.webp" alt="210@4x" width="25%" />

### 5.5 闹钟概述(Alarms Overview)

闹钟界面可以编辑已设置的闹钟或设置新的用药计划。

**注意:** 如果设置了新的用药计划,药物分配器将自动旋转并重置回起始位置。

**编辑闹钟:**
1. 点击其中一个闹钟时间段
2. 调整时间或编辑该闹钟的备注
3. 点击"保存"(Save)确认更改

<img src="./assets/211@4x.webp" alt="211@4x" width="25%" />

### 5.6 设置概述(Settings Overview)

设置界面允许您更改以下选项:

- **日期格式(Date Format):** 更改日期显示格式

- **24小时制(24 Hour Time):** 激活以24小时制显示时间

- **音量(Volume):** 在高、中、低和静音之间调整

- **铃声(Ringtone):** 在2种闹钟音调中选择

- **闹钟持续时间(Alarm Duration):** 调整闹钟持续时间,选择范围从5分钟到2小时

- **推送通知(Push Notifications):** 激活通知以接收以下提醒:
  - 重新装填提醒
  - 用药准备提醒
  - 已服药提醒
  - 错过服药提醒
  
  即使APP未打开也会收到这些通知。可以激活全部或部分通知。

- **重置闹钟(Reset Alarms):** 重置所有闹钟

- **全部重置(Reset All):** 重置所有内容,重新开始

<img src="./assets/212@4x.webp" alt="212@4x" width="25%" />

### 5.7 选项概述(Options Overview)

点击屏幕右上角的选项<img src="./assets/3.svg" alt="3" width="3%" />图标进入选项界面。

在此界面可以:
- 查看设备信息
- 查看设备网络
- 更改药物分配器名称
- 与其他APP用户共享药物分配器信息
- 从APP中完全移除设备

#### 设备更新

iDispenser APP会在药物分配器需要更新时通知您:
1. 弹窗出现时,点击"立即更新"(Update Now)进入设备更新页面
2. 点击"更新"(Update)开始更新

---

## 6. 设备管理

### 6.1 APP通知设置

在主页选择: Me → Settings → APP notification

<img src="./assets/11@4x.webp" alt="11" width="85%" />

### 6.2 移除设备

1. 在主页,长按"设备"(Device)图标2秒进入"设备选择"(Device Selected)页面
2. 选择一个或多个要移除的设备
3. 点击"移除设备"(Remove device)图标
4. 点击"完成"(Done)返回主页

<img src="./assets/10@4x.webp" alt="10" width="60%"/>

---

## 7. 操作药物分配器

### 基本操作步骤

1. **选择每日剂量环:** 选择符合您需求的每日剂量环(请参考说明书中的"理解每日剂量环"部分)

2. **放置剂量环和药物:**
   - 将每日剂量环放置在内部药盒的中心
   - 将药物放入药盒中,对应服用时间(第1次、第2次、第3次等)
   - 按照环上的数字(1、2、3等)指示放置
   - 不要在白色部分放置任何药物
   - 当看到白色接近出药口时,就该重新装填了

3. **安装电池:** 请参考说明书中的"安装电池"部分

4. **解锁盖子:**
   - 使用钥匙解锁盖子(请参考"锁定和解锁盖子"部分)
   - 将药杯放入主体内部

5. **插入电源线**

6. **连接Wi-Fi网络:** 使用iDispenser APP连接(请参考"Wi-Fi设置"部分)

7. **设置时间:** 请参考说明书中的"设置时间"部分

8. **调整设置:**
   - 从iDispenser APP调整音量、日期格式和时间格式(请参考"设置概述"部分)
   - 或在分配器上调整闹钟音量、闹钟类型,选择12或24小时制(请参考说明书相关部分)

9. **设置用药时间:**
   - 从iDispenser APP设置用药计划(请参考"设置用药计划"部分)
   - 或在分配器上设置用药闹钟时间(请参考说明书中的"设置闹钟"部分)

10. **锁定盖子:** 使用提供的钥匙关闭并锁定盖子

11. **自动出药:** 在指定的用药时间,警报将响起,药杯会自动推出

12. **停止闹钟:** 取出药杯时,闹钲应自动停止

13. **放回药杯:** 服药后,将药杯放回出口,直到听到"哒"的一声,表示药杯处于正确位置

14. **放置设备:** 将药物分配器放在平坦的表面上

---

## 8. 护理与维护

- **清洁外部:** 用柔软的湿布擦拭外部。不要使用刺激性清洁剂

- **清洁内部药盒:**
  - 如需要,取出内部药盒
  - 轻轻冲洗/擦拭各个药格
  - 在重新放置或重新装填之前,让容器完全干燥

- **防水注意:** 不要将外部药物分配器浸入水或任何其他液体中

- **保持清洁:** 确保内部药盒在重新装填之前清洁干燥

---

## 注意事项

- Wi-Fi、WPA和WPA2是Wi-Fi Alliance在美国和/或其他国家的商标
- Bluetooth是Bluetooth SIG, Inc. USA的商标
- Android和Google Play是Google LLC的商标
- Apple、iOS和App Store是Apple Inc.在美国和其他国家的商标
- 所有其他产品、品牌名称、公司名称和徽标均为其各自所有者的商标,仅用于识别其各自产品,并不意味着任何赞助、认可或批准

---

**如有疑问，请联系Retekess客户服务，联系方式见产品包装盒或纸质说明书上**
