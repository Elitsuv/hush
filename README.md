<p align="center">
  <img src="assets/hush.png" width="128" height="128" alt="Hush Logo">
</p>

# Hush | Encrypted Whispers

A minimal, stateless protocol for sharing private, deliberate messages. Content is encoded locally and exists only within the generated URL.

## 🔐 Security Principles
* **Zero-Knowledge**: Messages are never sent to or stored on a server.
* **Client-Side**: Encoding and decoding happen entirely within the browser.
* **Stateless**: No database. No tracking. No logs.
* **Ephemeral**: If the link is lost, the message is gone forever.

## 🚀 Deployment
Designed for seamless hosting on **Vercel**.
* Uses `cleanUrls` for professional, extension-less routing.
* Optimized for mobile "Keepsake" saving via `html2canvas`.

## 🛠️ Stack
* **UI**: Tailwind CSS / Lucide Icons
* **Animation**: Particles.js
* **Logic**: Vanilla JavaScript / Base64 Protocol

## ⚖️ License
Licensed under the [MIT License](LICENSE).