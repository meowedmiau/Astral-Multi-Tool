# ASTRAL MULTI TOOL

**A modular Python-based multi-tool for cryptography and network analysis.**

ASTRAL is a terminal-based toolkit bringing together cryptographic utilities, networking diagnostics, and security-related tools in one organized application.

Built with Python, ASTRAL features a modular architecture with individually implemented tools, an interactive terminal dashboard, fuzzy search, and live execution feedback.

## Features

### Cryptography — 151 Tools

- Encoding and Decoding
- Hashing
- Fernet Encryption and Decryption
- AES Encryption and Decryption
- Classical Ciphers
- RSA
- Elliptic Curve Cryptography (ECC)

### Networking — 40 Tools

- IP and DNS Utilities
- Port Utilities
- HTTP Utilities
- Network Analysis

### Terminal Experience

- Interactive terminal dashboard
- Organized module and category navigation
- Tool numbering and aliases
- Fuzzy search
- Command autocomplete
- Live execution feedback
- Configurable application settings

## Project Statistics

| Metric | Count |
|---|---:|
| Total Tools | 191 |
| Cryptography Tools | 151 |
| Networking Tools | 40 |
| Python Files | 229 |

## Requirements

- Python 3
- pip

## Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
cd Astral-Multi-Tool
```

Install the dependencies:

```bash
py -m pip install -r requirements.txt
```

## Running ASTRAL

Start the application:

```bash
py main.py
```

Navigate through the dashboard to explore the available modules and execute individual tools.

## Configuration

Application settings are stored in `settings.json`.

You can configure:

- Application name and version
- Accent and secondary colors
- Background color
- Banner visibility
- Command history
- Fuzzy search
- Maximum command history size

## Project Structure

```text
Astral-Multi-Tool/
├── astral/
│   ├── core/
│   ├── terminal/
│   └── modules/
│       ├── cryptography/
│       └── networking/
├── data/
├── DISCLAIMER.md
├── LICENSE
├── README.md
├── requirements.txt
├── settings.json
└── main.py
```

## Disclaimer

ASTRAL is intended for educational, diagnostic, and authorized security-testing purposes only.

Users are responsible for ensuring that their activities are lawful and authorized.

The software is provided "AS IS". Read the full [DISCLAIMER](DISCLAIMER.md) before using ASTRAL.

## License

See the [LICENSE](LICENSE) file for licensing information.

---

**ASTRAL MULTI TOOL**

*One terminal. 191 tools. Multiple capabilities.*