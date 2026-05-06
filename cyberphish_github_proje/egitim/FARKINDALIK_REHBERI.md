# 🎓 Sosyal Mühendislik Farkındalık Eğitimi

## Bölüm 1: Saldırı Türlerini Tanıma

### 1.1 Oltalama (Phishing) Belirtileri

| Risk İşareti | Açıklama | Örnek |
|-------------|----------|-------|
| **Aciliyet** | "Hemen yapın yoksa..." | "24 saat içinde hesabınız kapanacak" |
| **Otorite** | Sahte yetki figürü | "Güvenlik departmanı", "Banka yönetimi" |
| **Korku** | Tehdit içerikli mesaj | "Hesabınız hacklendi" |
| **Ödül** | Aşırı cazip teklif | "Kazandınız! Hemen tıklayın" |

### 1.2 Sahte Web Sitelerini Ayırt Etme

```
✅ GERÇEK:   https://www.bank.com/login
❌ SAHTE:    http://bank-login.com
❌ SAHTE:    https://bank.com.suspicious.ru
❌ SAHTE:    https://www.bank.com@fake.site/login
```

**Kontrol Listesi:**
- [ ] URL'yi dikkatle okuyun
- [ ] SSL sertifikası var mı? (Kilit simgesi)
- [ ] Domain yazımı doğru mu?
- [ ] Alt domain'e dikkat edin (bank.com.sahte.site)

---

## Bölüm 2: Savunma Mekanizmaları

### 2.1 Kişisel Seviye

1. **Şüpheci Olun**
   - Tanımadığınız göndericilerden gelen e-postalara şüpheyle yaklaşın
   - Beklenmeyen bağlantılar için göndericiyi doğrulayın

2. **Çok Faktörlü Doğrulama (MFA)**
   - Her hesapta aktif edin
   - SMS yerine uygulama tabanlı (Google Authenticator, Authy) tercih edin

3. **Şifre Yönetimi**
   - Her hesap için benzersiz şifre
   - Şifre yöneticisi kullanın (Bitwarden, KeePass)
   - Hiçbir zaman e-posta/telefonda şifre paylaşmayın

### 2.2 Kurumsal Seviye

```
Farkındalık Eğitimi
    ↓
Simülasyon Testi (Phishing Drill)
    ↓
Sonuç Analizi ve Raporlama
    ↓
Tekrar Eğitim (Zayıf alanlar için)
    ↓
Sürekli İyileştirme
```

---

## Bölüm 3: Olay Müdahale

### 3.1 Şüpheli E-posta Aldığınızda

1. **Tıklamayın** - Bağlantıya veya eke tıklamayın
2. **Raporlayın** - Kurumunuzun IT/güvenlik birimine bildirin
3. **Silin** - E-postayı silin (önce raporlayın)
4. **Kontrol Edin** - Hesap aktivitelerinizi kontrol edin

### 3.2 Yanlışlıkla Tıkladıysanız

1. **Bağlantıyı Kesin** - WiFi/veriyi kapatın
2. **Şifre Değiştirin** - Hemen ilgili hesabın şifresini değiştirin
3. **MFA Kontrolü** - MFA ayarlarını kontrol edin, yetkisiz cihaz var mı?
4. **Antivirüs Taraması** - Cihazı tarayın
5. **Bildirin** - Güvenlik birimine olayı anlatın

---

## Bölüm 4: Simülasyon Senaryoları

### Senaryo A: CEO Dolandırıcılığı (BEC)

```
Gönderen: ceo@sirket.com → ceo@sirket.co (farkı fark ettiniz mi?)
Konu: ACİL - Para Transferi
İçerik: "Müşteriye acil ödeme yapmalıyız, detaylar ekte"

🚩 Kırmızı Bayraklar:
- CEO normalde e-posta atmaz
- Domain .co yerine .com olmalı
- "ACİL" kelimesi baskı oluşturuyor
- Ek dosya şüpheli
```

### Senaryo B: Kargo Teslimatı

```
Gönderen: kargo@teslimat-servisi.net
Konu: Kargonuz teslim edilemedi
İçerik: "Adres güncellemesi için tıklayın"

🚩 Kırmızı Bayraklar:
- Resmi kargo şirketi domain'i farklı
- Takip numarası yok veya sahte
- Genel hitap ("Sayın Müşteri" yerine isim yok)
```

---

## 📊 Eğitim Değerlendirme

### Test Soruları

**Soru 1:** Aşağıdaki URL'lerden hangisi güvenlidir?
```
a) http://bank.com/login
b) https://www.bank.com/login
c) https://bank.com-security-alert.net
d) https://www.bank.com@phishing.site
```

**Soru 2:** Şüpheli bir e-posta aldığınızda ilk yapmanız gereken nedir?
```
a) Bağlantıya tıklayıp kontrol etmek
b) Göndericiyi arayıp doğrulamak
c) IT birimine raporlamak
d) Cevap yazıp detay istemek
```

**Soru 3:** MFA ne anlama gelir ve neden önemlidir?
```
[Cevap alanı]
```

---

## 🔗 Faydalı Kaynaklar

- [Have I Been Pwned](https://haveibeenpwned.com/) - E-posta sızıntı kontrolü
- [Phishing Quiz by Google](https://phishingquiz.withgoogle.com/) - Interaktif test
- [CISA Phishing Guidance](https://www.cisa.gov/phishing) - Resmi rehber

---

**Eğitim Tamamlandı! 🎉**

Unutmayın: Teknoloji %10, İnsan Faktörü %90
En güvenli sistem bile dikkatsiz bir kullanıcı ile tehlikeye girer.
