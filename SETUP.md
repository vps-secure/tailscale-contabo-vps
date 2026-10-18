# Full Setup Guide - Contabo + Tailscale

## Step 1: Install Tailscale on VPS (Arch Linux)

```bash
sudo pacman -S tailscale
sudo systemctl enable --now tailscaled
sudo tailscale up --ssh