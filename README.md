# SecureChatC: Encrypted Communication in C

## Introduction

SecureChatC is a multi-client chat server application that provides secure and encrypted communication channels. This project emphasizes secure messaging through encryption and the use of concurrent server-client architecture.

## Features

- **Multi-Client Support:** Allows multiple clients to connect and communicate with the server concurrently.
- **Encryption:** Implements basic encryption to keep messages secure.
- **POSIX Threading:** Utilizes threading for handling multiple chat sessions simultaneously.

## Getting Started

### Prerequisites

- GCC Compiler
- POSIX-compliant system for threading

### Installation

1. Clone the repository to your local machine.
2. Compile the server and client programs using GCC.
   ```
   gcc server.c -o server -lpthread
   gcc client.c -o client -lpthread
   ```
3. Run the server program.
   ```
   ./server
   ```
4. In a new terminal, connect a client to the server.
   ```
   ./client
   ```

## Usage

Follow the on-screen prompts to communicate with other connected clients securely.

## Contributing

Contributions to SecureChatC are welcome. Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests.
