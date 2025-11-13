# Sentinel

> A Software Designed For Remote Monitoring With Very Little Interaction.

<div align="center">

<img src="https://files.catbox.moe/wq58dm.png" alt="Sentinel Logo" width="200"/>

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

</div>

---

## 📋 About

**Sentinel** is a powerful, lightweight remote monitoring and administration tool designed for seamless oversight with minimal user interaction. Built for IT professionals, system administrators, and authorized personnel, Sentinel provides comprehensive remote access capabilities while maintaining a low footprint. Operating silently in the background, Sentinel delivers real-time intelligence without disrupting the target system's performance or alerting the end user.

## ✨ Features

### 🖥️ Remote Screen Monitoring
Capture and stream real-time screenshots from the target device at configurable intervals. View exactly what the user sees with high-quality image transmission. Supports multiple monitor configurations and can capture specific applications or the entire desktop. Screenshots are compressed for efficient bandwidth usage and can be stored locally or transmitted instantly to your command server.

**Key Capabilities:**
- Adjustable capture intervals (from seconds to hours)
- Multi-monitor support with individual screen selection
- Automatic image compression and optimization
- Timestamp and metadata embedding
- Live streaming or on-demand capture modes

### 🎤 Remote Microphone Access
Covertly activate and record audio from the target device's microphone. Capture conversations, ambient sounds, and audio activity with crystal-clear quality. Supports background recording with automatic voice activation detection to save storage space and bandwidth.

**Key Capabilities:**
- Continuous or voice-activated recording
- Adjustable audio quality and bitrate
- Automatic silence detection to reduce file size
- Real-time audio streaming or scheduled recordings
- Support for multiple audio input devices
- Audio file encryption and secure transmission

### ⌨️ Keylogging
Comprehensive keystroke capture and logging system that records every key pressed on the target device. Intelligent logging separates inputs by application, making it easy to identify passwords, messages, searches, and documents. Captures clipboard content, autocomplete data, and form submissions.

**Key Capabilities:**
- Application-specific keystroke separation
- Timestamp precision down to milliseconds
- Clipboard content monitoring and logging
- Special key detection (Ctrl, Alt, Function keys)
- Language and keyboard layout detection
- Smart filtering to identify credentials and sensitive data
- Offline caching with automatic upload when connection restored

### 📁 Remote File Explorer
Full-featured file system browser and manager that provides complete access to the target device's storage. Navigate directories, preview files, upload and download data, and perform file operations remotely. Search functionality allows you to quickly locate specific files or file types across the entire system.

**Key Capabilities:**
- Browse all accessible drives and network shares
- Download files and entire directories
- Upload files to any location on the target system
- Delete, rename, move, and copy files remotely
- File search with filters (name, type, size, date modified)
- Preview text files and view file metadata
- Access hidden and system files
- Compress folders before download for faster transfer

### 💬 Chat Log Extraction
Automatically locate and extract message logs from popular communication platforms. Supports Discord, Telegram, Slack, WhatsApp, Signal, Facebook Messenger, Skype, and more. Retrieves complete conversation history including text messages, shared media, and metadata.

**Key Capabilities:**
- Multi-platform support for major messaging apps
- Extraction of text messages, images, and shared files
- Contact list and group chat identification
- Message timestamps and conversation threading
- Database decryption for encrypted local storage
- Automatic detection of installed messaging applications
- Export in readable formats (JSON, TXT, HTML)

### 🌐 Network Monitoring
Track all network activity and connections in real-time. Monitor active connections, identify communication endpoints, log visited websites, and track data transfer volumes. Provides insights into the target's online behavior and network usage patterns.

**Key Capabilities:**
- Real-time active connection monitoring
- DNS query logging (all visited domains)
- Bandwidth usage tracking per application
- Protocol analysis (HTTP, HTTPS, FTP, etc.)
- IP address geolocation of connections
- Network packet inspection and logging
- Wi-Fi network history and saved credentials
- Browser history extraction (Chrome, Firefox, Edge, Safari)

