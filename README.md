# 🛡️ NFC Security & Emulation Toolkit

This repository provides in-depth technical references, diagrams, and practical insights into NFC technologies and physical security assessments. It covers the structure, authentication flows, attack surfaces, and emulation capabilities of major NFC card types including:

- **MIFARE Classic 1K** – Sector-based memory, CRYPTO1, weak security, cloning & key extraction (e.g., mfkey32).
- **MIFARE Ultralight / C / EV1** – Lightweight, low-security cards with optional 3DES/password authentication.
- **MIFARE DESFire (EV1, EV2, EV3)** – Secure file-based cards with AES encryption, mutual authentication, rolling keys, SDM, and proximity checks.
- **Magic Cards (Gen1a, Gen4)** – Special MIFARE Classic clones used in red teaming for UID rewriting, sector trailer editing, and advanced **shadow modes** (Pre-Write, Restore, Disable, Split).
- **FeliCa** – High-speed, secure cards widely used in Asia for transit and payments, with service/block-based architecture and strong mutual authentication.

🔧 Includes:
- ✅ Authentication flow diagrams for each card type (Mermaid + PNG)
- ✅ DESFire memory structure visualizations
- ✅ Shadow modes explained with real-world examples
- ✅ mfkey32 and Flipper Zero usage for key extraction
- ✅ Sequence diagrams (Mermaid) showing interaction between readers, PICC, apps, and files

📚 Ideal for:
- Penetration testers
- Red teamers
- Security researchers
- NFC hobbyists
- Physical security assessments

> ⚠️ Educational use only. Use responsibly and only on systems you are authorized to assess.
