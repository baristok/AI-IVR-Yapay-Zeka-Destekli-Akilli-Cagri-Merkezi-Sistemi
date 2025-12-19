# 🎓 IVR - Interactive Voice Response Management System
## Bitirme Projesi | Bilişim Sistemleri Mühendisliği

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-12.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
  <img src="https://img.shields.io/badge/PHP-8.4-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Tailwind-4.0-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind">
  <img src="https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Status-Active%20Development-yellow?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/AI-Gemini%202.5%20Flash-blue?style=for-the-badge" alt="AI">
  <img src="https://img.shields.io/badge/Real--time-Pusher-FF6B6B?style=for-the-badge&logo=pusher&logoColor=white" alt="Pusher">
</p>

<p align="center">
  <strong>Yapay Zeka Destekli, Modern ve Ölçeklenebilir IVR Yönetim Platformu</strong><br>
  Gerçek zamanlı AI konuşma sistemi ile kurumsal müşteri hizmetleri çözümü
</p>

---

## 📋 Proje Hakkında

### 🎯 Proje Özeti

Bu proje, **Bilişim Sistemleri Mühendisliği Bitirme Projesi** olarak geliştirilmekte olup, kurumsal firmaların müşteri hizmetleri süreçlerini otomatikleştirmek için tasarlanan bir **Yapay Zeka Destekli Interactive Voice Response (IVR)** yönetim sistemidir. 

Sistem, **Google Gemini AI**, **Google Cloud Speech-to-Text (STT)** ve **Google Cloud Text-to-Speech (TTS)** teknolojileri ile gerçek zamanlı, doğal konuşma deneyimi sunmaktadır.

Modern web teknolojileri kullanılarak geliştirilen sistem, esnek modüler mimarisi, çok dilli desteği, güçlü rol-yetki yönetimi ve yapay zeka entegrasyonu ile ölçeklenebilir bir çözüm sunmaktadır.

> **✅ Güncel Durum:** Sistem aktif geliştirme aşamasında olup, **gerçek zamanlı streaming AI konuşma sistemi** tamamlanmıştır. TTS/STT entegrasyonları, **Pusher ile real-time broadcasting**, **Redis queue sistemi**, **Supervisor ile otomatik queue worker yönetimi** ve **performans optimizasyonları** (TTS cache, paralel işleme) çalışır durumdadır.

### 🚀 Girişim Potansiyeli

Sistem, **SaaS (Software as a Service)** modeline uygun olarak geliştirilmekte olup, aşağıdaki iş modellerini desteklemeyi hedeflemektedir:

- 📞 **Multi-tenant Mimari** - Çoklu müşteri desteği (Planlanan)
- 💰 **Abonelik Tabanlı Gelir Modeli** - Aylık/yıllık paketler (Planlanan)
- 📊 **Analitik ve Raporlama** - Veri odaklı karar destek sistemi (Geliştiriliyor)
- 🤖 **AI Destekli Müşteri Hizmetleri** - 7/24 otomatik destek (✅ Tamamlandı)
- 🔧 **Özelleştirilebilir Çözümler** - Sektörel ihtiyaçlara özel modüller (Planlanan)
- ☁️ **Bulut Tabanlı Altyapı** - Düşük maliyet, yüksek erişilebilirlik (✅ Hazır)

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

### ✅ Önerilen ve Uygulanan Çözümler

1. **Yapay Zeka Destekli IVR Sistemi** ✅ **TAMAMLANDI**
   - ✅ Google Gemini 2.5 Flash ile doğal dil işleme
   - ✅ **Gerçek zamanlı streaming konuşma döngüsü** (Server-Sent Events)
   - ✅ **Real-time broadcasting** (Pusher ile anlık güncellemeler)
   - ✅ Senaryo bazlı konuşma yönetimi
   - ✅ Bağlam takibi ve konuşma geçmişi yönetimi
   - ✅ **Paralel TTS işleme** (performans optimizasyonu)
   - ✅ **TTS cache sistemi** (~600x hız artışı)
   - 🔄 Dinamik menü yapılandırması - Geliştiriliyor

