# Arduino Rickroll
This project plays a Piezo buzzer rendition of the song "Never gonna give you up" by Rick Astley and displays the lyrics on an LCD. This project is based on the Arduino platform. It is a **pet project** to get experience with **Arduino**.
## Scheme
This project uses the following components:
* Arduino Nano board
* Buzzer KY-006
* Character display LCD 1602
* Breadboard

Below is a diagram of the assembly of the system for clarity. The diagram was compiled on the Wokwi. [At this link](https://wokwi.com/projects/328185995083121236), you can try out this system in the online Arduino simulator. Just click on the Start the simulation button.

_Tip: turn the volume down._

![1](https://user-images.githubusercontent.com/115897935/196052300-061c7ecb-5135-496b-a064-f73c021659cb.png)

These tables show how to connect the pins of all components to the Arduino Nano.

**Table 1**. LCD1602 pin connections to the Arduino Nano

|  LCD1602      |  Arduino Nano        |
| :-----------: | :------------------: |
|  VSS          |  GND                 |
|  VDD          |  5V                  |
|  V0           |  GND                 |
|  RS           |  D12                 |
|  RW           |  GND                 |
|  E            |  D11                 |
|  D0           |  Without connection  |
|  D1           |  Without connection  |
|  D2           |  Without connection  |
|  D3           |  Without connection  |
|  D4           |  D5                  |
|  D5           |  D4                  |
|  D6           |  D3                  |
|  D7           |  D2                  |
|  A            |  5V                  |
|  K            |  GND                 |

**Table 2**. Buzzer KY-006 pin connections to the Arduino Nano

|  Buzzer KY-006  |  Arduino Nano        |
| :-------------: | :------------------: |
|  S              |  D7                  |
|  V5             |  Without connection  |
|  —              |  GND                 |

Here's what the assembled system might look like.

![image](https://user-images.githubusercontent.com/115897935/196058621-0cb5b744-8efc-4ea5-a8a0-5118dd215c54.png)

## Installation
#### Step 1. Install [Arduino IDE](https://www.arduino.cc/en/software).
Requires Arduino v.1.8.19.
#### Step 2. Download [LiquidCrystal](https://github.com/arduino-libraries/LiquidCrystal) library for working with LCD.
Import LiquidCrystal to the folder where Arduino is installed. By default `C:\Program Files (x86)\Arduino\libraries`.
#### Step 3. In the tools tab, select the Arduino Nano board and ATmega328P (Old Bootloader) processor.
#### Step 4. Clone this repository to your local computer.
```
git clone https://github.com/SpaceLacuna/arduino-rickroll.git
```
# Running
#### Step 1. Assemble the scheme.
#### Step 2. Connect the assembled scheme to the computer.
#### Step 3. Verify and Upload sketch.
