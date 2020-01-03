← [Back to Menu](https://telinkgithub.github.io/Telink/ "Menu")
![header-telink](https://i.imgur.com/5kRG6CF.jpg)

# 8258 BLE RCU Quick Start

## Features

The RC demo supports the following features:

* Works with dual batteries
* 25 valid buttons and 1 indicating LED
* Telink proprietary voice service
* Voice compressed with ADPCM, supported sample rate 16khz/16bit
* OTA firmware upgrade
* PC tool for button display and demonstration
* Low power consumption

For detailed descriptions, please refer to the product specification document “[Specification For TLSR8258-based BLE Audio Remote Control Demo](https://telinkgithub.github.io/Assets/09_Solutions-RCU/Spec%20For%20TLSR8258-based%20BLE%20Audio%20Remote%20Control%20Demo.zip)”.

## Quick Setup Guide

This quick start guide uses the Telink 8258 RCU demo as an step-by-step example to show how to get the RCU sample up and running quickly. For other flavors of RCU, the steps may differ slightly, please refer to the corresponding user guide.

### The guidance on BLE

__Step 1__: The appearance of the 8258RCU and dongle are as follows:

![825RCU-dongle-appearance-1](https://telinkgithub.github.io/Assets/09_Solutions-RCU/20181022-152334.png)
![825RCU-dongle-appearance-2](https://telinkgithub.github.io/Assets/09_Solutions-RCU/20181022-152642.png)


__Step 2__: Download the remote.bin file to the RCU ([Burning and Debugging Tool](https://telinkgithub.github.io/Programming-Debugging/))

This is the RCU bin link: [8258_ble_remote_IR.bin](https://telinkgithub.github.io/Assets/09_Solutions-RCU/remote_bin.zip)

This is the dongle bin link: [8258_master_kma_dongle.bin](https://telinkgithub.github.io/Assets/09_Solutions-RCU/dongle_bin.zip)

This is the SDK link: [8258_ble_sdk](https://telinkgithub.github.io/Assets/09_Solutions-RCU/ble_sdk.zip)


__Step 3__: Connection and pair method

Power on the RCU, and RCU will be advertise state for 60 seconds.

Plug dongle into PC, then press the SW1 and that will trigger dongle to receive advertise packets. When dongle red led is on, it indicate RCU connect to dongle.


__Step 4__: BLE button and voice test method

We can just open .txt file on PC side, and when you press the number key, the number will be display in the txt file.That is button's operation.

When need to use the voice function, you can open the PC software audacity. click the record icon to start recording. Then press and hold the MIC key ![MIC key](https://telinkgithub.github.io/Assets/09_Solutions-RCU/20181022-155251.png) over 1 second,and you will see that the audacity starts to record voice data.


## The guidance on IR

__Step 1__: The guidance on IR

Press the switch key ![Switch key](https://telinkgithub.github.io/Assets/09_Solutions-RCU/20181022-155557.png) to switch IR mode. and the demo IR protocal is NEC.

__Step 2__: IR test method

Plug the IR code analyzer to PC and open the revelant PC software about IR code analyzer.

Press the button and the software will display the IR data.


← [View the Project on GitHub](https://github.com/TelinkGithub/RCU)


![footer-telink](https://telinkgithub.github.io/Assets/General/footer.jpg)