### 📊 System Information
Comprehensive system profiling that gathers detailed information about the target device's hardware, software, and configuration. Includes operating system details, installed programs, hardware specifications, user accounts, and system settings.

**Key Capabilities:**
- Complete hardware inventory (CPU, RAM, GPU, storage)
- Operating system version and build information
- List of all installed applications and software
- Active user accounts and privileges
- System uptime and boot history
- Environment variables and system paths
- Antivirus and security software detection
- System configuration and registry information (Windows)

### 🔔 Real-time Notifications
Configure custom alerts and triggers based on specific activities or events. Receive instant notifications when certain keywords are typed, specific applications are launched, particular websites are visited, or files are accessed. Keeps you informed without requiring constant monitoring.

**Key Capabilities:**
- Keyword triggers for keylogger events
- Application launch/close notifications
- File access alerts for specified directories
- Website visit notifications
- USB device connection alerts
- Screenshot capture on specific triggers
- Customizable notification delivery methods
- Webhook integration for external systems

### 📸 Webcam Access
Remotely activate the target device's webcam to capture photos or record video.Useful for physical security verification and identity confirmation.

**Key Capabilities:**
- Silent webcam activation
- Photo capture at configurable intervals
- Video recording with adjustable quality
- Support for multiple connected cameras
- Motion detection triggers
- Automatic low-light compensation
- Timestamp and location embedding in images
- Secure encrypted transmission of media

### 🗝️ Credential Recovery
Extract and decrypt saved passwords and credentials from browsers, email clients, FTP clients, and other applications. Recover Wi-Fi passwords, browser autofill data, and stored login information. Presents credentials in an organized, readable format.

**Key Capabilities:**
- Browser password extraction (Chrome, Firefox, Edge, Opera, Brave)
- Email client credentials (Outlook, Thunderbird)
- FTP/SFTP client saved sessions
- Wi-Fi network passwords
- Windows Credential Manager access
- Application-specific credential databases
- Cryptocurrency wallet detection
- Automatic decryption of stored passwords

### 🔍 Process Management
Monitor all running processes and applications in real-time. View detailed information about each process including memory usage, CPU consumption, and process trees. Terminate processes remotely or monitor specific applications for activity.

**Key Capabilities:**
- Real-time process list with resource usage
- Process tree visualization (parent-child relationships)
- Detailed process information (PID, path, command line arguments)
- Remote process termination
- Application usage time tracking
- Startup program identification
- Service and background task monitoring
- DLL and module enumeration for each process

### 🗺️ Geolocation Tracking
Track the physical location of the target device using IP geolocation, Wi-Fi positioning, and GPS data (on supported devices). Creates a location history timeline showing movement patterns and frequently visited locations.

**Key Capabilities:**
- IP-based geolocation
- Wi-Fi network triangulation
- GPS coordinates (on devices with GPS hardware)
- Location history timeline with timestamps
- Frequent location identification
- Address reverse geocoding
- Movement pattern analysis
- Automatic location updates at configurable intervals

---

## 🔧 Requirements

- **Operating System:** Windows 10/11, Linux, macOS
- **Network:** Stable internet connection
- **Permissions:** Administrator/Root access for full functionality
- **Python:** 3.8+ (or specify your tech stack)

## 🚀 Getting Started

*Installation and setup instructions coming soon...*

## 📚 Documentation

Comprehensive documentation is available in the `/docs` directory, including:
- Installation guide
- Configuration options
- API reference
- Security best practices
- Legal compliance guidelines

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **kas-sec/ufih** - *Initial work*

## 🙏 Acknowledgments

- Built for legitimate system administration and monitoring purposes
- Inspired by the need for efficient remote management tools
- Thanks to all contributors and the open-source community

---

<div align="center">

**Remember: With great power comes great responsibility. Use Sentinel ethically and legally.**

*Made with 🛡️ for authorized monitoring*

</div>
