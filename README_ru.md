# PXNotifier – Мониторинг сети в реальном времени

## Выбор языка:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

PXNotifier — это инструмент **мониторинга сети в реальном времени** для OpenWrt.  
Он постоянно проверяет ваше интернет-соединение через Passwall и немедленно уведомляет вас, если возникают проблемы.  
PXNotifier поддерживает несколько каналов уведомлений, чтобы вы никогда не пропустили важное сообщение о состоянии соединения.

---

## Возможности

- **Мониторинг в реальном времени** – Постоянная проверка состояния соединения.  
- **Несколько способов уведомления** – Получайте уведомления через **ntfy**, **Telegram Bot** или **WhatsApp**.  
- **Автоматическое тестирование** – Встроенная кнопка теста в LuCI для проверки уведомлений.  
- **Интеллектуальные уведомления** – Сообщения отправляются только при изменении состояния, чтобы избежать спама.  
- **Удобный интерфейс** – Простая настройка через LuCI в разделе PeDitXOS Tools.  

---

## Установка

Вы можете установить PXNotifier с помощью следующей команды:

```sh
sh -c "$(curl -sL https://peditx.ir/projects/PXnotifier/pxnotifier)"
```

Или установите его напрямую через **PeDitXOS Store**.

---

## Начало работы

1. Выйдите из LuCI и войдите снова после установки.  
2. Откройте **PeDitXOS Tools → PXNotifier**.  
3. Включите службу уведомлений и выберите предпочитаемый способ уведомления (**ntfy**, **Telegram**, **WhatsApp**).  
4. Нажмите кнопку **Send Test Notification**, чтобы проверить работу уведомлений.  
5. Теперь PXNotifier будет отслеживать ваше соединение в реальном времени и автоматически уведомлять при изменении состояния.

---

## Особая благодарность  

- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)
- [Mohamadreza Broujerdi](https://t.me/MR13_B)
- [Sia7ash](https://github.com/Sia7ash)

---

© 2018–2025 PeDitX. Все права защищены.  
Для поддержки или вопросов присоединяйтесь к нам в [Telegram](https://t.me/peditx).  
