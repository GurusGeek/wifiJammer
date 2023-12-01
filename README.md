# WiFi Jammer

WiFi Jammer is a Python script designed for ethical hacking and security research purposes. It automates the process of setting up your Wi-Fi adapter in monitor mode, scanning for nearby WiFi networks, and launching de-authentication attacks on selected networks. This project was developed as part of my Information Security Course Project.

## Features

- **Monitor Mode Setup:** Automatically sets up your Wi-Fi adapter in monitor mode.
  
- **WiFi Scanning:** Scans for nearby WiFi networks and displays a list of available targets.

- **Deauthentication Attack:** Launches a deauthentication attack on a selected WiFi network.

- **User Disconnection:** Disconnects all users connected to the targeted WiFi network temporarily.

- **User-Friendly:** Simple and interactive script with easy-to-follow instructions.

## Installation

To use WiFi Jammer, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/GurusGeek/wifiJammer
    ```

2. Change to the project directory:

    ```bash
    cd wifiJammer
    ```

3. Run the script with elevated privileges:

    ```bash
    sudo python wifideauth.py
    ```

## Usage

Once you have executed the script, follow the on-screen instructions:

1. Select your WiFi adapter for monitor mode setup.
2. Scan for available WiFi networks.
3. Choose a target WiFi network for the deauthentication attack.
4. Initiate the deauthentication attack.
5. Press `Ctrl+C` to stop the attack.

**Note:** This tool is intended for educational and research purposes only. Ensure that you have the necessary permissions before using it.

## Disclaimer

The author is not responsible for any misuse or damage caused by this script. Use it responsibly and only in environments where you have explicit authorization.



Feel free to contribute or report issues by creating a pull request or opening an issue. Happy hacking!
