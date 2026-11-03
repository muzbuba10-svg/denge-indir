## Denge v1.0.0

Windows için ilk sürüm. Tek dosya, kurulum gerektirmez.

### İçindekiler
- Yerel hesap: kayıt, giriş, PBKDF2 korumalı şifre, otomatik kilit
- Ana sayfa: ay seçici, gelir/gider/net özeti, kategori dağılımı, son hareketler
- Hareketler: ekleme, düzenleme, silme, filtre, arama, güne göre gruplama
- Rapor: 0-100 denge puanı, tasarruf oranı, günlük ortalama, önceki ay karşılaştırması, öneriler
- Yedek: AES-GCM-256 şifreli .denge dosyası, geri yükleme, CSV dışa aktarma
- Masaüstü: kendi penceresi, yerel kaydetme penceresi, tek örnek kilidi

### Kurulum
1. Aşağıdan Denge.exe dosyasını indir.
2. Çift tıkla. Kurulum gerekmez.

### Notlar
- Windows 10/11 ve Microsoft Edge WebView2 Runtime gerekir.
- Kod imzalama sertifikası yok; SmartScreen uyarısında "Ek bilgi > Yine de çalıştır" seç.
- Veriler %LOCALAPPDATA%\Denge altında kalır, dışarı gönderilmez.
