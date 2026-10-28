# Oflync app downloads

Installers for Oflync apps. The files are attached to **[Releases](https://github.com/oflync/app-dist/releases)**, not stored in this repository.

## Oflync Billing Desk

Free, offline billing desk for small retail shops: GST receipts, USB/network thermal printing, customers with QR cards, end-of-day insights, and backups. All data stays on the shop's computer.

**Latest version: 1.0.0** — [release page](https://github.com/oflync/app-dist/releases/tag/billing-desk-v1.0.0)

| Platform | Download | Install |
|----------|----------|---------|
| Ubuntu / Debian (recommended for Linux) | [Oflync-Billing-Desk-1.0.0-linux-amd64.deb](https://github.com/oflync/app-dist/releases/download/billing-desk-v1.0.0/Oflync-Billing-Desk-1.0.0-linux-amd64.deb) | `sudo apt install ./Oflync-Billing-Desk-1.0.0-linux-amd64.deb`, then open **Oflync Billing Desk** from the app menu |
| Other Linux (portable) | [Oflync-Billing-Desk-1.0.0-linux-x86_64.AppImage](https://github.com/oflync/app-dist/releases/download/billing-desk-v1.0.0/Oflync-Billing-Desk-1.0.0-linux-x86_64.AppImage) | `chmod +x Oflync-Billing-Desk-*.AppImage` and run it. On Ubuntu 23.10+, use the `.deb` instead, or run the AppImage with `--no-sandbox`. |
| Windows 10/11 | Coming soon | — |

### USB receipt printer on Linux

Give the shop's user account access to the printer once, then log out and back in:

```bash
sudo usermod -aG lp $USER
```

### Verify your download

| File | SHA-256 |
|------|---------|
| `Oflync-Billing-Desk-1.0.0-linux-amd64.deb` | `17a88ffcd1b658190b1a9728ab9f424b258d1965fef0786759cc6afadd16633b` |
| `Oflync-Billing-Desk-1.0.0-linux-x86_64.AppImage` | `34bac841ae95c18c21a395f47abb62d0bc5f273af193ae9d149966b80b8cbb80` |

Check with `sha256sum <file>`. `SHA256SUMS.txt` is also attached to the release.
