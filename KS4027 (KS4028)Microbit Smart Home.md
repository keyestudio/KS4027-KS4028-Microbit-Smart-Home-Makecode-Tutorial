# Smart Home Kit for Micro:bit

**![房子前的草地上
中度可信度描述已自动生成](media/5fc34a9e6d669e6b472728fb5f0655f2.jpeg)**

# 1.Introduction：

Fueled by the rapid development of technology, smart homes automatically
controlled remotely by smart phones and other devices have become more common.
For the same reason, they have increasingly gained closer attention and caught
people’s fancy.

Bearing the aim to make improvements in household living conditions, the smart
home system has been integrated with technologies including computer science,
telecommunication, automatic control and others and emerged as a comprehensive
and smart system featuring safety, convenience, coziness, services , utility and
environmental consciousness.

# 2.Description：

Launched by Keyestudio, this smart home kit is based on the open-source hardware
of Micro:bit and designed for those who dream of living a more comfortable life
with the help of technologies.

This smart home system, with Micro:bit as its control board, is equipped with a
1602 LCD, a DHT11 temperature and humidity sensor, an analog gas sensor(MQ_2), a
PIR motion sensor , a 6812 RGB module, a servo, a steam sensor, a Micro:bit BT
and other sensors.

With the help of these sensors, this kit can be applied to detect temperature,
humidity and the concentration of flammable gases in your home and open and
close doors. Furthermore, all the information detected can display on 1602 LCD
in real time available for you to check and monitor via smart phones or iPad. By
the way, it supports powering by solar energy or via USB cable.

This tutorial will guide you to make and control the smart home kit by the code
written in the online graphical programming platform Makecode. In this process,
not only can you enhance your ability to make stuffs but also learn the skills
of programming.

MakeCode for micro:bit is the most widely used graphical programming environment
on the micro:bit official website. It is based on the graphical programming
environment developed by Microsoft's open source project MakeCode. This
graphical programming can also be converted to textual version, namely Python or
JavaScript. The combination of code and graphics makes it very convenient and
easy to learn. At the same time, it can be simulated or programmed for
electronic components.

# **3.Kit List：**

When you get this delicate kit, please confirm whether all components listed
below have been delivered.

| \#   | Parts                                                               | Quantity | Picture                                                                                                                                                             |
|------|---------------------------------------------------------------------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  1   | Micro:bit Main Board Included in KS4027 Not included in KS4028      | 1        | ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png)                                                                                                                 |
|  2   | Keyestudio Micro:bit Expansion Board with IO Port                   | 1        | ![IMG_256](media/2c5649b3c64450c4faa749a198196ace.png)                                                                                                              |
|  3   |  Wooden Board                                                       | 7        | ![椴木板_画板 1](media/2a8901b02157d4cc61471b024d7ba7f8.png)                                                                                                        |
|  4   |  Acrylic Board                                                      | 3        | ![9](media/a0a2dcbce9b904fbf0325c743016142c.png)![11](media/b7d94f011790aeb2427c33d6d30f62f6.png)![10](media/c1fdd1f128aa47a44d4c5148d0dd2af1.png)                  |
|  5   |  6812 RGB Module                                                    | 1        | ![16](media/cdebaf0805f0e933e1ccfb3691258bc7.png)                                                                                                                   |
| 6    | Analog Gas Sensor                                                   | 1        | ![17](media/5ad704f1db5e43058513cf8ed2d53047.png)                                                                                                                   |
|  7   |  130 Motor Module                                                   |  1       | ![25(1)](media/e092ffebd3240e6e157a7872731a9b58.png)                                                                                                                |
|  8   |  Steam Sensor                                                       | 1        | ![14](media/932398f7831e7e6d0f1c0b6f035a79a4.png)                                                                                                                   |
|  9   | DHT11 Temperature and Humidity Sensor                               | 1        | ![1](media/f7ff148f3c57a033e5898e955479d368.png)                                                                                                                    |
|  10  |  PIR Motion Sensor                                                  | 1        | ![15](media/8e527b21d2e89c43f0fa894cb32f55c8.png)                                                                                                                   |
|  11  |  Yellow LED Module                                                  | 1        | ![13](media/98c9efc46d004ad501e0fe56f826a69c.png)                                                                                                                   |
|   12 | Rechargeable Lithium Battery Power Module with Solar and USB Ports  | 1        | ![18](media/74979752fe2d570b21f519bb6fc522c5.png)                                                                                                                   |
| 13   | Battery Holder                                                      | 1        | ![21](media/5f1f05ea2814a185771483b163eceeb1.png)                                                                                                                   |
| 14   | Micro:bit Solar Energy Panel                                        | 1        | ![22](media/f6b395ab7bb1afeed1f6861ad0bf1679.png)                                                                                                                   |
| 15   | Servo                                                               | 2        | ![IMG_256](media/577b99a4380c5014bd482812222be0b4.png)                                                                                                              |
| 16   | I2C 1602 LCD Module                                                 | 1        | ![KS0062 (4)](media/b28242c31d938ab51c634aa121490ffa.jpeg)                                                                                                          |
| 17   | Rocker Switch                                                       | 1        | ![13 (2)](media/68ba54c557d7e9707ba87d19845eca52.png)                                                                                                               |
| 18   | 15cm 3Pin F-F DuPont Wire                                           | 4        | ![C:\\Users\\Admin\\Desktop\\KS0078 旅行房车机器人安装步骤\\模块\\3pin 黑红黄 150mm（1）.png3pin 黑红黄 150mm（1）](media/67d47059e10398d11cc4970ca621a0c8.png)     |
| 19   | 20cm 3Pin F-F DuPont Wire                                           | 2        | ![C:\\Users\\Admin\\Desktop\\KS0078 旅行房车机器人安装步骤\\模块\\3pin 黑红黄 200mm（1）.png3pin 黑红黄 200mm（1）](media/2f7c9968ae7bbc7515060ef721d7b155.png)     |
| 20   | 20cm F-F DuPont Wire                                                | 4        | ![23](media/4e16c0d9d83e62d232c7823dea8e4a86.png)                                                                                                                   |
| 21   | 20cm 4Pin F-F DuPont Wire                                           | 1        | ![C:\\Users\\Admin\\Desktop\\KS0078 旅行房车机器人安装步骤\\模块\\4pin 黑红蓝绿 200mm（1）.png4pin 黑红蓝绿 200mm（1）](media/90c270d9a66fdebe7e48c4b981848701.png) |
| 22   | 200mm 2Pin DuPont Wire                                              | 2        | ![20](media/f3588d0214e7eb9cf88d1585eaf139f8.png)                                                                                                                   |
| 23   | M2\*8MM Round-head Screw                                            | 3        | ![M3X6MM圆头 十字](media/05a777927510346c0201f5fdfec45bda.png)                                                                                                      |
| 24   | M1.4\*6MM Round-head Self-tapping Screw                             | 10       | ![MICRO SERVO 9G](media/359c47286d1eb9289c6e4d5cd272358e.jpeg)                                                                                                      |
| 25   | M3 Nickel-plated Self-locking Nut                                   | 5        | ![](media/4e3bbf6938c7bdabdc974f81a9e45780.png)                                                                                                                     |
| 26   | M4\*8MM Round-head Screw                                            | 18       |  ![M3X6MM圆头 十字](media/05a777927510346c0201f5fdfec45bda.png)                                                                                                     |
| 27   | M3\*6MM Round-head Screw                                            | 9        |  ![M3X6MM圆头 十字](media/05a777927510346c0201f5fdfec45bda.png)                                                                                                     |
| 28   | M3\*10MM Round-head Screw                                           | 9        | ![M3X8MM圆头 十字](media/2f7b5616f43002e2903a3e7eec952bfa.png)                                                                                                      |
| 29   | M2\*12MM Round-head Screw                                           | 5        |  ![M3X8MM圆头 十字](media/2f7b5616f43002e2903a3e7eec952bfa.png)                                                                                                     |
| 30   | M4 Nickel-plated Nut                                                | 18       | ![M3镀镍](media/3665fc5a77e96330bd56e9e00dda8c93.png)                                                                                                               |
| 31   | M3 Nickel-plated Nut                                                | 6        | ![M3镀镍](media/3665fc5a77e96330bd56e9e00dda8c93.png)                                                                                                               |
| 32   | M2 Nickel-plated Nut                                                | 7        | ![M2镀镍](media/ac69e595a9873e0553e1fa4242ae5ad8.png)                                                                                                               |
| 33   | M3\*8MM Round-head Screw                                            | 2        | ![M3X10MM平头](media/58fd61e64e7907e75ff08a92aefbfd32.png)                                                                                                          |
| 34   | Wrench                                                              | 1        | ![C:\\Users\\Admin\\Desktop\\模块\\十字套筒.jpg十字套筒](media/e8e1c04d2c03b995842b0bd92e2fdf72.jpeg)                                                               |
| 35   | 3.0\*40MM Screwdriver Red-Black                                     | 1        | ![](media/f353b46e6c2c0597c3268d5aa137fd99.png)                                                                                                                     |
| 36   | 2.0\*40MM Screwdriver Purple-Black                                  | 1        | ![螺丝钉](media/aa12dd0fe16e3f122e1822f671b3c0c7.png)                                                                                                               |
| 37   | M3\*45MM Dual-pass Copper Pillar                                    | 4        | ![双通铜柱1](media/a9f278135227bab8d230e09d7a885f43.png)                                                                                                            |
| 38   | USB Cable AM/MK5P(micro) Black OD：3.5 L=1M PVC                     | 1        | ![IMG_256](media/3f89a39ed2fa223a407df6ecff43229c.jpeg)                                                                                                             |
| 39   |  F5 Blue to Blue LED                                                | 2        | ![蓝灯](media/5f8b2d0544b86e3267b2cee1b8b1b88c.png)                                                                                                                 |
| 40   | 18650 Battery（Not Included）                                       | 1        | ![](media/0f98f85ff2e87ccc77ad7f9ec99c3fde.png)                                                                                                                     |

# Preparations:

1.  **Background Information about Micro:bit**

**( 1 )What is Micro:bit?**

Micro:bit is an open source hardware platform based on the ARM architecture
launched by British Broadcasting Corporation (BBC) together with ARM, Barclays,
element14, Microsoft and other institutions. The core device is a 32-bit Arm
Cortex-M4 with FPU micro-processing.

Though it is just the size of a credit card, the Micro:bit main board is
equipped with loads of components,including a 5\*5 LED dot matrix, 2
programmable buttons, an accelerometer, a compass, a thermometer, a
touch-sensitive logo and a MEMS microphone, a Bluetooth module of low energy,
and a buzzer and others. Thus, it also boasts multiple functions.

The buzzer built in the other side of the board makes playing all kinds of sound
possible without any external equipment. The golden fingers and gears added
provide a better fixing of crocodile clips. Moreover, this board has a sleeping
mode to lower power consumption of batteries and it can be entered if users long
press the Reset & Power button on the back of it. It is capable of reading the
data of sensors, controlling servos and RGB lights and attaching with a shield
so as to connect with various sensors. It also supports a variety of codes and
graphical programming platforms, and is compatible with almost all PCs and
mobile devices. It has no need to install drivers. It is of high integration of
electronic modules, and has a serial port monitoring function for easy
debugging.

The board has found wild applications. It can be applied in programming video
games, making interactions between light and sound, controlling a robot,
conducting scientific experiments, developing wearable devices and make some
cool inventions like robots and musical instruments, basically everything
imaginable.

**( 2 )Layout**

![](media/ae1ddaa286548b2e6414a8284f85325d.png)

For the Micro: Bit main board, pressing the Reset & Power button, it will reset
the board and rerun the program.If you hold it tight, the red LED will slowly
get darker.When the power indicator flickers into darkness, releasing the button
and your Micro: Bit board will enter sleep mode for power saving .This will make
the battery more durable. And you could press this button again to‘wake up’your
Micro:bit.

For more information,please resort to following links：

<https://tech.microbit.org/hardware/>

https://microbit.org/new-microbit/

https://www.microbit.org/get-started/user-guide/overview/

<https://microbit.org/get-started/user-guide/features-in-depth/>

**( 3 ) Pinout**

![v2.0引脚-01(2)](media/827b32e06f290b4aa4425c60b335d5b2.png)

**The functions of pins:**

| GPIO                       | P0，P1，P2，P3，P4，P5，P6，P7，P8，P9，P10，P11，P12，P13，P14，P15，P16，P19，P20                |
|----------------------------|----------------------------------------------------------------------------------------------------|
| ADC/DAC                    | P0，P1，P2，P3，P4，P10                                                                            |
| IIC                        | P19（SCL），P20（SDA）                                                                             |
| SPI                        | P13（SCK），P14（MISO），P15（MOSI）                                                               |
| PWM（used frequently）     | P0，P1，P2，P3，P4，P10                                                                            |
| PWM（not frequently used） | P5、P6、P7、P8、P9、P11、P12、P13、P14、P15、P16、P19、P20                                         |
| Occupied                   | P3(LED Col3)，P4(LED Col1)，P5(Button A)，P6(LED Col4)，P7(LED Col2)，P10(LED Col5)，P11(Button B) |

Browse the official website for more details:

<https://tech.microbit.org/hardware/edgeconnector/>

<https://microbit.org/guide/hardware/pins/>

**( 4 )Notes for the application of Micro:bit main board**

1.  It is recommended to cover it with a silicone protector to prevent short
    circuit for it has a lot of sophisticated electronic components.

1.  Its IO port is very weak in driving since it can merely handle current less
    than 300mA. Therefore, do not connect it with devices operating in large
    current, such as servo MG995 and DC motor or it will get burnt. Furthermore,
    you must figure out the current requirements of the devices before you use
    them and it is generally recommended to use the board together with a
    Micro:bit shield.

1.  It is recommended to power the main board via the USB interface or via the
    battery of 3V. The IO port of this board is 3V, so it does not support
    sensors of 5V. If you need to connect sensors of 5 V, a Micro: Bit expansion
    board is required.

1.  When using pins(P3, P4, P6, P7 and P10)shared with the LED dot matrix,
    blocking them from the matrix or the LEDs may display randomly and the data
    about sensors connected maybe wrong.

1.  Pin 19 and 20 can not be used as IO ports though the Makecode shows they
    can. They can only be used as I2C communication.

1.  The battery port of 3V cannot be connected with battery more than 3.3V or
    the main board will be damaged.

1.  Forbid to operate it on metal products to avoid short circuit.

To put it simple, Micro:bit V2 main board is like a microcomputer which has made
programming at our fingertips and enhanced digital innovation. And as for
programming environment, BBC provides a website: <https://microbit.org/code/,>
which has a graphical MakeCode program easy for use.

## 4.2.Install Micro:bit driver

Micro:bit is free of driver installation. However, in case your computer fail to
recognize the main board, you can install the diver too.

Just enter the link https://fs.keyestudio.com/KS4027-4028

to download the driver file ![](media/78709f5e0a6fdbd6a0f1c47873273353.png) of
micro:bit in file folder ![](media/0639221bcfa4728e2f8eeb5bc81a73d3.png).

**5.Getting Started with Micro:bit**

The following instructions are applied for Windows system but can also serve as
a reference if you are using a different system.

**5.1 Write code and program**

This chapter describes how to write program and load the program to the Micro:
Bit main board V2.

You are recommended to browse the official website of Micro:bit for more
details, and the link is attached below:

