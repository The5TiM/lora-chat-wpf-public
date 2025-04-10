# LoRa Chat

<p align="center">
  <img src=".github/images/Logo-LoRa.png" alt="LoRa Chat Logo" width="300">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/WPF-512BD4?style=for-the-badge&logo=.net&logoColor=white" alt="WPF">
  <img src="https://img.shields.io/badge/Entity%20Framework%20Core-512BD4?style=for-the-badge&logo=.net&logoColor=white" alt="Entity Framework Core">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino/C">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge" alt="C#">
  <img src="https://img.shields.io/badge/LoRa-2C2E35?style=for-the-badge" alt="LoRa">
</p>

## About

LoRa Chat is a messaging application that enables communication over LoRa networks. This project was developed during a three-month Software Engineering and Scrum-focused college project by a team of four developers: Juwan Jouma, Joulian Alsuliman, Sergej Jahne, and Ilja Groo.

**Key Features**: The application allows users to create chats, send and receive encrypted messages over LoRa networks, and manage connections with LoRa devices.

## Features

- Secure messaging over LoRa networks
- End-to-end encryption for messages
- User-friendly chat interface
- Device connection management
- System tray notifications
- Friend request functionality
- Message history and chat management

## Technologies

- **WPF**: Windows Presentation Foundation for building the desktop UI
- **C#**: Primary programming language
- **Arduino/C**: Programming language for LoRa communication
- **LoRa**: Long Range Communication technology for wireless communication
- **Entity Framework Core**: ORM for database operations
- **SQLite**: Lightweight database for storing chat and user information
- **WPF-UI**: Modern UI components for WPF
- **System.IO.Ports**: For serial communication with LoRa devices

## Getting Started

### Prerequisites

- Windows 11
- .NET SDK 8.0 or higher
- Visual Studio 2022 or Visual Studio Code
- LoRa hardware device (for full functionality)


### Installation

1. Clone the repository
2. Open the solution in Visual Studio
3. Restore NuGet packages
4. Run the application

## See it in Action

<p align="center">
  <img src=".github/images/LoRa-first-time-page.png" alt="First Time Setup" width="600">
  <br>
  <em>First Time Setup - Enter your nickname to start using the application</em>
</p>

<p align="center">
  <img src=".github/images/LoRa-chat-page.png" alt="Main Chat Interface" width="600">
  <br>
  <em>Main Chat Interface - Send and receive messages over LoRa</em>
</p>

<p align="center">
  <img src=".github/images/LoRa-chat-page-pm.png" alt="Private Messaging" width="600">
  <br>
  <em>Private Messaging - Start secure conversations with other users</em>
</p>

<p align="center">
  <img src=".github/images/LoRa-chat-page-pm-2.png" alt="Private Chat Window" width="600">
  <br>
  <em>Private Chat Window - Exchange messages in a dedicated private chat</em>
</p>

<p align="center">
  <img src=".github/images/LoRa-chat-page-pm-encryption-key.png" alt="Encryption Key Setup" width="600">
  <br>
  <em>Encryption Key Setup - Configure end-to-end encryption for private chats</em>
</p>

<p align="center">
  <img src=".github/images/LoRa-device-not-connected.png" alt="Device Connection Status" width="600">
  <br>
  <em>Device Connection Status - Real-time LoRa device connectivity monitoring</em>
</p>

<p align="center">
  <img src=".github/images/LoRa-tray-notification.png" alt="Tray Notifications" width="300">
  <br>
  <em>System Tray Notifications - Stay updated with message alerts</em>
</p>

## Project Structure

  - **Assets**: Application resources including images, styles and themes
  - **Data**: Database layer for data persistence
    - **Models**: Entity models for users, chats, messages and LoRa devices
    - **Repositories**: Data access layer implementing CRUD operations
  - **Logic**: Core business logic implementation
    - **Managers**: Services handling chat operations, client management, message encryption and LoRa communication
  - **Presentation**: User interface components
    - **Controls**: Custom WPF controls for chat bubbles and message displays
    - **Pages**: Main application pages including chat, settings and device management
    - **Views**: Window definitions and UI components for the application

## Contributors

<p align="center">
  <a href="https://github.com/The5TiM"><img src="https://img.shields.io/badge/The5TiM%20|%20Juwan%20Jouma-181717?style=for-the-badge&logo=github" alt="The5TiM | Juwan Jouma" /></a>
  <a href="https://github.com/JoulianALS"><img src="https://img.shields.io/badge/JoulianALS%20|%20Joulian%20Alsuliman-181717?style=for-the-badge&logo=github" alt="JoulianALS | Joulian Alsuliman" /></a>
  <a href="https://github.com/SergejJahne"><img src="https://img.shields.io/badge/SergejJahne%20|%20Sergej%20Jahne-181717?style=for-the-badge&logo=github" alt="SergejJahne | Sergej Jahne" /></a>
  <img src="https://img.shields.io/badge/Ilja_Groo-181717?style=for-the-badge" alt="Ilja Groo" />
</p>
