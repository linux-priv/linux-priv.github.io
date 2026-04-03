---
title: "Download"
---

## Download Linux-Priv 1.0.0 "Zero"

Linux-Priv is free, open source, and always will be.

### Recommended: Cinnamon Edition

| File | Size | SHA256 |
|------|------|--------|
| linux-priv-1.0.0-cinnamon-64bit.iso | ~2.8 GB | `coming soon` |

[**Direct Download**](#) | [**Torrent**](#) | [**GitHub Releases**](https://github.com/linux-priv/releases)

---

### Verify your download

```bash
sha256sum linux-priv-1.0.0-cinnamon-64bit.iso
```

Compare the output to the SHA256 checksum listed above.

---

### System Requirements

- **CPU**: 64-bit (x86_64), 2 cores minimum
- **RAM**: 4 GB minimum, 8 GB recommended
- **Disk**: 25 GB minimum
- **Boot**: UEFI or Legacy BIOS

---

### Create a bootable USB

```bash
# Linux
sudo dd if=linux-priv-1.0.0-cinnamon-64bit.iso of=/dev/sdX bs=4M status=progress

# Or use Balena Etcher (Windows/Mac/Linux)
```