2. **Ses Teknolojileri Entegrasyonu** ✅ **TAMAMLANDI**
   - ✅ Google Cloud Text-to-Speech (TTS) - Metin → Ses
   - ✅ Google Cloud Speech-to-Text (STT) V2 API - Ses → Metin
   - ✅ SSML (Speech Synthesis Markup Language) ön işleme
   - ✅ Otomatik format tespiti (AutoDetectDecodingConfig)
   - ✅ Çoklu dil desteği (Türkçe, İngilizce, vb.)
   - ✅ Yüksek kaliteli ses sentezi (Chirp3-HD modeli)

3. **Modüler ve Ölçeklenebilir Mimari** ✅ **TAMAMLANDI**
   - ✅ Modüler mimari tabanlı yaklaşım (nwidart/laravel-modules)
   - ✅ TestSimulasyonu modülü (TTS/STT test ve gerçek zamanlı streaming konuşma)
   - ✅ Users modülü (Kullanıcı yönetimi)
   - ✅ **Redis queue sistemi** (yüksek performanslı job işleme)
   - ✅ **Supervisor ile otomatik queue worker yönetimi** (7/24 stabil çalışma)
   - ✅ Kolay entegrasyon desteği (REST API, Webhooks)
   - ✅ Bulut altyapı uyumluluğu

4. **Gelişmiş Yönetim Paneli** ✅ **KISMEN TAMAMLANDI**
   - ✅ Kullanıcı dostu arayüz
   - ✅ Gerçek zamanlı konuşma simülasyonu arayüzü
   - ✅ TTS/STT test ortamı
   - 🔄 Gerçek zamanlı izleme ve raporlama - Geliştiriliyor
   - ✅ Rol tabanlı erişim kontrolü

5. **Kurumsal Güvenlik ve Uyumluluk** (İlerleyen Aşamalarda)
   - 📅 KVKK/GDPR uyumlu veri yönetimi - Planlanıyor
   - ✅ Şifreli iletişim (TLS/SSL)
   - 📅 Audit log ve izlenebilirlik - Planlanıyor

---

## 🏗️ Sistem Mimarisi

### Mevcut Teknoloji Stack'i

#### **Backend & Framework** ✅ Hazır
```
┌─────────────────────────────────────┐
│     Laravel 12.x Framework         │
├─────────────────────────────────────┤
│  ✅ PHP 8.4                         │
│  ✅ MySQL 8.0                       │
│  ✅ Redis (Queue & Cache)           │
│  ✅ nwidart/laravel-modules         │
│  ✅ Spatie Laravel Permission       │
│  ✅ Supervisor (Queue Worker)        │
└─────────────────────────────────────┘
```

#### **AI & Speech Services** ✅ Tamamlandı
```
┌─────────────────────────────────────┐
│     Google Cloud Services           │
├─────────────────────────────────────┤
│  ✅ Google Gemini 2.5 Flash         │
│  ✅ Gemini Streaming (SSE)           │
│  ✅ Google Cloud TTS (Text-to-Speech)│
│  ✅ Google Cloud STT V2 (Speech-to-Text)│
│  ✅ SSML Preprocessor               │
│  ✅ TTS Cache System                │
└─────────────────────────────────────┘
```

#### **Real-time & Infrastructure** ✅ Tamamlandı
```
┌─────────────────────────────────────┐
│     Real-time Services              │
├─────────────────────────────────────┤
│  ✅ Pusher (Broadcasting)           │
│  ✅ Laravel Echo (Frontend)          │
│  ✅ Redis Queue System               │
│  ✅ Supervisor (Auto Queue Worker)   │
│  ✅ Event Broadcasting               │
└─────────────────────────────────────┘
```

#### **DevOps & Infrastructure** ✅ Hazır
```
┌─────────────────────────────────────┐
│     Docker & Docker Compose         │
├─────────────────────────────────────┤
│  ✅ Laravel Sail - Dev Environment  │
│  ✅ Vite - Asset Building           │
│  ✅ Tailwind CSS 4.0                │
└─────────────────────────────────────┘
```

### Sistem Bileşenleri (Güncel Durum)

