```markdown
<div align="center">

# 📖 سامانه جامع قرآن کریم | Quran Pro (Material 3)

[![Version](https://img.shields.io/badge/Version-2.5.0-059669?style=for-the-badge&logo=semver&logoColor=white)](https://github.com)
[![Architecture](https://img.shields.io/badge/Architecture-Vanilla%20JS%20%7C%20CSS3-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com)
[![Design](https://img.shields.io/badge/Design-Material%20Design%203-4285F4?style=for-the-badge&logo=materialdesign&logoColor=white)](https://m3.material.io)
[![API](https://img.shields.io/badge/API-AlQuran%20Cloud-0284C7?style=for-the-badge&logo=cloud&logoColor=white)](https://alquran.cloud/api)
[![License: MIT](https://img.shields.io/badge/License-MIT-10B981?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)

<p align="center">
  <b>یک وب‌اپلیکیشن جامع، فوق‌سبک و بدون وابستگی (Zero-Dependency) برای قرائت، مطالعه تطبیقی تفاسیر و استماع ترتیل کلام‌الله مجید بر پایه زبان طراحی Google Material Design 3.</b>
</p>

[🌐 پیش‌نمایش زنده](#-دموی-آنلاین) •
[✨ ویژگی‌ها](#-ویژگی‌های-کلیدی) •
[📐 معماری و دیاگرام‌ها](#-معماری-فنی-و-دیاگرام‌های-سیستم) •
[🎙️ قاریان و قلم‌ها](#️-قاریان-و-قلم‌های-پشتیبانی‌شده) •
[🚀 نحوه راه‌اندازی](#-نحوه-راه‌اندازی-و-استفاده) •
[🤝 مشارکت](#-مشارکت-در-توسعه-contributing)

</div>

---

## 🌟 دموی آنلاین

> [!TIP]
> برای تجربه زنده و بدون نیاز به نصب، روی لینک زیر کلیک کنید:
> 
> 👉 **[مشاهده و اجرای پروژه در CodePen](https://codepen.io/editor/Silent-Galaxy/pen/01a192b0-cbd7-7082-8434-665dfe2d6fae)**

---

## 🖼️ گالری تصاویر

<div align="center">
  <table>
    <tr>
      <td width="50%"><img src="image.png" alt="نمای اصلی سامانه" /></td>
      <td width="50%"><img src="image-1.png" alt="پلیر و تنظیمات صوتی" /></td>
    </tr>
    <tr>
      <td width="50%"><img src="image-2.png" alt="مطالعه تطبیقی تفاسیر" /></td>
      <td width="50%"><img src="image-3.png" alt="پالت‌های رنگی و تم‌ها" /></td>
    </tr>
    <tr>
      <td colspan="2" align="center"><img src="image-4.png" alt="پنل تنظیمات فونت و تجوید" width="85%" /></td>
    </tr>
  </table>
</div>

---

## ✨ ویژگی‌های کلیدی

### 🔠 مطالعه تطبیقی چند ترجمه به صورت همزمان
- مشاهده موازی چند ترجمه معتبر زیر هر آیه (استاد انصاریان، مکارم شیرازی، فولادوند، الهی قمشه‌ای، بهرام‌پور، خرمشاهی و Saheeh International انگلیسی).
- امکان فعال یا غیرفعال‌سازی گزینشی هر ترجمه به تناسب نیاز کاربر.

### 🎨 رنگ‌آمیزی هوشمند علائم وقف و تجوید (Regex-Powered)
- شناسایی خودکار کدهای یونیکد علائم مصحف شریف بر پایه Regex:
  - **وقف لازم (مـ):** تفکیک بصری قرمز با برچسب هشدار
  - **وقف ممنوع (لا):** نشانه‌گذاری صورتی یاقوتی
  - **علامت سکته (س):** هایلایت بنفش اختصاصی
  - **شروع حزب و سجده:** برچسب فیروزه‌ای متمایز

### 🎧 موتور صوتی پیشرفته و رهگیری هوشمند خط
- **۳ حالت تلاوت:** تک‌آیه، سوره کامل و ختم پیوسته قرآن (انتقال خودکار بین سوره‌ها).
- **Auto-Scroll هوشمند:** حرکت نرم صفحه و مشخص کردن آیه جاری هماهنگ با صوت قاری.
- **کنترل صوتی درون‌برنامه‌ای:** اسلایدر تنظیم حجم صدا بدون وابستگی به کلیدهای سخت‌افزاری.
- دانلود مستقیم صوت هر آیه یا دانلود یکپارچه کل سوره.

### 🌙 سلامت چشم و بهینه‌سازی ارگونومیک
- حالت شب (Dark Mode) پیش‌فرض با رعایت دقیق کنتراست رنگی متریال ۳.
- اسلایدر کاهش نور نرم‌افزاری (Brightness Dimmer) برای مطالعه در تاریکی مطلق.
- ۸ پالت رنگی داینامیک: *زمردی، سرمه‌ای، طلایی، یاقوتی، بنفش، فیروزه‌ای و ...*

### ⚡ ذخیره‌سازی محلی و عملکرد بی‌نیاز از سرور
- ذخیره خودکار آخرین موقعیت مطالعه (Bookmark) و بازگشت آنی در مراجعات بعدی.
- داشبورد آماری داخلی برای پایش زمان مطالعه و تخمین حجم اینترنت مصرفی.

---

## 🛠 معماری و ساختار فنی

این سامانه به صورت **Single-File Application** پیاده‌سازی شده و نیازی به فرایند ساخت یا باندلر (`Webpack`, `Vite`, `npm build`) ندارد.

```text
quran-pro-material3/
├── index.html           # ساختار سمانتیک، لی‌آوت اصلی و دسترس‌پذیری (ARIA)
├── CSS (Embedded)       # متغیرهای CSS (:root)، توکن‌های Material Design 3 و رسپانسیو
└── JS (Embedded)        # مدیریت وضعیت (State)، کنترل DOM، موتور Audio و AlQuran API
```

### اصول مهندسی به‌کار رفته:
1. **Material Design 3 Tokens:** تغییر داینامیک رنگ‌ها و متغیرهای بصری بدون نیاز به بازنشانی DOM.
2. **REST API Integration:** دریافت بهینه‌سازی‌شده دسته‌های داده از سرویس `api.alquran.cloud`.
3. **Data Persistence:** ذخیره‌سازی داده‌های سشن، تنظیمات شخصی‌سازی و بوکمارک در `localStorage`.
4. **Unicode Regex Engine:** پارس متون و اعراب‌گذاری علائم عثمان‌طه:
   ```javascript
   text.replace(/([\u06D8])/g, '<span class="quran-mark mark-lazim">$1</span>');
   ```

---

## 📐 معماری فنی و دیاگرام‌های سیستم

<details open>
<summary><b>۱. دیاگرام معماری کلان (System Architecture)</b></summary>
<br>

نمای ارتباطی میان کلاینت، APIهای خارجی، شبکه توزیع محتوا (CDN) و حافظه محلی مرورگر:

<p align="center">
  <img src="image-5.png" alt="System Architecture Diagram" width="90%" />
</p>

<details>
<summary>نمایش کد منبع PlantUML</summary>

```plantuml
@startuml
!theme vibrant
title دیاگرام معماری کلان و بسترهای ارتباطی (Quran Pro M3)

