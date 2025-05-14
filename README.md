# Film Kayıt Uygulaması

Bu proje, ASP.NET Core MVC kullanılarak hazırlanmış basit bir film kayıt sistemidir. Kullanıcı, yeni film ekleyebilir, filmleri listeleyebilir ve fotoğraf yükleyebilir. Projede veritabanı işlemleri Entity Framework ile yapılmıştır.

---

## Özellikler

- Film ekleme (adı, türü, yılı vs.)
- Film listesini tablo halinde gösterme
- Fotoğraf yükleme (her filme özel)
- Veritabanı ile kayıt alma
- Basit kullanıcı arayüzü (Razor sayfaları)

---

## Kullanılan Teknolojiler

- ASP.NET Core MVC
- Entity Framework Core
- C#
- Razor Pages
- HTML / CSS

---

## Kurulum

1. Bilgisayarında [.NET SDK](https://dotnet.microsoft.com/download) yüklü olmalı.
2. Proje klasörünü Visual Studio ile aç veya terminalden şu komutları yaz:

```
cd proje
dotnet restore
dotnet ef database update
dotnet run
```

3. Uygulama açıldığında tarayıcıda otomatik olarak çalışacaktır. Çalışmazsa şu adresi açabilirsin:
```
https://localhost:5001
```

---

## Klasörler Hakkında

- **Controllers**: Sayfa yönlendirmeleri ve işlemler burada.
- **Models**: Film sınıfı ve veritabanı bağlantısı burada.
- **Views**: Görsel arayüz Razor ile buradan hazırlanır.
- **wwwroot**: Fotoğraflar burada tutulur.
- **Migrations**: Veritabanı kayıt sistemi.

---

## Not

Bu proje bir ders ödevi olarak yapılmıştır. Temel seviyede bir film kayıt sistemi örneğidir. Gerçek bir uygulama değildir.

---

**Hazırlayan:**  
Ömer Eren Danyıldız
11/ATL / 1069  
Tarih: 11.04.2025
Son Düzenleme Tarihi: 14.05.2025