[https://microbit.org/guide/quick/](Https://microbit.org/guide/quick/)

**Step 1: connect the Micro: Bit main board with your computer**

Firstly, link the Micro: Bit main board with your computer via the USB cable.
Macs, PCs, Chromebooks and Linux（including Raspberry Pi）systems are all
compatible with the Micro: Bit main board.

Note that if you are about to pair the board with your phone or tablet, please
refer to this link:

[https:/microbit.org/get-started/user-guide/mobile/](https://microbit.org/get-started/user-guide/mobile/)

![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png)
![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

Secondly, if the red LED on the back of the board is on, that means the board is
powered. When your computer communicates with the main board via the USB cable,
the yellow LED on it will flashes. For example, it will flicker when you burn a
“hex”file.

Then Micro: bit main board will appear on your computer as a driver named
“MICROBIT(E:)”. Please note that it is not an ordinary USB disk as shown below.

![](media/a2b53f93f4c24b81fc5cdb5986fd100d.png)

**Step 2: write programs**

View the link <https://makecode.microbit.org/> in your browser;

Click ‘New Project’;

The dialog box‘Create a Project’ appears, fill it with‘heartbeat’and click
‘Create √’to edit.

(If you are running Windows 10 system, it is also viable to edit on the APP
MakeCode for micro:bit , which is exactly like editing in the website. And the
link to the APP is
[https://www.microsoft.com/zh-cn/p/makecode-for-micro-bit/9pjc7sv48lcx?ocid=badgep&rtc=1&activetab=pivot:overviewtab](https://www.microsoft.com/zh-cn/p/makecode-for-micro-bit/9pjc7sv48lcx?ocid=badgep&rtc=1#activetab=pivot:overviewtab)
)

Take Google Chrome as an example as shown below and it is almost the same for
other browsers.

![](media/fd741a4a932cf25b5165c8135b512848.png)

![](media/f76062b0607cfca5d20bc26199b2f711.png)

Write a set of micro:bit code. You can drag some modules in the Blocks to the
editing area and then run your program in Simulator of MakeCode editor as shown
in the picture below which demonstrates how to edit ‘heartbeat’ program .

The path to the demonstration video:

.../2. Makecode Tutorial\\Makecode Code\\Project Code/Project 1：Heart beat

The next chapter will illustrate more details about Makecode.

![](media/215b27bc1633c62d16fe208e06e39ad9.png)

Click the arrow behind “JS JavaScript”to choose between“JavaScript”or
“Python”and you will find the corresponding program in JavaScript language or
Python language as shown below:

![](media/67b86dacacfb0d716068af592d79382a.png)

![](media/c3950b45a80b660c60d4ca8544c6acbd.png)

**Step 3: download code**

If your computer is Windows 10 and you have downloaded the APP MakeCode for
micro:bit to write program, what you will have to do to download the program to
your Micro: Bit main board is merely clicking the ‘Download’ button, then all is
done.

If you are writing program through the website, following these steps:

Click the ‘Download’ in the editor to download a "hex" file, which is a compact
program format that the Micro: Bit main board can read. Once the hexadecimal
file is downloaded, copy it to your board just like the process that you copy
the file to the USB driver. If you are running Windows system, you can also
right-click and select ‘Send to → MICROBIT(E:) ‘to copy the hex file to the
Micro: Bit main board.

![](media/c5b462b6e3acbfedf6c9b22e4651d69a.png)

![无标题](media/a81d4430eb152346d13bf67b2233b9db.png)

You can also directly drag the "hex" file onto the MICROBIT (E:) disk.

![无标题](media/fe0f2de72ba0b38f00403f1aaef7f514.png)

![无标题](media/b4f3602c0e192646f77b150e2acaf947.png)

During the process of copying the downloaded hex file to the Micro: bit main
board, the yellow signal light on the back side of the board flashes. When the
copy is completed, the yellow signal light will stop flashing and remain on.

**Step 4: run the program：**

After the program is uploaded to the Micro: bit main board, you could still
power it via the USB cable or change to via an external power. The 5 x 5 LED dot
matrix on the board displays the heartbeat pattern.

| ![7](media/672bfb4d87b938fc586a849bff0229fe.png) | ![8](media/d61a26d2f2367f0378974832f679efe1.png) |
|--------------------------------------------------|--------------------------------------------------|
| Power via USB cable                              | Power via external power (3V)                    |

**Caution:**

When you programs each time, the driver of Micro: bit will automatically eject
and return and your hexadecimal files will disappear . And the board can only
have access to hexadecimal files (hex) and save no other files.

**Step 5：about other programming languages**

This chapter has described how to use the Micro:bit main board.

But except for the Makecode graphical programming introduced you can also write
Micro:bit programs in other languages. Go to the link:
<https://microbit.org/code/> to know about other programming languages , or view
the link: <https://microbit.org/projects/>, to find something you want to have a
go.

## 5.2.Makecode：

Browse <https://makecode.microbit.org/> and enter Makecode online editor or open
the APP MakeCode for micro:bit of Windows 10.

![](media/285f5ee70c3d95855f87a17d227b8675.png)

Click“New Project”, and input“heartbeat”, then click “create √”to enter Makecode
editor, as shown below:

![IMG_256](media/5d8174f605724953bcb4a00edade8f30.png)

There are blocks“on start”and“forever”in the code editing area.

When the power is plugged or reset,“on start”means that the code in the block
only executes once, while“forever”implies that the code runs cyclically.

## 5.3 Quick Download

As mentioned before, if your computer is Windows 10 and you have downloaded the
APP MakeCode for micro:bit to write programs, the program written can be quickly
downloaded to the Micro: Bit main board by selecting ‘Download’.

While it is a little more trickier if you are using a browser to enter Makecode.
However, if you use Google Chrome, suitable for Linux，macOS and Windows 10, the
process can be quicker too.

We use the webUSB function of Chrome to allow the internet page to access the
hardware device connected USB.

You could refer to the following steps to connect and pair devices.

**Device pairing:**

Connect micro:bit to your computer by USB cable.

Click“...”beside“Download”and tap“Connect device”;

![Untitled](media/39effe268391a9a64558a0438f5f2fe5.png)

Click“Next”;

![](media/e843e223f125fdd0448c49d80e576d39.png)

Click another“Next”;

![](media/fe5c6991e1ba8bd46f0bc6b7069b91c1.png)

Then select the corresponding device and click“Connect”. If no devices shows up
for selection, please refer to:

[https://makecode.microbit.org/device/usb/webusb/troubleshoot](https://makecode.microbit.org/device/usb/webusb/troubleshoot%20)

And for updating the firmware of the Micro:bit:
[https://microbit.org/guide/firmware/](https://microbit.org/guide/firmware/%20)
.

If the links are too troublesome for you , then you can also turn to our
‘Troubleshooting Downloads with WebUSB’and“upload the firmware”in the folder we
provided in the link:

https://fs.keyestudio.com/KS4027-4028

![Untitled](media/4cf10fecd346658a9943e900eef2e265.png)

Click“Done”to finish the pairing.

![](media/0b3776a491c27034738926b3f958b3f0.png)

![](media/37f01f5a75b4127a193a1099bdd142d3.png)

**Download program:**

After the pairing, click “download”to directly download the program to the
board. If it is successfully downloaded, the icon
![](media/af296c6d48f189a98fcb96522182ffa9.png) will shift to
![](media/c55e4d43d82301258cbc0367cb3b3d49.png).

![Untitled](media/96fbd5a50eb87de8ad464cbbd09624f1.png)

## 5.4.Makecode extension library:

For your convenience, we have made a makecode extension library for this smart
home kit.

**Add smart home extension library:**

Please follow the following steps to add extension files:

Open Makecode to enter a certain project→click the gear-shaped icon(for setting)
in the upper right corner→choose “Extensions”;

![Untitled](media/9bee14f94789507ec63f56c322c8ad88.png)

Or click”Advanced”to select “Extensions”as shown below:

![](media/b78a1ba52cf7d70976961bbf12e846ba.png)

Input the link <https://github.com/keyestudio2019/ks_IoT> to search;

Tap the searching result “IoT_keyestudio” to download and install it;

This process may take a few seconds.

![](media/ece90bfd9eb4023e7004dfba4abca5ae.png)

After the installation, you can find the extension files DHT11/DHT22 and
I2C_LCD1602 on the left side.

And extension file Neopixel is also installed.

![](media/0d4d6d7e47085561894a8beb35312f65.png)

![](media/72ec32002774ab76c5d2f2c98cc8cabd.png)

![](media/fbf4a61770a2950b5857e17afd88b2e9.png)

Note: the extension files added are only available for this project. Therefore,
when you create a new **IoT_keyestudio** project, you will need to add these
extension files again.

**Update or delete the IoT_keyestudio extension files:**

Please follow the following steps to update or delete extension files:

Click "Js JavaScript" to change to textual version:

![](media/9d00388b4e88a55f44d36f0d46d2d20d.png)

Click the “Explorer”on the left side:

![](media/a061d1ac034c0767eb5037c9c5f2c8e9.png)

You can find these added files in the list;

Click the dustbin icon beside the file to delete the corresponding file;

Tap the refresh icon to update the corresponding IoT_keyestudio extension file.

![](media/818a03c369319240dc38e23af5c21ec2.png)

## 5.4.Resources and test code

We also provide a link：https://fs.keyestudio.com/KS4027-4028

containing the information of the product from relevant tools to test codes,
tutorials and troubleshooting methods as well, as shown in the figure below:

![](media/f7cc0f0ff37a6267dce479048ae6c655.png)

## 5.5.Input test code

We provide hexadecimal code files (project files) for each project. The file
contains all the contents of the project and can be imported directly, or you
can manually drag the code blocks to complete the program for each project. For
simple projects, dragging a block of code to complete the program is
recommended.For complex projects, it is recommended to conduct the program by
importing the hexadecimal code file we provide.

Let's take the "Heatbeat" project as an example to show how to load the code.

Open the Web version of Makecode or the Windows 10 App version of Makecode;

![](media/40e8e36d4a7e9b8a726ff1a832393df5.png)

Click“Import File”;

![](media/3358909f898dd9898923f72945613851.png)

![](media/ff66d0d78d170913676e361a62078faf.png)

Select“../Makecode Code/Project 1\_ Heart beat/Project 1\_ Heart beat.hex”

Then click “Go ahead”.

![](media/c919527e842cb6dd603a03b8f850a7f8.png)

![](media/b5f985386359a415c102d3deefecce53.png)

In addition to importing the test code file provided into the Makecode compiler
above, you can also drag the the test code file provided into the code editing
area of the Makecode compiler, as shown in the figure below:

![dsBuffer.bmp](media/115cceaf5de0eb4f2079ca09681dbb7c.png)

After a few seconds, it is done.

![](media/a451132713cbd16f3f7957c5312673ba.png)

Note: if your computer system is Windows7 or 8 instead of Windows 10, the
pairing cannot be done via Google Chrome. Therefore, digital signal or analog
signal of sensors and modules cannot be shown on the serial port simulator.
However, you need to read the corresponding digital signal or analog signal.So
what can we do? You can use the CoolTerm software to read the serial port data
of the microbit. Next chapter is about how to install CoolTerm.

## 5.6. Install CoolTerm：

CoolTerm program is used to read the data on serial port.

Download CoolTerm program:

<https://freeware.the-meiers.org/>

After the download, we need to install CoolTerm program file, below is PC Window
system taken as an example.

1.  Choose“win”to download the zip file of CoolTerm

2.  Unzip file and open it. (also suitable for Mac and Linux system)

![](media/97f831d38df9ee01dcfedac244bfe281.png)

![IMG_256](media/e77548d01727e523e9e8c900d2fa962d.png)

1.  Double-click![](media/5f29eed25fc16602cfc0716f047c2da1.png).（please make
    sure that the driver of Micro:bit is installed and the main board is
    connected with the computer.)

![](media/74fd81c83f0c0a26b4e299b93ce4ede4.png)

The functions of each button on the Toolbar are listed below:
<http://wiki.keyestudio.com/index.php/File:IDE.png>

![](media/70bebd79d7cd20336ae394c916500a28.png)

| ![](media/2b728375ed2b8cd288c884e553418001.png)        | Open up a new Terminal                           |
|--------------------------------------------------------|--------------------------------------------------|
| ![](media/5f972f2eac5050ca0107416b2be067c2.png)        | Open a saved Connection                          |
| ![](media/be6f8b560e0afc447f9c32b4474f633f.png)        |  Save the current Connection to disk             |
| ![IMG_256](media/52257d028694a313fc4eea4d9c2469d7.png) | Open the Serial Connection                       |
| ![IMG_256](media/6ad366842b18084553a142ab82a613cf.png) | Close the Serial Connection                      |
| ![IMG_256](media/8fa3ac342549d33b6c9aa5a9e4688bea.png) | Clear the Received Data                          |
| ![IMG_256](media/c8d1dd8c3356b4938e143de1022e5842.png) | Open the Connection Options Dialog               |
| ![IMG_256](media/36e13c266fd4b9723d9db40fe30cd203.png) | Display the Terminal Data in Hexadecimal Format  |
| ![](media/b505c71c3344036730b1d67f0c62a354.png)        | Display the Help Window                          |

6.Install the Smart Home

| **Part 1**                                               |                                                                                                                                                                                                                                                                                                        |        |
|----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
|  Components Needed                                       |  ![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第一部分.jpg！_第一部分](media/123d0bb2dd100c6a112fcab1e0dc2203.jpeg)                                                                                                                                 |        |
|  Installation Diagram                                    | ![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第一部分安装.jpg！_第一部分安装](media/f598262f06657a3013ea7e890b6c3bf5.jpeg)                                                                                                                          |        |
|  Prototype                                               | ![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第一部分完成.jpg！_第一部分完成](media/f4080989a9c22fab97bb7f84ff1509fb.jpeg) （wire up the 1602 LCD, as shown below） ![ef7d6ce5e6c7408c956d14399d8504e](media/0bae113cf2bd840be13265b24f0c326f.jpeg) |        |
| **Part 2**                                               |                                                                                                                                                                                                                                                                                                        |        |
|   Components Needed                                      |  ![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第二部分.jpg！_第二部分](media/242142caa5724135b985427f1b0e7ce9.jpeg)                                                                                                                                 |        |
|    Installation Diagram                                  | ![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第二部分安装.jpg！_第二部分安装](media/b2e099af204a4bcb92a1b71d5abf5653.jpeg)                                                                                                                          |        |
|    Prototype                                             | ![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第二部分完成.jpg！_第二部分完成](media/a2d5f6af77a253eede36f93b3cab82f1.jpeg)                                                                                                                          |        |
| **Part 3**                                               |                                                                                                                                                                                                                                                                                                        |        |
|  Components Needed                                       | ![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第三部分.jpg！_第三部分](media/ec801c1a812f6255ebd266a78ed20e4c.jpeg)                                                                                                                                  |        |
|   Installation Diagram                                   |  ![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第三部分安装.jpg！_第三部分安装](media/a9b432e5c26a594bfbf81a1011071511.jpeg)                                                                                                                         |        |
|   Prototype                                              |  ![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第三部分完成.jpg！_第三部分完成](media/c4505fa11b62de60ec16b00b25854a5d.jpeg)                                                                                                                         |        |
| Adjust the angle of the servo controlling windows to 0°  | **Wiring：** Micro:bit Expansion Board                                                                                                                                                                                                                                                                 | Servo  |
| GND                                                      | Brown Wire                                                                                                                                                                                                                                                                                             |        |
| 5V                                                       | Red Wire                                                                                                                                                                                                                                                                                               |        |
| S（9）                                                   | Orange Wire                                                                                                                                                                                                                                                                                            |        |

Connect the main board with the shield and with the computer via USB cable;

Plug them up;

Turn the slide switch on the board to the “ON”end, and the rocker switch to the
“1”end.

![IMG_256](media/ed04ea1ea546dbfe97586822882c99f3.jpeg)

**Example code：**

![](media/74148846f4d17d3b2011d0aa90b301e1.png)

After uploading the example code to Micro:bit, the angle of the servo is set to
0°.

**Part 4**

Components Needed (peel the sticker off the gear-shaped Acrylic board first)

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第四部分.jpg！_第四部分](media/c4e1cde64c3fd91d30dc2a8d7174cd9c.jpeg)

Installation Diagram

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第四部分安装.jpg！_第四部分安装](media/d86f9aa6d0f415643629b747471e6cbb.jpeg)

Prototype

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第四部分完成.jpg！_第四部分完成](media/5cf8e8d0cb992c857704eaf3e7b35046.jpeg)

**Part 5**

Components Needed

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第五部分.jpg！_第五部分](media/fca723b6025c4d68e2329e285aab2e31.jpeg)

Installation Diagram

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第五部分安装.jpg！_第五部分安装](media/2a2f1ebb390afdfcd5819e5c18218b75.jpeg)

Prototype

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第五部分完成.jpg！_第五部分完成](media/5a27f78056cce42948eb52f82069e40a.jpeg)

**Part 6**

Components Needed

(peel the sticker off the Acrylic board first)

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第六部分.jpg！_第六部分](media/f52ff0e7e0650b901a8bff6e40eec2b3.jpeg)

Installation Diagram

(The gears of the N Board should be properly jointed with the wooden gear and do
not fix the self-locking nut tight; after installation, the door is closed.）

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第六部分安装.jpg！_第六部分安装](media/da2272a3e51c9e2a02d36293a72da977.jpeg)

Prototype

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第六部分完成.jpg！_第六部分完成](media/92f9f949c080cc89f298781be7532e05.jpeg)