actor "کاربر نهایی" as User
package "مرورگر کاربر (Client Browser)" {
    component [Single-File Application\n(index.html)] as App
    database "LocalStorage\n(تنظیمات، نشانک، تاریخچه)" as Storage
    node "Audio Engine\n(HTML5 Audio API)" as AudioAPI
}

cloud "شبکه‌های توزیع محتوا (CDNs)" {
    [Google Fonts\n(Amiri, Vazir, Noto, ...)] as Fonts
    [FontAwesome CDN\n(Icons)] as Icons
}

cloud "زیرساخت‌های خارجی (APIs)" {
    [AlQuran Cloud REST API\n(متون، ترجمه‌ها و ابرداده)] as QuranAPI
    [Islamic Network CDN\n(استریم فایل‌های صوتی MP3)] as AudioCDN
}

User --> App : تعامل کاربری / ورودی‌ها
App <--> Storage : همگام‌سازی وضعیت (State Sync)
App --> Fonts : دریافت فونت‌های وب
App --> Icons : دریافت آیکون‌های وکتور
App --> QuranAPI : درخواست دسته‌ای داده سوره‌ها
App --> AudioAPI : فرمان پخش، ولوم و توقف
AudioAPI --> AudioCDN : استریم صوت قاریان
@enduml
```
</details>
</details>

---

<details open>
<summary><b>۲. دیاگرام توالی واکشی و رندر داده (Sequence Diagram)</b></summary>
<br>

چرخه بارگذاری سوره، تفکیک ترجمه‌ها، پردازش اعراب و به‌روزرسانی DOM:

<p align="center">
  <img src="image-6.png" alt="Sequence Diagram" width="90%" />
</p>

<details>
<summary>نمایش کد منبع PlantUML</summary>

```plantuml
@startuml
!theme crt-green
autonumber
title توالی دریافت داده و رندر همزمان متون و صوت

