# Decentralized Peer-to-Peer Messaging Application

## Overview

This project is a decentralized peer-to-peer messaging application designed for extremely secure encrypted communication. Built using Python3, this application runs as a web application in the browser, ensuring end-to-end encryption and privacy. Users can create their own decentralized groups, making secure communication accessible to everyone.

## Key Features

- **AES 256 Encryption for Messaging:** Ensures secure message communication between peers.
- **Serverless Architecture for Messaging Traffic:** All messaging is handled directly between peers.
- **Real-Time Communication:** Users can communicate in real-time via WebSockets.
- **Unique User Identification:** Each user is identified by a unique 15-digit number.
- **Secure Key Exchange using Signal Protocol:** Ensures secure exchange of encryption keys.
- **Multi-Media Support:** Users can send text, images, videos, and documents up to 25 MB.
- **Delivery Confirmation:** Syn-ack system ensures users are notified of message delivery status.

## Vision

To enable people to create their own decentralized groups that can communicate securely over the internet, making decentralized secure communication accessible to everyone.

## Technology Stack

- **Backend:** Python3, Flask, Django, WebSockets, libsignal-protocol-python
- **Frontend:** HTML, CSS, JavaScript (React or Vue.js)
- **Bluetooth Integration:** Python Bluetooth library
- **Database:** For discovery server to store user information

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/p2p-messaging-app.git
    cd p2p-messaging_app
    ```

2. **Create a virtual environment:**

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies:**

    ```sh
    pip install -r requirements.txt
    ```

4. **Run the application:**

    ```sh
    python run.py
    ```

## Usage

1. **User Registration and Key Generation:**
   - Users register and generate a unique 15-digit ID.
   - Generate identity keys and prekeys using the Signal Protocol.
   - Publish prekeys to the discovery server.

2. **Key Exchange:**
   - Retrieve the target user’s prekeys from the discovery server.
   - Establish a secure session using the Signal Protocol.

3. **Peer-to-Peer Messaging:**
   - Use WebSockets for real-time communication.
   - Encrypt messages with AES 256 before sending.
   - Decrypt messages upon receiving.

4. **Secure Communication:**
   - Ensure all messaging traffic is encrypted and handled directly between peers without relying on a central server.

## Contribution

We welcome contributions from the community. Please fork the repository and submit pull requests for any improvements or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