**Part 7**

Components Needed

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第七部分.jpg！_第七部分](media/458550d18ab28ef0a81c0611f74bda60.jpeg)

Installation Diagram

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第七部分安装.jpg！_第七部分安装](media/e30fee21f227157cc5bc0e777a4ea442.jpeg)

Prototype

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第七部分完成.jpg！_第七部分完成](media/2c119f1d452112a574682e3d3a915f50.jpeg)

**Part 8**

Components Needed

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第八部分.jpg！_第八部分](media/a0f688fda0d7aec152e8a655c7bfc663.jpeg)

Installation Diagram

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第八部分安装.jpg！_第八部分安装](media/f87a6ea4f7582ec159ac234880db4297.jpeg)

Prototype

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第八部分完成.jpg！_第八部分完成](media/7f79470a49224d41e3e0cabb593ed8f6.jpeg)

**Part 9**

Components Needed

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第九部分.jpg！_第九部分](media/423507f7618c8ca6c443dc50e2faf562.jpeg)

Installation Diagram

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第九部分安装.jpg！_第九部分安装](media/95b9ae04325d8384854514100731577f.jpeg)

Prototype

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第九部分完成.jpg！_第九部分完成](media/395c8a379018d036856a721005e8cf33.jpeg)

**Part 10**

Components Needed

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第十部分.jpg！_第十部分](media/68548685a63dbfff5e13fc68e335619e.jpeg)

Installation Diagram

(stick the solar panel along the right side of the line marked in the picture;
pull the wires on the panel out from the hole in the middle.)

![](media/b57fa2f1cedde558ad04de3916b1e187.png)

Prototype

![1](media/f42dbc85b50a2737287286fa8e57362a.jpeg)

**Part 11**

Components Needed

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第十一部分.jpg！_第十一部分](media/3e26469ef8bf8b5dc361a7315833ec54.jpeg)

Installation Diagram

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第十一部分安装.jpg！_第十一部分安装](media/c09c75d05a3ef97858c7da2f3a69712f.jpeg)

Prototype

![C:\\Users\\Administrator\\Desktop\\熊巍\\创客教育组\\项目\\新智能家居\\安装步骤\\安装图片\\！_第十一部分完成.jpg！_第十一部分完成](media/299b316c713a3b56d5d28de5bcd4ea97.jpeg)

**Part 12**

Components Needed

![！_第十二部分](media/c1fa17b061c9e8140e65eb1afe320cca.jpeg)

Installation Diagram

![！_第十二部分安装](media/708c8757ce0318746508ed845eb40bc1.jpeg)

Prototype

![！_第十二部分完成](media/343332699bba9b2701b3be0c97b9878a.jpeg)

**Part 13**

Components Needed

![！_第十三部分](media/3c7f391571c4fc8bc0d8ae5d0a09d392.jpeg)

Installation Diagram

![！_第十三部分安装](media/a2038986efd53765acd444e3c5c185fe.jpeg)

Prototype

![！_第十三部分完成](media/b1e6af115562a1c5f331057d879d59b6.jpeg)

**Part 14**

Components Needed

![！_第十四部分](media/211f5064600cd9be237536c92b3e4909.jpeg)

Installation Diagram

![！_第十四部分安装](media/7dcda07aed625bc324e878fab036f2e0.jpeg)

Prototype

![！_第十四部分完成](media/16d58658922bcdc66079eb9b39edade4.jpeg)

**Part 15**

Components Needed

![！_第十五部分](media/9cb36007b3cfad984ba31086f278f771.jpeg)

Installation Diagram

![！_第十五部分安装](media/23e54197e618c6d4f6e2aaaebae23382.jpeg)

Prototype

![！_第十五部分完成](media/9aba461dd63ba101851411d5add219dd.jpeg)

**Part 16**

Components Needed

![！_第十六部分](media/aae2c6783f7d47b047e8949080515c24.jpeg)

Installation Diagram

![！_第十六部分安装](media/d3a4d49d710206357e2ae7d34888e077.jpeg)

Prototype

![！_第十六部分完成](media/ab8c06e24f7dfee541a81069a4b7c6f0.jpeg)

**Part 17**

Component Needed

![！_第十七部分](media/00db16085eb865e5e24b707b7c62701d.jpeg)

Installation Diagram

![2](media/b69109869c6340019eb85c4b4e1eb4a3.jpeg)

Prototype

![！_第十七部分完成](media/c9aca89336d5abbb24d89f779d861322.jpeg)

**Part 18**

Components Needed

![！_第十八部分](media/a582e7389114ca21482b571f8f796904.jpeg)

Installation Diagram

![！_第十八部分安装](media/7a1aed92d569d14f286edfb3b07b45c4.jpeg)

Prototype

![！_第十八部分完成](media/3df7bde0937018ca032c8dd5a66e681a.jpeg)

**Part 19**

Components Needed

(peel the sticker off the Acrylic board first)

![！_第十九部分](media/13309291230b405a6752cfd8ad888756.jpeg)

Installation Diagram

![！_第十九部分安装](media/082451d4426d27f862a68a5a659db8ba.jpeg)

Prototype

![！_第十九部分完成](media/74e46ec89eb9e5c0bbc80eec023b9a80.jpeg)

**Part 20**

Components Needed

![！_第二十部分](media/e1d9b993301caae84a1bb13cd79a6ea6.jpeg)

Installation Diagram

![！_第二十部分安装](media/79d73d05c4b721eacd32328b1b9000aa.jpeg)

Prototype

![！_第二十部分完成](media/a243f8c97d1badb7e4a9907cafc5803b.jpeg)

**Part 21**

Components Needed

![！_第二十一部分](media/a55addd599ae6af15688e7de11bb2d17.jpeg)

Installation Diagram

![！_第二十一部分安装](media/8c4afdddcff669db10aafb06cdabf693.jpeg)

Prototype

![！_第二十一部分完成](media/26848fae53908dc5eca30b27987fbe89.jpeg)

**Start Wiring**

The wiring of the battery holder

(plug its jack to the BAT end of the rechargeable power module)

![cb8c1554135811286767d2a42b2880d](media/4897d617bcd7a3b1dffc73be11ddb8a9.jpeg)

![](media/54c30cd9df2b6d77cd9aba5a7c797977.png)

![](media/154648ebbf3b28a0e8ca68be0e61460f.png)

The wiring of the yellow LED

![aa334cbf32c9effe78b2e4796e05310](media/7d3578cebec69df3ae0f4d1f0b4cf551.jpeg)![C:/Users/Administrator/AppData/Local/Temp/picturecompress_20210806091342/output_1.jpgoutput_1](media/66b00a17346c1f04ad00c7449d99eef0.jpeg)

![IMG_256](media/22a8451e674da7f486410974c10b88f4.png)

The wiring of the RGB module

![3e485e00ca9e8695c4b113c8c724e8a](media/e465549002b852ddb1ebfdebfa4de0f6.jpeg)![C:/Users/Administrator/AppData/Local/Temp/picturecompress_20210806091438/output_1.jpgoutput_1](media/4031d8ea455995dafe6a62ea7cbfbdee.jpeg)

![IMG_256](media/433900d113f60cb9adb8f1c3d73cb510.png)

The wiring of the PIR motion sensor

Use the longer Dupont wire

![23599a31a9a21a3e2715add9ac5bc55](media/16cb55b79777563bdd3b079f11e3f6d0.jpeg)![C:/Users/Administrator/AppData/Local/Temp/picturecompress_20210806091533/output_1.jpgoutput_1](media/bd8ecd2293d3f323c9d73ddede2c6f18.jpeg)

![IMG_256](media/99e198c130c51804c9dd4237529fa947.png)

The wiring of the 1602LCD

![ef7d6ce5e6c7408c956d14399d8504e](media/01f31e8172ae900f01de669749c3e2d9.jpeg)![C:/Users/Administrator/AppData/Local/Temp/picturecompress_20210806091556/output_1.jpgoutput_1](media/89d3143c93e1cbee66d4358427e0dcc9.jpeg)

![IMG_256](media/36f7c0f0542d0d172d2657b35e9d1ca8.png)

The wiring of the analog gas sensor

![88b1ec43f948b822c0d56354a1fd194](media/fdd2405e31b6c6d420aa150f96cc8616.jpeg)![C:/Users/Administrator/AppData/Local/Temp/picturecompress_20210806091624/output_1.jpgoutput_1](media/06abba36593d624f2160510b4e9c50f0.jpeg)

![IMG_256](media/108f501eb3833514b3f687d26d8037f4.png)

The wiring of the humidity and temperature sensor

Use the longer Dupont wire

![54692b56d2983e1ff24bb2cdc67824d](media/663f8978927cfabfe3abfd5d8a3536f5.jpeg)![C:/Users/Administrator/AppData/Local/Temp/picturecompress_20210806091700/output_1.jpgoutput_1](media/ea300faea14b38886b14c2a2d2fd6852.jpeg)

![IMG_256](media/38d05d1f009604d9a4b39d4c3e3df96d.png)

The wiring of the servo controlling the door

![C:/Users/Administrator/AppData/Local/Temp/picturecompress_20210806091758/output_1.jpgoutput_1](media/4813f5dd2f3179d76e1fffaa5bae9476.jpeg)

![IMG_256](media/9c0782ddd631d98862a07249c221622a.png)

The wiring of the servo controlling the window

![a068e0fa63eef8e4c7d9376796b0f1a](media/d0c4ff4c7daa5029d162567f730bb1a1.jpeg)![C:/Users/Administrator/AppData/Local/Temp/picturecompress_20210806091827/output_1.jpgoutput_1](media/9aa8ea49a7d62973117c5ec29e6db4cf.jpeg)

![IMG_256](media/606280c54c14b3d6daba4a613c5b34ad.png)

The wiring of the rechargeable lithium battery power module (Connect the shield
with it; attach the red wire to V and the black one to G.）

![](media/e7db1e1e1a0a1f17a3a34372312d6f60.png)

![](media/c33d0cd3eaaacee384f2bd842099bd41.png)

![1381ef64bec45c99a61a415c336ebfc](media/98c0a54bec25cee42fc60adfcee0cd32.jpeg)

The wiring of the solar panel

![](media/c56e7d4227e840076408e46a39dfb8a3.png)

![](media/d5d2e2bb699061ec593c80370b077ee5.png)

![](media/5c13c134f86bd80eaed8d4e9d257ad05.png)

The wiring of the motor (Please pay attention to the pins and the connection
cannot be reversed.)

![5a9676493c388feb8c7c835afc3db33](media/29a6be7fb5a2e00092567c0eee834fab.jpeg)![](media/14877d0e2b9eaa6df5bdadacdc3eb442.png)

![](media/f269672e09aa49569d90f97b63c3c7d7.png)

The wiring of the steam sensor

(Connect it to the P0 of 3.3V or the analog value can not be read.)

![IMG_256](media/33cba18f520d97b9c0d429b437f12bbe.jpeg)![](media/04baa65c05c2350075814a2546a8f1c6.png)

![](media/1e27f23139327bdc7636fde376cb66cf.png)

**Mount the Roof**

Components Needed

![！_第二十二部分](media/63e234ef6d2dbb21476207084e853503.jpeg)

Installation Diagram

![！_第二十二部分安装1](media/1c0a4a05612051b0569c9f38f5b86b26.jpeg)

Prototype

![！_第二十二部分安装1完成](media/155bd1cb7793e1ffd8b76030d37287ad.jpeg)

Installation Diagram

![！_第二十二部分安装2](media/2e49c13915d2b94ae6c98878283c9a5a.jpeg)

Prototype

![！_第二十二部分安装2完成](media/df97e2bf16f1ec754934f607318d0c6a.jpeg)

Install Micro:bit main board

![！_第二十二部分安装3](media/1afde626df327cdad5466a5008902058.jpeg)

Prototype

![！_第二十二部分完成（总装完成）](media/07a2c3b46c7920d96552f00f69406460.jpeg)

# Project：

## Project 1: Heartbeat

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

1.  **Project Introduction**

This project is easy to conduct with a micro:bit main board, a Micro USB cable
and a computer. The micro:bit LED dot matrix will display a relatively big
heart-shaped pattern and then a smaller one. This alternative change of this
pattern is like heart beating. This experiment serves as a starter for your
entry to the programming world.

**(2)Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Path                                                                             | File Name                 |
|-----------|----------------------------------------------------------------------------------|---------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 1：Heart beat | Project 1：Heart beat.hex |

You can also drag blocks to form code. No need to worry though you are not good
at programming.

Firstly, you can view this link
[https://makecode.micro:bit.org/reference](https://makecode.microbit.org/reference)
to find more information about micro: bit blocks. Then this link
[https://makecode.micro:bit.org/](https://makecode.microbit.org/) can help you
write code.

**Command blocks can be found on the right:**

![](media/ac78c9efa592693d1a0d6a3f06873e8c.png)

Make combinations of these blocks:

![](media/7cbc1fb718ea873d5e9bba7aaf2b01ea.png)

Click the arrow behind“JS JavaScript”to select between“JavaScript”and “Python”to
show the code in JavaScript language or Python language:

![](media/00e2115f7e171c91af90f27889395dde.png)

![](media/a938b288e7e24846aac80d6890a7c9a0.png)

**(5)Test Results:**

After uploading test code to micro:bit main board and keeping the connection
with the computer to power the main board, the LED dot matrix shows
pattern“![](media/f496ba08ff8af3164cdbd5fc56cc5abb.png)”and
then“![](media/04fdfc9060943954e7938bb1a741d626.png)”alternatively.

( Please refer to chapter 5.3 to know how to download test code quickly.)

If the downloading is not smooth, please remove the USB cable from the main
board and then reconnect them and reopen Makecode to try again.

**Project 2: Light A Single LED**

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

1.  **Project Introduction**

In this project, we intend to control a certain LED of the micro:bit main board
to shine.

**(2)Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Introduction of components:**

The LED dot matrix consists of 25 LEDs arranged in a 5 by 5 square. In order to
locate these LEDs quickly, as the figure shown below, we can regarded this
matrix as a coordinate system and create two aces by marking those in rows from
0 to 4 from top to bottom, and the ones in columns from 0 to 4 from the left to
the right. Therefore, the LED sat in the second of the first line is (1,0）and
the LED positioned in the fifth of the fourth column is (3,4）and others
likewise.

![](media/fe710eb3e622ac0e3544576acce9f03f.png)

**(5)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                    | File Name                         |
|-----------|------------------------------------------------------------------------------------------|-----------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 2：Light A Single LED | Project 2：Light A Single LED.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/65344f5c09b6100e39bd5c3749ea7c23.png)
![](media/aeb54a37d5588a71cac95a25fde1ff4a.png)

![](media/fe86356d61cade8641f76f9db5e8e7f0.png)

Make combinations of these blocks:

![](media/39f056dc915f09a2cd4cea1587684b85.png)

**(6)Test Result**

After uploading test code to micro:bit main board and powering the main board
via the USB cable, the LED in (1,0) lights up for 1s and the one in (3,4) shines
for 1s and repeat this sequence.

**Project 3: LED Dot Matrix**

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

1.  **Project Introduction**

Dot matrices are very commonplace in daily life. They have found wide
applications in LED advertisement screens, elevator floor display, bus stop
announcement and so on.

The LED dot matrix of Micro: Bit main board contains 25 LEDs in a grid.
Previously, we have succeeded in controlling a certain LED to light by
integrating its position value into the test code. Supported by the same theory,
we can turn on many LEDs at the same time to showcase patterns, digits and
characters.

What’s more, we can also click”show icon“ to choose the pattern we like to
display. Last but not the least, we can design patterns by ourselves as well.

**(2)Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the Micro USB cable.

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name                     |
|-----------|--------------------------------------------------------------------------------------|-------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 3：LED Dot Matrix | Project 3：LED Dot Matrix.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/0d6882d9ef08e1cf56a8bd73c768d9c2.png)

Make combinations of these blocks:

![](media/d73b631e743d7bcef480068e70e140e8.png)

**(5)Test Result:**

After uploading test code to micro:bit main board and powering the main board
via the USB cable, we find that the 5\*5 dot matrix start to show numbers
1,2,3,4 and 5, and then it alternatively shows a downward arrow
![](media/2d4524f650129197874d4d62985e47c6.png), word “Hello”, a heart pattern
![](media/9b18b2b8dfaa0533d8859d08ff12611e.png), an arrow pointing at northeast
![IMG_256](media/364f2e355d6c354155b2e6db80830a62.png), then at southeast
![](media/fb3ba009a20245ab6076e537159a229c.png), then at southwest
![](media/7ec21961398787ca5155f0648bbd82cc.png), and then at northwest
![](media/ced0bb410c8269205fe18554aa2c9926.png).

**Project 4: Programmable Buttons**

![](media/06be84fb11b1fd07cd0cbb392132b903.png)

1.  **Project Introduction**

Buttons can be used to control circuits. In an integrated circuit with a push
button, the circuit is connected when pressing the button and it is open the
other way around.

Micro: Bit main board boasts three push buttons, two are programmable
buttons(marked with A and B), and the one on the other side is a reset button.
By pressing the two programmable buttons can input three different signals. We
can press button A or B alone or press them together and the LED dot matrix
shows A,B and AB respectively. Let’s get started.

1.  **Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                      | File Name             |
|-----------|--------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 4：Programmable Buttons | Project 4：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/692855e3fe76aab1d8f0d120de9568b6.png)
![](media/e8c25665bb483f21a1f6c721626dab35.png)

Make combinations of these blocks:

![](media/01444f089d9ea4c81168fe5d5df27a93.png)

**(5)Test Result 1:**

After uploading test code to micro:bit main board and powering the main board
via the USB cable, the 5\*5 LED dot matrix shows A if button A is pressed and
then released, B if button B pressed and released, and AB if button A and B
pressed together and then released.

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                      | File Name             |
|-----------|--------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 4：Programmable Buttons | Project 4：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/72ac10a0b5e013d094e2c4d7392ae352.png)
![](media/0770dd8923359e6ed7cc6610de93555c.png)

![](media/2d58c013226b989c07a5ecacf669f026.png)
![](media/edd6f8b1577835b623ebb72dbca83e62.png)

![](media/50f89239057ac521950b5f110647f443.png)

Make combinations of these blocks:

![](media/306b715cb45327d906419eafcf1af521.png)

**(7)Test Result 2:**

After uploading test code to micro:bit main board and powering the main board
via the USB cable, when the button A is pressed, the LEDs turning red increase
while when the button B pressed, the LEDs turning red reduce.

**Project 5: Temperature Detection**

![](media/206c8ec1c3f11d2de8d0f42fdf5b6b47.png)

1.  **Project Introduction**

The Micro:bit main board is not equipped with a temperature sensor, but uses the
temperature sensor built into NFR52833 chip for temperature detection.
Therefore, the detected temperature is more closer to the temperature of the
chip, and there maybe deviation from the ambient temperature. The sensor can
detect temperature of external environment with the range of 40℃\~105℃.

1.  **Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                       | File Name             |
|-----------|---------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 5：Temperature Detection | Project 5：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/28c0c3261e05e7d512858b49acf48988.png)
![](media/3070e71d489e1626b97cff9049c106db.png)

