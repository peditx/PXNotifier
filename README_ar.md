# PXNotifier – مراقبة الشبكة في الوقت الحقيقي

## اختيار اللغة:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

PXNotifier هو **أداة لمراقبة الشبكة في الوقت الحقيقي** لنظام OpenWrt.  
يقوم بمراقبة اتصال الإنترنت الخاص بك باستمرار عبر Passwall ويقوم بإرسال إشعار فوري في حال حدوث أي مشكلة.  
يدعم PXNotifier عدة قنوات للإشعارات لضمان عدم تفويت أي تنبيه مهم يتعلق بحالة الاتصال.

---

## المميزات

- **مراقبة في الوقت الحقيقي** – يتحقق باستمرار من حالة الاتصال بالإنترنت.  
- **خيارات إشعار متعددة** – استلم التنبيهات عبر **ntfy** أو **بوت تيليجرام (Telegram Bot)** أو **واتساب (WhatsApp)**.  
- **اختبار تلقائي** – زر اختبار مدمج في واجهة LuCI للتحقق من عمل الإشعارات.  
- **تنبيهات ذكية** – لا يرسل إشعارات إلا عند تغيّر الحالة لتجنّب الإزعاج.  
- **واجهة سهلة الاستخدام** – يمكن ضبط جميع الإعدادات بسهولة من خلال LuCI تحت قسم أدوات PeDitXOS.  

---

## التثبيت

يمكنك تثبيت PXNotifier باستخدام الأمر التالي:

```sh
sh -c "$(curl -sL https://peditx.ir/projects/PXnotifier/pxnotifier)"
```

أو قم بتثبيته مباشرة من خلال متجر PeDitXOS.

---

البدء بالاستخدام
	1.	بعد التثبيت، سجّل الخروج ثم أعد تسجيل الدخول إلى LuCI.
	2.	افتح المسار PeDitXOS Tools → PXNotifier.
	3.	فعّل خدمة الإشعارات واختر طريقة الإشعار المفضّلة (ntfy أو Telegram أو WhatsApp).
	4.	اضغط على زر إرسال إشعار تجريبي للتأكد من عمل الإشعارات.
	5.	سيبدأ PXNotifier بمراقبة اتصالك بالإنترنت في الوقت الحقيقي وإرسال تنبيهات تلقائية عند تغيّر الحالة.

---

الشكر الخاص


- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)
- [Mohamadreza Broujerdi](https://t.me/MR13_B)
- [Sia7ash](https://github.com/Sia7ash)


---

© 2018–2025 PeDitX. جميع الحقوق محفوظة.
للدعم أو الاستفسارات، انضم إلينا على [Telegram](https://t.me/peditx).

---