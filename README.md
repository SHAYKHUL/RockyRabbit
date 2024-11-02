# RockyRabbit

RockyRabbit is a data encryption program written in Python, inspired by the concepts of "Rocky" and "Rabbit." This program employs advanced cryptographic techniques to encrypt files securely, and it is designed for educational purposes to demonstrate the principles of data security and encryption.

## Features

- **File Encryption**: Securely encrypts files using AES-GCM.
- **Key Management**: Uses RSA to manage encryption keys securely.
- **User Identification**: Generates user-specific passwords and salts based on system identifiers.
- **System Information Gathering**: Collects system metrics and can send this data to a designated server.
- **Multi-threading**: Efficiently processes multiple files simultaneously.
- **Secure Deletion**: Overwrites original files before deletion to ensure data cannot be recovered.
- **User Notifications**: Provides feedback to the user upon successful encryption.

## Flask Server

The RockyRabbit project includes a Flask server for storing and managing user data securely. This server handles incoming data from the RockyRabbit encryption program and stores it in a SQLite database.

### Features

- **Data Storage**: Receives and stores user data, including usernames, encrypted passwords, salts, and system information.
- **Data Retrieval**: Allows retrieval of stored data with pagination support.
- **Search Functionality**: Enables searching for users by username.

### Setup

1. Ensure you have Flask installed. If not, install it using pip:
   ```bash
   pip install Flask

## Disclaimer

**IMPORTANT**: This project is intended for educational and research purposes only. Use responsibly and ensure compliance with all applicable laws. Misuse of this software may lead to legal consequences. 

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RockyRabbit.git
   cd RockyRabbit