![](media/76c43e7cd320c9d19e60450c9a42c902.png)

Make combinations of these blocks:

![](media/e1e316ab2c9727c9b5a36dd82a7ab11a.png)

**(5)Test Result 1：**

After uploading test code 1 to micro:bit main board, powering the main board via
the USB cable, and clicking“Show console Device”, the data of temperature shows
in the serial monitor page as shown below.

![](media/a4763cbc3f2ec740ccf244319118eb95.png)

When you touch the processor nNRF52833 on the board for a while, its temperature
will rise gradually and the CoolTerm serial monitor will show the change of
temperature in the current environment, as shown in the figures below :

![](media/c2b124723b6dc8ca80e3a6537e9365ba.png)

If you're running Windows 7 or 8 instead of Windows 10, via Google Chrome won't
be able to match devices. You'll need to use the CoolTerm serial monitor
software to read data.

You could open CoolTerm software, click Options, select SerialPort, set COM port
and put baud rate to 115200 (after testing, the baud rate of USB SerialPort
communication on Micro: Bit main board is 115200), click OK, and Connect. The
CoolTerm serial monitor shows the change of temperature in the current
environment, as shown in the figures below :

![无标题](media/b3a18bca1b2a7b5337470735e5a0c5aa.png)

![无标题](media/f78128c148de3862a3fe10d86f063e22.png)

![无标题](media/13238e98c31d620f4ffd7742dd71c78d.png)

![](media/43c0b63e21f6d5e701d603f5f38e530e.png)

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                       | File Name             |
|-----------|---------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 5: Temperature Detection | Project 5：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/6f1dd442a876e18ba91c775d0b838635.png)
![](media/803d39cec781e323ec6c49aba7853846.png)

![](media/3070e71d489e1626b97cff9049c106db.png)
![](media/a74e2faccc9921d75270d6440f686fb8.png)

Make combinations of these blocks:

(Please note that the value 35 in the statement below can be changed according
to real situation.)

![](media/cd83c3647fe7044fb13add0957b9d89e.png)

1.  **Test Result 2:**

After uploading the code 2 to the board, when the ambient temperature is less
than 35℃, the 5\*5 LED dot matrix shows
![](media/4b1765e12b413dc5d562f2a16d32392f.png). When the temperature is
equivalent to or greater than 35℃, the
pattern![](media/f2705fbc4886efcfaac96589ca255f66.png) appears.

**Project 6: Geomagnetic Sensor**

![](media/24c31bb0174e2ac672203e5c36c6875e.png)

1.  **Project Introduction**

This project aims to explain the use of the Micro: bit geomagnetic sensor, which
can not only detect the strength of the geomagnetic field, but also be used as a
compass to find bearings. It is also an important part of the Attitude and
Heading Reference System (AHRS).

Micro: Bit main board uses LSM303AGR geomagnetic sensor, which supports four
modes namely 100 kHz,400 kHz,1 MHz and 3.4 MHz and the dynamic range of magnetic
field is ±50 gauss.

In the board, the magnetometer module is used in both magnetic detection and
compass. In this experiment, the compass will be introduced first, and then the
original data of the magnetometer will be checked.The main component of a common
compass is a magnetic needle, which can be rotated by the geomagnetic field and
point toward the geomagnetic North Pole (which is near the geographic South
Pole) to determine direction.

Attention: this geomagnetic sensor built in the board can help us determine
bearings by showing readings in the value from 0 to 360. And the system will ask
us to calibrate it the first time it is put into operation by rotating the
board.Please note that metal materials around may attenuate the accuracy of the
reading and calibration.

**(2)Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                    | File Name             |
|-----------|------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 6：Geomagnetic Sensor | Project 6：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/f133f96ecbab58bbdf67524fdea8dd06.png)
![](media/bfcdd73df2de99f489b53a943e08debf.png)

![](media/444745d070942a94e096e4e14ce170a4.png)

Make combinations of these blocks:

![](media/4d6f5e8725ef37d1a4a6f7567849d8c3.png)

Note: it is imperative to calibrate the Micro:bit board for different
geomagnetic fields existing in different places. And the system will make an
automatic requirement if it is used for the first time.

**(5)Test Result1：**

After uploading Test Code 1 to micro:bit main board and powering the board via
the USB cable, and pressing the button A, the board asks us to calibrate compass
and the LED dot matrix shows “TILT TO FILL SCREEN”. Then enter the calibration
page. Rotate the board until all 25 red LEDs are on as shown below.

![1(5)](media/acf3b8c0dee027d9e555fc708831f874.jpeg)

After that, a smile pattern
![IMG_256](media/55ad39536dff7bdf66379a1da7a4c137.png) appears, which implies
the calibration is done. When the calibration process is completed, pressing the
button A will make the magnetometer reading display directly on the screen. And
the direction north, east, south and west correspond to 0°, 90°, 180° and 270°
respectively.

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                        | File Name             |
|-----------|----------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Tutorial/Project Code/Project 6: Geomagnetic Sensor | Project 6：Code-2.hex |

![](media/66c4482e3bcd71e712a54f4d73044104.png)

This module can keep reading data to determine direction, so does point to the
current magnetic North Pole by arrow.

![](media/d1a4e9f62bdf690ba809ae35c347b233.png)

For the above picture, the arrow pointing to the upper right when the value
ranges from 292.5 to 337.5. Because 0.5 can’t be input in the code, the values
we get are 293 and 338.

Then add other statements to make a set of complete code.

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/3720a2ee4a14d8e93f1e75d3ce697ade.png)
![](media/c60e9564b3912849511d7550e307f25c.png)

![](media/107ea0e69966ae8a5e198dcf31cb2293.png)
![](media/7bdf6cce3ae0f91c75c420ab44c29c57.png)

![](media/283d5470c7a3ccd095f14fa8bdce526f.png)

Make combinations of these blocks:

![](media/05d50822bb14445e292471642dc0170d.png)

![](media/dfffc7d3a9d1ce55f4c27aa1067aa635.png)

![](media/3d333244fea33b607327c4334c886d98.png)

**(7)Test Result 2:**

Upload code 2 and plug micro:bit into power. After calibration, tilt micro:bit
board, and the LED dot matrix displays the direction signs.

**Project 7: Accelerometer**

![](media/24c31bb0174e2ac672203e5c36c6875e.png)

1.  **Project Introduction**

The Micro: Bit main board V2 has a built-in LSM303AGR gravity acceleration
sensor, also known as accelerometer, with a resolution of 8/10/12 bits. The code
section sets the range to 1g, 2g, 4g, and 8g.

We often use accelerometer to detect the status of machines.

In this project, we will introduce how to measure the position of the board with
the accelerometer. And then have a look at the original three-axis data output
by the accelerometer.

1.  **Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)Attach the Micro:bit main
board to your computer via the USB cable.

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name             |
|-----------|--------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 7：Accelerometer  | Project 7：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/2213a02053bc1eb939854d28ddb9eaf0.png)
![](media/a2dada106cdd0c950024b884e3ad9102.png)
![](media/69ef2fc14c29ee8d8273ec04173fae17.png)

Make combinations of these blocks:

![](media/b630c9c381f5182ea7a8ef8b2834d519.png)

**(5)Test Result 1：**

After uploading the test code 1 to micro:bit main board and powering the board
via the USB cable, if we shake the Micro: Bit main board，no matter at any
direction, the LED dot matrix displays the digit “1”.

When it is kept upright （make its logo above the LED dot matrix）, the number 2
shows.

![\_DSC3687](media/1600323e3e61e331c248cbeda5ccdcfc.jpeg)

When it is kept upside down( make its logo below the LED dot matrix) , it shows
as below.

![\_DSC3688](media/3be80acf957e53117f695801ce19c449.jpeg)

When it is placed still on the desk, showing its front side, the number 4
appears.

![\_DSC3689](media/5797dd7be9a9c2d3226123e0c29db0bd.jpeg)

When it is placed still on the desk, showing its back side, the number 5
exhibits.

When the board is tilted to the left , the LED dot matrix shows the number 6 as
shown below.

![\_DSC3703](media/326095934bcff0a925b4f9a09d6cf7d2.jpeg)

When the board is tilted to the right , the LED dot matrix displays the number 7
as shown below：

![\_DSC3697](media/185b0ac204e9b2c54dd8fa93d852568c.jpeg)

When the board is knocked to the floor, this process can be considered as a free
fall and the LED dot matrix shows the number 8. (Please note that this test is
not recommended for it may damage the main board.)

Attention: if you’d like to try this function, you can also set the acceleration
to 3g, 6g or 8g. But still ,we do not recommend.

1.  **Test Code 2：**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                               | File Name             |
|-----------|-------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 7：Accelerometer | Project 7：Code-2.hex |

You can edit command blocks yourself

**Command blocks:**

![](media/3edd89b699b2e9ac793d44cf6fb7a9dc.png)
![](media/e781d350b96f186440baeacf43947a2b.png)

![](media/47307ff96c1a312385facc77fe4914b7.png)

Make combinations of these blocks:

![](media/16b846fa31b42bfad8776ec71a678f7b.png)

**(7)Test Result 2:**

Upload test code to micro:bit main board, power the main board via the USB
cable, and click “Show console Device”.

![](media/feb1d8c40c5ac88363223a162de2fa38.png)

After referring to the MMA8653FC data manual and the hardware schematic diagram
of the Micro: Bit main board, the accelerometer coordinate of the Micro: Bit are
shown in the figure below:

![10](media/6303a0ac122680207fe856d9be38d01c.png)

The following interface shows the decomposition value of acceleration in X axis,
Y axis and Z axis respectively, as well as acceleration synthesis (acceleration
synthesis of gravity and other external forces).

![](media/8bb6dd52d8d22db71f023bf5c811fd78.png)

If you're running Windows 7 or 8 instead of Windows 10, via Google Chrome won't
be able to match devices. You'll need to use the CoolTerm serial monitor
software to read data.

You could open CoolTerm software, click Options, select SerialPort, set COM port
and put baud rate to 115200 (after testing, the baud rate of USB SerialPort
communication on Micro: Bit main board is 115200), click OK, and Connect. The
CoolTerm serial monitor shows the data of X axis, Y axis and Z axis , as shown
in the figures below :

![](media/46d779cbd39f94325b5f68026486abed.png)

**Project 8: Light Brightness Detection**

1.  **Project Introduction**

In this project, we focus on the light detection function of the Micro: Bit main
board V2. It is achieved by the LED dot matrix. And it can be viewed as a
photosensor.

![](media/8c3f540a07aab97e1608ba8770837f7b.png)

**(2)Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

Attach the Micro:bit main board to your computer via the USB cable.

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                            | File Name                                 |
|-----------|--------------------------------------------------------------------------------------------------|-------------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 8：Light Brightness Detection | Project 8：Light Brightness Detection.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/3edd89b699b2e9ac793d44cf6fb7a9dc.png)
![](media/6294d3f74a97be6bf4a6e6b81f9535f0.png)

![](media/938fc78372d2b979421ade80986a0eb1.png)
![](media/26bc469d89b7cc2fa98f0fd26bb496b1.png)

Make combinations of these blocks:

![](media/197b14a691a7eaab083b59bb2bd0ea6f.png)

**(5)Test Result:**

Upload the test code to micro:bit main board, power the board via the USB cable
and click“Show console Device”.

![](media/80362de124b0f33064382555326f6076.png)

When the LED dot matrix is covered by hand, the light intensity showed is
approximately 0; when the LED dot matrix is exposed to light,the light intensity
displayed gets stronger with the light as shown below:

![](media/043c01cc37a5eb6432d7975748509538.png)

The 20 in the code is an arbitrary value of light intensity. If the current
light level is less than or equal to 20, the icon moon will appear on the LED
dot matrix. If it's bigger than 20, the sun will appear.

If you're running Windows 7 or 8 instead of Windows 10, via Google Chrome won't
be able to match devices. You'll need to use the CoolTerm serial monitor
software to read data.

You could open CoolTerm software, click Options, select SerialPort, set COM port
and baud rate to 115200 (after testing, the baud rate of USB SerialPort
communication on Micro: Bit main board is 115200), click OK, and Connect. The
CoolTerm serial monitor shows the value of light intensity , as shown in the
figures below :

![](media/b7b8a5af7fd7e74320a402117821a6d5.png)

**Project 9: Speaker**

![](media/ac515b9ae8891dc32f368a29f194a2fb.png)

1.  **Project Introduction**

Micro: Bit main board has an built-in speaker, which makes adding sound to the
programs easier. With a speaker, all Micro:bit board can be used to create
sound-related projects. But the new version, that’s the version 2 is able to
make the speaker utter giggles, greetings and yawning and sound sad. It can also
be programmed to air all kinds of tones, like playing the song *Ode to Joy.*

**(2)Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                         | File Name             |
|-----------|-------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 9: Speaker | Project 9：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/80655aa9a6fd1d5466992df654c73cab.png)
![](media/336245f9fd75aaee9a08f505827f2cb5.png)

![](media/e6d293945d0591c3b1ae78fb2aec1eec.png)

Make combinations of these blocks:

![](media/2b511a53d8af5fc7accea0e6af2e1693.png)

**(5)Test Result 1:**

After uploading the Test Code 1 to micro:bit main board and powering the board
via the USB cable, the speaker utters sound and the LED dot matrix shows the
logo of music.

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                         | File Name             |
|-----------|-------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 9：Speaker | Project 9：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/80655aa9a6fd1d5466992df654c73cab.png)
![](media/336245f9fd75aaee9a08f505827f2cb5.png)

![](media/b781245f8f0b1d52e201cbbb339ad4c5.png)

Make combinations of these blocks:

![](media/613fb1c7ebcd319626cfd3d201c321ec.png)

![](media/0322f9f64ca23b0c9e1aea98af922dfc.png)

