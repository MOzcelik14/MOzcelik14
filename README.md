<p align="center">
  <a href="https://muratozcelik.vercel.app/">
    <img src="assets/banner.svg" alt="Murat Özçelik — Bilişim teknisyeni · Radyo, Televizyon ve Sinema öğrencisi · Açık kaynak geliştiricisi · Vibecoder" width="100%" />
  </a>
</p>

<p align="center">
  <sub><i>IT technician · Radio, Television &amp; Cinema student · Open-source developer · Vibecoder</i></sub>
</p>

<p align="center">
  <a href="https://muratozcelik.vercel.app/"><b>Portfolyo / Portfolio</b></a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/murat-%C3%B6z%C3%A7elik-398713292">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://instagram.com/muratozclik">Instagram</a>
</p>

---

Bolu Abant İzzet Baysal Üniversitesi'nde Radyo, Televizyon ve Sinema bölümünün 4. sınıfındayım. Lisede bilişim teknolojileri / veritabanı programcılığı okudum. Yazılımı sinema, ses ve müzikle aynı yerde, kendi ihtiyaçlarımdan yola çıkarak yapıyorum: kurguda, seste ve günlük Linux kullanımında eksik bulduğum araçları tasarlıyor, geliştiriyor ve kullanılabilir bir ürüne dönüştürmeye çalışıyorum. Bazı projeler hâlâ gelişme aşamasında; her birinin durumunu ilgili depoda belirtiyorum.

*I'm a final-year Radio, Television and Cinema student at Bolu Abant İzzet Baysal University, with a vocational high school background in information technology and database programming. I build software alongside film, sound and music, starting from my own needs: I design and develop the tools I find missing in editing, audio work and everyday Linux use, and try to turn them into something usable. Some projects are still evolving; each repository states its own status.*

## Öne çıkan projeler / Featured projects

