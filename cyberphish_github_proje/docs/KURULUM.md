# Kurulum Rehberi

## Gereksinimler

- Kali Linux (önerilen) veya Debian tabanlı dağıtım
- Python 3.13+
- Root erişimi (ağ işlemleri için)

## Kurulum Adımları

```bash
# 1. Sistemi güncelle
sudo apt update && sudo apt upgrade -y

# 2. Gerekli araçları kur
sudo apt install -y python3 python3-pip wget nmap

# 3. Metasploit (opsiyonel)
sudo apt install -y metasploit-framework

# 4. Projeyi klonla
git clone https://github.com/kullaniciadi/cyberphish-awareness.git
cd cyberphish-awareness
```

## Çalıştırma

```bash
# Eğitim modüllerini çalıştır
sudo python3 egitim_modulu.py
```

> ⚠️ Tüm işlemler sanal makine veya izole ortamda yapılmalıdır.
