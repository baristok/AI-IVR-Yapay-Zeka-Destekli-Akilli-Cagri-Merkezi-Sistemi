# 🎓 IVR - Interactive Voice Response Management System
## Bitirme Projesi | Bilişim Sistemleri Mühendisliği

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-12.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/PHP-8.2+-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Tailwind-4.0-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind">
  <img src="https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge" alt="Status">
</p>

<p align="center">
  <strong>Modern, Ölçeklenebilir ve Çok Dilli IVR Yönetim Platformu</strong><br>
  Kurumsal müşteri hizmetleri için geliştirilmekte olan bulut tabanlı IVR çözümü
</p>

---

## 📋 Proje Hakkında

### 🎯 Proje Özeti

Bu proje, **Bilişim Sistemleri Mühendisliği Bitirme Projesi** olarak geliştirilmekte olup, kurumsal firmaların müşteri hizmetleri süreçlerini otomatikleştirmek için tasarlanan bir **Interactive Voice Response (IVR)** yönetim sistemidir. 

Modern web teknolojileri kullanılarak geliştirilen sistem, esnek modüler mimarisi, çok dilli desteği ve güçlü rol-yetki yönetimi ile ölçeklenebilir bir çözüm sunmayı hedeflemektedir.

> **⚠️ Not:** Proje aktif geliştirme aşamasındadır. Bazı özellikler henüz tamamlanmamış veya planlama aşamasındadır.

### 🚀 Girişim Potansiyeli

Sistem, **SaaS (Software as a Service)** modeline uygun olarak geliştirilmekte olup, aşağıdaki iş modellerini desteklemeyi hedeflemektedir:

- 📞 **Multi-tenant Mimari** - Çoklu müşteri desteği (Planlanan)
- 💰 **Abonelik Tabanlı Gelir Modeli** - Aylık/yıllık paketler (Planlanan)
- 📊 **Analitik ve Raporlama** - Veri odaklı karar destek sistemi (Geliştiriliyor)
- 🔧 **Özelleştirilebilir Çözümler** - Sektörel ihtiyaçlara özel modüller (Planlanan)
- ☁️ **Bulut Tabanlı Altyapı** - Düşük maliyet, yüksek erişilebilirlik (Hazırlanıyor)

### 👨‍💻 Geliştirici Bilgileri

**Ad Soyad:** Barış Tok  
**Bölüm:** Bilişim Sistemleri Mühendisliği  
**Sınıf:** 4. Sınıf  
**Üniversite:** Burdur Mehmet Akif Ersoy Üniversitesi  
**Danışman:** Dr. Öğr. Üyesi Ayhan ARISOY  
**Proje Dönemi:** 2025-2026 Güz Dönemi  
**Mesleki Durum:** Full Stack Developer (Öğrenci)