actor "کاربر" as User
participant "رابط کاربری (UI)" as UI
participant "هسته منطقی (JS Logic)" as Logic
participant "سرویس AlQuran API" as API
participant "حافظه محلی (Storage)" as DB

User -> UI : انتخاب سوره جدید (یا کلیک بعدی/قبلی)
UI -> Logic : فراخوانی loadSurah(surahId)
activate Logic

Logic -> UI : نمایش لودر انیمیشنی (showLoader)
Logic -> Logic : ترکیب شناسه‌های ترجمه و قاری فعال

Logic -> API : GET /surah/{id}/editions/quran-uthmani,{trans},{qari}
activate API
API --> Logic : بازگشت پکیج تجمیعی JSON
deactivate API

Logic -> Logic : تفکیک داده متن اصلی، صوت و آرایه ترجمه‌ها
Logic -> Logic : اجرای تابع formatArabicWithColoredSymbols()
Logic -> DB : ذخیره نشانک (Save Bookmark)
Logic -> UI : رندر کارت‌های آیات (renderAyahs)
Logic -> UI : به‌روزرسانی کارت معرف سوره (Banner Card)
Logic -> UI : مخفی‌سازی لودر
deactivate Logic

UI --> User : نمایش آیات، هایلایت خط اول و آماده‌سازی پلیر
@enduml
```
</details>
</details>

---

<details open>
<summary><b>۳. ماشین وضعیت پلیر صوتی (Audio State Machine)</b></summary>
<br>

مدیریت رویدادهای پخش در سه حالت تلاوت (تک‌آیه، کل سوره و ختم پیوسته):

<p align="center">
  <img src="image-7.png" alt="Audio State Machine" width="90%" />
</p>

<details>
<summary>نمایش کد منبع PlantUML</summary>

```plantuml
@startuml
!theme materia
title ماشین وضعیت پخش صوت و هدایت خودکار خط

[*] --> متوقف : لود اولیه سوره

state متوقف {
  متوقف : audio.paused = true
  متوقف : دکمه Play فعال است
}

state در_حال_پخش {
  در_حال_پخش : audio.play()
  در_حال_پخش : آیه جاری هایلایت می‌شود
  در_حال_پخش : اسکرول نرم به مرکز صفحه (Auto-Scroll)
}

state تصمیم_گیری_پایان_آیه <<choice>>

متوقف --> در_حال_پخش : کلیک Play / کلیک آیکون پخش آیه
در_حال_پخش --> متوقف : کلیک Pause / کلیک Stop

در_حال_پخش --> تصمیم_گیری_پایان_آیه : رخداد ended (اتمام صوت آیه)

تصمیم_گیری_پایان_آیه --> متوقف : اگر مود == 'single'
تصمیم_گیری_پایان_آیه --> در_حال_پخش : اگر هنوز در سوره آیه مانده (آیه بعد)
تصمیم_گیری_پایان_آیه --> بارگذاری_سوره_بعد : مود == 'khatm' و انتهای سوره
تصمیم_گیری_پایان_آیه --> متوقف : مود == 'surah' و انتهای سوره

state بارگذاری_سوره_بعد {
  بارگذاری_سوره_بعد : loadSurah(current + 1)
}
بارگذاری_سوره_بعد --> در_حال_پخش : شروع آیه اول سوره جدید
@enduml
```
</details>
</details>

---

<details open>
<summary><b>۴. پایپ‌لاین پردازش علائم تجوید و وقف (Data Pipeline)</b></summary>
<br>

جریان تبدیل یونیکدهای خام استاندارد عثمان‌طه به عناصر تعاملی و برچسب‌های رنگی:

<p align="center">
  <img src="image-8.png" alt="Tanjweed Pipeline Diagram" width="90%" />
</p>

<details>
<summary>نمایش کد منبع PlantUML</summary>

```plantuml
@startuml
!theme lightgray
title پایپ‌لاین تبدیل یونیکدهای تجوید به المان‌های غنی بصری