```
┌──────────────────────────────────────────────────────────┐
│                     CLIENT LAYER                         │
│             (Web Dashboard, Test Interface)              │
│  ✅ TestSimulasyonu Modülü - TTS/STT Test & AI Konuşma  │
└────────────────────────┬─────────────────────────────────┘
                         │
                         ▼
┌──────────────────────────────────────────────────────────┐
│                  APPLICATION LAYER                       │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐       │
│  │   Auth      │  │   Users     │  │ TestSim     │       │
│  │  Module ✅  │  │  Module ✅  │  │  Module ✅  │       │
│  └─────────────┘  └─────────────┘  └─────────────┘       │
│  ┌──────────────────────────────────────────────┐       │
│  │         AI & Speech Services Layer           │       │
│  │  ✅ ConversationEngine (Konuşma Motoru)       │       │
│  │  ✅ GoogleGeminiService (AI Yanıt Üretimi)   │       │
│  │  ✅ GoogleTtsService (Ses Sentezi)           │       │
│  │  ✅ GoogleSttService (Ses Tanıma)           │       │
│  │  ✅ SsmlPreprocessor (SSML İşleme)            │       │
│  └──────────────────────────────────────────────┘       │
│  ┌─────────────┐  ┌─────────────┐                        │
│  │   IVR       │  │   Reports   │                        │
│  │  Module 🔄  │  │  Module 📅  │                        │
│  └─────────────┘  └─────────────┘                        │
└────────────────────────┬─────────────────────────────────┘
                         │
                         ▼
┌──────────────────────────────────────────────────────────┐
│                     DATA LAYER                           │
│  • MySQL (Relational)  • File Storage                   │
│  • Cache (Session & Conversation History)                 │
└──────────────────────────────────────────────────────────┘
```

**Durum Göstergeleri:**
- ✅ Tamamlandı
- 🔄 Geliştiriliyor
- 📅 Planlanıyor

### Gerçek Zamanlı Streaming Konuşma Mimarisi

```
┌─────────────────────────────────────────────────────────────┐
│                    CLIENT LAYER (Browser)                    │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │ MediaRecorder│  │ Laravel Echo │  │ Audio Player │      │
│  │ (Ses Kaydı)  │  │ (Pusher)     │  │ (Chunk Play) │      │
│  └──────┬───────┘  └──────┬───────┘  └──────┬───────┘      │
└─────────┼─────────────────┼─────────────────┼──────────────┘
          │                 │                 │
          │ 1. Audio Upload │                 │
          ▼                 │                 │
┌─────────────────────────────────────────────────────────────┐
│              APPLICATION LAYER (Laravel)                      │
│  ┌──────────────────────────────────────────────────────┐   │
│  │  TestSimulasyonuController                            │   │
│  │  processConversationTurnStreaming()                    │   │
│  └──────────────┬───────────────────────────────────────┘   │
│                 │                                            │
│                 │ 2. Dispatch OrchestrateConversationJob     │
│                 ▼                                            │
│  ┌──────────────────────────────────────────────────────┐   │
│  │  Redis Queue (high priority)                           │   │
│  │  OrchestrateConversationJob                           │   │
│  └──────────────┬───────────────────────────────────────┘   │
│                 │                                            │
│                 ├─► 3. GoogleSttService                      │
│                 │   (Ses → Metin, V2 API)                   │
│                 │   Event: SttProcessingCompleted            │
│                 │                                            │
│                 ├─► 4. GoogleGeminiStreamingService         │
│                 │   (AI Streaming, SSE Parsing)             │
│                 │   Event: AiChunkReceived (her chunk)       │
│                 │                                            │
│                 └─► 5. ProcessTtsChunkJob (Paralel)         │
│                     (Metin → Ses, Cache Check)                │
│                     Event: TtsChunkReady (her chunk)         │
│                 │                                            │
│                 │ 6. Event: ConversationTurnCompleted        │
│                 ▼                                            │
└─────────────────────────────────────────────────────────────┘
          │
          │ Real-time Events (Pusher Broadcasting)
          ▼
┌─────────────────────────────────────────────────────────────┐
│              BROADCASTING LAYER (Pusher)                     │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │ Private     │  │ Event        │  │ Frontend     │      │
│  │ Channels    │  │ Broadcasting │  │ Updates      │      │
│  └─────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────────────────────────────────────────┘
          │
          │ WebSocket/HTTP Long Polling
          ▼
┌─────────────────────────────────────────────────────────────┐
│                    CLIENT LAYER (Browser)                    │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │ Event        │  │ Audio        │  │ UI Updates   │      │
│  │ Listeners    │  │ Chunk Fetch  │  │ (Real-time)  │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────────────────────────────────────────┘
```