![](media/c9612e9369f7196dc3e31852e9c14262.png)

![](media/d48b0a427801da7774d15359533ffdd4.png)

![](media/7646cc2b252c07013bf99c09152edef9.png)

![](media/15acfae12f9164401aa3c7e336d19796.png)

![](media/415d937907c490408451d2cf9eafe83c.png)

The musical score of *Ode to Joy* is attached below:

![乐谱](media/4a79470cc28f087a3834d168bc0c343f.jpeg)

Find more information about musical notations via this link:

https://en.wikipedia.org/wiki/Numbered_musical_notation

**(7) Test Result 2:**

After uploading the Test Code 2 to micro:bit main board and powering the board
via the USB cable, the speaker on built-in the Micro:bit board plays the sound
*Ode to Joy .*

## Project 10: Touch-sensitive Logo

![](media/644695850097c5ade080bb4848b4b481.png)

1.  **Project Introduction**

The Micro: Bit main board is equipped with a golden touch-sensitive logo, which
can act as an input component and function like an extra button.

It contains a capacitive touch sensor that senses small changes in the electric
field when pressed (or touched), just like your phone or tablet screen do.When
you press it , you can activate the program.

**(2)Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg)  |
|-----------------------------------------------------|-----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                        |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                       | File Name                            |
|-----------|---------------------------------------------------------------------------------------------|--------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 10：Touch-sensitive Logo | Project 10：Touch-sensitive Logo.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/5eac17c2b2297d4d58c631a40aa6e5d6.png)
![](media/00044636e4f1edb842c33ecdf952333c.png)

![](media/dc330b1d211f5066b4f8ecbd6e5180bb.png)
![](media/0b29fe8b7226b0fcdcd14a6490632c83.png)![](media/22ce4b96ea8e01f6bb6301585b474f8e.png)

![](media/018f9772fe5e038a93022fd625377522.png)

Make combinations of these blocks:

![](media/b29db93d167521d7d20e8606703167a7.png)

**(5)Test Results:**

After uploading the test code to micro:bit main board and powering the board via
the USB cable, the LED dot matrix exhibits the heart pattern when the
touch-sensitive logo is pressed or touched and displays digit when the logo is
released. The longer it is pressed, the bigger the number is when it is
released.

**Project 11: Microphone**

![](media/3073a8af772ab91ecf264843b37d3b74.png)![](media/7f0741158e734ff8449d5b87d5ba85f4.png)

1.  **Project Introduction**

The Micro: Bit main board is built with a microphone which can test the volume
of ambient environment. When you clap, the microphone LED indicator turns on.
Since it can measure the intensity of sound, you can make a noise scale or disco
lighting changing with music. The microphone is placed on the opposite side of
the microphone LED indicator and in proximity with holes that lets sound
pass.When the board detects sound, the LED indicator lights up.

1.  **Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) |
|-----------------------------------------------------|----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                       |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the USB cable.

**![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)**

**(4)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                             | File Name              |
|-----------|-----------------------------------------------------------------------------------|------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 11：Microphone | Project 11：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/64fb7ef7474f8bf6dfb4b4a3f70f7468.png)
![](media/d5fa6362f08016b3a171a33197515c7f.png)

Make combinations of these blocks:

![](media/184625afa720a5621c83dd4722b46247.png)

**(5)Test Result 1:**

After uploading test code to micro:bit main board and powering the board via the
USB cable, the LED dot matrix displays
pattern“![](media/f496ba08ff8af3164cdbd5fc56cc5abb.png)”when you clap and
pattern ![](media/04fdfc9060943954e7938bb1a741d626.png) when it is quiet around.

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                             | File Name              |
|-----------|-----------------------------------------------------------------------------------|------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 11: Microphone | Project 11: Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/c22cc01fb824faed553d82eb66ee4632.png)
![](media/6645b09fcf339557aecdd4baea422c5c.png)

![](media/681bbd89228d414999f3afee128b14a0.png)
![](media/58a3639dfce22fa6246f8ab791a5203c.png)

![](media/22961dbf753ba383da060507e542a083.png)
![](media/b20a86aa98579aa973d44ee44c26379e.png)

Make combinations of these blocks:

![](media/c42455108c20d4ae51546957ab4198bb.png)

**(2)Test Result 2:**

Upload test code to micro:bit main board, power the board via the USB cable and
click “Show console Device”as shown below:

![](media/e22507af4953df977269bbdb2463d69e.png)

When the sound is louder around, the sound value shows in the serial port is
bigger as shown below:

![](media/50b81518d9f7925b0c20476ab1f64185.png)

What’s more, when the button A is pressed, the LED dot matrix displays the value
of the biggest volume( please note that the biggest volume can be reset via the
Reset button on the other side of the board ) while when clapping, the LED dot
matrix shows the pattern of the sound.

## Project 12: Play Music

1.  **Project Introduction**

In the previous projects, we have learned about the touch-sensitive logo and the
speaker respectively. In the project, we will combine these two components to
play music. That’s the logo will be applied to control the speaker to sing
songs.

**(2) Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) | ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg)   |
|-----------------------------------------------------|-----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                        |

**(3)Connection Diagram:**

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)Attach the Micro:bit main
board to your computer via the USB cable.

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                             | File Name                  |
|-----------|-----------------------------------------------------------------------------------|----------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 12: Play Music | Project 12：Play Music.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/f31bfc90ab7c4f5be17716ff6572bf16.png)![](media/08c9693968eccf0853632d80fb68bda6.png)

![IMG_256](media/7f761aee65bce7f67dd9d7b98ac9ac81.png)![](media/336245f9fd75aaee9a08f505827f2cb5.png)

![](media/c3d265154ac1b454efa270f1f87caf1c.png)

Make combinations of these blocks:

![](media/ca779e9249693f0788c8bcc66a5784bd.png)

**(5)Test Results:**

After uploading test code to micro:bit main board and powering the board via the
USB cable, the speaker plays the song *Happy Birthday to You* when the logo is
touched.

## Project 13: Dodge Bullets

1.  **Project Introduction**

In the previous projects, we have learned about the two programmable buttons,
button A and B, and the LED dot matrix respectively. In this one, we will
combine them to design a game- Dodge Bullets.

**(2)Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg)  |
|-----------------------------------------------------|-----------------------------------------------------|
| Micro:bit main board \*1                            | USB cable\*1                                        |

**(3)Connection Diagram:**

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)Attach the Micro:bit main
board to your computer via the USB cable.

**(4)Game Rule1**

There are two bullets (marked as G1 and G2)falling from the LED dot matrix and a
role G on the bottom of the matrix. Button A and B can be used to control the
movement of the role to dodge bullets. It moves to the right when A is pressed
and to the left when B is pressed. The game is over when G is hit and the game
can start over by pressing A and B together.

**(5)Test Code 1:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name              |
|-----------|--------------------------------------------------------------------------------------|------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 13：Dodge Bullets | Project 13：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/59f4a7a5220320ed53862131eb0bdee0.png)
![](media/b0da291750cd328652b24fc3aa2a46b1.png)

![](media/bcb120fbe26807b6437652050543a15c.png)![](media/edfc0dcea9d7f0da349385478f6d8c62.png)

![](media/22f1deba1162a4438bd8459fb17873cf.png)
![](media/3d5d2e066df5919772690a5c1d74affa.png)

![](media/9d82e6fb0df19d56e196efd524fbb24b.png)
![](media/7f2ed2cbf5ce8b76b4d1940e068a3151.png)

Make combinations of these blocks:

![IMG_256](media/3dd30813e02238b6d00fa3f37d5e0138.png)

![IMG_256](media/78cda4f6892beb811f750562a355bf28.png)

1.  **Test Result 1:**

The game begins when the code is uploaded to the main board. The bullets G1 and
G2 fall off and the role G is controlled by Button A and B to shun them. If the
role fail to avert the attacks, the game is over.

**(7)Game Rule 2:**

Built on the rule1, a new rule is added that one will get score in this game.
And with the accumulation of the score, the difficulty of this game mounts. The
detail of rule2 is that when the role G dodge a bullet, 1 score is gained and
that the game stops when it is hit and the game is over after the display of the
scores. Like rule1, the game will restart when button A and B pressed together.

**(8)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name              |
|-----------|--------------------------------------------------------------------------------------|------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Project Code/Project 13：Dodge Bullets | Project 13：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/040845a1bf151447a4b4d57c219aa5a0.png)
![](media/602f887f942574b02a6d4f125a66ccaf.png)

![](media/471db99b4e224c956cb0e09d15c03781.png)
![](media/0bf268056da8347f78d1eb9a8943cac4.png)

![](media/a293e3fdfa0ef1ef7603ffbe0af3f5d4.png)![](media/22f1deba1162a4438bd8459fb17873cf.png)

![](media/3d5d2e066df5919772690a5c1d74affa.png)
![](media/e279f6a1e3685f63383a36b22b7facb2.png)

![](media/9d82e6fb0df19d56e196efd524fbb24b.png)
![](media/7f2ed2cbf5ce8b76b4d1940e068a3151.png)

Make combinations of these blocks:

![](media/052acb2b79e7e98ebb1d654319da653f.png)

![](media/67b19b88b39707c547815ff97d6ba86d.png)

![](media/a5d9234373f1e27f918a86019072194e.png)

![](media/8a810b569b1b159bed44e19a18af3ab5.png)

**(9)Test Result 2:**

The game begins when the code is uploaded to the main board. The bullets G1 and
G2 fall off and the role G is controlled by Button A and B to shun them. 1 score
will be tallied for each successful dodging. If the role fail to avert the
attacks, the game halts and it is over after the exhibition of the scores
gained.

## Project 14: Bluetooth Wireless Communication

![](media/55b2424d88ba1ba8a711c49418ca8dc6.png)

**(1)Project Introduction**

The Micro: Bit main board comes with a nRF52833 processor (with a built-in
BLE(Bluetooth Low Energy) device Bluetooth 5.1 ) and a 2.4GHz antenna for
Bluetooth wireless communication and 2.4GHz wireless communication. With the
help of them, the board is able to communicate with a variety of Bluetooth
devices, including smart phones and tablets.

In this project, we mainly concentrate on the Bluetooth wireless communication
function of this main board. Linked with Bluetooth, it can transmit code or
signals. To this end, we should connect an Apple device (a phone or an iPad) to
the board.

Since setting up Android phones to achieve wireless transmission is similar to
that of Apple devices, no need to illustrate again.

**(2)Components Needed:**

| ![6(1)](media/b5a90ee5338cd7fb96e135fe71a79a61.png) |  ![3](media/81bfee2741c94f7e5cb7f8ec66b83945.jpeg) | ![](media/41abce34fdbca029fdea842bba8208c0.png)![12](media/989d26695fd03ea630b7fdf186ff78c1.png) |
|-----------------------------------------------------|----------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Micro:bit main board \*1                            | Micro USB cable\*1                                 | Smart Phone/iPad\*1                                                                              |

**(3)Connection Diagram:**

Attach the Micro:bit main board to your computer via the Micro USB cable.。

![5(1)](media/18c70cf16dcf8c9694a1af8b12530cf9.png)

**(4)Procedures:**

**Step 1:**

For Apple devices, enter this link
<https://www.microbit.org/get-started/user-guide/ble-ios/> with your computer
first, and then click **“Download pairing HEX file”**to download the Micro: Bit
firmware to a folder or desk, and upload the downloaded firmware to the Micro:
Bit main board.

(Only Apple devices should follow this step. Not needed for Android systems.)

![](media/cfaf7f8ae83cbe2636c39162a78adc7f.png)

![图片11](media/6c1cef08d31fe3c4876b90ecc11554ff.jpeg)

![Untitled](media/63f1faf124af4949b31d7a84cee19a92.png)

**Step 2:**

Search “micro bit”in your App Store to download the APP micro:bit.

![](media/66d1f34d8d4c52e2b7c0ce10e602a063.png)

**Step 3:** Connect your Apple device with Micro: Bit main board :

Firstly, turn on the Bluetooth of your Apple device and click icon
![](media/ddfd27bdd24da96eb998ccc2e13fcf72.png) to open the APP micro:bit and
select item “Choose micro:bit”to start pairing Bluetooth.

![](media/34f5fbb1c0c371970d1aec6c59c5cbb5.png)

Secondly, click“Pair a new micro:bit”;

![](media/e20270a0ade9c00b61198b26fc2fd83b.png)

Following the instructions to press button A and B at the same time(do not
release them until you are told to) and press Reset & Power button for a few
seconds.

Release the Reset & Power button, you will see a password pattern shows on the
LED dot matrix. Now , release buttons A and B and click “Next”.

![](media/c00520400ecd1f20f958c1c6d1a3c907.png)

![](media/cabc60d7f8a030f5c9d86ac7de6c7bd7.png)

Set the password pattern on your Apple device as the same pattern showed on the
matrix and click “Next”.

![](media/9411a5280e6f3b0d45306a31f80c1b38.png)

Still click “Next”and a dialog box props up as shown below. Then click "Pair". A
few seconds later, the match is done and the LED dot matrix displays the "√"
pattern.

![](media/7b56c56e10415ac2881ac69448b4ad3c.png)![](media/803cb5cf5f7d595581a11f5e6b7e61ed.png)![](media/dc570950dd81f427edb5ea58f50b3a7e.png)![](media/f72e83dc6276d520e82c349659106e1a.png)

After the match with Bluetooth, write and upload code with the App.

Click “Create Code” to enter the programming page and write code.

Click ![](media/f3e9cc7884f7bba807fa4633c429422b.png) and the box
![](media/e081360be7c91b7a156b01a787e4a58c.png) appears, and then select “Create
√”.

![](media/d54bf2d1c01cd3c18544009b1f9dc5a0.png)

![](media/4e7a5d06a5f9a5a209ef5fbc005e9f62.png)

![](media/5bd84e8d293bf8c0c999c7f4e756cf30.png)

![](media/bd19bb4c97ad2a5bc300412b8eb93ede.png)

Name the project as “1 “and click
![](media/a32c2d832ab38d19eb623108143c744e.png) to save it.

![](media/25cf76f891c5eac7381b8095363a2748.png)

Click the third item“Flash”to enter the uploading page. The default code program
for uploading is the one saved just now and named "1" and then click the other
"Flash" to upload the code program "1".

![](media/c1661720ea2eaa521ff31a778501eb23.png)

![](media/350abcbb09d431d40427f34c3764f2eb.png)

![](media/4863bf826f119805a6a9bf9c12d5ec81.png)

If the program “1”is uploaded successfully a few seconds later, the App will
emerge as below and the LED dot matrix of the Micro: Bit main board will exhibit
a heart pattern.

![](media/ebfd31347a0553de0be4e01636652a15.png)

# 8.Expansion Projects：

The former 14 projects are the introduction of sensors and modules. The further
lessons are challenging for new starters.

Note: (G), marked on each sensor and module, is the negative pole and connected
to “G”, ”-”or “GND”on the sensor shield or control board ; (V) is the positive
pole and linked with V , VCC, + or 5V on the sensor shield or control board. And
you need to connect a power in case that power supply is weak.

## Project 1：LED Blinks

![13](media/98c9efc46d004ad501e0fe56f826a69c.png)

**(1)Project Introduction**

We’ve set up the micro:bit smart home. Now let’s get started from the most
simple experiment---LED blink.

LED is a type of semiconductor called "Light Emitting Diode "which is an
electronic device made of semiconductor materials (silicon, selenium, germanium,
etc.). It features unidirectional conductivity, that is, the positive voltage is
applied to the anode (long leg) and the cathode (short leg) of the diode. when
the voltage of its anode is higher than the voltage of its cathode, thus, the
diode is turned on(LED is on). When a reverse voltage is applied to the anode
and cathode, the diode is disconnected(that is, the LED is off). Therefore, the
disconnection and connection of the diode is equivalent to turning on and off
LED. Light-emitting diodes have an anode (+) and a cathode (-), and they can
only allow current to flow from one anode to the cathode. The components will be
damaged if LED is directly connected to the power supply. It’s essential that a
certain resistor must be connected in series in the LED circuit.

1.  **Yellow LED：**