|متن خام از سرور|
start
:دریافت رشته عربی Uthmani;
note right: شامل کاراکترهای اعراب و علائم استاندارد

|موتور پردازش رگولار اکسپرشن|
:بررسی کد [\u06D6\u06D7\u06DA\u06DB];
:برچسب‌گذاری: وقف جایز، صلی، قلی (رنگ طلایی);

:بررسی کد [\u06D8];
:برچسب‌گذاری: وقف لازم - مـ (رنگ قرمز هشدار);

:بررسی کد [\u06D9];
:برچسب‌گذاری: وقف ممنوع - لا (رنگ صورتی);

:بررسی کد [\u06DC];
:برچسب‌گذاری: علامت سکته (رنگ بنفش);

:بررسی کد [\u06DE و \u06E9];
:برچسب‌گذاری: علامت شروع حزب و سجده (فیروزه‌ای);

|خروجی سند DOM|
:تولید تگ <span class="quran-mark ...">;
:اعمال انیمیشن Hover و نمایش Tooltip فارسی;
stop
@enduml
```
</details>
</details>

---

<details open>
<summary><b>۵. مدل داده وضعیت برنامه (State & Storage Model)</b></summary>
<br>

ساختار متمرکز آبجکت‌های نگه‌داری داده و تنظیمات در `APP_STATE`:

<p align="center">
  <img src="image-9.png" alt="Class Diagram" width="80%" />
</p>

<details>
<summary>نمایش کد منبع PlantUML</summary>

```plantuml
@startuml
!theme plain
title ساختار مدل وضعیت مرکزی (APP_STATE Model)

class APP_STATE {
    +int currentSurah
    +int currentAyahIndex
    +String playMode [single | surah | khatm]
    +String qari
    +String theme
    +Boolean showTranslation
    +Array<String> selectedTranslations
    +String arabicFont
    +String transFont
    +int arabicSize
    +int transSize
    +float volume
    +Boolean autoScroll
    +int totalAyahsRead
    +int downloadedBytes
    +Bookmark lastReadBookmark
}

class Bookmark {
    +int surah
    +int ayah
}

class AyahData {
    +int numberInSurah
    +String text
    +String audioUrl
    +Array<TranslationItem> translations
}

class TranslationItem {
    +String id
    +String translatorName
    +String dir [rtl | ltr]
    +String text
}

APP_STATE *-- Bookmark
APP_STATE o-- AyahData
AyahData *-- TranslationItem
@enduml
```
</details>
</details>

---

<details open>
<summary><b>۶. ساختار درختی اجزای رابط کاربری (UI Component Hierarchy)</b></summary>
<br>

سلسله‌مراتب المان‌های صفحه، لایه‌ها و مودال‌های کنترلی:

<p align="center">
  <img src="image-10.png" alt="UI Component Hierarchy" width="90%" />
</p>

<details>
<summary>نمایش کد منبع PlantUML</summary>

```plantuml
@startuml
!theme cerulean
title ساختار درختی و دسته‌بندی اجزای رابط کاربری (UI Hierarchy)

package "نمای اصلی (DOM Viewport)" {
    [Brightness Overlay\n(لایه کاهش نور)] 
    
    package "Header (هدر چسبان)" {
        [دکمه منوی سوره‌ها]
        [نام سوره جاری]
        [دکمه تنظیمات]
        [دکمه آمار]
    }

    package "Main Content (کانتینر مطالعه)" {
        [نوار ناوبری سریع (قبلی / بعدی / بوکمارک)]
        [بنر مشخصات سوره (مکی/مدنی، جزء)]
        folder "لیست کارت آیات" {
            [هدر کارت (شماره، پلی، دانلود)]
            [متن عربی رنگ‌آمیزی‌شده]
            [کانتینر مقایسه موازی ترجمه‌ها]
        }
    }

    package "Floating Bottom Player (پلیر شناور)" {
        [سلکتور مود پخش (تک‌آیه / سوره / ختم)]
        [اسلایدر ولوم و کلید Mute]
        [کنترل‌های جابه‌جایی و پلی/پاز]
        [دکمه دانلود کل سوره و سوییچ اسکرول]
    }
}