**İletişim:**
- 📧 Email: info@baristok.com.tr
- 💼 LinkedIn: [linkedin.com/in/baristok](https://www.linkedin.com/in/baristok)
- 🐙 GitHub: [github.com/baristok](https://www.github.com/baristok)
- 🌐 Website: [baristok.com.tr](https://www.baristok.com.tr)

---

## 🎯 Problem Tanımı ve Çözüm

### 📌 Mevcut Problemler

1. **Yüksek Çağrı Merkezi Maliyetleri**
   - İnsan kaynağı maliyetleri
   - 7/24 hizmet verme zorunluluğu
   - Eğitim ve operasyon giderleri

2. **Müşteri Deneyimi Sorunları**
   - Uzun bekleme süreleri
   - Operatör bağlantı problemleri
   - Tutarsız bilgi aktarımı

3. **Ölçeklenebilirlik Problemleri**
   - Yoğun saatlerde kapasite yetersizliği
   - Mevsimsel talep dalgalanmaları
   - Coğrafi kısıtlamalar

4. **Veri ve Analitik Eksikliği**
   - Müşteri davranış analizi zorluğu
   - Performans ölçümlemede yetersizlik
   - Raporlama ve karar destek eksikliği

### ✅ Önerilen Çözümler

1. **Akıllı IVR Sistemi**
   - Otomatik yanıt ve yönlendirme sistemi
   - Dinamik menü yapılandırması
   - Yapay zeka destekli müşteri anlayışı (İlerleyen aşamalarda)

2. **Modüler ve Ölçeklenebilir Mimari**
   - Modüler mimari tabanlı yaklaşım
   - Kolay entegrasyon desteği (REST API, Webhooks)
   - Bulut altyapı uyumluluğu

3. **Gelişmiş Yönetim Paneli**
   - Kullanıcı dostu arayüz
   - Gerçek zamanlı izleme ve raporlama (Geliştiriliyor)
   - Rol tabanlı erişim kontrolü

4. **Kurumsal Güvenlik ve Uyumluluk** (İlerleyen Aşamalarda)
   - KVKK/GDPR uyumlu veri yönetimi
   - Şifreli iletişim (TLS/SSL)
   - Audit log ve izlenebilirlik

---

## 🏗️ Sistem Mimarisi

### Mevcut Teknoloji Stack'i


#### **DevOps & Infrastructure** ✅ Hazır
```
┌─────────────────────────────────────┐
│     Docker & Docker Compose         │
├─────────────────────────────────────┤
│  ✅ Laravel Sail - Dev Environment  │
│  ✅ Vite - Asset Building           │
└─────────────────────────────────────┘
```

### Sistem Bileşenleri (Planlanan)

```
┌──────────────────────────────────────────────────────────┐
│                     CLIENT LAYER                         │
│             (Web Dashboard, API Clients)                 │
└────────────────────────┬─────────────────────────────────┘
                         │
                         ▼
┌──────────────────────────────────────────────────────────┐
│                  APPLICATION LAYER                       │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐       │
│  │   Auth      │  │   Users     │  │   Admin     │       │
│  │  Module ✅  │  │  Module ✅  │  │  Module 🔄  │       │
│  └─────────────┘  └─────────────┘  └─────────────┘       │
│  ┌─────────────┐  ┌─────────────┐                        │
│  │   IVR       │  │   Reports   │                        │
│  │  Module 📅  │  │  Module 📅  │                        │
│  └─────────────┘  └─────────────┘                        │
└────────────────────────┬─────────────────────────────────┘
                         │
                         ▼
┌──────────────────────────────────────────────────────────┐
│                     DATA LAYER                           │
│  • MySQL (Relational)  • File Storage                    │
└──────────────────────────────────────────────────────────┘
```

**Durum Göstergeleri:**
- ✅ Tamamlandı
- 🔄 Geliştiriliyor
- 📅 Planlanıyor

---

## ✨ Özellikler ve Durum

### 🔐 Kullanıcı Yönetimi ve Güvenlik
- ✅ Laravel authentication sistemi
- ✅ Rol tabanlı erişim kontrolü (RBAC)
- ✅ Dinamik izin yönetimi (Spatie Permission)
- ✅ Session yönetimi
- 🔄 Çok faktörlü kimlik doğrulama (2FA) - Geliştiriliyor
- 📅 API token yönetimi - Planlanıyor

### 📞 IVR Yönetimi (Core Modülü)
- 🔄 IVR akış tasarımcısı - Geliştiriliyor
- 📅 Dinamik menü yapılandırması - Planlanıyor
- 📅 Çağrı yönlendirme sistemi - Planlanıyor
- 📅 DTMF (tuş tonu) algılama - Planlanıyor
- 📅 TTS (Text-to-Speech) entegrasyonu - Planlanıyor

### 📊 Analitik ve Raporlama
- 🔄 Temel dashboard - Geliştiriliyor
- 📅 Çağrı istatistikleri - Planlanıyor
- 📅 Gerçek zamanlı metrikler - Planlanıyor
- 📅 Excel/PDF export - Planlanıyor
- 📅 Grafik görselleştirme - Planlanıyor

### 🌍 Çok Dil Desteği
- ✅ Türkçe arayüz
- ✅ İngilizce arayüz
- ✅ Dinamik dil değiştirme
- ✅ Locale tabanlı içerik yönetimi
- ✅ Helper fonksiyonları

### 🔧 Modüler Mimari
- ✅ nwidart/laravel-modules entegrasyonu
- ✅ Users modülü (temel CRUD)
- ✅ Bağımsız modül geliştirme altyapısı
- 📅 IVR core modülü - Geliştirme aşamasında
- 📅 API modülü - Planlanıyor

---


### Docker ile Kurulum

```bash
# Docker container'ları başlat
./vendor/bin/sail up -d

# Veritabanı kurulumu
./vendor/bin/sail artisan migrate --seed

# Asset build
./vendor/bin/sail npm install
./vendor/bin/sail npm run build

# Uygulama: http://localhost
```

---


## 📚 Akademik Katkılar ve Hedefler

### Araştırma Konuları

1. **Modüler Web Uygulama Mimarileri**
   - Laravel Modules paketi ile modüler mimari
   - Bağımsız modül geliştirme metodolojisi
   - Modüler sistemlerde bağımlılık yönetimi

2. **Çok Dilli Web Uygulamaları**
   - Lokalizasyon best practices
   - Dinamik dil değiştirme sistemleri
   - Route ve içerik yönetiminde locale kullanımı

3. **Rol Tabanlı Erişim Kontrolü (RBAC)**
   - Laravel'de RBAC implementasyonu
   - Dinamik izin yönetimi
   - Performans optimizasyonu

### Kullanılan Metodoloji

- 📖 **Literatür Araştırması:** IVR sistemleri, SaaS mimarileri, Laravel best practices
- 🔬 **Uygulama Geliştirme:** Modüler mimari ile prototip geliştirme
- 📝 **Dokümantasyon:** UML diyagramları, API docs, kullanıcı kılavuzları

### Beklenen Çıktılar

- 📄 Bitirme tezi/raporu
- 💻 Çalışan MVP (Minimum Viable Product)
- 📚 Teknik dokümantasyon
- 🎤 Bitirme sunumu
- 📊 Case study ve performans analizi



## 📖 Referanslar ve Kaynaklar

### Teknik Dokümantasyon
- [Laravel 12.x Official Docs](https://laravel.com/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Docker Documentation](https://docs.docker.com)
- [MySQL 8.0 Reference Manual](https://dev.mysql.com/doc)
- [Spatie Laravel Permission](https://spatie.be/docs/laravel-permission)
- [nwidart Laravel Modules](https://nwidart.com/laravel-modules)

---

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

**Akademik Kullanım:** Bu proje bitirme projesi olarak geliştirilmiş olup, akademik amaçlı kullanım için açık kaynaklıdır.

**Ticari Kullanım:** Proje tamamlandıktan sonra ticari kullanım için değerlendirilecektir.

---

## 📞 İletişim ve Destek

### Proje Sahibi
**Barış Tok**
- 📧 Email: info@baristok.com.tr
- 💼 LinkedIn: [linkedin.com/in/baristok](https://www.linkedin.com/in/baristok)
- 🐙 GitHub: [github.com/baristok](https://www.github.com/baristok)
- 🌐 Website: [baristok.com.tr](https://www.baristok.com.tr)

---

---

## 🎓 Proje Durumu

> **📍 Mevcut Durum:** Aktif Geliştirme Aşamasında  
> **📅 Proje Dönemi:** 2025-2026 Güz Dönemi  
> **🎯 Bitirme Projesi Teslimi:** Ocak 2026  
> **🚀 SaaS Lansmanı Hedefi: ** Mayıs 2026  
> **✅ İlerleme:** ~%

---

<p align="center">
  <strong>Bu proje, Bilişim Sistemleri Mühendisliği Bitirme Projesi olarak<br>
  Burdur Mehmet Akif Ersoy Üniversitesi tarafından değerlendirilmek üzere geliştirilmektedir.</strong>
</p>

<p align="center">
  <sub>© 2025-2026 Barış Tok. Tüm hakları saklıdır.</sub>
</p>

<p align="center">
  ⭐ Projeyi beğendiyseniz GitHub'da yıldız vermeyi unutmayın!
</p>

---

<p align="center">
  <em>"Sürekli gelişim ve öğrenme, başarının anahtarıdır."</em>
</p>
