# AND-MCU
**The Anonymous Nestling Disclosing project microcontroller application**

## Prerequisites
### Hardware Requirements:
- ESP32 development board (e.g., NodeMCU-32S, ESP32 DevKitC).
- Micro-USB cable for programming.
- External sensors or peripherals (optional, based on your project).

### Software Requirements:
- Arduino IDE.

## Getting Started
### Step 1: Install the ESP32 Board in Arduino IDE
Open the Arduino IDE.
Go to File > Preferences.
In the Additional Board Manager URLs field, add the following URL:
`https://dl.espressif.com/dl/package_esp32_index.json`
Go to *Tools > Board > Boards Manager*.
Search for "ESP32" and install the latest version of the esp32 by Espressif Systems package.

### Step 2: Clone the Repository
Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/your-esp32-project.git
```
Open the Arduino IDE and navigate to File > Open. Select the main .ino file in the repository.

### Step 3: Select the Board and Port
Go to Tools > Board and select your ESP32 board model (e.g., ESP32 Dev Module).
Go to Tools > Port and select the COM port corresponding to your ESP32 board.

### Step 4: Install Required Libraries
Open Tools > Manage Libraries.
Search for and install the libraries specified in the libraries.txt file included in this repository.

### Step 5: Upload the Code
Connect your ESP32 board to your computer via USB.
In the Arduino IDE, click the Upload button (right arrow icon) to compile and upload the code to your ESP32.
Monitor the serial output by clicking Tools > Serial Monitor (set baud rate to 115200).
