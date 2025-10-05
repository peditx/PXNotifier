# PXNotifier – مانیتورینگ شبکه در زمان واقعی

## انتخاب زبان:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

PXNotifier یک **ابزار مانیتورینگ شبکه در زمان واقعی** برای OpenWrt است.  
این ابزار به صورت مداوم اتصال اینترنت شما را از طریق Passwall بررسی می‌کند و در صورت بروز مشکل بلافاصله هشدار می‌دهد. PXNotifier از چندین کانال اعلان پشتیبانی می‌کند تا هیچ اطلاعیه مهمی را از دست ندهید.

---

## امکانات

- **مانیتورینگ در زمان واقعی** – اتصال اینترنت شما را به صورت مداوم بررسی می‌کند.  
- **چندین گزینه اعلان** – دریافت هشدارها از طریق **ntfy**، **Telegram Bot** یا **WhatsApp**.  
- **تست خودکار** – دکمه تست داخلی در LuCI برای بررسی عملکرد اعلان‌ها.  
- **هشدار هوشمند** – فقط در صورت تغییر وضعیت اطلاع‌رسانی می‌کند تا از اعلان‌های مزاحم جلوگیری شود.  
- **رابط کاربری آسان** – همه تنظیمات را می‌توانید به راحتی از طریق LuCI و بخش PeDitXOS Tools مدیریت کنید.

---

## نصب

برای نصب PXNotifier از دستور زیر استفاده کنید:

```sh
sh -c "$(curl -sL https://peditx.ir/projects/PXnotifier/pxnotifier)"
```

یا از طریق **فروشگاه PeDitXOS** نصب کنید.

---

## شروع به کار

1. پس از نصب، از LuCI خارج و دوباره وارد شوید.  
2. به مسیر **PeDitXOS Tools → PXNotifier** بروید.  
3. سرویس اعلان را فعال کنید و روش اعلان مورد نظر خود را انتخاب کنید (**ntfy**، **Telegram**، **WhatsApp**).  
4. برای اطمینان از عملکرد، دکمه **Send Test Notification** را فشار دهید.  
5. حالا PXNotifier به صورت مداوم اتصال شما را بررسی کرده و در صورت تغییر وضعیت، هشدار می‌دهد.

---

##  تشکر ویژه  

- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)
- [Mohamadreza Broujerdi](https://t.me/MR13_B)
- [Sia7ash](https://github.com/Sia7ash)


---

© 2018–2025 PeDitX. All rights reserved.  
For support or inquiries, join us on [Telegram](https://t.me/peditx).  