---

## ✨ Özellikler ve Durum

### 🤖 Yapay Zeka ve Konuşma Özellikleri ✅ **TAMAMLANDI**

#### **Gerçek Zamanlı Streaming AI Konuşma Sistemi** ✅
- ✅ Google Gemini 2.5 Flash entegrasyonu
- ✅ **Gemini Streaming API** (Server-Sent Events parsing)
- ✅ **Real-time broadcasting** (Pusher ile anlık güncellemeler)
- ✅ Gerçek zamanlı konuşma döngüsü (STT → AI Streaming → TTS Paralel)
- ✅ Senaryo bazlı konuşma yönetimi
  - ✅ Müşteri Desteği (customer_support)
  - ✅ Ödeme İşlemleri (billing)
  - ✅ Randevu Talebi (appointment)
  - ✅ Teknik Destek (technical_support)
- ✅ Konuşma geçmişi ve bağlam takibi
- ✅ Session yönetimi (Redis Cache tabanlı)
- ✅ **Performans metrikleri** (STT: ~1.3s, AI: ~1.2s, TTS: 0ms paralel)
- ✅ **Paralel TTS işleme** (job-based, non-blocking)
- ✅ **TTS cache sistemi** (~600x hız artışı, tekrarlanan cümleler için)
- ✅ Kullanıcı dostu arayüz (TestSimulasyonu modülü)
- ✅ **Voice Activity Detection (VAD)** - Otomatik ses algılama

#### **Text-to-Speech (TTS)** ✅
- ✅ Google Cloud TTS entegrasyonu
- ✅ Türkçe ses sentezi (Chirp3-HD-Achernar modeli)
- ✅ SSML (Speech Synthesis Markup Language) desteği
- ✅ Otomatik SSML ön işleme (SsmlPreprocessor)
  - ✅ Telefon numarası formatlama
  - ✅ Email adresi formatlama
  - ✅ URL formatlama
  - ✅ Para birimi formatlama
  - ✅ Tarih/saat formatlama
  - ✅ Kısaltma telaffuzları (IVR, CRM, API, vb.)
