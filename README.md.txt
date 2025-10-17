# 123 - Geoguessr Konum Haritası

Bu, Geoguessr oynarken mevcut turun gerçek konumunu gösteren etkileşimli bir harita arayüzü ekleyen bir Tarayıcı Kullanıcı Komut Dosyasıdır.

## Özellikler

- **Gerçek Konum Tespiti:** Geoguessr'ın API isteklerini dinleyerek anlık turun koordinatlarını yakalar.
- **Etkileşimli Harita:** Açık kaynaklı **OpenStreetMap**'i kullanarak, penceresi sürüklenip yeniden boyutlandırılabilen bir haritada konumu işaretler.
- **Klavye Kısayolları:**
    - `Insert`: Haritayı açıp kapatır.
    - `Q` (Harita açıkken): Mevcut konumu haritada yeniden yükler/günceller.

## Kurulum 🛠️

Bu bir kullanıcı komut dosyasıdır (`.user.js`), bu nedenle tarayıcınızda çalışması için bir kullanıcı komut dosyası yöneticisine ihtiyacınız var.

1.  **Gerekli Eklentiyi Kurun:** Tarayıcınıza uygun olan aşağıdaki eklentilerden birini kurun:
    * **Tampermonkey** (Önerilen)
    * **Greasemonkey** (Firefox için)

2.  **Komut Dosyasını Yükleyin:**
    * **GitHub'daki bu dosyanın Raw (Ham) linkini** kopyalayın.
    * Tarayıcınızda bu linke gidin.
    * Kullanıcı komut dosyası yöneticiniz (örn. Tampermonkey) otomatik olarak yükleme ekranını açacaktır.
    * **"Yükle"** butonuna tıklayın.

## Kullanım 🚀

1.  `https://www.geoguessr.com/*` adresinde bir oyuna başlayın.
2.  Oyun başladığında, harita penceresini açmak için klavyenizdeki **`Insert`** tuşuna basın.
3.  Harita, mevcut turun konumunu gösterecektir.
4.  Haritayı sürükleyebilir ve köşelerinden tutarak yeniden boyutlandırabilirsiniz.
5.  Yeni bir konuma geçtiğinizde, harita otomatik olarak güncellenmezse **`Q`** tuşuna basarak konumu güncelleyebilirsiniz.