# Merhaba, Ben Muhammed Şehit Sevim! 👋
### Backend Mimarı & Yazılım Geliştiricisi

Modern, ölçeklenebilir ve temiz kod prensiplerine (Clean Code/Architecture) dayalı yazılımlar geliştiriyorum. Bir sistemi sadece "çalışır hale getirmek" değil, *neden bu şekilde tasarlandığını* açıklayabilmek benim için önemli — bu yüzden mimari kararlarımı genelde somut geçiş stratejileri ve ölçülebilir trade-off'larla ele alıyorum.

2018'den bu yana depo/robotik otomasyon, IoT cihaz haberleşmesi, mikroservis mimarisine geçiş ve fintech/ödeme sistemleri gibi birbirinden farklı problem alanlarında backend çözümleri ürettim. Ortak nokta: gerçek zamanlı, mesaj kuyruklu ve dayanıklı sistemler kurmak.

---

### 🚀 Deneyimlerim ve Öne Çıkan Çalışmalarım

* **Depo Robotik Otomasyon Sistemi** — *Bottobo Robotics*
    * *Kapsam:* Depo robotlarının sipariş ve ürün toplama süreçlerini yöneten uçtan uca bir sistem. .NET Core Web API ile robot/sipariş takibi backend'i, DevExpress + Blazor ile yönetim arayüzü.
    * *Saha tarafı:* Robotların görev yönetimi için Flutter tabanlı bir tablet uygulaması geliştirdim (Bloc ve GetX ile state management). Tablet ile web API arasındaki gerçek zamanlı iletişimi RabbitMQ ve MQTT ile kurdum.
    * *Mimari:* Modular Monolith yaklaşımı, Hangfire ile arka plan işleri, Docker ile konteynerizasyon, Kanban ile iş takibi.

* **Cihaz Haberleşmesi & Mikroservis Planlaması** — *Yapıdrom Mobility*
    * *Kapsam:* Sahadaki cihazlarla TCP/MQTT üzerinden iletişim kuran bir dinleyici servisi, .NET'in Windows Service yapısı kullanılarak geliştirildi.
    * *Mesajlaşma:* Cihazlardan gelen mesajların web servislerine ulaşmadan önce RabbitMQ kuyruğuna alınmasını sağladım — yoğun mesaj trafiğinde servislerin boğulmasını engelleyen bir tampon katmanı.
    * *Modernizasyon:* Eski monolitik yapının mikroservislere geçiş planlamasında yer aldım; Cihaz, Müşteri ve Yönetim panelleri için servisleri .NET Core ile yeniden yazdım. Scrum ile süreç yönetimi, ASP.NET MVC + Entity Framework + MSSQL (trigger/stored procedure) ile hata düzeltme çalışmaları.

* **Ödeme Gateway & Açık Bankacılık Entegrasyonu** — *Parolapara*
    * *Kapsam:* FAST para transferi için QR üretme/okuma altyapısı ve TCMB entegrasyonu; Üye İş Yeri sisteminin TCMB entegrasyonları.
    * *Ek servisler:* Email/SMS/Push bildirimlerini tek merkezden yöneten Bildirim Servisi (SMTP, OneSignal); kullanıcı taleplerinin doğru birime yönlendirilip takip edildiği bir Talep Destek Servisi.
    * *Mimari:* Onion Architecture, mikroservisler, Redis, Hangfire, OpenTelemetry ile gözlemlenebilirlik.

* **Node.js Muhasebe Uygulaması** *(kişisel proje)*
    * *Kapsam:* PostgreSQL (Docker) ve Prisma ORM kullanılarak geliştirilen full-stack muhasebe sistemi.
    * *Not:* .NET dışında Node.js ekosisteminde de aktif proje geliştiriyorum.

* **Oyun ve Mobil Çalışmalar** *(kişisel proje)*
    * Godot Engine ve C# ile 3D/2D oyun projeleri (örn. Türkçe bir bulmaca oyunu).
    * Flutter ile çapraz platform mobil uygulama prototipleri.

---

### 🛠 Teknik Yetkinliklerim

**Backend, Mimari & Tasarım**

![.NET Core](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=.net&logoColor=white) ![Microservices](https://img.shields.io/badge/Microservices-00ADD8?style=for-the-badge&logo=microservices&logoColor=white) ![Modular Monolith](https://img.shields.io/badge/Modular_Monolith-663399?style=for-the-badge&logo=dotnet&logoColor=white) ![Onion](https://img.shields.io/badge/Onion_Arch-007ACC?style=for-the-badge&logo=onion&logoColor=white) ![Hexagonal](https://img.shields.io/badge/Hexagonal-FF9900?style=for-the-badge&logo=hexagon&logoColor=white)

**Clean Code & Prensipler**

![SOLID](https://img.shields.io/badge/SOLID-61DAFB?style=for-the-badge&logo=solid&logoColor=black) ![KISS](https://img.shields.io/badge/KISS-FF5733?style=for-the-badge&logo=simpleicons&logoColor=white) ![YAGNI](https://img.shields.io/badge/YAGNI-FFC300?style=for-the-badge&logo=simpleicons&logoColor=white) ![CQRS](https://img.shields.io/badge/CQRS-E10098?style=for-the-badge&logo=cqrs&logoColor=white) ![Repository](https://img.shields.io/badge/Repository-4CAF50?style=for-the-badge&logo=repository&logoColor=white) ![Adapter](https://img.shields.io/badge/Adapter-FF5722?style=for-the-badge&logo=abstract&logoColor=white)

**Altyapı & Haberleşme**

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white) ![Hangfire](https://img.shields.io/badge/Hangfire-0F4C81?style=for-the-badge&logo=dotnet&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)

**Frontend & UI**

![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white) ![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white) ![DevExpress](https://img.shields.io/badge/DevExpress-FF7200?style=for-the-badge&logo=devexpress&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Sistem & Self-Hosting**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![CachyOS](https://img.shields.io/badge/CachyOS-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white) ![Tailscale](https://img.shields.io/badge/Tailscale-000000?style=for-the-badge&logo=tailscale&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=for-the-badge&logo=caddy&logoColor=white)

**Oyun, Mobil & Veri**

![Godot](https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godot-engine&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white) ![ML.NET](https://img.shields.io/badge/ML.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

---

### 🌐 İletişim

* **LinkedIn:** [https://www.linkedin.com/in/msehitsevim/](https://www.linkedin.com/in/msehitsevim/)
* **E-posta:** sehitsevim@gmail.com
