Trollkat's (forker's) note: I initially forked this project to improve it and contribute back the changes. However, I do not agree with the way GitHub is partnering with xAI, so I have moved my fork to GitLab: https://gitlab.com/alejandrovr/Unity-3D-Xmpp-Protocol .

All the new improvements (So far AutoPong and some bugfixes) will be over there.

---

# Unity 3D XMPP Protocol Library

[![GitHub Stars](https://img.shields.io/github/stars/attributeyielding/Unity-3D-Xmpp-Protocol-.svg?style=social)](https://github.com/attributeyielding/Unity-3D-Xmpp-Protocol-)

An **XMPP (Extensible Messaging and Presence Protocol)** library for **Unity 3D** targeting **C# .NET 2.0**, designed to facilitate real-time communication in Unity applications. This library is ideal for implementing chat systems, presence updates, and other real-time messaging features within your Unity projects.

## Overview

This project represents the first attempt at implementing an **XMPP library** for **Unity 3D** targeting **.NET 3.5** and earlier versions. It is optimized to work within Unity's Mono runtime environment, which has certain limitations compared to modern .NET environments. 

The library supports core XMPP functionalities such as message exchange, presence updates, roster management, and more. It is lightweight, cross-platform, and suitable for use across multiple platforms including **PC, Linux, Mac, Android, and iOS**.

---

## Key Features

### Core Protocol Support
- **Message Exchange**: Send and receive messages in real-time.
- **Presence Updates**: Manage user statuses like online, away, busy, etc.
- **Roster Management**: Handle contacts and friend lists.
- **XML-based Communication**: Handles communication with the XMPP server using XML.

### Unity Compatibility
- Designed to work seamlessly within Unity's **Mono runtime** environment.
- Optimized for **.NET 2.0**, making it compatible with older Unity versions.

### Async Communication
- Uses **asynchronous callbacks** or **threads** to handle XMPP events without blocking Unity's main thread.

### Commonly Supported Features
- **Authentication**: Supports methods like Plain, Digest-MD5, etc.
- **1:1 Chats & Group Chats**: Facilitates both personal and group conversations.
- **Presence Updates**: Manage user availability statuses.
- **Roster Management**: Add, remove, and manage contacts.
- **Extensions**: Includes support for **MUC (Multi-User Chat)**, **Service Discovery**, and **PubSub (Publish-Subscribe)**.

### Lightweight and Cross-Platform
- Lightweight design ensures minimal performance overhead.
- Compatible with multiple platforms: **PC, Linux, Mac, Android, iOS**.

---

## Popular Libraries and Considerations

### AgsXMPP
- **Pros**:
  - Lightweight and compatible with **.NET 2.0**.
  - Simple API for handling XMPP messages.
  - Suitable for lightweight chat applications in Unity.
- **Cons**:
  - Lacks some modern features and security protocols (e.g., XMPP over WebSocket).

### MatriX XMPP
- Another robust library, but may require licensing for advanced features.
- Compatible with **.NET 2.0** and Unity.

### Custom Implementation
- If pre-built libraries are insufficient, you can build an XMPP client from scratch using:
  - `System.Xml` for parsing XML.
  - `System.Net.Sockets` for TCP communication.
- Provides flexibility but requires familiarity with the XMPP protocol and its extensions.

---

## Steps to Use the XMPP Library in Unity

### Prerequisites
- **A working XMPP server** is required to test this library.

### Setup
1. **Read Documentation**: Familiarize yourself with the documentation included in this repository.
2. **Build DLL**: Build the DLL file from the Visual Studio solution provided.
3. **Import DLL into Unity**:
   - Place the built DLL into the `Assets/Plugins` folder in your Unity project.
   - Ensure the library is compatible with Unity's **.NET 2.0 subset**.

### Initialization
1. **Create a Connection**: Establish a connection to the XMPP server.
2. **Authenticate**: Authenticate using the desired method (e.g., username/password).

### Messaging
1. **Subscribe to Events**: Subscribe to message and presence events.
2. **Send and Receive Messages**: Send and receive XMPP messages in real-time.

---

## Supported Platforms

- **Standalones**: PC, Linux, Mac
- **Mobile**: Android, iOS

---

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests. If you encounter any issues or have suggestions for improvements, please open an issue in the repository.

---

## Acknowledgments

Thank you for putting a star on my repository! 😊

Have a great development day!

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contact

For any questions or feedback, feel free to reach out:

- **GitHub Repository**: [Unity-3D-Xmpp-Protocol-](https://github.com/attributeyielding/Unity-3D-Xmpp-Protocol-)

---

Happy coding! 🚀
