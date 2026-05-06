# CyberPhish Awareness Lab 🔒

> **Sosyal Mühendislik Farkındalık ve Eğitim Platformu**
> 
> Bu proje, siber güvenlik eğitimlerinde sosyal mühendislik saldırılarının **nasıl çalıştığını anlatmak** ve kurumların/kişilerin farkındalığını artırmak amacıyla hazırlanmıştır.
> 
> ⚠️ **Tüm içerik eğitim amaçlıdır. Gerçek sistemlere izinsiz uygulanması yasa dışıdır.**

---

## 📚 Proje Hakkında

| Özellik | Açıklama |
|---------|----------|
| **Amaç** | Sosyal mühendislik tekniklerini eğitim ortamında simüle etmek |
| **Hedef Kitle** | Siber güvenlik öğrencileri, pentest uzmanları, kurum çalışanları |
| **Platform** | Kali Linux üzerinde Python 3 ile geliştirilmiştir |
| **Lisans** | MIT - Eğitim kullanımına açık, kötüye kullanım yasaktır |

---

## 🎯 Eğitim Modülleri

### 1. Oltalama (Phishing) Farkındalığı
Sosyal mühendislik saldırılarının en yaygın türü olan oltalama e-postalarının nasıl oluşturulduğunu ve kurbanların nasıl tuzağa düşürüldüğünü anlatan teorik modül.

**Öğrenme Hedefleri:**
- Sahte giriş sayfalarının nasıl ayırt edileceği
- URL analizi ve SSL sertifikası kontrolü
- Şüpheli bağlantılara tıklama davranışının riskleri

### 2. Web Sitesi Klonlama Teknikleri
Saldırganların gerçek siteleri nasıl kopyaladığını ve bu kopyalar üzerinden veri topladığını gösteren simülasyon.

**Öğrenme Hedefleri:**
- Site klonlama yöntemlerinin tanınması
- DNS ve domain spoofing farkındalığı
- Güvenli bağlantı alışkanlıkları

### 3. E-posta Kampanyası Analizi
Sosyal mühendislik e-postalarının yapısını, psikolojik tetikleyicilerini ve savunma stratejilerini içeren eğitim modülü.

**Öğrenme Hedefleri:**
- Aciliyet, otorite ve korku temalı manipülasyon teknikleri
- E-posta başlık ve içerik analizi
- Raporlama ve olay müdahale prosedürleri

### 4. Ağ Keşfi ve Tespit
Yerel ağdaki cihazların nasıl keşfedildiğini ve bu bilgilerin saldırı planlamasında nasıl kullanıldığını anlatan modül.

**Öğrenme Hedefleri:**
- ARP taraması ve pasif keşif yöntemleri
- Ağ segmentasyonunun önemi
- Anomali tespiti ve log analizi

---

## 📂 Proje Yapısı

```
cyberphish-awareness/
├── README.md                 # Ana proje dosyası
├── LICENSE                   # MIT Lisans
├── docs/
│   ├── TEKNOLOJILER.md       # Kullanılan teknolojiler
│   └── KURULUM.md            # Kurulum rehberi
├── egitim/
│   ├── FARKINDALIK_REHBERI.md    # Eğitim içeriği
│   ├── SENARYOLAR.md             # Simülasyon senaryoları
│   └── TEST_SORULARI.md          # Değerlendirme soruları
└── sunum/
    └── proje_sunumu.pdf      # 9 slaytlık sunum
```

---

## 🛠️ Kullanılan Teknolojiler

```
Python 3.x
- http.server (yerleşik modül)
- socket / threading
- json / html raporlama

Kali Linux Araçları
- wget (site analizi)
- nmap / arp-scan (ağ keşfi)
- metasploit-framework (payload eğitimi)
```

---

## 📊 Raporlama ve Dokümantasyon

Proje kapsamında üretilen eğitim materyalleri:

| Format | İçerik |
|--------|--------|
| **PDF Sunum** | 9 slaytlık proje tanıtımı |
| **HTML Rapor** | Etkileşimli eğitim notları |
| **JSON Log** | Simülasyon senaryoları |

---

## 🛡️ Etik Kurallar ve Uyarılar

### Beyaz Şapka Prensipleri

1. **Yetki** - Sadece izin verilen sistemlerde ve sanal ortamlarda kullanılır
2. **Eğitim** - Tüm simülasyonlar izole laboratuvar ortamında yapılır
3. **Şeffaflık** - Test edilen kişiler/kurumlar sonradan bilgilendirilir
4. **Loglama** - Tüm aktiviteler kaydedilir ve denetlenebilir

### Yasal Uyarı

> Bu depo, siber güvenlik eğitimi amacıyla hazırlanmıştır. İçerdiği teknik bilgilerin izinsiz kullanımından doğacak yasal sorumluluk tamamen kullanıcıya aittir. Türkiye'de 5651 sayılı İnternet Ortamında Yapılan Yayınların Düzenlenmesi ve Bu Yayınlar Yoluyla İşlenen Suçlarla Mücadele Edilmesi Hakkında Kanun ve ilgili mevzuat kapsamında, izinsiz erişim ve veri toplama suçtur.

---

## 🎓 Eğitim Senaryoları

### Senaryo 1: Kurumsal Farkındalık Testi
```
Hedef: Şirket çalışanlarının oltalama e-postalarına karşı duyarlılığı
Yöntem: Eğitim sonrası simülasyon e-postası gönderimi
Metrik: Tıklama oranı, raporlama oranı, eğitim öncesi/sonrası karşılaştırma
```

### Senaryo 2: Güvenli Giriş Alışkanlıkları
```
Hedef: Çalışanların sahte login sayfalarını tanıma becerisi
Yöntem: Simüle edilmiş oltalama sayfası + anlık geri bildirim
Metrik: Doğru tespit oranı, ortalama tepki süresi
```

---

## 📖 Kaynaklar ve Referanslar

- [OWASP Social Engineering Cheat Sheet](https://cheatsheetseries.owasp.org/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [Social-Engineer Framework](https://www.social-engineer.org/framework/)
- Kevin Mitnick - "The Art of Deception"
- Christopher Hadnagy - "Social Engineering: The Science of Human Hacking"

---

## 🤝 Katkıda Bulunma

Eğitim içeriğini geliştirmek için:

1. Yeni senaryo önerileri
2. Farkındalık testi metrikleri
3. Çeviri ve yerelleştirme
4. Eğitim videosu/scriptleri

Katkılar için lütfen **Pull Request** açın veya **Issue** oluşturun.

---

## 📧 İletişim

Proje hakkında sorularınız için:
- E-posta: [your-email@example.com]
- LinkedIn: [your-profile]
- Eğitim talepleri için kurumunuzun güvenlik birimi ile iletişime geçin

---

## 📜 Lisans

MIT License - Copyright (c) 2026

Bu proje eğitim amaçlıdır. Ticari kullanım veya kötüye kullım yasaktır.

---

**🔒 Unutmayın: Bilgi güçtür, ama sorumlu kullanım en büyük güçtür.**