- ✅ MP3 audio encoding
- ✅ Özelleştirilebilir konuşma hızı ve ton
- ✅ **TTS Cache Sistemi** (Redis tabanlı, tekrarlanan cümleler için ~600x hız)
- ✅ **Paralel TTS işleme** (Queue job'ları ile non-blocking)
- ✅ **Chunk-based audio delivery** (Pusher 10KB limit bypass)
- ✅ Test arayüzü (TestSimulasyonu modülü)

#### **Speech-to-Text (STT)** ✅
- ✅ Google Cloud Speech-to-Text V2 API entegrasyonu
- ✅ Otomatik format tespiti (AutoDetectDecodingConfig)
- ✅ Çoklu dil desteği (Türkçe, İngilizce, vb.)
- ✅ Güven skoru (confidence score)
- ✅ Alternatif transkripsiyon sonuçları
- ✅ Gelişmiş modeller (latest_long, latest_short)
- ✅ Otomatik noktalama işaretleri
- ✅ WebM Opus, MP3, WAV, FLAC format desteği
- ✅ Test arayüzü (TestSimulasyonu modülü)

### 🔐 Kullanıcı Yönetimi ve Güvenlik
- ✅ Laravel authentication sistemi
- ✅ Rol tabanlı erişim kontrolü (RBAC)
- ✅ Dinamik izin yönetimi (Spatie Permission)
- ✅ Session yönetimi
- ✅ CSRF koruması
- 🔄 Çok faktörlü kimlik doğrulama (2FA) - Geliştiriliyor
- 📅 API token yönetimi - Planlanıyor

### 📞 IVR Yönetimi (Core Modülü)
- ✅ TTS (Text-to-Speech) entegrasyonu - **TAMAMLANDI**
- ✅ STT (Speech-to-Text) entegrasyonu - **TAMAMLANDI**
- ✅ Gerçek zamanlı AI konuşma simülasyonu - **TAMAMLANDI**
- ✅ TestSimulasyonu modülü (TTS/STT test ve AI konuşma) - **TAMAMLANDI**
- 🔄 IVR akış tasarımcısı - Geliştiriliyor
- 📅 Dinamik menü yapılandırması - Planlanıyor
- 📅 Çağrı yönlendirme sistemi - Planlanıyor
- 📅 DTMF (tuş tonu) algılama - Planlanıyor

### 📊 Analitik ve Raporlama
- ✅ **Gerçek zamanlı konuşma metrikleri** (STT, AI, TTS süreleri)
- ✅ **Performans analiz raporları** (detaylı log analizi)
- ✅ Konuşma geçmişi görüntüleme
- ✅ Performans logları
- ✅ **TTS cache hit/miss istatistikleri**
- ✅ **Queue worker durum izleme**
- 🔄 Temel dashboard - Geliştiriliyor
- 📅 Çağrı istatistikleri - Planlanıyor
- 📅 Gerçek zamanlı metrikler dashboard - Planlanıyor
- 📅 Excel/PDF export - Planlanıyor
- 📅 Grafik görselleştirme - Planlanıyor

### 🌍 Çok Dil Desteği
- ✅ Türkçe arayüz
- ✅ İngilizce arayüz
- ✅ Dinamik dil değiştirme
- ✅ Locale tabanlı içerik yönetimi
- ✅ Helper fonksiyonları
- ✅ TTS/STT çoklu dil desteği

### 🔧 Modüler Mimari
- ✅ nwidart/laravel-modules entegrasyonu
- ✅ Users modülü (temel CRUD, rol/izin yönetimi)
- ✅ TestSimulasyonu modülü (TTS/STT test, **streaming AI konuşma simülasyonu**)
- ✅ Bağımsız modül geliştirme altyapısı
- ✅ **Queue Worker otomasyonu** (Supervisor ile 7/24 çalışma)
- ✅ **Redis entegrasyonu** (Queue ve Cache)
- ✅ **Event Broadcasting sistemi** (Pusher ile real-time)
- 🔄 IVR core modülü - Geliştirme aşamasında
- 📅 API modülü - Planlanıyor

---

## 🚀 Kurulum ve Kullanım

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

### Gerekli Environment Variables

```env
# Google Cloud Credentials
GOOGLE_APPLICATION_CREDENTIALS=storage/app/ivr-sistemi-ed76c921a9dd.json
GOOGLE_CLOUD_PROJECT_ID=ivr-sistemi

# Gemini AI
GEMINI_API_KEY=your-gemini-api-key-here

# Broadcasting (Pusher)
BROADCAST_CONNECTION=pusher
PUSHER_APP_ID=your-pusher-app-id
PUSHER_APP_KEY=your-pusher-app-key
PUSHER_APP_SECRET=your-pusher-app-secret
PUSHER_APP_CLUSTER=your-pusher-cluster

# Queue & Cache (Redis)
QUEUE_CONNECTION=redis
CACHE_STORE=redis
REDIS_HOST=redis
REDIS_PORT=6379
```

### Test Simülasyonu Kullanımı

1. **Test Sayfasına Erişim:**
   ```
   http://localhost:8000/tr/testsimulasyonus
   ```

2. **TTS Test:**
   - Metin girişi yapın
   - "Sentezle" butonuna tıklayın
   - Ses dosyasını dinleyin veya indirin

3. **STT Test:**
   - Mikrofon butonuna tıklayın
   - Konuşun
   - Tekrar tıklayın - transkripsiyon görünecek

4. **Gerçek Zamanlı Streaming AI Konuşma:**
   - Senaryo seçin (Müşteri Desteği, Ödeme, Randevu)
   - Yeşil telefon butonuna tıklayın
   - AI selamlama mesajını dinleyin
   - **VAD (Voice Activity Detection)** otomatik olarak aktif
   - Konuşmaya başlayın (otomatik algılama)
   - **Real-time AI chunk'ları** ekranda görünür
   - **Paralel TTS işleme** ile ses anında hazır
   - Konuşmaya devam edin (döngüsel)

---

## ⚡ Performans Metrikleri

### 🎯 Gerçek Zamanlı Konuşma Performansı

Sistem, **production-ready** performans göstermektedir:

| Metrik | Ortalama | Min | Max | Durum |
|--------|----------|-----|-----|-------|
| **STT Time** | **~1,350ms** | 1,036ms | 1,742ms | ✅ İyi |
| **AI Time** | **~1,178ms** | 889ms | 1,790ms | ✅ Çok İyi |
| **TTS Time** | **0ms** | 0ms | 0ms | ✅ Mükemmel (Paralel) |
| **Total Time** | **~2,631ms** | 2,012ms | 3,661ms | ✅ İyi |

### 🚀 TTS Cache Performansı

**Cache Hit (Tekrarlanan Cümleler):**
- ⚡ Ortalama: **1.43ms** (1-2ms arası)
- ⚡ Hız: **~600x daha hızlı** cache miss'e göre
- ⚡ Cache Hit Oranı: **%25** (tekrarlanan cümleler için)

**Cache Miss (Yeni Cümleler):**
- ⏱️ Ortalama: **856ms** (405-1863ms arası)
- ⏱️ Metin uzunluğuna göre değişken

### ✅ Sistem Durumu

- ✅ **Queue Worker:** Otomatik çalışıyor (Supervisor ile 7/24)
- ✅ **Job İşleme:** Hızlı ve stabil
- ✅ **Cache Sistemi:** Çok etkili (~600x hız artışı)
- ✅ **Streaming:** Real-time çalışıyor
- ✅ **Paralel İşleme:** TTS job'ları non-blocking

**Detaylı performans raporu için:** `PERFORMANS_ANALIZ_RAPORU.md`

---

## 📚 Akademik Katkılar ve Hedefler

### Araştırma Konuları

1. **Yapay Zeka Destekli Konuşma Sistemleri**
   - Google Gemini 2.5 Flash entegrasyonu
   - **Streaming AI** (Server-Sent Events parsing)
   - Doğal dil işleme (NLP) uygulamaları
   - Konuşma bağlamı yönetimi
   - Senaryo bazlı AI kişilik geliştirme
   - **Real-time broadcasting** mimarileri

2. **Ses Teknolojileri Entegrasyonu**
   - Google Cloud TTS/STT API kullanımı
   - SSML (Speech Synthesis Markup Language) işleme
   - Gerçek zamanlı ses işleme pipeline'ları
   - Çoklu format ve dil desteği

3. **Modüler Web Uygulama Mimarileri**
   - Laravel Modules paketi ile modüler mimari
   - Bağımsız modül geliştirme metodolojisi
   - Modüler sistemlerde bağımlılık yönetimi
   - Service layer pattern uygulaması

4. **Çok Dilli Web Uygulamaları**
   - Lokalizasyon best practices
   - Dinamik dil değiştirme sistemleri
   - Route ve içerik yönetiminde locale kullanımı
   - Çok dilli ses teknolojileri entegrasyonu

5. **Rol Tabanlı Erişim Kontrolü (RBAC)**
   - Laravel'de RBAC implementasyonu
   - Dinamik izin yönetimi
   - Performans optimizasyonu

6. **Real-time Sistemler ve Queue Yönetimi**
   - Laravel Queue sistemi (Redis driver)
   - Supervisor ile process yönetimi
   - Pusher broadcasting entegrasyonu
   - Event-driven architecture
   - Paralel işleme ve performans optimizasyonu
   - Cache stratejileri (TTS cache sistemi)

### Kullanılan Metodoloji

- 📖 **Literatür Araştırması:** IVR sistemleri, AI konuşma sistemleri, SaaS mimarileri, Laravel best practices
- 🔬 **Uygulama Geliştirme:** Modüler mimari ile prototip geliştirme, AI entegrasyonu
- 🧪 **Test ve Simülasyon:** Gerçek zamanlı konuşma simülasyonu, TTS/STT test ortamı
- 📝 **Dokümantasyon:** UML diyagramları, API docs, kullanıcı kılavuzları, teknik rehberler

### Beklenen Çıktılar

- 📄 Bitirme tezi/raporu
- 💻 Çalışan MVP (Minimum Viable Product) - **✅ Temel özellikler tamamlandı**
- 🤖 AI destekli konuşma sistemi - **✅ Tamamlandı**
- 📚 Teknik dokümantasyon - **✅ Kısmen tamamlandı**
- 🎤 Bitirme sunumu
- 📊 Case study ve performans analizi

---

## 📖 Referanslar ve Kaynaklar

### Teknik Dokümantasyon
- [Laravel 12.x Official Docs](https://laravel.com/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Docker Documentation](https://docs.docker.com)
- [MySQL 8.0 Reference Manual](https://dev.mysql.com/doc)
- [Spatie Laravel Permission](https://spatie.be/docs/laravel-permission)
- [nwidart Laravel Modules](https://nwidart.com/laravel-modules)
- [Google Cloud Text-to-Speech](https://cloud.google.com/text-to-speech/docs)
- [Google Cloud Speech-to-Text V2](https://cloud.google.com/speech-to-text/v2/docs)
- [Google Gemini API](https://ai.google.dev/docs)

### Proje Dokümantasyonu
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

## 🎓 Proje Durumu

> **📍 Mevcut Durum:** Aktif Geliştirme Aşamasında  
> **📅 Proje Dönemi:** 2025-2026 Güz Dönemi  
> **🎯 Bitirme Projesi Teslimi:** Ocak 2026  
> **🚀 SaaS Lansmanı Hedefi:** Mayıs 2026  
> **✅ İlerleme:** ~%75

### Tamamlanan Özellikler (✅)
- ✅ Kullanıcı yönetimi ve authentication
- ✅ Rol ve izin yönetimi (RBAC)
- ✅ Çok dilli destek (Türkçe/İngilizce)
- ✅ Modüler mimari altyapısı
- ✅ Google Cloud TTS entegrasyonu
- ✅ Google Cloud STT V2 entegrasyonu
- ✅ Google Gemini 2.5 Flash entegrasyonu
- ✅ **Gerçek zamanlı streaming AI konuşma sistemi**
- ✅ **Pusher real-time broadcasting**
- ✅ **Redis queue sistemi**
- ✅ **Supervisor ile otomatik queue worker yönetimi**
- ✅ **TTS cache sistemi** (~600x performans artışı)
- ✅ **Paralel TTS işleme** (non-blocking)
- ✅ TestSimulasyonu modülü (TTS/STT test ve streaming AI konuşma)
- ✅ SSML ön işleme sistemi
- ✅ Senaryo bazlı konuşma yönetimi
- ✅ **Voice Activity Detection (VAD)**
- ✅ **Performans metrikleri ve analiz**

### Geliştirilmekte Olan Özellikler (🔄)
- 🔄 IVR akış tasarımcısı
- 🔄 Dashboard ve analitik
- 🔄 Çok faktörlü kimlik doğrulama (2FA)

### Planlanan Özellikler (📅)
- 📅 Multi-tenant mimari
- 📅 Abonelik sistemi
- 📅 Dinamik menü yapılandırması
- 📅 Çağrı yönlendirme sistemi
- 📅 DTMF algılama
- 📅 Raporlama ve export işlemleri
- 📅 API token yönetimi

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

---

## 📝 Notlar

**Güncelleme Tarihi:** Aralık 2025  
**Versiyon:** 2.5.0  
**Son Güncelleme:** 
- ✅ Gerçek zamanlı streaming AI konuşma sistemi tamamlandı
- ✅ Pusher real-time broadcasting entegrasyonu
- ✅ Redis queue sistemi ve Supervisor otomasyonu
- ✅ TTS cache sistemi ve paralel işleme optimizasyonları
- ✅ Performans metrikleri: STT ~1.3s, AI ~1.2s, TTS 0ms (paralel)
- ✅ TestSimulasyonu modülü aktif ve production-ready
