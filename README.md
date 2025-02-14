SecureChatBot - End-to-End Encrypted Discord Messaging Bot

🚀 SecureChatBot is a high-security, end-to-end encrypted Discord bot designed for private, untraceable communication. Built with AES-256 & RSA hybrid encryption, it ensures that only the intended recipient can decrypt and read messages.


---

🔒 Key Features

✅ End-to-End Encryption → Messages are encrypted before sending and decrypted only by the receiver.
✅ Zero Message Storage → Sent messages are never stored, ensuring maximum privacy.
✅ Permanent User Codes → Every user has a 12-digit secret user code and a permanent 3-digit sending code.
✅ Auto-Decryption → Messages auto-decrypt for 15 minutes after authentication.
✅ Re-Encryption → If unread after 15 minutes, messages are automatically re-encrypted.
✅ Permanent Account Destruction → Secure multi-step deletion process requiring user code & Discord Passkey.
✅ Professional UI → High-quality embeds for commands, while received messages remain plain text (Sent by {sender code}).


---

⚙️ How It Works

1️⃣ User Registration

Every user gets a 12-digit secret user code and a permanent 3-digit sending code.

The sending code allows others to find and message the user securely.


2️⃣ Secure Messaging

Messages are encrypted using AES-256 & RSA hybrid encryption before being sent.

The bot transmits the message without storing it.


3️⃣ Receiver Authentication & Decryption

The receiver authenticates using their credentials.

Messages auto-decrypt for 15 minutes after authentication.


4️⃣ Auto Re-Encryption

If the receiver doesn’t respond within 15 minutes, messages are re-encrypted for security.


5️⃣ Permanent Account Destruction

Users can permanently delete their account using a multi-step verification process.

Requires user code & Discord Passkey for security.

Once deleted, data cannot be recovered.



---

🔧 Tech Stack

Python (discord.py 2.4.0)

Cryptography (AES-256 & RSA hybrid encryption)

Asyncio & JSON (Secure user handling)

Secrets Module (Secure random generation)



---

💡 Commands Overview

🔹 User Registration

/register

Generates 12-digit user code & permanent 3-digit sending code.


🔹 Send Encrypted Message

/send <sending_code> <message>

Encrypts the message and sends it to the receiver.


🔹 Authenticate & Read Messages

/authenticate

Decrypts received messages for 15 minutes.


🔹 Destroy Account (Permanent)

/destroy_account

Multi-step verification before permanent deletion.



---

🔗 Get Started

For any issues, feel free to open an issue or contribute to the project! 🚀


---
