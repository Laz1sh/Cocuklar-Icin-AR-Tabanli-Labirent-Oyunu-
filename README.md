# Çocuklar İçin AR Tabanlı Labirent Oyunu

Unity ile geliştirilmiş, artırılmış gerçeklik tabanlı bir mobil labirent oyunu.
Telefonun kamerası tetikleyici görseli tanıdığında 3B labirent gerçek dünya
üzerinde beliriyor; oyuncu telefonu eğerek labirentteki topu çıkışa ulaştırmaya
çalışıyor.

Çocukların artırılmış gerçeklik teknolojisiyle oyun oynayarak tanışması
hedeflenerek tasarlandı.

**Geliştirici:** Huzeyfe Beyazal · **Tarih:** Nisan 2025

## Tanıtım videosu

https://youtube.com/shorts/gaVyAOST1e0

## Nasıl denenir

1. [Sürümler sayfasından](https://github.com/HarbiLaz/Cocuklar-Icin-AR-Tabanli-Labirent-Oyunu-/tags)
   APK dosyasını indirin.
2. Android telefonunuzda "bilinmeyen kaynaklara izin ver" ayarını açıp APK'yı
   kurun.
3. Uygulamayı açın ve kamera iznini onaylayın.
4. Aşağıdaki tetikleyici görseli ekranda açın veya yazdırın, ardından telefonun
   kamerasını görsele doğrultun.
5. Labirent görselin üzerinde belirdiğinde telefonu eğerek topu yönlendirin.

### Tetikleyici görsel

Kameraya gösterilmesi gereken görsel:

![Labirent tetikleyici](https://github.com/user-attachments/assets/5628f46e-d8f4-4f6b-b3a6-144ce5b778b3)

## Unity içinden görünüm

<img width="940" src="https://github.com/user-attachments/assets/b9328b79-5d53-44a0-8cdb-e7a7da069505" alt="Unity sahne görünümü">

## Kullanılan teknolojiler

| Alan | Teknoloji |
|---|---|
| Oyun motoru | Unity |
| AR altyapısı | Vuforia (görsel hedef takibi) |
| Programlama dili | C# |
| Hedef platform | Android |

`DefaultTrackableEventHandler.cs`, hedef görselin takip durumuna göre sahnedeki
nesneleri gösterip gizleyen olay yöneticisidir: görsel kameradan çıktığında
labirent gizlenir, tekrar görüldüğünde geri gelir.

## Sistem gereksinimleri

- Android 8.0 (Oreo) ve üzeri
- Kamera erişim izni
- En az 2 GB RAM

## Proje dokümantasyonu

Oyunun yanı sıra yazılım yaşam döngüsü belgeleri de hazırlandı:

| Belge | İçerik |
|---|---|
| [Kullanıcı Dokümanı](Kullanici_Dokumani.pdf) | Kurulum, kullanım adımları, sorun giderme |
| [SDLC Analizi](SDLC%20Yazilim_Yasam_Dongusu.pdf) | Yazılım yaşam döngüsü modeli ve aşamaları |
| [SWOT Analizi](Swot_Analizi.pdf) | Güçlü/zayıf yönler, fırsatlar ve tehditler |
| [RAMS Analizi](Rams_Analizi.pdf) | Güvenilirlik, kullanılabilirlik, bakım yapılabilirlik ve güvenlik |

## Sorun giderme

**Labirent belirmiyor:** Ortamın yeterince aydınlık olduğundan ve tetikleyici
görselin tamamının kamerada göründüğünden emin olun. Parlayan bir ekrandan
gösteriyorsanız yansıma takibi zorlaştırabilir; yazdırılmış hâli daha iyi sonuç
verir.

**Kamera açılmıyor veya siyah ekran:** Cihaz ayarlarından uygulamaya kamera
izni verildiğini kontrol edin.

**Top hareket etmiyor:** Telefonu hafifçe eğerek deneyin; hareket cihazın
eğim sensörüne bağlıdır.

## Depo içeriği hakkında not

Bu depoda oyunun AR olay yönetimi script'i, proje dokümanları ve yayınlanmış
APK bulunuyor. Unity projesinin tamamı (sahneler, modeller, materyaller) depoya
dahil değil.
