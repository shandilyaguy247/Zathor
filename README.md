### Vision for the Project

The vision for this decentralized peer-to-peer messaging application is to empower individuals and groups to create their own secure, decentralized communication networks. By leveraging a Distributed Hash Table (DHT) for user discovery and AES 256 encryption for secure messaging, the application aims to make private and secure communication accessible to everyone, without reliance on central servers. This ensures that privacy and security are maintained, fostering a more open and secure internet for all users.

# Decentralized Peer-to-Peer Messaging Application

## Overview
This project is a decentralized peer-to-peer messaging application designed for extremely secure encrypted communication. Built using Python3, this application runs as a web application in the browser, ensuring end-to-end encryption and privacy. Users can create their own decentralized groups, making secure communication accessible to everyone.

## Key Features
- **AES 256 Encryption:** All communications are secured with AES 256 encryption, ensuring data confidentiality and integrity.
- **Serverless Architecture:** The application is fully decentralized, allowing direct peer-to-peer communication without any central server.
- **Real-Time Communication:** Users can communicate in real-time, but both users must be online to exchange messages.
- **Unique User Identification:** Each user is identified by a unique 15-digit number.
- **Secure Key Exchange:** Encryption keys are exchanged in person via Bluetooth or displayed as text for manual entry, enhancing security.
- **Multi-Media Support:** Users can send text, images, videos, and documents up to 25 MB.
- **Delivery Confirmation:** A syn-ack system ensures users are notified whether their messages are successfully delivered or dropped.
- **Decentralized Groups:** Users can create their own decentralized groups to communicate securely over the internet.

## Technology Stack
- **Backend:** Python3, Flask/Django, WebSockets, Cryptography library
- **Frontend:** HTML, CSS, JavaScript (React/Vue.js)
- **Bluetooth Integration:** Python Bluetooth library
- **DHT:** Kademlia library

## Installation
1. **Clone the repository:**
    ```sh
    git clone https://github.com/shandilyaguy247/encrypted_chat.git
    cd p2p-messaging-app
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
1. Open the application in your browser.
2. Register by obtaining a unique 15-digit identification number.
3. Exchange encryption keys with your contacts via Bluetooth or manually.
4. Start secure communication with your contacts.
5. Create or join decentralized groups for secure group communication.

## Contribution
We welcome contributions from the community. Please fork the repository and submit pull requests for any improvements or new features.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