| [**prisM. Suite**](https://github.com/MOzcelik14/prism-suite) |
|:--|
| Yaratıcı masaüstü uygulamaları ekosistemi için yerel başlatıcı, paket yöneticisi ve otomatik güncelleme merkezi. **triM.** (video), **steM.** (ses) ve **beaM.** (RAW fotoğraf) stüdyolarını tek bir bağımsız ekosistem altında toplar; arka planda hafif çalışan, çapraz platform bir deneyim sunar.<br><br>*A native desktop launcher, package manager, and auto-updater for creative desktop applications. Unifies **triM.** (video), **steM.** (audio), and **beaM.** (RAW photo) under a single cohesive ecosystem, delivering a lightweight and native cross-platform experience.*<br><br>![Rust](https://img.shields.io/badge/Rust-21262d?style=flat-square&logo=rust&logoColor=white) ![egui](https://img.shields.io/badge/egui_/_eframe-21262d?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-21262d?style=flat-square&logo=githubactions&logoColor=white) ![GPL-3.0](https://img.shields.io/badge/GPL--3.0-21262d?style=flat-square) |

| [**triM.**](https://github.com/MOzcelik14/triM) |
|:--|
| Linux ve Windows için Rust ile yazdığım, Electron kullanmayan yerel ve doğrusal olmayan bir video düzenleyici (NLE). egui/eframe arayüzü, FFmpeg tabanlı donanım hızlandırmalı medya işleme, çok kanallı zaman çizelgesi, ses miksajı, renk düzenleme, başlık klipleri ve dışa aktarma sunar; CMX 3600 EDL ve Final Cut Pro XML desteğiyle diğer kurgu programlarıyla birlikte çalışabilirliği hedefler.<br><br>*A native, Electron-free non-linear video editor for Linux and Windows, written in Rust. It offers an egui/eframe interface, FFmpeg-based hardware-accelerated media processing, a multi-track timeline, audio mixing, color grading, title clips and export, and aims for interoperability with other editors through CMX 3600 EDL and Final Cut Pro XML.*<br><br>![Rust](https://img.shields.io/badge/Rust-21262d?style=flat-square&logo=rust&logoColor=white) ![egui](https://img.shields.io/badge/egui_/_eframe-21262d?style=flat-square) ![FFmpeg](https://img.shields.io/badge/FFmpeg-21262d?style=flat-square&logo=ffmpeg&logoColor=white) ![GPL-3.0](https://img.shields.io/badge/GPL--3.0-21262d?style=flat-square) |

| [**steM.**](https://github.com/MOzcelik14/steM) |
|:--|
| Rust ile sıfırdan geliştirilen, yüksek performanslı ve tahribatsız (non-destructive) çok kanallı ses iş istasyonu ve dalga biçimi düzenleyicisi. Gerçek zamanlı ses iş parçacığında kilit ve bellek tahsisi yapmayan (lock-free SPSC) ses motoru, Demucs v4 ile vokal ve enstrüman ayrıştırma, kanal başına seviye / solo / mute kontrolü, senkronize çok kanallı oynatma ve GPU hızlandırma içerir.<br><br>*A high-performance, non-destructive multi-track audio workstation and waveform editor built from scratch in Rust. Features a lock-free real-time audio thread, Demucs v4 stem separation (vocals, drums, bass, other), per-track level/solo/mute controls, synchronized multi-channel playback, and GPU acceleration.*<br><br>![Rust](https://img.shields.io/badge/Rust-21262d?style=flat-square&logo=rust&logoColor=white) ![egui](https://img.shields.io/badge/egui_/_eframe-21262d?style=flat-square) ![cpal](https://img.shields.io/badge/cpal_/_Symphonia-21262d?style=flat-square) ![Demucs](https://img.shields.io/badge/Demucs_v4-21262d?style=flat-square) ![GPL-3.0](https://img.shields.io/badge/GPL--3.0-21262d?style=flat-square) |

| [**beaM.**](https://github.com/MOzcelik14/beaM) |
|:--|
| Linux ve Windows için saf Rust ile geliştirilen açık kaynaklı, tahribatsız (non-destructive) RAW fotoğraf düzenleyici ve görsel stüdyosu. Orijinal dosyayı asla değiştirmeyen `.beam` yan dosyaları (sidecar), modüler WGSL gölgelendiricileriyle GPU hızlandırmalı doğrusal Rec.2020 renk işleme hattı ve geniş katalog yönetimi sunar; Adobe Lightroom'a yerel ve saf Rust bir alternatif oluşturmayı hedefler.<br><br>*An open-source, non-destructive RAW photo editor and library manager for Linux and Windows built in pure Rust. Features sidecar edit storage (`.beam`), a GPU-accelerated WGSL pipeline operating internally in linear Rec.2020 color space, and high-performance library management as a pure-Rust alternative to Adobe Lightroom.*<br><br>![Rust](https://img.shields.io/badge/Rust-21262d?style=flat-square&logo=rust&logoColor=white) ![wgpu](https://img.shields.io/badge/wgpu_30.0-21262d?style=flat-square&logo=webgpu&logoColor=white) ![egui](https://img.shields.io/badge/egui_0.37-21262d?style=flat-square) ![GPL-3.0](https://img.shields.io/badge/GPL--3.0-21262d?style=flat-square) |

| [**Puresteel OS**](https://github.com/MOzcelik14/Puresteel-OS) |
|:--|
| Debian 13 (Trixie) ve KDE Plasma 6 tabanlı, bağımsız bir Linux dağıtımı. Oyun, yaratıcı üretim ve geliştirici araçlarını temiz bir masaüstünde toplar. Calamares tabanlı grafiksel kurulum, imzalı APT deposu, kendi sistem yönetim uygulaması Puresteel Center, Intel / AMD / NVIDIA ve hibrit GPU desteği, ZRAM ayarları ve GitHub Actions ile otomatik ISO derlemesi içerir.<br><br>*An independent Linux distribution based on Debian 13 (Trixie) and KDE Plasma 6, bringing gaming, creative and developer tools together on a clean desktop. It includes a Calamares-based installer, a signed APT repository, its own system management app (Puresteel Center), Intel / AMD / NVIDIA and hybrid GPU support, ZRAM tuning and automated ISO builds on GitHub Actions.*<br><br>![Debian](https://img.shields.io/badge/Debian_13-21262d?style=flat-square&logo=debian&logoColor=white) ![KDE Plasma](https://img.shields.io/badge/KDE_Plasma_6-21262d?style=flat-square&logo=kde&logoColor=white) ![Calamares](https://img.shields.io/badge/Calamares-21262d?style=flat-square) ![PySide6](https://img.shields.io/badge/PySide6-21262d?style=flat-square&logo=qt&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-21262d?style=flat-square&logo=githubactions&logoColor=white) |

| [**Aether**](https://github.com/MOzcelik14/Aether) |
|:--|
| Ollama üzerinden yerel veya uzak modellerle konuşan GTK4 / Libadwaita masaüstü istemcisi. Sohbet arayüzü, model yönetimi ve model ayarları sunar; amaç, kendi çalıştırdığım modelleri sade bir masaüstü uygulamasından kullanabilmek.<br><br>*A GTK4 / Libadwaita desktop client for talking to local or remote models through Ollama. It provides a chat interface, model management and model settings, so models I run myself can be used from a simple desktop app.*<br><br>![Python](https://img.shields.io/badge/Python-21262d?style=flat-square&logo=python&logoColor=white) ![GTK4](https://img.shields.io/badge/GTK4_/_Libadwaita-21262d?style=flat-square&logo=gtk&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-21262d?style=flat-square&logo=ollama&logoColor=white) ![MIT](https://img.shields.io/badge/MIT-21262d?style=flat-square) |

| [**İLEFBot**](https://github.com/MOzcelik14/ILEFBot) |
|:--|
| BAİBÜ İletişim Fakültesi öğrencileri için geliştirdiğim bağımsız, mobil uyumlu bir yapay zekâ sohbet uygulaması. OpenRouter üzerinden ücretsiz modellere erişir; çoklu sohbet, tarayıcıda saklanan geçmiş ve açık / koyu tema içerir. Üniversitenin resmî hizmeti değildir.<br><br>*An independent, mobile-friendly AI chat app I built for students of the BAİBÜ Faculty of Communication. It uses free models through OpenRouter and includes multiple chats, browser-stored history and light / dark themes. It is not an official university service.*<br><br>![JavaScript](https://img.shields.io/badge/JavaScript-21262d?style=flat-square&logo=javascript&logoColor=white) ![HTML](https://img.shields.io/badge/HTML_/_CSS-21262d?style=flat-square&logo=html5&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-21262d?style=flat-square&logo=vercel&logoColor=white) ![OpenRouter](https://img.shields.io/badge/OpenRouter-21262d?style=flat-square) |

## Diğer projeler / More projects

| Proje | Açıklama / Description |
|:--|:--|
| [**MintGuard**](https://github.com/MOzcelik14/MintGuard) | Linux Mint için sistem sağlığı ve bakım uygulaması. Temizlik işlemleri kullanıcı onayı ister, telemetri yoktur.<br>*System health and maintenance app for Linux Mint. Cleanups require confirmation; no telemetry.*<br>`Python` `PySide6` |
| [**DebGear**](https://github.com/MOzcelik14/DebGear) | Debian odaklı donanım ve sürücü merkezi. Paket işlemleri yalnızca Debian'da etkindir, evrensel bir sürücü yöneticisi değildir.<br>*Debian-focused hardware and driver center. Package operations are enabled only on Debian; not a universal driver manager.*<br>`Python` `GTK4` `MIT` |
| [**MRT**](https://github.com/MOzcelik14/MRT) | Standart C ile sıfırdan yazdığım dinamik tipli bir programlama dili ve GTK4 tabanlı yerel IDE'si MRT Studio. Deneysel bir çalışma.<br>*A dynamically typed language written from scratch in standard C, with a native GTK4 IDE. Experimental.*<br>`C` `GTK4` `MIT` |
| [**KalemX**](https://github.com/MOzcelik14/KalemX) | Linux masaüstünde ekran üzerine çizim ve açıklama aracı. Beta aşamasında; Wayland desteği masaüstü ortamına bağlı ve deneyseldir.<br>*Screen annotation tool for Linux. In beta; Wayland support depends on the compositor and is experimental.*<br>`Python` `GTK3 / Cairo` `MIT` |
| [**HabitForge**](https://github.com/MOzcelik14/habitforge) | Günlük alışkanlık ve rutin takipçisi. GTK4, Libadwaita ve Cairo 2D motoru ile çizilen 52 haftalık aktivite ısı haritası.<br>*Daily habit and routine tracker. Features GTK4, Libadwaita and a 52-week activity heatmap drawn with Cairo.*<br>`Python` `GTK4 / Libadwaita` `Cairo` `MIT` |

## Teknolojiler / Technologies

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rust/rust-original.svg" alt="Rust" title="Rust" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" title="Python" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/c/c-original.svg" alt="C" title="C" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" alt="C#" title="C#" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" alt="Java" title="Java" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" height="40" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git" title="Git" height="40" />
</p>

Hepsinde aynı derinlikte değilim; hangi projede ne kullandığım yukarıda belirtilmiş durumda.
*My depth varies across these; the project entries above show what I actually use where.*

- **Diller / Languages:** Rust, Python, C, WGSL (WebGPU), C#, Java, JavaScript, HTML, CSS
- **Masaüstü & Grafik / Desktop & Graphics:** egui / eframe, wgpu (WebGPU), GTK4 / Libadwaita, GTK3 / Cairo, PySide6 (Qt 6)
- **Medya, Ses ve Video / Media, Audio & Video:** FFmpeg, cpal, Symphonia, Demucs v4, GStreamer
- **Linux ve Sistem / Linux and Systems:** Debian, APT paketleme, Flatpak, Calamares, Bash
- **Yapay Zekâ / AI:** Ollama, OpenRouter
- **Araçlar / Tooling:** Git, Cargo, GitHub Actions

---

<p align="center">
  <a href="https://muratozcelik.vercel.app/"><b>muratozcelik.vercel.app</b></a>
</p>
