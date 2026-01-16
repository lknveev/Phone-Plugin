# Eaglercraft Phone Plugin

A comprehensive phone system plugin for Eaglercraft 1.12.2 featuring messages, emails, contacts, group chats, and settings.

## Features

- 📱 **Messages** - Direct messaging between players
- 📧 **Email System** - Send and receive emails with subjects
- 👥 **Contacts** - Manage your contact list
- 💬 **Group Chats** - Create group conversations
- ⚙️ **Settings** - Customize notifications, ringtone, and phone number

## Installation

1. Download the latest release JAR file
2. Place it in your `plugins/` folder
3. Restart your server
4. Use `/phone` to access your phone

## Commands

- `/phone` - Open your phone interface

## Permissions

- `phone.use` - Allows using the phone (default: true)
- `phone.admin` - Admin permissions (default: op)

## Building from Source

Requirements:
- Java 8 or higher
- Maven

Build command:
```bash
mvn clean package
```

The compiled JAR will be in the `target/` folder.

## License

MIT License - Feel free to modify and distribute!