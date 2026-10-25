# kod_asistanim
* 1_asistan_ismi = "KODİ"
  - Hata Gerekçesi: Değişken isimleri rakamla başlayamaz. SyntaxError (Söz Dizimi Hatası) verir.
  - Düzeltilmiş Hali: asistan_ismi = "KODİ"

* asistan_bellek-kapasitesi = "16 GB"
  - Hata Gerekçesi: Değişken isimlerinde tire (-) karakteri kullanılamaz. Ayrıca küresel standartlar gereği Türkçe karakter (ı) kullanılmamalıdır.
  - Düzeltilmiş Hali: asistan_bellek_kapasitesi = "16 GB"

* while = 2026
  - Hata Gerekçesi: "while" ifadesi Python diline ait ayrılmış bir anahtar kelimedir (reserved word). Değişken adı olarak atanamaz.
  - Düzeltilmiş Hali: sistem_yili = 2026

* Kullanıcı Adı = "Ebru"
  - Hata Gerekçesi: Değişken isimlerinde boşluk bırakılamaz ve Türkçe karakter (ı, ç) kullanılmamalıdır.
  - Düzeltilmiş Hali: kullanici_adi = "Ebru"

* sistem_durumu$ = True
  - Hata Gerekçesi: Değişken isimlerinde alt tire (_) hariç özel karakterler ($) kullanılamaz.
  - Düzeltilmiş Hali: sistem_durumu = True

----------------------------------------------------------------------
2. AŞAMA: DÜZELTİLMİŞ VE STANDARTLARA UYGUN KOD BLOKU

# Sistem Yapılandırma Taslağı (Düzeltilmiş)
asistan_ismi = "KODİ"
asistan_bellek_kapasitesi = "16 GB"
sistem_yili = 2026
kullanici_adi = "Ebru"
sistem_durumu = True
