SecureChatBot - End-to-End Encrypted Discord Messaging Bot

🚀 SecureChatBot is a high-security, end-to-end encrypted Discord bot designed for private and untraceable communication. Built with AES-256 & RSA hybrid encryption, it ensures that only the intended recipient can decrypt and read messages.

🔒 Key Features

✅ End-to-End Encryption → Messages are encrypted before sending and decrypted only by the receiver.
✅ Zero Message Storage → Sent messages are never stored, ensuring maximum privacy.
✅ Unique User Codes → Each user gets a 12-digit secret code and a randomly changing 3-digit sending code for secure identity masking.
✅ Auto-Decryption → Messages auto-decrypt for 15 minutes after authentication.
✅ Re-Encryption → If unread for 15 minutes, messages are automatically re-encrypted.
✅ Permanent Account Destruction → Secure multi-step deletion process requiring user code & Discord Passkey.
✅ Professional UI → High-quality embeds for commands, while received messages remain plain text (Sent by {sender code}).

⚙️ How It Works

1️⃣ Users register and receive a 12-digit secret user code & 3-digit sending code.
2️⃣ Senders encrypt messages and transmit them through the bot (without storing them).
3️⃣ Receivers authenticate, decrypt messages, and can read them for 15 minutes before re-encryption.
4️⃣ Accounts can be permanently deleted using the Destruction Command with multi-step verification.

🔧 Tech Stack

Python (discord.py 2.4.0)

Cryptography (AES-256 & RSA)

Asyncio & JSON (Secure user handling)

Secrets Module (Secure random generation)


🔗 Get Started

Clone this repository and follow the installation guide to deploy SecureChatBot on your Discord server!


---

Let me know if you want any modifications! 🚀

