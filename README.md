# Chat-Box Application

Secure Chat Box Application demonstrates the use of socket programming and RSA encryption in Python. It is designed to provide a basic example of secure communication between multiple clients and a server.

## Features

- **Secure Communication**: Messages are encrypted using RSA encryption, ensuring secure communication between clients.
- **Multi-client Support**: The server can handle multiple clients simultaneously.
- **GUI Client**: The client application includes a graphical user interface (GUI) built with Tkinter.
- **Real-time Messaging**: Clients can send and receive messages in real-time.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/anishvedant/Chat-box-application.git
    cd Chat-box-application
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the server**:
    ```bash
    python3 server.py
    ```

4. **Run the client**:
    ```bash
    python3 client.py
    ```

## Usage

### Server

1. Start the server by running `server.py`.
2. The server will listen for incoming client connections on the specified host and port.

### Client

1. Start multiple clients on different terminals by running `client.py`.
2. Enter a username and connect to the server.
3. Send and receive messages securely.

## Customization

- **Host and Port**: You can change the `HOST` and `PORT` variables in `server.py` and `client.py` to run the server and client on different addresses and ports.
- **Encryption**: The RSA encryption keys can be customized in the `decrypto.py` module.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests with your improvements and bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Disclaimer

Chat-box application enhances communication security but does not guarantee absolute protection against all forms of attacks. Users are advised to understand the limitations and potential risks associated with the implementation. Use this project responsibly and in compliance with applicable laws and regulations.


