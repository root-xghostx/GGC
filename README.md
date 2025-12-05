[GGC_README.md](https://github.com/user-attachments/files/23972462/GGC_README.md)
# Golden Ghost Chat 🔐👻



###### Where your conversations remain truly private. 👻🔒

A secure, invite-only encrypted messaging application with true end-to-end encryption and database security.



####  	📄 License

* ###### This project is proprietary software. All rights reserved.



####  	⚠️ Important Security Notes

* ###### Browser Security: Use modern, updated browsers for best encryption support.
* ###### VPN Usage: Use a secure, reliable VPN provider for additional security.



####  	🌟 Features:

* Invite-Only System: Controlled user registration with usage limits
* True E2E Encryption: Client-generated keys, server never sees plaintext messages
* Database Encryption: AES-256-GCM encryption for sensitive data at rest
* No Chat Logs: Ephemeral messaging - no message history stored



####  	🛡️ Security Architecture (Triple-Layer Protection):

* Transport Security: HTTPS + secure WebSockets
* Message Encryption: True E2E with client-generated keys
* Database Security: AES-256-GCM encryption at rest



####  	Key Security Features:

* No Plaintext Storage: All sensitive data is encrypted
* Client-Side Key Generation: Server never sees encryption keys
* Atomic Transactions: Prevent race conditions
* Row-Level Locking: Secure concurrent access
* Automatic Key Rotation: Per-message encryption keys



####  	🔐 Encryption Details:

###### Message Encryption Flow

* First client generates random room key using Web Crypto API
* Clients exchange public keys via server relay
* Room key encrypted separately for each participant using ECDH
* Messages encrypted with room key using AES-256-GCM
* Server only sees encrypted payloads

###### Database Encryption

* Algorithm: AES-256-GCM

###### Encrypted Fields:

* Group names
* Admin notes

###### Key Management: 256-bit key



####  	👤 Default Admin Account

###### Username: \*\*REDACTED\*\*

###### Password: \*\*REDACTED\*\*



####  	👑 Admin Controls:

* Manage users (freeze/unfreeze accounts)
* Create and manage private group chats
* Generate invite codes with expiration and usage limits
* Add private admin notes about users
* Delete unused invite codes



####  	📱 Usage Guide

###### For Admins:

* Log in with admin credentials
* Access the Admin Dashboard from the sidebar
* Generate invite codes for new users
* Create and manage group chats
* Monitor user activity and add private notes



###### For Users:

* Request an invite code from an admin
* Register with the invite code
* Join existing groups or wait to be added
* Start chatting with end-to-end encryption



####  	💬 Messaging:

* Real-time WebSocket communication
* Group chat support with per-group encryption
* Online/offline user status
* Mobile-responsive design
* Clean, modern UI with black/gold theme



####  	🙏 Acknowledgments

* Built with security and privacy as primary concerns
* Designed for secure team communications
* Inspired by the need for truly private messaging solutions



####  	📞 Support \& Contact:

###### For inquiries, support, and reporting issues:

Telegram: https://t.me/ggc\_admin  OR  https://t.me/goldenghost\_chat

In-app: Contact link available in header

