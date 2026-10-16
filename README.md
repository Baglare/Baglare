# Batuhan Parıltı

**Computer Engineering Student · Software Developer**

[ArtifactHub](https://artifact-hub-xi.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/baglare/) · [GitHub](https://github.com/Baglare)

---

# EN

## About Me

I am a Computer Engineering student building software projects across developer tooling, AI infrastructure, full-stack applications, desktop software, game systems, audio processing and computer vision.

I am particularly interested in projects where the main engineering challenge goes beyond the interface: data flow, architecture, deterministic processing, validation, provider boundaries, release workflows and system reliability.

Some projects remain focused prototypes, while others grow into larger systems with testing, release preparation and longer-term architecture work.

Detailed technical breakdowns of the projects, including architecture decisions, implemented scope and known limitations, are available on [ArtifactHub](https://artifact-hub-xi.vercel.app/).

## Main Projects

### [GameLocalizer](https://artifact-hub-xi.vercel.app/artifacts/gamelocalizer)

A Python developer tool for building safer game-localization workflows.

The project covers format-aware extraction and application, structural QA, translation memory, deterministic context handling, glossary support, multiple localization formats, Unity localization investigation and reversible patch packaging.

A major part of the project is not the translation itself, but protecting the structure surrounding it: placeholders, formatting, file ownership, repeatable processing and validation before changes are applied to a game.

**Focus:** Developer Tooling · Localization Engineering · Deterministic Pipelines · QA

---

### [KnowledgeCompiler](https://artifact-hub-xi.vercel.app/artifacts/knowledgecompiler)

A deterministic, provider-neutral infrastructure project for managing AI-assisted software development workflows.

It introduces structured project authority, context compilation, task/result contracts, transactional knowledge promotion, controlled synchronization and automation boundaries.

The main goal is to make AI-assisted development more reproducible and auditable instead of relying on loosely structured prompts and conversational context.

**Focus:** AI Infrastructure · Developer Tooling · Transactions · Automation Governance

---

### [MediaTracker](https://github.com/Baglare/MediaTracker)

**Live v1:** [Try MediaTracker](https://mediatracker.baglare.com.tr) · [Technical case study](https://artifact-hub-xi.vercel.app/artifacts/media-tracker) · [Source](https://github.com/Baglare/MediaTracker)

A deployed local-first full-stack product for tracking series, films, anime, manga, and books. Guest access works without an account; verified users can use controlled Cloud Sync, progress tracking, goals, release calendar, social features, and deterministic recommendations.

The engineering focus is owner-scoped data integrity, PostgreSQL 18 row-level security, Better Auth sessions, revision/idempotency-based synchronization, and validated Linux/Passenger releases. Paid AI and several third-party content providers are deliberately disabled in production.

**Focus:** Full-Stack Development · Next.js · PostgreSQL · Local-First Architecture · Product Engineering

---

### [PulseForge](https://github.com/Baglare/PulseForge)

A Unity rhythm-combat systems prototype built around turning external music into gameplay data.

The current pipeline can import custom songs, normalize them through FFmpeg, perform runtime beat/onset analysis and generate Guard/Strike-oriented beatmaps used by the combat system.

The project combines audio processing with runtime gameplay architecture rather than relying only on manually authored rhythm maps.

**Focus:** Unity · C# · Audio Processing · Runtime Systems · Game Architecture

---

### [TempoBlade](https://github.com/Baglare/TempoBlade)

A Unity gameplay-systems project focused on tempo-driven combat and roguelite progression.

Its systems include weapon-specific combo data, parry/deflect behavior, enemy variants, encounter flow, hub progression and data-driven gameplay structures using ScriptableObjects.

The project is primarily valuable as a combat-architecture and gameplay-systems prototype rather than as a finished game.

**Focus:** Unity · C# · Combat Architecture · Data-Driven Gameplay

## Other Projects

### [VoxForge](https://github.com/Baglare/VoxForge)

A local voice and TTS experimentation environment built around XTTS.

It includes voice profiles, audio preprocessing, dataset preparation, experimental fine-tuning workflows, checkpoint comparison, inference parameter testing and human evaluation tools.

**Focus:** Python · TTS · Audio Tooling · Model Evaluation

### [VisionForge](https://github.com/Baglare/VisionForge)

A computer-vision interaction prototype that converts camera input into application interactions.

It combines face and hand detection, local identity verification and gesture-driven interface mechanics.

**Focus:** Python · OpenCV · MediaPipe · Computer Vision

### [PoD Localization Engineering](https://github.com/Baglare/PoD-Localization-Engineering)

A public engineering case study derived from a larger Turkish localization project distributed through Steam Workshop.

The public repository uses synthetic data to demonstrate protected syntax handling, deterministic processing, structural QA and package verification without publishing the private production localization corpus.

**Focus:** Localization Engineering · QA · Release Engineering

### [Aria AI](https://artifact-hub-xi.vercel.app/artifacts/aria-ai)

An **early-stage** Windows-first desktop AI architecture prototype.

Current work focuses on the application foundation: React/Tauri desktop UI, a local FastAPI core, SSE streaming and cancellation, SQLite persistence, local Ollama integration and secure credential storage.

It is not currently presented as a feature-complete AI assistant.

**Focus:** Desktop Architecture · Tauri · FastAPI · Local AI

### [OpenAI Image Studio](https://artifact-hub-xi.vercel.app/artifacts/openai-image-studio)

A smaller Next.js tool for single-user image generation and reference-image editing.

It keeps provider calls server-side and includes local output history and usage/cost estimation.

**Focus:** Next.js · API Integration · Image Generation

## Technical Areas

- Developer tooling and automation
- AI infrastructure and provider boundaries
- Local-first and full-stack application architecture
- Deterministic processing and validation
- Unity gameplay systems
- Localization and release engineering
- Audio and TTS tooling
- Computer vision
- Testing, documentation and release preparation

## Technologies

**Languages:** Python · TypeScript · C# · SQL

**Application:** Next.js · React · FastAPI · Tauri · Unity

**Data / Infrastructure:** SQLite · PostgreSQL · Supabase

**Specialized:** OpenCV · MediaPipe · FFmpeg · XTTS

---

# TR

## Hakkımda

Geliştirici araçları, AI altyapısı, full-stack uygulamalar, masaüstü yazılımlar, oyun sistemleri, ses işleme ve bilgisayarlı görü alanlarında yazılım projeleri geliştiren bir Bilgisayar Mühendisliği öğrencisiyim.

Özellikle temel mühendislik probleminin arayüzün ötesine geçtiği projeler ilgimi çekiyor: veri akışı, mimari, deterministik işleme, doğrulama, provider sınırları, release süreçleri ve sistem güvenilirliği.

Bazı projeler odaklı prototipler olarak kalırken bazıları test, release hazırlığı ve daha uzun vadeli mimari çalışmalar içeren daha büyük sistemlere dönüşüyor.

Projelerin mimari kararları, uygulanmış kapsamı ve bilinen sınırları dahil daha ayrıntılı teknik açıklamaları [ArtifactHub](https://artifact-hub-xi.vercel.app/) üzerinde bulunuyor.

## Ana Projeler

### [GameLocalizer](https://artifact-hub-xi.vercel.app/artifacts/gamelocalizer)

Daha güvenli oyun yerelleştirme iş akışları oluşturmak için geliştirdiğim Python tabanlı bir geliştirici aracı.

Proje; format-aware extraction ve application, yapısal QA, translation memory, deterministik context yönetimi, glossary desteği, birden fazla localization formatı, Unity localization araştırmaları ve geri alınabilir patch paketleme süreçlerini kapsıyor.

Projenin önemli kısmı yalnızca çeviri yapmak değil, çevirinin çevresindeki yapıyı korumak: placeholder'lar, biçimlendirme, dosya sahipliği, tekrarlanabilir işlemler ve değişiklikler oyuna uygulanmadan önce yapılan doğrulamalar.

**Odak:** Geliştirici Araçları · Yerelleştirme Mühendisliği · Deterministik Pipeline · QA

---

### [KnowledgeCompiler](https://artifact-hub-xi.vercel.app/artifacts/knowledgecompiler)

AI destekli yazılım geliştirme iş akışlarını yönetmek için geliştirdiğim deterministik ve provider-neutral bir altyapı projesi.

Yapılandırılmış proje yetkisi, context derleme, task/result sözleşmeleri, transactional bilgi promotion, kontrollü senkronizasyon ve otomasyon sınırları oluşturuyor.

Temel amaç, AI destekli geliştirmeyi yalnızca serbest biçimli promptlara ve sohbet context'ine bağlı bırakmak yerine daha tekrarlanabilir ve denetlenebilir hale getirmek.

**Odak:** AI Altyapısı · Geliştirici Araçları · Transaction · Otomasyon Yönetişimi

---

### [MediaTracker](https://github.com/Baglare/MediaTracker)

**Canlı v1:** [MediaTracker'ı Dene](https://mediatracker.baglare.com.tr) · [Teknik Vaka Çalışması](https://artifact-hub-xi.vercel.app/artifacts/media-tracker) · [Kaynak Kod](https://github.com/Baglare/MediaTracker)

Dizi, film, anime, manga ve kitapların takibi için canlıya alınmış yerel öncelikli full-stack ürün. Misafir kullanımı hesapsız çalışır; doğrulanmış hesaplarla kontrollü Cloud Sync, ilerleme, hedefler, yayın takvimi, sosyal özellikler ve deterministik öneriler sunar.

Mühendislik odağı; owner-scoped veri bütünlüğü, PostgreSQL 18 RLS, Better Auth oturumları, revision/idempotency temelli eşitleme ve doğrulanmış Linux/Passenger yayın akışıdır. Ücretli AI ve bazı harici içerik sağlayıcıları Production'da bilinçli olarak kapalıdır.

**Odak:** Full-Stack Geliştirme · Next.js · PostgreSQL · Local-First Mimari · Ürün Mühendisliği

---

### [PulseForge](https://github.com/Baglare/PulseForge)

Harici müzikleri oynanış verisine dönüştürmek üzerine kurulu bir Unity ritim-combat sistem prototipi.

Mevcut pipeline özel şarkıları içe aktarabiliyor, FFmpeg ile normalize ediyor, runtime beat/onset analizi gerçekleştiriyor ve combat sistemi tarafından kullanılan Guard/Strike odaklı beatmap'ler üretiyor.

Proje yalnızca elle hazırlanmış ritim haritalarına dayanmak yerine ses işlemeyi runtime gameplay mimarisiyle birleştiriyor.

**Odak:** Unity · C# · Ses İşleme · Runtime Sistemleri · Oyun Mimarisi

---

### [TempoBlade](https://github.com/Baglare/TempoBlade)

Tempo tabanlı combat ve roguelite progression üzerine odaklanan bir Unity gameplay-systems projesi.

Weapon-specific combo verileri, parry/deflect davranışı, düşman varyasyonları, encounter akışı, hub progression ve ScriptableObject tabanlı data-driven gameplay yapıları içeriyor.

Projenin temel değeri tamamlanmış bir oyun olmaktan çok combat architecture ve gameplay systems prototipi olması.

**Odak:** Unity · C# · Combat Architecture · Data-Driven Gameplay

## Diğer Projeler

### [VoxForge](https://github.com/Baglare/VoxForge)

XTTS etrafında geliştirdiğim yerel voice ve TTS deney ortamı.

Voice profile, ses ön işleme, dataset hazırlama, deneysel fine-tuning akışları, checkpoint karşılaştırma, inference parametre testleri ve insan değerlendirme araçları içeriyor.

**Odak:** Python · TTS · Ses Araçları · Model Değerlendirme

### [VisionForge](https://github.com/Baglare/VisionForge)

Kamera girdisini uygulama etkileşimlerine dönüştüren bilgisayarlı görü prototipi.

Yüz ve el algılama, yerel kimlik doğrulama ve gesture-driven interface mekaniklerini bir araya getiriyor.

**Odak:** Python · OpenCV · MediaPipe · Bilgisayarlı Görü

### [PoD Localization Engineering](https://github.com/Baglare/PoD-Localization-Engineering)

Steam Workshop üzerinden dağıtılan daha büyük bir Türkçe yerelleştirme projesinden türetilmiş public mühendislik vaka çalışması.

Public repository, private production localization corpus'unu yayınlamadan protected syntax yönetimi, deterministik işleme, yapısal QA ve paket doğrulamasını sentetik verilerle gösteriyor.

**Odak:** Yerelleştirme Mühendisliği · QA · Release Engineering

### [Aria AI](https://artifact-hub-xi.vercel.app/artifacts/aria-ai)

**Erken aşamadaki** Windows-first masaüstü AI mimari prototipi.

Mevcut çalışma uygulamanın temel mimarisine odaklanıyor: React/Tauri masaüstü arayüzü, yerel FastAPI core, SSE streaming ve cancellation, SQLite persistence, yerel Ollama entegrasyonu ve güvenli credential saklama.

Şu anda feature-complete bir AI asistanı olarak sunulmuyor.

**Odak:** Masaüstü Mimarisi · Tauri · FastAPI · Local AI

### [OpenAI Image Studio](https://artifact-hub-xi.vercel.app/artifacts/openai-image-studio)

Tek kullanıcılı görsel üretme ve referans görsel düzenleme için geliştirdiğim daha küçük bir Next.js aracı.

Provider çağrılarını server-side tutuyor ve yerel çıktı geçmişi ile kullanım/maliyet tahmini içeriyor.

**Odak:** Next.js · API Entegrasyonu · Görsel Üretimi

## Teknik Alanlar

- Geliştirici araçları ve otomasyon
- AI altyapısı ve provider sınırları
- Local-first ve full-stack uygulama mimarisi
- Deterministik işleme ve doğrulama
- Unity gameplay sistemleri
- Yerelleştirme ve release engineering
- Ses ve TTS araçları
- Bilgisayarlı görü
- Test, dokümantasyon ve release hazırlığı

## Teknolojiler

**Diller:** Python · TypeScript · C# · SQL

**Uygulama:** Next.js · React · FastAPI · Tauri · Unity

**Veri / Altyapı:** SQLite · PostgreSQL · Supabase

**Özel Alanlar:** OpenCV · MediaPipe · FFmpeg · XTTS