package "کشوی جانبی و مودال‌ها (Drawers & Modals)" {
    [کشوی فهرست ۱۱۴ سوره + جستجوگر زنده]
    [مودال تنظیمات جامع (فونت، سایز، تم، ترجمه‌ها)]
    [مودال گزارش آمار و مصرف ترافیک]
}
@enduml
```
</details>
</details>

---

<details open>
<summary><b>۷. جریان تجربه و سفر کاربر (User Journey)</b></summary>
<br>

سناریوهای تعاملی کاربر از ورود تا شخصی‌سازی، پخش صوت و نشانه‌گذاری:

<p align="center">
  <img src="image-11.png" alt="User Journey Diagram" width="90%" />
</p>

<details>
<summary>نمایش کد منبع PlantUML</summary>

```plantuml
@startuml
!theme amiga
title دیاگرام تجربه و سناریوهای کاربری (User Journey)

start
:ورود به وب‌اپلیکیشن;
:اعمال تم تاریک پیش‌فرض و بازیابی نشانک از حافظه;

if (آیا کاربر مایل به ادامه مطالعه قبلی است؟) then (بله)
    :کلیک روی چیپ «ادامه آخرین قرائت»;
    :هدایت خودکار به سوره و آیه نشانه‌گذاری‌شده;
else (خیر)
    :انتخاب سوره از کشو یا استفاده از دکمه‌های ناوبری سریع;
endif

fork
    :مطالعه متن عربی همراه با نشانه‌های رنگی وقف;
fork again
    :مقایسه همزمان تفاسیر و ترجمه‌های منتخب;
fork again
    :فعال‌سازی پلیر صوتی (ترتیل قاری منتخب);
    :فعال بودن Auto-Scroll برای دنبال کردن خودکار خط;
fork again
    :شخصی‌سازی محیط (اندازه قلم، فونت عثمان‌طه، نور صفحه);
end fork

:توقف مطالعه یا خروج از صفحه;
:ذخیره خودکار موقعیت آیه در LocalStorage;
stop
@enduml
```
</details>
</details>

---

## 🎙️ قاریان و قلم‌های پشتیبانی‌شده

| قلم‌های قرآنی و متنی | قاریان برجسته جهان اسلام |
| :--- | :--- |
| • **امیری قرآنی** (Amiri Quran - مصحف مدینه) | • **مشاری راشد العفاسی** |
| • **شهرزاد نسخ** (Scheherazade New) | • **عبدالباسط عبدالصمد** (مجود) |
| • **نوتو نسخ عربی** (Noto Naskh Arabic) | • **محمد صدیق منشاوی** |
| • **وزیرمتن** (Vazirmatn) | • **سعود الشریم** |
| • **لطیف** (Lateef) | • **شهریار پرهیزگار** (آموزشی) |

---

## 🚀 نحوه راه‌اندازی و استفاده

برای اجرای این سامانه به نصب هیچ‌گونه ابزار پیش‌نیاز یا کتابخانه سنگین نیاز ندارید.

### روش اول: اجرای مستقیم (سریع‌ترین حالت)
1. مخزن را کلون کنید:
   ```bash
   git clone https://github.com/YOUR_USERNAME/quran-pro-material3.git
   cd quran-pro-material3
   ```
2. فایل `index.html` را در هر مرورگر به‌روز (کروم، فایرفاکس، اج، سافاری) باز کنید.

### روش دوم: اجرای Local Server (پیشنهادی برای شبیه‌سازی PWA)
با استفاده از وب‌سرور داخلی پایتون:
```bash
# Python 3
python -m http.server 8000
```
سپس آدرس `http://localhost:8000` را در مرورگر باز کنید.

---

## 🤝 مشارکت در توسعه (Contributing)

مشارکت در توسعه و بهینه‌سازی این پروژه مورد استقبال است:

1. پروژه را **Fork** کنید.
2. یک شاخه جدید بسازید (`git checkout -b feature/NewFeature`).
3. تغییرات خود را ثبت (Commit) کنید (`git commit -m 'feat: Add NewFeature'`).
4. تغییرات را ارسال کنید (`git push origin feature/NewFeature`).
5. یک **Pull Request** ایجاد کنید.

---

## 📄 مجوز و لایسنس

این پروژه تحت مجوز متن‌باز **[MIT License](LICENSE)** منتشر شده است. استفاده تجاری و غیرتجاری، تغییر و بازنشر آن آزاد و بلامانع است.

<div align="center">
  <sub>با آرزوی بهره‌مندی و آرامش در تلاوت کلام وحی ✨</sub>
</div>
```