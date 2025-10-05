# PXNotifier – 实时网络监控工具

## 语言选择：

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

PXNotifier 是一个用于 OpenWrt 的 **实时网络监控工具**。  
它通过 Passwall 持续检测您的互联网连接，并在出现任何问题时立即通知您。  
PXNotifier 支持多种通知方式，以确保您不会错过任何重要的网络状态更新。

---

## 功能特点

- **实时监控** – 持续检测您的连接状态。  
- **多种通知方式** – 通过 **ntfy**、**Telegram 机器人** 或 **WhatsApp** 接收通知。  
- **自动测试** – 在 LuCI 中内置测试按钮以验证通知是否正常工作。  
- **智能提醒** – 仅在状态变化时发送通知，避免重复提醒。  
- **用户友好界面** – 可在 LuCI 的 PeDitXOS 工具菜单中轻松配置。  

---

## 安装方法

您可以使用以下命令安装 PXNotifier：

```sh
sh -c "$(curl -sL https://peditx.ir/projects/PXnotifier/pxnotifier)"
```

或直接通过 PeDitXOS 应用商店 安装。

---

使用指南
	1.	安装完成后，请退出并重新登录 LuCI。
	2.	打开 PeDitXOS 工具 → PXNotifier。
	3.	启用通知服务并选择您偏好的通知方式（ntfy、Telegram 或 WhatsApp）。
	4.	点击 发送测试通知 按钮以验证通知功能。
	5.	PXNotifier 将开始实时监控您的网络连接，并在状态发生变化时自动通知您。

---

特别感谢


- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)
- [Mohamadreza Broujerdi](https://t.me/MR13_B)
- [Sia7ash](https://github.com/Sia7ash)


---

© 2018–2025 PeDitX. 保留所有权利。
如需支持或咨询，请加入我们的 [Telegram](https://t.me/peditx).   群组。