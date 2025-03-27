# 🛡️ NFC and RFID Phyiscal Security

This repository provides in-depth technical references, diagrams, and practical insights into NFC technologies and physical security assessments. It covers the structure, authentication flows, attack surfaces, and emulation capabilities of major NFC card types including:

- **MIFARE Classic 1K** – Sector-based memory, CRYPTO1, weak security, cloning & key extraction (e.g., mfkey32).
- **MIFARE Ultralight / C / EV1** – Lightweight, low-security cards with optional 3DES/password authentication.
- **MIFARE DESFire (EV1, EV2, EV3)** – Secure file-based cards with AES encryption, mutual authentication, rolling keys, SDM, and proximity checks.
- **FeliCa** – High-speed, secure cards widely used in Asia for transit and payments, with service/block-based architecture and strong mutual authentication.
- **Magic Cards (Gen1a, Gen4)** – Special MIFARE Classic clones used in red teaming for UID rewriting, sector trailer editing, and advanced **shadow modes** (Pre-Write, Restore, Disable, Split).

🔧 Includes:
- ✅ Authentication flow diagrams for each card type.
- ✅ Memory structure visualizations for each card type.
- ✅ Magic card Capabilities.
- ✅ mfkey32 and Flipper Zero usage for key extraction
- ✅ Physical Security Assessment Tools
- ✅ NFC Relay Attack Explained

📚 Ideal for:
- Penetration testers
- Red teamers
- Security researchers
- Physical security assessments

> ⚠️ Educational use only. Use responsibly and only on systems you are authorized to assess.
