# 📦 Docker Eğitim Serisi — Sıfırdan Uzmana

## 🎬 Giriş

### 1. Docker Nedir?
- Konteyner Nedir? Sanallaştırma vs Konteyner
- Docker Ne İşe Yarar?
- Docker’ın Yazılım Geliştirmedeki Yeri
- Docker'ı Nerelerde Kullanırız?

---

## ⚙️ Kurulum

### 2. Docker Kurulumu
- Docker Desktop vs CLI: Hangisi?
- Windows, macOS, Linux için Kurulum
- İlk Komut: `docker version` ve `docker info`
- Docker Hub Nedir?

---

## 🔧 Temel Komutlar

### 3. İlk Docker Komutları
- `docker run`, `docker ps`, `docker stop`, `docker rm`
- `docker pull` ve `docker images`
- `docker exec` ve `docker logs`
- Basit bir container çalıştırmak (`nginx` örneği)

---

## 🧱 Dockerfile ve Image Yönetimi

### 4. Dockerfile ve Image Oluşturma
- Dockerfile Yapısı
- `FROM`, `RUN`, `COPY`, `CMD` gibi direktifler
- Kendi Image’ını oluşturmak
- Image Tagleme ve Versiyonlama
- Image Push Etmek (Docker Hub veya Private Registry)

---

## 📂 Dosya ve Veri Yönetimi

### 5. Volume ve Bind Mounts
- Verilerin Container içinde kalıcı olması
- `-v` kullanımı: Named vs Anonymous Volumes
- Bind Mount ile dış klasörü bağlamak
- Volume Yedekleme ve Paylaşma

---

## 🌐 Ağ Yönetimi

### 6. Network Kavramları
- Container’lar Arası İletişim
- `bridge`, `host`, `none` network'leri
- `docker network` komutları
- Çoklu container ile örnek senaryo: Web + DB

---

## ⚙️ Compose ile Çoklu Servis Yönetimi

### 7. Docker Compose
- Compose Nedir? Neden Kullanılır?
- `docker-compose.yml` Yapısı
- Çoklu Servisleri Tanımlamak
- `depends_on`, `env_file`, `volumes`, `build` kullanımı
- Gerçek Hayattan Örnek: Nginx + PHP + MySQL Projesi

---

## 🔐 Güvenlik

### 8. Docker Güvenliği
- Root olmayan kullanıcı ile çalışmak
- Secret Management
- Güvenli Image seçimi ve tarama (Docker Scout / Trivy)
- Best Practices

---

## 📊 İzleme ve Log Yönetimi

### 9. Monitoring & Logging
- Loglara Erişim Yolları
- Basit Monitoring (örnek: cAdvisor, Portainer)
- Container Sağlık Kontrolleri (Healthchecks)
- Metrics toplamak (Prometheus ile basit örnek)

---

## 🚀 Production Hazırlığı

### 10. Docker’ı Production’a Hazırlamak
- Resource Limitleri (`cpu`, `memory`)
- Multi-stage Build
- Alpine tabanlı minimal image'lar
- CI/CD ile Deploy Senaryosu (GitHub Actions + Docker)

---

## ❓ Sık Sorulan Sorular & İpuçları

### 11. Sık Sorulan Sorular ve İpuçları
- “Container kapanınca ne olur?”
- “Bir container içinde birden fazla servis çalıştırabilir miyim?”
- Debug ve Hata Ayıklama Yöntemleri
- Yaygın Hatalar ve Çözüm Yolları

---

## 🎁 Bonus Konular

### 12. Bonus Bölümler
- Docker Swarm'a Giriş
- Kubernetes vs Docker
- Docker ile Laravel / React / Node.js Uygulaması Yayınlama
- Docker Registry Kurmak (Harici depolama)

---

Hazırlayan: **Mücahit [YouTube Kanal Adı]**  
İletişim: [LinkedIn, GitHub, vs.]

---
