# PXNotifier – Real-time Network Monitor

## Language Selection:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

PXNotifier is a **real-time network monitoring tool** for OpenWrt.  
It continuously checks your internet connection via Passwall and alerts you immediately if there are any issues. PXNotifier supports multiple notification channels to ensure you never miss a critical status update.

---

## Features

- **Real-time monitoring** – Continuously checks your connection status.  
- **Multiple notification options** – Receive alerts via **ntfy**, **Telegram Bot**, or **WhatsApp**.  
- **Automatic testing** – Built-in test button in LuCI to verify notifications.  
- **Intelligent alerts** – Notifies only on status changes to avoid spamming.  
- **User-friendly interface** – Configure everything easily from LuCI under PeDitXOS Tools.  

---

## Installation

You can install PXNotifier using the following command:

```sh
sh -c "$(curl -sL https://peditx.ir/projects/PXnotifier/pxnotifier)"
```

Or install it directly via the **PeDitXOS Store**.

---

## Getting Started

1. Log out and back into LuCI after installation.  
2. Open **PeDitXOS Tools → PXNotifier**.  
3. Enable the notifier service and select your preferred notification method (**ntfy**, **Telegram**, **WhatsApp**).  
4. Click the **Send Test Notification** button to verify that notifications work.  
5. PXNotifier will now monitor your connection in real-time and notify you automatically on status changes.


---

##  Special Thanks  

- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)
- [Mohamadreza Broujerdi](https://t.me/MR13_B)
- [Sia7ash](https://github.com/Sia7ash)


---

© 2018–2025 PeDitX. All rights reserved.  
For support or inquiries, join us on [Telegram](https://t.me/peditx).  
