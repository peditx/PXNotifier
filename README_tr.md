# PXNotifier – Gerçek Zamanlı Ağ İzleme Aracı

## Dil Seçimi:

[**English**](README.md) | [**فارسی**](README_fa.md) | [**中文**](README_zh.md) | [**Русский**](README_ru.md) | [**Türkçe**](README_tr.md) | [**العربية**](README_ar.md)

![PeDitX Banner](https://raw.githubusercontent.com/peditx/luci-theme-peditx/refs/heads/main/luasrc/brand.png)  

---

PXNotifier, OpenWrt için geliştirilmiş bir **gerçek zamanlı ağ izleme aracıdır**.  
Passwall üzerinden internet bağlantınızı sürekli olarak kontrol eder ve herhangi bir sorun olduğunda sizi anında bilgilendirir.  
PXNotifier, önemli bağlantı durumlarını asla kaçırmamanız için birden fazla bildirim kanalını destekler.

---

## Özellikler

- **Gerçek zamanlı izleme** – İnternet bağlantınızı sürekli olarak denetler.  
- **Birden fazla bildirim seçeneği** – **ntfy**, **Telegram Bot** veya **WhatsApp** üzerinden uyarılar alın.  
- **Otomatik test** – Bildirimleri doğrulamak için LuCI arayüzünde yerleşik test butonu.  
- **Akıllı uyarılar** – Gereksiz bildirimleri önlemek için yalnızca durum değişikliklerinde bilgilendirme yapar.  
- **Kullanıcı dostu arayüz** – Tüm ayarlar, LuCI’deki PeDitXOS Araçları altında kolayca yapılandırılabilir.  

---

## Kurulum

PXNotifier’ı aşağıdaki komutla yükleyebilirsiniz:

```sh
sh -c "$(curl -sL https://peditx.ir/projects/PXnotifier/pxnotifier)"
```

Veya doğrudan PeDitXOS Mağazası üzerinden yükleyin.

---

Başlarken
	1.	Kurulumdan sonra LuCI oturumunuzu kapatıp yeniden açın.
	2.	PeDitXOS Tools → PXNotifier menüsüne gidin.
	3.	Bildirim hizmetini etkinleştirin ve tercih ettiğiniz yöntemi seçin (ntfy, Telegram, WhatsApp).
	4.	Bildirimlerin çalıştığından emin olmak için Test Bildirimi Gönder butonuna tıklayın.
	5.	PXNotifier artık bağlantınızı gerçek zamanlı olarak izleyecek ve durum değişikliklerinde sizi otomatik olarak bilgilendirecektir.

---

Özel Teşekkürler


- [PeDitX](https://github.com/peditx)  
- [PeDitXRT](https://github.com/peditx/peditxrt)  
- [OpenWrt](https://github.com/openwrt)  
- [Bootstrap Theme](https://github.com/twbs/bootstrap)
- [Mohamadreza Broujerdi](https://t.me/MR13_B)
- [Sia7ash](https://github.com/Sia7ash)


---

© 2018–2025 PeDitX. Tüm hakları saklıdır.
Destek veya sorularınız için [Telegram](https://t.me/peditx) grubumuza katılabilirsiniz.

---