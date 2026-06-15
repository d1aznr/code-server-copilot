# GitHub Copilot Code Server Installer

Installs GitHub Copilot and Copilot Chat extensions in code-server by automatically finding and downloading compatible versions based on your code-server VS Code version.

## Run

```bash
curl -fsSL https://raw.githubusercontent.com/d1aznr/code-server-copilot/refs/heads/main/install-copilot.sh | bash
```

or download it manually and then run:

```bash
chmod +x install-copilot.sh && ./install-copilot.sh
```

## Requirements

- code-server
- curl
- jq
- gzip or gunzip
