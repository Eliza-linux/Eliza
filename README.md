# Eliza Linux APT Repository

This repository provides Debian packages for **Eliza Linux**.

## Usage

Add the repository:

```bash
echo "deb https://eliza-linux.org/repo stable main" | sudo tee /etc/apt/sources.list.d/eliza.list
sudo apt update
