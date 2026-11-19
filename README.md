<div align="center">

# ğŸ›ï¸ Kastamonu Ãœniversitesi â€” ToplantÄ± & Ajanda YÃ¶netim Sistemi
### *Kastamonu University â€” Meeting Room & Academic Agenda Management System*

[![.NET 8.0](https://img.shields.io/badge/.NET-8.0-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![ASP.NET Core MVC](https://img.shields.io/badge/ASP.NET_Core-MVC-512BD4?style=for-the-badge&logo=aspnetcore&logoColor=white)](https://dotnet.microsoft.com/apps/aspnet)
[![SignalR](https://img.shields.io/badge/Real--Time-SignalR-F04D23?style=for-the-badge&logo=signalr&logoColor=white)](https://dotnet.microsoft.com/apps/aspnet/signalr)
[![Entity Framework Core](https://img.shields.io/badge/EF_Core-SQL_Server-blue?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)](https://learn.microsoft.com/ef/core/)
[![Bootstrap 5.3](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)

<br/>

**[ğŸ‡¹ğŸ‡· TÃ¼rkÃ§e DokÃ¼mantasyon](#-tÃ¼rkÃ§e-dokÃ¼mantasyon)** &nbsp;|&nbsp; **[ğŸ‡¬ğŸ‡§ English Documentation](#-english-documentation)**

<br/>

<img src="screenshots/01_homepage_hero.png" alt="Kastamonu Ãœniversitesi ToplantÄ± ve Ajanda YÃ¶netim Sistemi" width="100%" style="border-radius: 8px; box-shadow: 0 4px 16px rgba(0,0,0,0.2);" />

</div>

---

# ğŸ‡¹ğŸ‡· TÃ¼rkÃ§e DokÃ¼mantasyon

## ğŸ“– Proje HakkÄ±nda
**Kastamonu Ãœniversitesi ToplantÄ± ve Ajanda YÃ¶netim Sistemi**, Ã¼niversite bÃ¼nyesindeki rektÃ¶rlÃ¼k birimleri, fakÃ¼lteler ve enstitÃ¼lere ait toplantÄ± ve konferans salonlarÄ±nÄ±n rezervasyonlarÄ±nÄ±, akademik etkinlik ajandasÄ±nÄ±, salon doluluk durumlarÄ±nÄ± ve kapÄ± tablet ekranlarÄ±nÄ± (Kiosk) tek merkezden yÃ¶netmek amacÄ±yla geliÅŸtirilmiÅŸ yeni nesil, gerÃ§ek zamanlÄ± kurumsal bir web platformudur.

Proje, Kastamonu Ãœniversitesi kurumsal renk kimliÄŸine (Bordo-KÄ±rmÄ±zÄ±, Siyah ve Beyaz) tam uyumlu olarak tasarlanmÄ±ÅŸ olup, zenginleÅŸtirilmiÅŸ kullanÄ±cÄ± deneyimi (UI/UX), Koyu/AÃ§Ä±k Tema desteÄŸi, ASP.NET Core SignalR ile canlÄ± takvim senkronizasyonu ve mobil uyumlu Kiosk kapÄ± ekranÄ± yeteneklerini bir arada sunar.

---

## ğŸ“¸ Ekran GÃ¶rÃ¼ntÃ¼leri ve ArayÃ¼z Galerisi

### 1. Anasayfa & Kurumsal Ä°statistik Paneli
KullanÄ±cÄ±larÄ± karÅŸÄ±layan kurumsal karÅŸÄ±lama alanÄ±, toplam salon sayÄ±sÄ±, bugÃ¼nkÃ¼ toplantÄ±lar ve yaklaÅŸan etkinlik sayaÃ§larÄ±.
<p align="center">
  <img src="screenshots/01_homepage_hero.png" width="95%" alt="Anasayfa & Ä°statistik Paneli" />
</p>

### 2. GÃ¼nÃ¼n ToplantÄ± AjandasÄ± & Takvim EntegrasyonlarÄ±
GÃ¼nÃ¼n planÄ±, Google Calendar ve Outlook entegrasyon kartlarÄ± ve iCal (.ics) indirme baÄŸlantÄ±larÄ±.
<p align="center">
  <img src="screenshots/02_homepage_agenda_integration.png" width="95%" alt="GÃ¼nÃ¼n ToplantÄ± AjandasÄ± & Entegrasyonlar" />
</p>

### 3. CanlÄ± Salon Durum GÃ¶stergesi (Pulse Badges)
Her salonda o an toplantÄ± olup olmadÄ±ÄŸÄ±nÄ± gÃ¶steren canlÄ± nabÄ±z gÃ¶stergesi (`ğŸŸ¢ Åu An MÃ¼sait` veya `ğŸ”´ ToplantÄ± SÃ¼rÃ¼yor` ve kalan sÃ¼re bildirimi).
<p align="center">
  <img src="screenshots/03_homepage_live_rooms.png" width="95%" alt="CanlÄ± Salon Durum KartlarÄ±" />
</p>

### 4. Ä°nteraktif ToplantÄ± Takvimi (FullCalendar & SignalR)
Sayfa yenilemeden canlÄ± senkronize olan, salon ve akademik toplantÄ± tÃ¼rÃ¼ne gÃ¶re filtrelenebilen, sÃ¼rÃ¼kle-bÄ±rak destekli ajanda.
<p align="center">
  <img src="screenshots/04_calendar_agenda_view.png" width="95%" alt="Ä°nteraktif ToplantÄ± Takvimi" />
</p>

### 5. Yeni ToplantÄ± Rezervasyon Formu
Akademik toplantÄ± tÃ¼rÃ¼ seÃ§imi (Senato, Akademik Kurul, Tez SavunmasÄ±, BAP), katÄ±lÄ±mcÄ± davet listesi ve gÃ¼ndem aÃ§Ä±klamalarÄ± giriÅŸi.
<p align="center">
  <img src="screenshots/06_reservation_create.png" width="95%" alt="Yeni Rezervasyon Formu" />
</p>

### 6. KullanÄ±cÄ± RezervasyonlarÄ±m Listesi & ICS Ä°ndirme
KullanÄ±cÄ±nÄ±n aktif ve geÃ§miÅŸ toplantÄ±larÄ±nÄ± takip edebildiÄŸi, tek tÄ±kla dijital takvim dosyasÄ± (.ics) indirebildiÄŸi ve detay tutanaÄŸÄ±na ulaÅŸabildiÄŸi yÃ¶netim alanÄ±.
<p align="center">
  <img src="screenshots/05_reservations_list.png" width="95%" alt="ToplantÄ± RezervasyonlarÄ±m Listesi" />
</p>

### 7. GÃ¼venli GiriÅŸ, reCAPTCHA & Grafik GÃ¼venlik Kodu (Captcha)
Google reCAPTCHA ve dinamik Ã§izilen gÃ¼venlik koduyla brute-force ve bot ataklarÄ±na karÅŸÄ± korumalÄ± oturum aÃ§ma sayfasÄ±.
<p align="center">
  <img src="screenshots/07_login_recaptcha.png" width="95%" alt="GÃ¼venli GiriÅŸ & Captcha" />
</p>

### 8. YÃ¶netim Paneli â€” Dashboard & AylÄ±k Rezervasyon AnalitiÄŸi
YÃ¶neticiler iÃ§in anlÄ±k istatistikler, en Ã§ok kullanÄ±lan salon sÄ±ralamasÄ± ve Chart.js destekli aylÄ±k rezervasyon trend grafiÄŸi.
<p align="center">
  <img src="screenshots/08_admin_dashboard.png" width="95%" alt="YÃ¶netim Paneli Dashboard" />
</p>

### 9. YÃ¶netim Paneli â€” KullanÄ±cÄ± ve Rol YÃ¶netimi
Sistemdeki kullanÄ±cÄ±larÄ± listeleme, detaylarÄ±nÄ± inceleme ve tek tÄ±kla Admin / User rol atamasÄ± yapabilme ekranÄ±.
<p align="center">
  <img src="screenshots/09_admin_user_management.png" width="48%" alt="KullanÄ±cÄ± YÃ¶netimi" />
  <img src="screenshots/10_admin_role_edit.png" width="48%" alt="Rol GÃ¼ncelleme" />
</p>

### 10. YÃ¶netim Paneli â€” TÃ¼m RezervasyonlarÄ±n Denetimi
Ãœniversite genelinde aÃ§Ä±lan tÃ¼m toplantÄ±larÄ± onaylama, detaylarÄ±nÄ± gÃ¶rme, gerektiÄŸinde iptal etme veya silme ekranÄ±.
<p align="center">
  <img src="screenshots/11_admin_reservations.png" width="95%" alt="Rezervasyon YÃ¶netimi" />
</p>

---

## ğŸŒŸ Ã–ne Ã‡Ä±kan Fonksiyonel Ã–zellikler

- **ğŸ›ï¸ Kurumsal Renk Paleti:** Kastamonu Ãœniversitesi'nin kurumsal kimliÄŸi olan `#B22525` Bordo-KÄ±rmÄ±zÄ±, `#111111` Siyah ve `#FFFFFF` Beyaz uyumu.
- **ğŸŒ“ Koyu / AÃ§Ä±k Mod (Dark & Light Theme):** Tek tÄ±kla gece moduna geÃ§iÅŸ; tercih `localStorage` hafÄ±zasÄ±nda tutulur.
- **ğŸŸ¢ CanlÄ± Salon Durum Rozetleri:** AnlÄ±k mÃ¼saitlik tespiti, devam eden toplantÄ± adÄ± ve kalan sÃ¼re sayacÄ±.
- **ğŸ”„ SignalR ile CanlÄ± Senkronizasyon:** FarklÄ± bir kullanÄ±cÄ±nÄ±n eklediÄŸi veya gÃ¼ncellediÄŸi toplantÄ±, aÃ§Ä±k olan tÃ¼m takvimlerde sayfa yenilenmeden anÄ±nda belirir.
- **ğŸ–±ï¸ SÃ¼rÃ¼kle & BÄ±rak ile Saat GÃ¼ncelleme:** FullCalendar Ã¼zerinden toplantÄ± kutusu fareyle sÃ¼rÃ¼klenerek saati deÄŸiÅŸtirilebilir; Ã§akÄ±ÅŸma durumunda iÅŸlem otomatik geri alÄ±nÄ±r.
- **âš¡ 5 Saniyede HÄ±zlÄ± Rezervasyon:** Takvimde boÅŸ bir aralÄ±k taranarak sayfa deÄŸiÅŸtirmeden modal penceresinden hÄ±zlÄ± kayÄ±t aÃ§Ä±labilir.
- **ğŸ“º Salon KapÄ± EkranÄ± / Kiosk Tablet Modu (`/Room/DoorDisplay/{id}`):** Salon kapÄ±sÄ±na asÄ±lan tabletler iÃ§in bÃ¼yÃ¼k saat, durum rengi parlamasÄ± ve salona Ã¶zel dinamik QR kod.
- **ğŸ“ Akademik ToplantÄ± TÃ¼rleri:** Senato ToplantÄ±sÄ±, FakÃ¼lte/BÃ¶lÃ¼m Kurulu, Tez SavunmasÄ±, BAP ToplantÄ±sÄ±, Ã–ÄŸrenci KulÃ¼bÃ¼ ve Konferans/Seminer kategorileri.
- **ğŸ“… Ajanda & Takvim Entegrasyonu:** Google Calendar, Apple Calendar ve Microsoft Outlook (.ics) tam uyumluluÄŸu.
- **ğŸ“„ Resmi Tutanak ve Ã‡aÄŸrÄ± Ã‡Ä±ktÄ±sÄ±:** Tek tÄ±kla resmi Ã¼niversite formatÄ±nda katÄ±lÄ±m yoklama tutanaÄŸÄ± yazdÄ±rma (`window.print()`).

---

<br/><br/>

# ğŸ‡¬ğŸ‡§ English Documentation

## ğŸ“– About The Project
**Kastamonu University Meeting Room & Academic Agenda Management System** is an enterprise-grade, real-time web platform built to manage conference rooms, academic board meetings, real-time room occupancy, and smart door tablet kiosk displays across university faculties and departments.

Built with **ASP.NET Core 8 MVC**, **SignalR**, and **Entity Framework Core**, it provides a corporate Red-Black-White aesthetic matching Kastamonu University's brand guidelines, featuring complete Dark/Light mode support, live calendar synchronization, drag-and-drop scheduling, and printable official attendance minutes.

---

## ğŸš€ Key Features

- **ğŸ›ï¸ University Identity & Responsive Design:** Elegant Red (`#B22525`), Black (`#111111`), and White (`#FFFFFF`) color scheme.
- **ğŸŒ“ Dark / Light Mode Toggle:** Smooth CSS-variable driven theme switching persisted in `localStorage`.
- **ğŸŸ¢ Live Room Occupancy Badges:** Real-time pulse indicator showing whether a room is currently available (`ğŸŸ¢ Available`) or occupied (`ğŸ”´ Meeting in Progress` with remaining minutes).
- **ğŸ”„ Real-Time SignalR Synchronization:** Instant cross-client calendar updates upon reservation creation, modification, or cancellation without page reloads.
- **ğŸ–±ï¸ FullCalendar Drag-and-Drop & Slot Booking:** Drag-and-drop rescheduling with automatic backend conflict validation, plus 5-second quick modal booking.
- **ğŸ“º Door Display / Kiosk Tablet Mode (`/Room/DoorDisplay/{id}`):** Designed for tablet displays mounted outside meeting rooms; features a live digital clock, status glow, meeting progress bar, and dynamic QR code.
- **ğŸ“ Academic Categorization:** Dedicated categories for Senate Meetings, Faculty Boards, Thesis Defenses, Research Projects (BAP), Student Clubs, and Seminars.
- **ğŸ“… Universal Calendar Integration:** 1-click Google Calendar add-link, Microsoft Outlook / Office 365, and RFC 5545 iCalendar (`.ics`) file export.
- **ğŸ›¡ï¸ Enterprise Security:** ASP.NET Core Identity with Cookie security, Role-Based Access Control (Admin/User), Google reCAPTCHA v2/v3, and dynamic graphical captcha.
- **ğŸ“„ Printable Minutes of Meeting:** Formatted university attendance sheet ready for signing and printing (`window.print()`).

---

## ğŸ› ï¸ Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Backend Framework** | .NET 8.0 / C# 12 | Enterprise-grade, high-performance MVC foundation |
| **Architecture** | ASP.NET Core MVC | Model-View-Controller + Modular Areas (Admin) |
| **Real-Time Engine** | ASP.NET Core SignalR | WebSocket-based bidirectional live calendar synchronization |
| **Database & ORM** | Entity Framework Core 8/9 + MS SQL Server | Code-First, Connection Resiliency, Automatic Schema Patching |
| **Security & Auth** | ASP.NET Core Identity | Cookie hardening, Password Hashing, RBAC (Admin / User) |
| **Frontend UI** | Bootstrap 5.3 + Custom CSS3 | University Palette, CSS Variables, Responsive Layout |
| **Calendar Engine** | FullCalendar v6 | DayGrid, TimeGrid, Interaction (Drag/Drop/Select) |
| **Libraries & Plugins** | SweetAlert2, FontAwesome 6, QRious.js, iCal.NET | Dynamic alerts, vector icons, dynamic QR codes, ICS generator |

---

## ğŸ“ Project Structure

```bash
UniversityMeetingSystem/
â”‚
â”œâ”€â”€ Areas/
â”‚   â””â”€â”€ Admin/                     # Admin Portal (Dashboard, Room & User Management)
â”‚       â”œâ”€â”€ Controllers/
â”‚       â””â”€â”€ Views/
â”‚
â”œâ”€â”€ Controllers/
â”‚   â”œâ”€â”€ HomeController.cs          # Public dashboard, live occupancy stats & today's agenda
â”‚   â”œâ”€â”€ ReservationController.cs   # Booking workflow, FullCalendar API, SignalR & ICS export
â”‚   â””â”€â”€ RoomController.cs          # Room directory, equipment filtering & Kiosk Door Display
â”‚
â”œâ”€â”€ Data/
â”‚   â””â”€â”€ ApplicationDbContext.cs    # EF Core database context & relationships
â”‚
â”œâ”€â”€ Hubs/
â”‚   â””â”€â”€ CalendarHub.cs             # Real-time SignalR event broadcast hub
â”‚
â”œâ”€â”€ Models/
â”‚   â”œâ”€â”€ ApplicationUser.cs         # Extended Identity user model
â”‚   â”œâ”€â”€ Reservation.cs             # Booking model (MeetingType, Attendees, Schedule)
â”‚   â”œâ”€â”€ Room.cs                    # Room model (Amenities, Department, Live Status)
â”‚   â””â”€â”€ HomeDashboardViewModel.cs  # Unified view model for the home dashboard
â”‚
â”œâ”€â”€ Services/
â”‚   â”œâ”€â”€ CalendarIntegrationService.cs  # RFC 5545 iCalendar (.ics) & Google Calendar generator
â”‚   â””â”€â”€ SmtpEmailSender.cs             # Email invitation and notification service
â”‚
â”œâ”€â”€ Views/
â”‚   â”œâ”€â”€ Home/                      # Landing page, statistics & live room cards
â”‚   â”œâ”€â”€ Reservation/               # Interactive calendar, details, printable sign sheet
â”‚   â”œâ”€â”€ Room/                      # Room catalog, amenity badges, and Kiosk DoorDisplay
â”‚   â””â”€â”€ Shared/                    # Navigation bar, Dark Mode switcher, SignalR listener
â”‚
â”œâ”€â”€ screenshots/                   # High-resolution screenshots showcasing the project
â”œâ”€â”€ wwwroot/
â”‚   â”œâ”€â”€ css/site.css               # Corporate Red-White-Black theme & Dark Mode styles
â”‚   â””â”€â”€ js/site.js                 # SignalR client listener & theme persistence
â”‚
â”œâ”€â”€ Program.cs                     # Service registrations, SignalR hub routing, Seed Data
â””â”€â”€ README.md                      # Comprehensive dual-language documentation
```

---

## ğŸš€ Quick Start & Installation

### Prerequisites
- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Microsoft SQL Server](https://www.microsoft.com/sql-server/) (or SQL Server Express / LocalDB)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or [VS Code](https://code.visualstudio.com/)

### 1. Clone the Repository
```bash
git clone https://github.com/YusufKoc05/UniversityMeetingSystem.git
cd UniversityMeetingSystem/KastamonuMeetingRoom/KastamonuMeetingRoom
```

### 2. Configure Database Connection
Open `appsettings.json` and adjust the connection string to match your local SQL Server instance:
```json
"ConnectionStrings": {
  "DefaultConnection": "Server=localhost\\SQLEXPRESS;Database=MeetingRoomDB;Trusted_Connection=True;MultipleActiveResultSets=true;TrustServerCertificate=True"
}
```

### 3. Run the Application
The application will automatically perform schema migration and seed initial meeting rooms along with the default administrator account:
```bash
dotnet run
```
Or press **`F5`** inside Visual Studio / VS Code.

Navigate to:
- **Web App:** `https://localhost:7187` or `http://localhost:5044`

---

## ğŸ”‘ Default Administrator Credentials

Upon initial launch, the system automatically creates the admin account:
- **Email:** `admin@kastamonu.com`
- **Password:** `Admin123!`

---

## ğŸ“º Kiosk / Tablet Door Display Route

Mount a tablet outside each conference hall and navigate to:
```text
https://localhost:7187/Room/DoorDisplay/{RoomId}
```
*Examples:*
- **Senate Hall Kiosk:** `/Room/DoorDisplay/1`
- **Ahmet Yesevi Hall Kiosk:** `/Room/DoorDisplay/2`

> **Note:** The dynamic QR code on the kiosk screen allows passersby to scan with their mobile devices to instantly view the room's live schedule on their phones.

---

## ğŸ“„ License
This project is licensed under the [MIT License](LICENSE). You are free to adapt and customize it for educational or institutional use.

---

## ğŸ‘¨â€ğŸ’» Developer & Contact

**Yusuf KoÃ§**  
- **GitHub:** [@YusufKoc05](https://github.com/YusufKoc05)  
- **Repository:** [UniversityMeetingSystem](https://github.com/YusufKoc05/UniversityMeetingSystem)

<div align="center">
  <sub>Developed for Kastamonu University Department of Information Technology & Academic Units.</sub>
</div>