| Working Voltage:    | DC 3.3-5V                      | ![](media/98a79cea0b6dae9d2b47785668ed2f9b.png) |
|---------------------|--------------------------------|-------------------------------------------------|
| Working current：   | \< 20mA                        |                                                 |
| Max Power：         | 0.1W                           |                                                 |
| Control Ports:      | Digital ports (digital input） |                                                 |
| Working Temperature | -10°C \~ +50°C                 |                                                 |
| Display Color：     | Yellow                         |                                                 |

**(3)Test Code**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| Type     | Route                                                                                  | File Name                 |
|----------|----------------------------------------------------------------------------------------|---------------------------|
| Hex file | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 1: LED Blinks | Project 1：LED Blinks.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/4c5f40ff2175d79937ce5a4be8a6bfcc.png)![](media/55a0e6575e1b39ca361f34b28a5984a8.png)

![](media/3647995145391436b5772ebf2baa9809.png)

Make combinations of these blocks:

| Micro：bit Shield | Yellow LED Module |
|-------------------|-------------------|
| GND               | G                 |
| 5V                | V                 |
| S（16）           | S                 |

![](media/5cf01444ca28493403cc59074bf063aa.png)

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show smile expression，and a yellow LED will flash with an
interval of 1000ms. ([How to download?](#A01) [How to quick
download?](#_7.3.快速下载))

**Project 2：Breathing LED**

![13](media/98c9efc46d004ad501e0fe56f826a69c.png)

1.  **Project Introduction**

In previous lesson, we control LED on and off and make it blink.

In this project, we will control LED’s brightness through PWM simulating
breathing effect. Similarly, you can change the step length and delay time in
the code so as to demonstrate different breathing effects.

PWM is a means of controlling the analog output via digital means. Digital
control is used to generate square waves with different duty cycles (a signal
that constantly switches between high and low levels) to control the analog
output.In general, the input voltages of ports are 0V and 3V. What if the 1.5V
is required? Or a switch among 1V, 1.5V and 3V? We cannot change resistors
constantly. For this reason, we resort to PWM.

For Micro:bit digital port voltage outputs, there are only LOW and HIGH levels,
which correspond to the voltage outputs of 0V and 3V respectively. You can
define LOW as“0”and HIGH as“ 1’, and let Micro:bit output five
hundred“0”or‘1’within 1 second. If output five hundred‘1”, that is 3V; if all of
which is‘0’,that is 0V; if output 250 01 pattern, that is 1.5V.

This process can be likened to showing a movie. The movie we watch are not
completely continuous. Actually, it generates 25 pictures per second, which
cannot be told by human eyes. Therefore, we mistake it as a continuous process.
PWM works in the same way. To output different voltages, we need to control the
ratio of 0 and 1. The more‘0’or ‘1’ output per unit time, the more accurate the
control.

In the graphic below, the green lines represent a regular time period. This
duration or period is the inverse of the PWM frequency. In other words, with
Micro:bit's PWM frequency at about 500Hz, the green lines would measure 2
milliseconds each. A call to analogWrite() is on a scale of 0-255, such that
analogWrite(255) requests a 100% duty cycle (always on), and analogWrite(127) is
a 50% duty cycle (on half the time).

![图1](media/704984700612966b997127cb9bde5c96.jpeg)

PWM is applied to light brightness adjustment, speed adjustment of motor and
sound emitting.

Parameters of PWM：

![IMG_256](media/b14db369936f55eef1dd18b050682a10.png)

pulse width (minimum / max)

Pulse cycle (insertion of pulse frequency within 1 second)

Voltage level（0V-3V）

There are commonly used PWM ports, namely P0, P1, P2, P3, P4 and P10. And there
are other rarely used ports, namely P5, P6, P7, P8, P9, P11, P12, P13, P14, P15,
P16, P19 and P20.

In the experiment, we connect the port S of yellow LED Module to the port S (16)
of the expansion board. And P16 can also be used as a PWM interface.

**(2)Yellow LED：**

| Working Voltage:      | DC 3.3-5V                     | ![](media/98a79cea0b6dae9d2b47785668ed2f9b.png) |
|-----------------------|-------------------------------|-------------------------------------------------|
| Working Current：     | \< 20mA                       |                                                 |
| Max Power：           | 0.1W                          |                                                 |
| Control Port:         | digital port (digital input） |                                                 |
| Working Temperature： | -10°C \~ +50°C                |                                                 |
| Display Color：       | Yellow                        |                                                 |

**(3) Test Code**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| Type     | Route                                                                                     | File Name                    |
|----------|-------------------------------------------------------------------------------------------|------------------------------|
| Hex file | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 2: Breathing LED | Project 2：Breathing LED.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/4c5f40ff2175d79937ce5a4be8a6bfcc.png)
![](media/55a0e6575e1b39ca361f34b28a5984a8.png)

![](media/3647995145391436b5772ebf2baa9809.png)
![](media/8c16a69b75ac41d59c7d9543133d0186.png)

![](media/20ef92f127236d4f1c7a773ca86d4e45.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|-------------------|
| GND                       | G                 |
| 5V                        | V                 |
| S（16）                   | S                 |

![](media/f153418709dfaddbcd0e9ab32637c5e8.png)

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show a smile expression, and LED smoothly changes its
brightness from light to dark and back to light, continuing to do so, which is
similar to a lung breathing in and out.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

## Project 3：6812 2x2 Full Color RGB

![16](media/cdebaf0805f0e933e1ccfb3691258bc7.png)

**(1)Project Introduction**

6812 2X2 full-color RGB module integrates the controlling circuit and the
illuminating circuit. Each LED is the same as a 5050 LED lamp bead, and each
component is a pixel point. The inner pixel point includes a amplify driving
circuit that latch signal from digital ports shapes, a high-precision internal
oscillator and and a 12V high voltage programmable current control portion,
which effectively ensures that the color of the pixel point.

The data protocol uses a single-line zero code communication method. After the
pixel point is reset, the S-terminal receives the data transmitted from the
controller. First, the 24bit data sent by the first pixel is extracted by the
first pixel point, and sent to the internal portion of the pixel point.

It has the advantages of low-voltage driving, environmental protection, high
brightness, large scattering angle, good consistency, ultra-low power, long life
expectancy.

**(2)6812 2x2 Full-color RGB:**

| Working Voltage：                               | DC 3.3-5V  | Max Working Current： | 200mA        | Max Power:          | 1W                                |
|-------------------------------------------------|------------|-----------------------|--------------|---------------------|-----------------------------------|
| Working Temperature：                           | -10℃\~+50℃ | Source of light：     | SMD 5050 RGB | IC Type：           | 4 pcs/WS2811                      |
| Gray Scale：                                    | 256        | Illuminating Angle：  | 180°         | Illuminating Color: | Red, yellow, blue,green and white |
| ![](media/29efaf32be2cfacb8d2f8f3438772236.png) |            |                       |              |                     |                                   |

**(3)Add NeoPixel Library:**

Set code by the library, and click“Extensions”to add the library file.

![](media/792e3ec83c270dffdae7758a0721600d.png)

Click the neoPixel library, then NeoPixel library is installed.

![](media/dd2a1e4d4b71fbdc7f400286c7694870.png)

You can view it in the blocks list.

![](media/0912defee95f32e352a21e481b836efb.png)

**(4)Test Code 1**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                             | File Name             |
|-----------|---------------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 3: 6812 2x2Full-colorRGB | Project 3：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/f662876dc93548199e1d84d3e6c97076.png)
![](media/5f10026b74fe5cbcf58c8c1606618ea1.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | 6812 2x2 Full Color  RGB Module |
|---------------------------|---------------------------------|
| GND                       | G                               |
| 5V                        | V                               |
| S（14）                   | S                               |

![](media/868e570d61e8706cfc54dbedf73658a6.png)

**(5)Test Result 1:**

Upload the Test Code 1to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. You will view the 6812 RGB module display red,
orange,yellow, green, blue,Indigo, violet, purple and white, in loop way. ([How
to download?](#A01) [How to quick download?](#_7.3.快速下载))

**(6)Test Code 2:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                             | File Name             |
|-----------|---------------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 3：6812 2x2Full-colorRGB | Project 3：Code-2.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/f662876dc93548199e1d84d3e6c97076.png)
![](media/8c16a69b75ac41d59c7d9543133d0186.png)

![](media/d1e2527365d23875a0e99774a4a58287.png)

![](media/e91267f0c5222aac0a9199908a7fba3d.png)
![](media/20ef92f127236d4f1c7a773ca86d4e45.png)

Make combinations of these blocks:

![](media/89b36514f1ca038801c7d8361f6c6dd3.png)

![](media/ff00587a8c567b621c278bc47a709ae6.png)

![](media/1f1b772742c705cf81450cd04f87625c.png)

**7.5. Test Result2:**

Upload the test code 2 to the micro:bit，plug in power, dial the DIP switch to
ON and press“1”on the rocket switch.

You can view four WS2812RGB lights light up，like a flowing light.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

**(8)Test Code 3:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                             | File Name             |
|-----------|---------------------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 3: 6812 2x2Full-colorRGB | Project 3：Code-3.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/f662876dc93548199e1d84d3e6c97076.png)
![](media/8c16a69b75ac41d59c7d9543133d0186.png)

![](media/d1e2527365d23875a0e99774a4a58287.png)![](media/b925689ddad7baf1cc48eb47ad00f57a.png)

![](media/c14853e5ed880dba471fcabf672caa69.png)
![](media/7ba31169ee48cebb69bda5e89ae4b7f0.png)

Make combinations of these blocks:

![](media/40d3dc54c3dc29c84b243d9f29e30036.png)

Upload the test code 3 to the micro:bit，plug in power, dial the DIP switch to
ON and press“1”on the rocket switch.

Then you will see 5 WS2812RGB lights light up with random colors, like a flowing
light.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

**Project 4：PIR Motion Sensor**

![15](media/8e527b21d2e89c43f0fa894cb32f55c8.png)

**(1)Project Introduction**

The Pyroelectric infrared motion sensor can detect infrared signals from moving
objects, and output switching signals. Applied to a variety of occasions, it can
detect movement of human body.

Conventional pyroelectric infrared sensors are much more bigger, with complex
circuit and lower reliability. Yet, this new pyroelectric infrared motion
sensor, is more practical. It integrates a digital pyroelectric infrared sensor
and connecting pins. It features higher sensibility and reliability, lower power
consumption, light weight, small size, lower voltage working mode and simpler
peripheral circuit.

**(2)About PIR Motion Sensor:**

![](media/ee515734c07dde5b3e5c06f3916e6b74.png)

| Working Voltage：      | DC 4.5-6.5V                                          |
|------------------------|------------------------------------------------------|
| Max Working Current：  | 50MA                                                 |
| Static Current:        | \<50uA                                               |
| Control Port：         | Digital output (high level is 3.3V，low level is 0V) |
| Control Signals:       | Digital signal 1/0                                   |
| Working Temperature：  | -10 \~ 50 ℃                                          |
| Max detection distance | 4m                                                   |
| Sensing Angle：        | ＜100°                                               |
| Trigger Way:           | L doesn’t repeatedly trigger/H trigger repeatedly    |

Note：

1\. The maximum distance is 4 meters during testing.

2\. In the test, open the white lens to check rectangular sensing part. When the
long line of the sensing part is parallel to the ground, the distance is the
best.

3\. In the test, covering the sensor with white lens can sense the distance
precisely.

4\. The distance is best at 25℃, and the detection distance value will reduce
when temperature exceeds 30℃.

5\. After powering up and uploading the code, you can start testing after 5-10
seconds, otherwise the sensor is not sensitive.

**(3)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                         | File Name                        |
|-----------|-----------------------------------------------------------------------------------------------|----------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 4：PIR Motion Sensor | Project 4：PIR Motion Sensor.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/ee606a1f9971d0a8225187832fca8faa.png)
![](media/57a0a37b70eb69d70483c66a49b71947.png)

![](media/ee272defaa7ac0cc8a31f3bddc7df0cf.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | PIR Motion Sensor |
|---------------------------|-------------------|
| GND                       | G                 |
| 5V                        | V                 |
| S（15）                   | S                 |

![](media/adf0052c901619962801e01e61a8a016.png)

**(4)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show a smile image. Then click“Show console device”

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

If PIR motion sensor detects someone nearby, the serial monitor will display “1”
, and the indicator on the module will be off. If nobody is around, the serial
monitor will show “0”, the indicator will be on.

As shown below:

![](media/e4cfd6624a82c7637694891563e2e27e.png)

If your computer system is Windows7/8 instead of Windows 10, the device can’t be
paired in Google Chrome, as a result, the digital and analog signals can’t be
read.

Here, we need CoolTerm software to read data.

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of micro:bit V2 is 115200 through
the test). Click“OK”and“Connect”.

![](media/6073f5ee860986fb8ba4e37d3a84e6d4.png)

## Project 5：Induction Lamp

**(1)Project Introduction**

In the previous project experiment, we have mastered the working principle of
the PIR motion sensor and its control method. In this project, we combine it
with a yellow LED to control LED’s brightness

**(2)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                       | File Name                      |
|-----------|---------------------------------------------------------------------------------------------|--------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 5：Induction Light | Project 5：Induction Light.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/4c5f40ff2175d79937ce5a4be8a6bfcc.png)
![](media/a638710a0ef8870cbd3c094f8c20e422.png)

![](media/f932d480eba97befaa1a0be7acd542b4.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | PIR Motion Sensor |   | Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|-------------------|---|---------------------------|-------------------|
| GND                       | G                 |   | GND                       | G                 |
| 5V                        | V                 |   | 5V                        | V                 |
| S（15）                   | S                 |   | S（16）                   | S                 |

![](media/1ac64ea0d3cc948c50197f60434fce3a.png)

**(3)Test Results:**

Upload the test code to the micro:bit, plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show a smile image.

When the PIR motion sensor detects people, the yellow LED will be on; otherwise,
the LED will be off.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

**Project 6: Adjust angles of servo**

![](media/6f0776b01b35f18b0568158ffbbc7a77.png)

1.  **Project Introduction**

![](media/69be958142b773acdae33eeef12afed7.png)

Servo motor is a position control rotary actuator. It mainly consists of a
housing, a circuit board, a core-less motor, a gear and a position sensor. Its
working principle is that the servo receives the signal sent by MCU or receiver
and produces a reference signal with a period of 20ms and width of 1.5ms, then
compares the acquired DC bias voltage to the voltage of the potentiometer and
obtain the voltage difference output.

When the motor speed is constant, the potentiometer is driven to rotate through
the cascade reduction gear, which leads that the voltage difference is 0, and
the motor stops rotating. Generally, the angle range of servo rotation is 0°
\--180°.

1.  **Working Principle of Servo：**

The rotation angle of servo motor is controlled by regulating the duty cycle of
PWM (Pulse-Width Modulation) signal. The standard cycle of PWM signal is 20ms
(50Hz). Theoretically, the width is distributed between 1ms-2ms, but in fact,
it's between 0.5ms-2.5ms. The width corresponds the rotation angle from 0° to
180°. But note that for different brand motors, the same signal may have
different rotation angles.

![6780083(1)](media/0982cb7b28f4accde7d378ba812c8bcb.png)

Through the experiment, the pulse range of the servo is 0.65ms\~2.5ms.

| high level time | Servo angle | Reference signal cycle time（20ms） |
|-----------------|-------------|-------------------------------------|
| 0.65ms          | 0°          | 0.65ms high level+19.35mslow level  |
| 1.5ms           | 90°         | 1.5ms high level+18.5mslow level    |
| 2.5ms           | 180°        | 2.5ms high level+17.5mslow level    |

1.  **Servo：**

| Working voltage：     | DC 4.8V〜6V                                            | Operational Angle： | About 180°(500→2500μsec) |
|-----------------------|--------------------------------------------------------|---------------------|--------------------------|
| Pulse width range：   | 500→2500 μsec                                          | Size：              | 22.9\*12.2\*30mm         |
| No-load speed：       | 0.12±0.01 sec/60°（DC 4.8V） 0.1±0.01 sec/60°（DC 6V） |                     |                          |
| No-load current：     | 200±20mA（DC 4.8V） 220±20mA（DC 6V）                  |                     |                          |
| Stop torque：         | 1.3±0.01kg·cm（DC 4.8V） 1.5±0.1kg·cm（DC 6V）         |                     |                          |
| Stop current：        | ≦850mA（DC 4.8V） ≦1000mA（DC 6V）                     |                     |                          |
| Standby Current：     | 3±1mA（DC 4.8V） 4±1mA（DC 6V）                        |                     |                          |
| Weight:               | 9±1g (without servo horn)                              |                     |                          |
| Working temperature： | -30℃\~60℃                                              |                     |                          |

Note: Supplying power via USB cable or computer may burn the servo; thus, we
recommend using batteries.

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                              | File Name                             |
|-----------|----------------------------------------------------------------------------------------------------|---------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 6: Adjust angles of servo | Project 6：Adjust angles of servo.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/7540e63e8641fd940b2a8c26e3ebcf18.png)
![](media/9200db9c2fdd6b0e9b5596009d6fa23b.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | Servo  |
|---------------------------|--------|
| GND                       | Brown  |
| 5V                        | Red    |
| S（8）                    | Orange |

![](media/917921752f61dcf82509c1dd245c7b0f.png)

**(5)Test Results:**

Upload the test code to the micro:bit, plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. The micro:bit will show smile expression, the
servo will rotate 0°\~45°\~90°\~135°\~180°\~0°，in loop way. ([How to
download?](#A01) [How to quick download?](#_7.3.快速下载))

## Project 7: 130 Motor

![25(1)](media/e092ffebd3240e6e157a7872731a9b58.png)

**(1)Project Introduction**

130 motor adopts the HR1124S chip which is applied to single-channel H-bridge
drive chip in direct current motor.

H-bridge driving part uses the PMOS and NMOS power tubes of low on-resistance.
In addition, the HR1124S chip has the low standby and static current.

This motor is compatible with all kinds of MCU control boards. It comes with
2.54mm anti-reverse white connectors. In the experiment, you can take advantage
of the voltage direction of IN+和IN- to control the rotation of motor and alter
its speed via PWM signals

**(2)Parameters：**

| Working Voltage：                               | 3.3-5V(DC)    | Max Current：             | 200mA (DC5V)                       |
|-------------------------------------------------|---------------|---------------------------|------------------------------------|
| Max Power：                                     | 1W            | Control port：            | Dual digital port（digital input） |
| Working Temperature：                           | -10°C \~+50°C | Environmental Attribute： | ROHS                               |
| ![](media/2498f64be175011ed8b3263749146e4f.png) |               |                           |                                    |

**(3) Test Code 1:（high/low level control）**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                 | File Name             |
|-----------|---------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 7：130 Motor | Project 7：Code-1.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/14926f94bec47701d715c550f546b163.png)
![](media/1c5639bb50df3862d3977f32f82d9279.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | Motor |
|---------------------------|-------|
| GND                       | G     |
| 5V                        | V     |
| S（13）                   | IN+   |
| S（12）                   | IN-   |

![](media/874ebce0d3b6a91d562d2033a3f5afbe.png)

**Code Explanation：**

| IN+（digital port P12）                         | IN-（digital port P13） | Fan              |
|-------------------------------------------------|-------------------------|------------------|
| high level（1）                                 | low level（0）          | Rotate clockwise |
| ![](media/5b05d8cffe8f993a7d7d66227dcaaa36.png) |                         |                  |

| IN+（digital portP12）                          | IN-（digital port P13） | fan                  |
|-------------------------------------------------|-------------------------|----------------------|
| low level（0）                                  | high level（1）         | Rotate anticlockwise |
| ![](media/5b05d8cffe8f993a7d7d66227dcaaa36.png) |                         |                      |

| IN+（digital portP12）                          | IN-（digital port P13） | fan          |
|-------------------------------------------------|-------------------------|--------------|
| low level（0）                                  | low level（0）          | Not rotating |
| ![](media/b05e7e6e2738c4c0cf746320a84f3b3b.png) |                         |              |

| IN+（digital portP12）                          | IN-（digital port P13） | fan          |
|-------------------------------------------------|-------------------------|--------------|
| high level（1）                                 | high level（1）         | Not rotating |
| ![](media/4c3fa131fad181e0cb7bc4d31e81773a.png) |                         |              |

**4.Test Code 2：（PWM Speed control ）**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                 | File Name             |
|-----------|---------------------------------------------------------------------------------------|-----------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 7：130-Motor | Project 7：Code-2.hex |

You can edit code blocks yourself:

![](media/670d33bab272a0cfdfd6b8cd772fde6b.png)
![](media/1c5639bb50df3862d3977f32f82d9279.png)

Make combinations of these blocks:

![](media/ef9a2353a2d876361480951775b67e5c.png)

**Code Explanation：**

| IN+（digital portP12）                          | IN-（digital portP13） | fan              |
|-------------------------------------------------|------------------------|------------------|
| high level（1）                                 | PWM 600                | Rotate clockwise |
| ![](media/9b4ffc888744c02b2cf152a3f3c43659.png) |                        |                  |

| IN+（digital portP12）                          | IN-（digital portP13） | Fan                  |
|-------------------------------------------------|------------------------|----------------------|
| low level（0）                                  | PWM 400                | Rotate anticlockwise |
| ![](media/432800171dbab6b1c2ae84de3d1246d8.png) |                        |                      |

| IN+（digital portP12）                          | IN-（digital portP13） | fan          |
|-------------------------------------------------|------------------------|--------------|
| low level（0）                                  | PWM 0                  | Not rotating |
| ![](media/5726c886bf6241e91702f02d5bd9d2af.png) |                        |              |

| IN+（digital portP12）                          | IN-（digital portP13） | fan          |
|-------------------------------------------------|------------------------|--------------|
| high level（1）                                 | PWM 1023               | Not rotating |
| ![](media/63545df9b0b7a819f0ee2f56c2048296.png) |                        |              |

**5.Test Results：**

Upload the test code to the micro:bit, plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. The fan will rotate clockwise for 5s, stop 1,
rotate anticlockwise for 5s and stop for 1s, in loop way. ([How to
download?](#A01) [How to quick download?](#_7.3.快速下载))

## Project 8：Lithium Battery Power Module

**(1)Project Introduction**

This module integrates a charging and discharging chip, which can be interfaced
with an external rechargeable battery through the PH2.0MM interface. In the
experiment,we use a single lithium battery.

It has a Micro USB port and a charging port for solar panels, which can supply
power for an external lithium battery.

In addition, this module has a boost module which can increase the voltage of
batteries to 6.6V. The DIP switch on the module is the OUTPUT switch of 6.6V.
The pin G and V can output 6.6V and the pin S can read the battery voltage after
the resistance 1/2 voltage

1.  **Parameters：**

| Charging Port                             | Micro USB, HP2.0MM port for solar panels |
|-------------------------------------------|------------------------------------------|
| Input Voltage of ports of the solar panel | 4.4-6V                                   |
| constant-voltage charging                 | 4.15-4.24V                               |
| Max Charging Current                      | 800mA                                    |
| Output Port                               | 3 P 2.54mm Pins                          |
| Input Voltage                             | 6.6V                                     |
| Max Output Current                        | 800mA                                    |
| Batteries                                 | Single-cell Lithium Battery              |
| Environmental Attribute                   | ROHS                                     |

1.  **Schematic Diagram：**

![](media/189777dcc6b180028d01671c2ea49186.png)

1.  **Features：**

![](media/07e545ee5517782911cb24aac7b87a2d.png)

SOLAR4.8-6.0V, the input port of power, is connected to polar panels.

The solar energy is converted into electric energy via solar panels.

![](media/ca26c0fdc91084511b3d9a948df1fd66.png)

BAT, the output port of power, is interfaced with the lithium battery
holder(rechargeable batteries) and saves the electric energy into batteries.

![](media/252c3ee03fefe739a910924413f1cc62.png)

This is the switch. Slid to ON end, then the external lithium battery will be
connected, supplying to the expansion board; on the contrary, slide to OFF, then
the current of lithium battery will be disconnected.

![](media/92b0c19b4eab104090d92d8c8c7b8391.png)

You can charge the lithium battery via USB cable.

**Test the solar battery panel：**

We can connect the solar battery panel and an LED we provide together, as shown
below.

Disconnect the power, after a while, you will see the LED light up.

![IMG_256](media/a4c83004e0303b67f36de54a9425c920.png)**![图2](media/5cbf09cac4f56831baf6224b1e9c546d.jpeg)**

## Project 9：1602 LCD

![KS0062 (4)](media/b28242c31d938ab51c634aa121490ffa.jpeg)

1.  **Project Introduction**

With I2C communication module, this is a display module that can show 2 lines
with 16 characters per line.

It shows blue background and white word and connects to I2C interface of MCU,
which highly save the MCU resources.

On the back of LCD display, there is a blue potentiometer for adjusting the
backlight. The communication address defaults to 0x27.

The original 1602 LCD can start and run with 7 IO ports, but ours is built with
Arduino IIC/I2C interface, saving 5 IO ports. Alternatively, the module comes
with 4 positioning holes with a diameter of 3mm, which is convenient for you to
fix on other devices.

Notice that when the screen gets brighter or darker, the characters will become
more visible or less visible.

![](media/fc7e69308162f73eda88903c6caf90e5.png)

1.  **Parameters：**

| Working Voltage ：                                               | DC5V                                             | I2C Address：                                                      | 0x27                     | Control Port： | I2C      |
|------------------------------------------------------------------|--------------------------------------------------|--------------------------------------------------------------------|--------------------------|----------------|----------|
| Working Current：                                                | \< 130mA                                         | Working Temperature：                                              | 0°C \~ 45°C（recommend） | Driving Chip： | PCF8574T |
| GND: a pin connected to the ground                               |  VCC：A pin that connects to a +5V power supply  | SDA： A pin that connects to analog port A4 for IIC communication  |                          |                |          |
| SCL：a pin interfaced with SCL or A5，used for IIC communication | Backlight                                        | Adjustable contrast                                                |                          |                |          |

**(3)Add I2C LCD 1602 Library：**

Set code by the library, and click“Extensions”to add the library file:

![](media/792e3ec83c270dffdae7758a0721600d.png)

Tap <https://github.com/keyestudio2019/ks_IoT> in the searching box and
click“Search”, as shown below. Click **IoT_keyestudio** library. Then the
IoT_keyestudio library is set up.

In addition, the I2C LCD 1602 library is included in the **IoT_keyestudio.**

![](media/b82aa069120beb40adcbf4dfbaab5b7b.png)

You can check the I2C LCD 1602 library in the block list.

![](media/e203135e4e792c75f1ac3c00df59ef0f.png)

**(4)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                | File Name               |
|-----------|--------------------------------------------------------------------------------------|-------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 9：1602 LCD | Project 9：1602 LCD.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/479e0d5b572bee55c927b7a03242fea7.png)
![](media/4ba05f6a2a403d67b8399f042923ed1e.png)

![](media/dc33c9fc033dd62a3a689c0f5f32f6d1.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | I2C 1602 LCD Module |
|---------------------------|---------------------|
| GND                       | GND                 |
| 5V                        | 5V                  |
| SDA                       | SDA                 |
| SCL                       | SCL                 |

![](media/194fc7b66c1eb392dcffd6dfb9d2a821.png)

**(5)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit board will show a smile image. Then rotate the knob of the
potentiometer at the back of the LCD module, you will see“Keyestudio”at one row
and numbers at the second row. In addition, the number increases by 1 with an
interval of 0.5s.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

Note: When the display doesn’t show characters, you can adjust the potentiometer
behind the 1602LCD and backlight to make the 1602LCD display the corresponding
character string.

## Project 10：Steam Sensor

![14](media/932398f7831e7e6d0f1c0b6f035a79a4.png)

**(1)Project Introduction**

This is a commonly used steam sensor. Its principle is to detect the amount of
water by bare printed parallel lines on the circuit board. The more the water
content is, the more wires will be connected. As the conductive contact coverage
increases, the output voltage will gradually rise. It can detect water vapor in
the air as well. The steam sensor can be used as a rain water detector and level
switch. When the humidity on the sensor surface surges, the output voltage will
increase.

The sensor is compatible with various microcontroller control boards, such as
Arduino series microcontrollers. When using it, connect the sensor to the analog
port of the Micro:bit microcontroller, and display the corresponding analog
value on the serial monitor.

Note: the connection part is not waterproof, therefore, don’t immerse it in the
water please.

**(2) Parameters：**

| Working Voltage：           | DC 3.3-5V                                                              | ![](media/3b0760476232188966281131ba9da7e5.png) |
|-----------------------------|------------------------------------------------------------------------|-------------------------------------------------|
| Working Temperature Range： | －10℃～＋70℃                                                           |                                                 |
| Max Working Current：       | 5uA (DC5V，when the two pins of the steam sensor are in short circuit. |                                                 |
| Control Port：              | Analog output                                                          |                                                 |

**(3)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                     | File Name                    |
|-----------|-------------------------------------------------------------------------------------------|------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 10：Steam Sensor | Project 10：Steam Sensor.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/dce9000ddbbe13b445bc25ad3cb284a6.png)![](media/6fa8bbc6fd7bbe12273cfdcad74a5f2d.png)

![](media/0741e42830dc22b6d7c2d482f8c34f1f.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | Steam Sensor |
|---------------------------|--------------|
| GND                       | G            |
| 3V3                       | V            |
| S(0)                      | S            |

![](media/ded674be8679604536eccf87703208d0.png)

**(4)Test Results:**

Upload the test code, and plug in power with micro USB cable. Then the micro:bit
will show“❤”. At same time, click the“Show console Device” ([How to
download?](#A01) [How to quick download?](#_7.3.快速下载))

![](media/9efcc8dab24cf3a1a7ca9ebc8d360502.png)

The more the immersed area of the module, the larger the analog value.

As shown below;

The serial monitor will show the output data, and the steam sensor will read the
analog signals at the signal end.

![](media/3c3e48189a767dc50dc67ca5c424ed67.png)

If your computer system is Windows7/8 instead of Windows 10, the device can’t be
paired in Google Chrome, as a result, the digital and analog signals can’t be
read.

Here, we need CoolTerm software to read data.

Open **CoolTerm**, click **Options** to select **SerialPort**. Set **COM** port
and 115200 baud rate(the baud rate of USB serial communication of micro:bit V2
is 115200 through the test). Click“OK”and“Connect”.

The more the immersed area of the module, the larger the analog value.

As shown below;

![](media/56881fbbdf58e29e7d187927cfe19919.png)

## Project 11：Rains Alarm

**(1)Project Introduction**

Steam Sensor is a wide range of applications, such as raining alarm, automotive
automatic scraping system, intelligent lighting system, and smart sunroof
system. In the previous project experiment, we already know the working
principle of Steam Sensor, then in this project experiment, we combine Steam
Sensor, Micro:bit, and yellow LEDs, making a simple rain alarm.

**(2)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                    | File Name                   |
|-----------|------------------------------------------------------------------------------------------|-----------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 11：Rains Alarm | Project 11：Rains Alarm.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/4c5f40ff2175d79937ce5a4be8a6bfcc.png)
![](media/0165996a1f0c761cae6fc031bbbc7bf4.png)

![](media/a6fa09b49609f60b900650eabf6f8885.png)
![](media/2ebe5fba3339783f1232c0e8e495ec7d.png)

![](media/d2763eca7dee6a88012a469a4a21506f.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | Steam Sensor |   | Micro:bit Expansion Board | Yellow LED Module |
|---------------------------|--------------|---|---------------------------|-------------------|
| GND                       | G            |   | GND                       | G                 |
| 3V3                       | V            |   | 5V                        | V                 |
| S（0）                    | S            |   | S（16）                   | S                 |

![](media/51eba37c228db705d08b783088b73c43.png)

**(3)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show smile expression. When the detected analog signals are
more than 500, the micro:bit will emit“tick, tick”and the yellow LED will flash.
Otherwise, no sound and LED off.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

## Project 12：Analog Gas（MQ-2）Sensor

![17](media/5ad704f1db5e43058513cf8ed2d53047.png)

**(1)Project Introduction**

This gas sensor is used for household gas leak alarms, industrial combustible
gas alarms and portable gas detection instruments. Also, it is suitable for the
detection of liquefied gas, benzene, alkane, alcohol, hydrogen, etc.,

The MQ-2 smoke sensor can be accurately a multi-gas detector, with the
advantages of high sensitivity, fast response, good stability, long life, and
simple drive circuit.

It can detect the concentration of flammable gas and smoke in the range of
300\~10000ppm. Meanwhile, it has high sensitivity to natural gas, liquefied
petroleum gas and other smoke, especially to alkanes smoke.

It must be heated for a period of time before using the smoke sensor, otherwise
the output resistance and voltage are not accurate. However, the heating voltage
should not be too high, otherwise it will cause internal signal line to blow.

It belongs to the tin dioxide semiconductor gas-sensitive material. At a certain
temperature, tin dioxide adsorbs oxygen in the air and forms negative ion
adsorption of oxygen, reducing the electron density in the semiconductor,
thereby increasing its resistance value.

When in contact with flammable gas in the air and smog, and the potential
barrier at the grain boundary is adjusted by the smog, it will cause the surface
conductivity to change. With this, information about the presence of smoke or
flammable gas can be obtained. The greater the concentration of smoke or
flammable gas in the air, the greater the conductivity, and the lower the output
resistance, the larger the analog signal output. In addition, the sensitivity
can be adjusted by rotating the potentiometer.

![](media/959fb3dc082b2bafcc8dc3f4a1845d6c.png)

1.  **Analog Gas（MQ-2）Sensor：**

| Working Voltage：          | 3.3-5V                             | ![](media/42a27e658a946a1d9845c5846db4b412.png) |
|----------------------------|------------------------------------|-------------------------------------------------|
| Working Current：          | 160mA (DC5V)                       |                                                 |
| Working Temperature：      | 0°C \~ 40°C                        |                                                 |
| Control Port：             | Digital and analog output          |                                                 |
| Detection concentration：  | 300-10000ppm (combustible gas )    |                                                 |
| Rake Ratio：               | ≤0.6(R3000ppm/R1000ppm C3H8)       |                                                 |
| Sensitivity                | Rs(in air)/Rs(1000ppm isobutane)≥5 |                                                 |
| Sensitive Resistance（Rs） | 2KΩ-20KΩ(in 2000ppm C3H8 )         |                                                 |

**Features：**

(1) Have a signal output instruction.

(2) Dual-channel signal output (analog output and TTL level output)

(3) TTL output effective signal is Low Level. (When the Low Level is output, the
signal light will be on)

(4) The analog output is 0 \~ 5V voltage. The higher the concentration, the
higher the voltage.

(5) a good sensitivity to liquefied gas, natural gas and urban gas.

(6) Have long-term life expectancy and reliable stability

(7) Fast response recovery.

**3.Test Code：**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                                | File Name                               |
|-----------|------------------------------------------------------------------------------------------------------|-----------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 12：Analog Gas(MQ-2) Sensor | Project 12：Analog Gas(MQ-2) Sensor.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/dce9000ddbbe13b445bc25ad3cb284a6.png)![](media/6fa8bbc6fd7bbe12273cfdcad74a5f2d.png)

![](media/af20cbb0fdb97531070ceed6f6ba16f5.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | Analog Gas（MQ-2）Sensor |
|---------------------------|--------------------------|
| GND                       | G                        |
| 5V                        | V                        |
| S（1）                    | D                        |

![](media/5603aaa728e4f48399f4f1debd41882a.png)

**(4)Test Results:**

Upload the test code to the micro:bit, plug in power and dial the DIP switch to
ON. Then the micro:bit will show smile expression and a green indicator will be
on. You can adjust the blue potentiometer to make the sensitivity high.

The micro:bit will show a smile image. You can maintain the sensitivity good by
adjusting the blue potentiometer and click“Show Console Device”.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

![](media/41568bf77231c21bc1794d72279bec00.png)

The serial monitor will show 1 if the sensor doesn’t detect any gas; however, if
you make the firelighter close to it, number 0 will be output and the indicator
will be on. As shown below;

![](media/99500f8575bada38053466a39e2a3a6c.png)

If your computer system is Windows7/8 instead of Windows 10, the device can’t be
paired in Google Chrome, as a result, the digital and analog signals can’t be
read.

Here, we need CoolTerm software to read data.

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of micro:bit V2 is 115200 through
the test). Click“OK”and“Connect”.

Enable fire lighter and make it close to the gas sensor , the serial monitor
will print 0; however, if you remove the fire lighter, number 1 will be output.

![](media/6073f5ee860986fb8ba4e37d3a84e6d4.png)

## Project 13：Gas Leakage Detector

**(1)Project Introduction**

This MQ-2 gas sensor is used for household gas leak alarms, industrial
combustible gas alarms and portable gas detection instruments. And it is
suitable for the detection of liquefied gas, benzene, alkane, alcohol, hydrogen,
etc., and widely used in various fire alarm systems. It can be accurately a
multi-gas detector, and has the advantages of high sensitivity, fast response,
good stability, long life, and simple drive circuit.

It can detect the concentration of flammable gas and smoke in the range of
300\~10000ppm.Meanwhile, it has high sensitivity to natural gas, liquefied
petroleum gas and other smoke, especially to alkanes smoke.

We will make a gas leakage detector with a MQ-2 gas sensor, a yellow LED and a
1602 LCD.

**(2)Add the 1602 LCD library**

Library link: <https://github.com/keyestudio2019/ks_IoT>

(refer to the project 91602 LCD)

**(3)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                             | File Name                            |
|-----------|---------------------------------------------------------------------------------------------------|--------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 13: Gas Leakage Detector | Project 13：Gas Leakage Detector.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/4c5f40ff2175d79937ce5a4be8a6bfcc.png)![](media/6c65dc19f8bfe1115a666096d74a44a9.png)![](media/ed4873373d5346867179af7eac2a5a24.png)
![](media/af20cbb0fdb97531070ceed6f6ba16f5.png)
![](media/8a2447bcc90336249196091050f3bab4.png)![](media/51bd2173e551c65288fcad9c6f6c4ad0.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | Analog Gas（MQ-2）Sensor |   | Micro:bit Expansion Board | Yellow LED Module |   | Micro:bit Expansion Board | 1602 LCD Module |
|---------------------------|--------------------------|---|---------------------------|-------------------|---|---------------------------|-----------------|
| GND                       | G                        |   | GND                       | G                 |   | GND                       | GND             |
| 5V                        | V                        |   | 5V                        | V                 |   | 5V                        | 5V              |
| S（1）                    | D                        |   | S（16）                   | S                 |   | SDA                       | SDA             |
|                           |                          |   |                           |                   |   | SCL                       | SCL             |

![](media/3ef749830a34e4fc15af9466024973ed.png)

**(4)Test Results**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch.

The micro:bit will show a smile image. Make a fire lighter close to the gas
sensor and press its button, 1602 LCD will display“MQ-2”at the first row and
show“gas leakage”at the second row. At same time, it will emit“tick,tick”sound
and LED will flash.

([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

## Project 14：DHT11 Temperature and Humidity Sensor

![1](media/f7ff148f3c57a033e5898e955479d368.png)

**(1)Project Introduction**

This DHT11 temperature and humidity sensor is a composite sensor which contains
a calibrated digital signal output of the temperature and humidity.

DHT11 temperature and humidity sensor uses the acquisition technology of the
digital module and temperature and humidity sensing technology, ensuring high
reliability and excellent long-term stability.

It includes a resistive element and a NTC temperature measuring device.

**(2) Parameters：**

| Working Voltage：     | 3.3V-5V（DC）              |    ![](media/915eb0254a9220c7441a5a1106d96d4f.png) |
|-----------------------|----------------------------|----------------------------------------------------|
| Max Working Current： | 50mA                       |                                                    |
| Max Power：           | 0.25W                      |                                                    |
| Control Port：        | Digital two-way single bus |                                                    |
| Temperature Range：   | 0-50℃（±2℃）               |                                                    |
| Humidity Range        | 20-90%RH（±5%RH）          |                                                    |
| Working Temperature   | -25℃\~+60℃                 |                                                    |

**DHT11 Temperature and Humidity Sensor：**

|                 | **Single-bus data format**                                                                                                                                                                                                                                     |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Initial signal  | The microprocessor pulls down the data bus(SDA) for at least 18 ms (less than 30 ms)                                                                                                                                                                           |
| Response signal | The sensor pulls down the data bus (SDA) 83 μs, and then pulls up 87 μs to respond to the initial signal of the host.                                                                                                                                          |
|  humidity       | The humidity high-bit is the humidity integer part of the data, the humidity low-bit is the humidity fractional part of the data.                                                                                                                              |
|   temperature   | The temperature high-bit is the temperature integer part of the data, the temperature low-bit is the temperature fractional part of the data. And the temperature low bit8 is 1, which indicates the negative temperature; otherwise the positive temperature. |
| Check bit       | Check bit = humidity high bit + humidity low bit+ temperature high bit + temperature low bit                                                                                                                                                                   |

**Overall Communication Process：**

After the user host (MCU) sends a start signal, the DHT11 is converted from the
low consumption mode to the high one. After the start signal is completed, the
DHT11 sends the 40bit data, triggering an information collection. The signal
transmission is shown in the figure.

Communication protocol of DHT11 Sensor：

<https://www.mouser.com/datasheet/2/758/DHT11-Technical-Data-Sheet-Translated-Version-1143054.pdf>

**(4)Add the DHT11 library**

Set code by the library, and click“Extensions”to add the library file.

![](media/792e3ec83c270dffdae7758a0721600d.png)

Copy the link <https://github.com/keyestudio2019/ks_IoT> in the searching box,
as shown below and click the **IoT_keyestudio** library. Then the
**IoT_keyestudio** library is set up.

![](media/b82aa069120beb40adcbf4dfbaab5b7b.png)

You can find it in the blocks list.

![](media/e962d234a486ee2c3e6ef4b5bb71df01.png)

**(5)Test Code:**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                                              | File Name                                             |
|-----------|--------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 14：DHT11 Temperature and Humidity Sensor | Project 14：DHT11 Temperature and Humidity Sensor.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/dce9000ddbbe13b445bc25ad3cb284a6.png)
![](media/a6de97b1224916ef06cd6c8f9de95808.png)

![](media/6fa8bbc6fd7bbe12273cfdcad74a5f2d.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | DHT11 Temperature and Humidity Sensor |
|---------------------------|---------------------------------------|
| GND                       | G                                     |
| 5V                        | V                                     |
| S（2）                    | S                                     |

![](media/807f2bff983f6abc91a8a1a2d4eedcdc.png)

**(6)Test Results:**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. The micro:bit will show a smile image. Then
click“Show console Device” ([How to download?](#A01) [How to quick
download?](#_7.3.快速下载))

![](media/41568bf77231c21bc1794d72279bec00.png)

The detected temperature and humidity value is shown as below:

![](media/1eed40db46ad803d2380f7e1a0b10794.png)

If your computer system is Windows7/8 instead of Windows 10, the device can’t be
paired in Google Chrome, as a result, the digital and analog signals can’t be
read.

Here, we need CoolTerm software to read data.

Open CoolTerm, click Options to select SerialPort. Set COM port and 115200 baud
rate(the baud rate of USB serial communication of micro:bit V2 is 115200 through
the test). Click“OK”and“Connect”.

The temperature and humidity value will be displayed on the serial monitor, as
shown below:

![](media/de24244dc80605fe72da4f6fae9e387b.png)

## Project 15：Temperature and Humidity Display

**(1)Project Introduction**

We’ve mastered the working principle of the DHT11 temperature and humidity
sensor. In this project, we will make a temperature and humidity display with it
and a 1602 LCD.

1.  **Add the 1602 LCD and DHT11 library：**

The link to add libraries: <https://github.com/keyestudio2019/ks_IoT>

You can refer to project 9 and 14

**3.Test Code：**

The route to get test codes（[How to load?](#_5.5.导入代码：)）

| File Type | Route                                                                                                         | File Name                                        |
|-----------|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| Hex file  | KS4027 folder/Makecode Tutorial/Makecode Code/Expansion Projects/Project 15：Temperature and Humidity Display | Project 15：Temperature and Humidity Display.hex |

You can also drag blocks to form code.

Command blocks can be found on the right as shown below:

![](media/dce9000ddbbe13b445bc25ad3cb284a6.png)
![](media/a6de97b1224916ef06cd6c8f9de95808.png)

![](media/51df049a60324fddc8e77194173f5ebe.png)

Make combinations of these blocks:

| Micro:bit Expansion Board | DHT11 Temperature and Humidity Sensor |   | Micro:bit Expansion Board | 1602 LCD Module |
|---------------------------|---------------------------------------|---|---------------------------|-----------------|
| GND                       | G                                     |   | GND                       | GND             |
| 5V                        | V                                     |   | 5V                        | 5V              |
| S（2）                    | S                                     |   | SDA                       | SDA             |
|                           |                                       |   | SCL                       | SCL             |

![](media/683c464e76048d9a423908d385200a43.png)

**4.Test Results：**

Upload the test code to the micro:bit，plug in power, dial the DIP switch to ON
and press“1”on the rocket switch. The micro:bit will show smile image.

The 1602 LCD will show the temperature and humidity value in the current
environment. ([How to download?](#A01) [How to quick download?](#_7.3.快速下载))

## Project 16：Multiple Functions

1.  **Project Description: ：**

The final lesson is the combination of all modules and sensors. It is an analog
smart home.

**2.Preparation：**

A micro:bit and the smart home model.

Interface the micro:bit with a computer with a micro USB cable.

Add the libraries：https://github.com/keyestudio2019/ks_IoT

**3. Test Code:**

![](media/77362ac27fd40fca47149ae6f424fd73.png)

![](media/3ce6552fe61fe19c3dc5ce149ab94fdb.png)

![](media/65131e75c32017ed98cfaae8de499936.png)

**Test Results:**

When you are close to the PIR motion sensor, the yellow LED will be on;
otherwise, the yellow LED will be off.

When dropping water onto the steam sensor and analog signal is more than 300,
the window will be close; when the analog signal is less than 300, the window
will be on.

The password can be set by the button A and B on the micro:bit board.

Pressing A and B respectively means‘.’and‘-’.

Pressing A and B simultaneously indicates“confirm”

The 5\*5 LED lights will show ![](media/15f93c52c9395ccaca4a5aa58e3aeef8.png)
picture and the I2C1602LCD will display “Successful”and“Open the door”, the 6812
2x2 RGB will show purple color. However, if the password is wrong, “error” will
pop up on the LCD module and show “Enter password”

Touch the logo area of the micro:bit, the 1602LCD will show“Close the
door”and“Enter password”. Next, the door will be closed and the 6812 module will
be off.

When the temperature sensor on the micro:bit detects the temperature higher than
or equal to 30℃ , the small fan will rotate

## Project 17：BT-controlled LED

**(1)Project Introduction**

We control LED on and off via app.

**2.Preparation：**

**Install App**

Android system：

Search IoT microbit on Google play, or install the app package we provide(in the
Android APK folder)

![](media/41211c1f0617bf0c5a3b5277c915c269.png)

iOS system: search IoT microbit in the App store, as shown
below:![](media/2db677ed5bd948d439b235c18842a6a7.png)

Add the BT library file as shown below:

![](media/b39b92316672f6e1c4c0a53399b8981a.png)

**3. Test Code:**

![](media/8bc5dacedc8f0ced6d5ca042ea579979.png)

Note: after finishing code, you need to enable “No paring Required: Anyone can
connect via Bluetooth”

![](media/aa681bc193cf3e2439e3c95e0c3823d3.png)

![](media/251cd113bfced468d8f947181675f168.png)

**4.Test Results:**

Upload code to the micro:bit, open the switch of the smart home, enable the App
and click **Connect**

![](media/24b08a4c573bc4ccee000c4884d9bd72.png)

Search the Bluetooth name of micro:bit board

![](media/4327ae9bebfc837896d6f99d019c1e2f.png)

After connecting well, click LED icon

![](media/bac6406492337c07e399362d5804024e.png)

Then you will see LED on. If you click this icon again, LED will be off.

## Project 18：Smart Home

**(1)Project Introduction**

In this section, we will control the smart home via Bluetooth

**(2) Preparation：**

Download this app first.

![英文说明图](media/3d2edb248f622ff3bed976dc3f9f244e.png)

Add the Bluetooth library file.

![](media/b39b92316672f6e1c4c0a53399b8981a.png)

Add the libraries：https://github.com/keyestudio2019/ks_IoT

1.  **Test Code:**

**Seen in the folder**

1.  **Test Results:**

Burn the code to the micro:bit, turn on the switch of the smart home model, and
enable the Bluetooth of your device and app.

![英文操作图111](media/b086bbbcf4dd831a9660ad977b6f9b50.png)

The password can be set by the button A and B on the micro:bit board.

Pressing A and B respectively means‘.’and‘-’.

Pressing A and B simultaneously indicates“confirm”

The 5\*5 LED lights will show ![](media/15f93c52c9395ccaca4a5aa58e3aeef8.png)
picture and the I2C1602LCD will display“Successful” and“Open the door”, the 6812
2x2 RGB will show purple color. However, if the password is wrong, “error” will
pop up on the LCD module and “Enter password”will appear.

You can touch the logo of the micro:bit to close the door.

**9.Resources:**

https://fs.keyestudio.com/KS4027-4028

# 
