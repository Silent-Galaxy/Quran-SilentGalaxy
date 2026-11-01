```markdown
<div dir="rtl">

# 📖 سامانه جامع قرآن کریم | Quran Pro (Material 3)

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.5.0-006c4c?style=for-the-badge" alt="Version" />
  <img src="https://img.shields.io/badge/Architecture-Vanilla%20JS%20%7C%20CSS3-f7df1e?style=for-the-badge&logo=javascript&logoColor=black" alt="Stack" />
  <img src="https://img.shields.io/badge/Design-Material%20Design%203-4285f4?style=for-the-badge&logo=materialdesign&logoColor=white" alt="Design" />
  <img src="https://img.shields.io/badge/API-AlQuran%20Cloud-00bcd4?style=for-the-badge&logo=cloud&logoColor=white" alt="API" />
  <img src="https://img.shields.io/badge/License-MIT-success?style=for-the-badge" alt="License" />
</p>

<p align="center">
  <b>یک وب‌اپلیکیشن جامع، فوق‌سبک و بدون وابستگی (Zero-Dependency) برای قرائت، مطالعه تطبیقی تفاسیر، و استماع ترتیل کلام‌الله مجید بر پایه زبان طراحی مدرن Material Design 3 گوگل.</b>
</p>

<p align="center">
  <a href="#-دموی-آنلاین">مشاهده دمو</a> •
  <a href="#-گالری-تصاویر">تصاویر رابط کاربری</a> •
  <a href="#-ویژگی‌های-کلیدی">ویژگی‌ها</a> •
  <a href="#-معماری-و-ساختار-فنی">معماری فنی</a> •
  <a href="#-قاریان-و-قلم‌های-پشتیبانی‌شده">قاریان و فونت‌ها</a> •
  <a href="#-نحوه-اجرا-و-استفاده">راه‌اندازی</a> •
  <a href="#-دیاگرام‌های-فنی-و-معماری-سیستم-plantuml">دیاگرام‌های مهندسی</a>
</p>

---

## 🌟 دموی آنلاین

شما می‌توانید پیش‌نمایش زنده این سامانه را مستقیماً در بستر آنلاین مشاهده فرمایید:

👉 **[مشاهده دمو در CodePen](https://codepen.io/editor/Silent-Galaxy/pen/01a192b0-cbd7-7082-8434-665dfe2d6fae)**

> [!TIP]
> این برنامه بدون نیاز به هیچ‌گونه نصب یا بیلد (Zero-Build) مستقیماً روی تمام مرورگرهای دسکتاپ و موبایل اجرا می‌شود.

---

## 🖼 گالری تصاویر

<table align="center" width="100%">
  <tr>
    <td align="center" width="50%">
      <img src="image.png" alt="نمای اصلی و کارت آیات" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); width:100%;" />
      <br><sub><b>نمای اصلی و متن آیات همراه با ترجمه</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="image-1.png" alt="کشوی انتخاب سوره و جستجو" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); width:100%;" />
      <br><sub><b>کشوی فهرست ۱۱۴ سوره و جستجوی لحظه‌ای</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="image-2.png" alt="مود تاریک و پنل تنظیمات" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); width:100%;" />
      <br><sub><b>پنل تنظیمات فونت، تم‌ها و ترجمه‌ها</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="image-3.png" alt="مطالعه تطبیقی چند ترجمه" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); width:100%;" />
      <br><sub><b>مطالعه تطبیقی همزمان چند ترجمه</b></sub>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="image-4.png" alt="پلیر صوتی و دنبال‌کننده خط" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); width:75%;" />
      <br><sub><b>پلیر صوتی شناور با قابلیت تنظیم سرعت و ولوم</b></sub>
    </td>
  </tr>
</table>

---

## ✨ ویژگی‌های کلیدی

### 🔠 مطالعه تطبیقی چند ترجمه به صورت همزمان
- مشاهده موازی چند ترجمه معتبر زیر هر آیه:
  - استاد حسین انصاریان
  - آیت‌الله مکارم شیرازی
  - دکتر محمد مهدی فولادوند
  - مهدی الهی قمشه‌ای
  - ابوالفضل بهرام‌پور
  - بهاءالدین خرمشاهی
  - Saheeh International (انگلیسی)
- امکان فعال یا غیرفعال‌سازی تک‌تک ترجمه‌ها طبق نیاز پژوهشگر.

### 🎨 رنگ‌آمیزی هوشمند علائم وقف و تجوید (Regex-Powered)
تشخیص و استایل‌دهی هوشمند بر اساس استانداردهای یونیکد رسم‌الخط عثمان طه:
- 🔴 **وقف لازم (مـ):** قرمز هشداردهنده
- 🌸 **وقف ممنوع (لا):** صورتی یاقوتی
- 🟣 **سکته:** بنفش اختصاصی
- 🟡 **وقف جایز (ج، قلی، صلی):** طلایی چشم‌نواز
- 🔷 **علامت حزب و سجده واجب:** نشانه‌گذاری متمایز فیروزه‌ای

### 🎧 پلیر پیشرفته صوتی و دنبال‌کننده تلاوت
- **۳ حالت تلاوت هوشمند:**
  1. *تک‌آیه:* توقف پس از پایان آیه جاری
  2. *سوره کامل:* پخش ترتیل تا انتهای سوره
  3. *ختم پیوسته:* ادامه خودکار تلاوت و بارگذاری سوره‌های بعدی بدون وقفه
- **Auto-Scroll هوشمند:** هدایت نرم صفحه و هایلایت بصری همزمان با صدای قاری.
- **کنترل بلندی صدا (Volume Slider):** تنظیم ولوم از داخل رابط بدون نیاز به کلیدهای فیزیکی دستگاه.
- امکان دانلود تکی صوت هر آیه یا صف دانلود تمام سوره.

### 🌙 سلامت چشم و تم‌های چندگانه
- حالت شب (Dark Mode) پیش‌فرض و ارگونومیک جهت جلوگیری از خستگی چشم.
- اسلایدر نرم‌افزاری کاهش نور صفحه برای مطالعه در تاریکی مطلق (Brightness Dimmer).
- **۸ پالت رنگی داینامیک:** *زمردی، سرمه‌ای، طلایی، یاقوتی، بنفش، فیروزه‌ای، زیتونی و کهربایی*.

### ⚡ ذخیره‌سازی ابری و عملکرد بدون نیاز به سرور
- ثبت خودکار آخرین آیه خوانده شده (Bookmark) و پرش سریع به آن در مراجعات بعدی.
- سیستم آمار داخلی جهت محاسبه زمان مطالعه و تخمین حجم اینترنت مصرفی.

---

## 🛠 معماری و ساختار فنی

این نرم‌افزار به صورت **Single-File Application** طراحی شده و نیازی به هیچ مرحله کامپایل (`npm build`, `webpack`, `vite`) ندارد.

```text
quran-pro-material3/
├── index.html       # شامل تگ‌های سمانتیک، لایوت اصلی و ساختار دسترسی‌پذیری
├── CSS (Embedded)   # توکن‌های متریال ۳، متغیرهای CSS (:root)، مدیاکوئری‌های ریسپانسیو
└── JS (Embedded)    # مدیریت وضعیت (APP_STATE)، تعامل با API، کنترل رویدادهای Audio و DOM
```

### استانداردهای به‌کار رفته:
1. **Material Design 3 Tokenization:** تعویض آنی رنگ‌بندی با تغییر متغیرهای پویا بدون رندر مجدد DOM.
2. **RESTful API Consumption:** واکشی دینامیک بسته‌های سوره‌ها از سرویس مرجع `api.alquran.cloud`.
3. **Data Persistence:** نگه‌داری اطلاعات سشن، تنظیمات و نشانک در `Window.localStorage`.
4. **Regular Expression Parsing:** پردازش رشته‌های حاوی نمادهای عثمان‌طه بر پایه استانداردهای یونیکد زبان عربی:
   ```javascript
   text.replace(/([\u06D8])/g, '<span class="quran-mark mark-lazim">$1</span>');
   ```

---

## 🎙️ قاریان و قلم‌های پشتیبانی‌شده

| فونت‌های قرآنی و متنی | قاریان برجسته جهان اسلام |
| :--- | :--- |
| • **امیری قرآنی** (Amiri Quran - عثمان طه) | • **مشاری راشد العفاسی** |
| • **شهرزاد نسخ** (Scheherazade New) | • **عبدالباسط عبدالصمد** (مجود) |
| • **نوتو نسخ گوگل** (Noto Naskh Arabic) | • **محمد صدیق منشاوی** |
| • **وزیرمتن** (Vazirmatn) | • **سعود الشریم** |
| • **لطیف** (Lateef) | • **شهریار پرهیزگار** (تلاوت آموزشی) |

---

## 🚀 نحوه اجرا و استفاده

برای اجرای این پروژه روی سیستم خود تنها به یک مرورگر مدرن نیاز دارید:

```bash
# ۱. کلون کردن مخزن
git clone https://github.com/YOUR_USERNAME/quran-pro-material3.git

# ۲. ورود به پوشه پروژه
cd quran-pro-material3

# ۳. اجرای فایل index.html (دوبار کلیک روی فایل یا باز کردن در مرورگر)
```

یا با استفاده از سرور محلی پایتون:
```bash
python3 -m http.server 8000
```
سپس آدرس `http://localhost:8000` را در مرورگر باز کنید.

---

## 📐 دیاگرام‌های فنی و معماری سیستم (PlantUML)

این دیاگرام‌ها زوایای مختلف معماری (ارتباطات سیستم، چرخه داده، ماشین وضعیت صوتی، پایپ‌لاین پردازش تجوید، ساختار کامپوننت‌ها و سفر کاربر) را پوشش می‌دهند.

> [!NOTE]
> کدهای هر بخش را می‌توانید مستقیماً در **[ادیتور آنلاین PlantUML](https://editor.plantuml.com/)** کپی و مشاهده فرمایید.

---

### ۱. دیاگرام معماری کلان سامانه (System Architecture Diagram)
> **هدف:** درک رابطه برنامه تک‌صفحه‌ای (Client-Side) با سرویس‌های ابری، شبکه CDN و حافظه محلی مرورگر.

<p align="center">
  <img src="image-5.png" alt="معماری کلان سیستم" width="85%" />
</p>

<details>
<summary><b>🔍 مشاهده سورس کد PlantUML</b></summary>

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

---

### ۲. دیاگرام توالی بارگذاری سوره و ترجمه‌ها (Sequence Diagram)
> **هدف:** نمایش دقیق ترتیبات رویدادها از زمان انتخاب یک سوره تا پردازش، استخراج ترجمه‌ها و رندرینگ کارت‌ها روی صفحه.

<p align="center">
  <img src="image-6.png" alt="توالی بارگذاری سوره و ترجمه‌ها" width="85%" />
</p>

<details>
<summary><b>🔍 مشاهده سورس کد PlantUML</b></summary>

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

---

### ۳. دیاگرام ماشین وضعیت پلیر صوتی (Audio State Machine)
> **هدف:** تشریح چگونگی مدیریت پخش پیوسته، رفتار پایان هر آیه بر اساس ۳ مود (تک‌آیه، سوره، ختم پیوسته)، و هماهنگی اسکرول خودکار.

<p align="center">
  <img src="image-7.png" alt="ماشین وضعیت پلیر صوتی" width="85%" />
</p>

<details>
<summary><b>🔍 مشاهده سورس کد PlantUML</b></summary>

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

---

### ۴. خط لوله پردازش علائم تجوید و وقف (Data Pipeline Diagram)
> **هدف:** بررسی زیرکاپوت نحوه تبدیل متون خام عثمان‌طه حاوی کدهای نامرئی یونیکد به المان‌های بصری غنی و رنگی.

<p align="center">
  <img src="image-8.png" alt="پایپ لاین پردازش تجوید" width="85%" />
</p>

<details>
<summary><b>🔍 مشاهده سورس کد PlantUML</b></summary>

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

---

### ۵. ساختار مدل داده وضعیت برنامه (State & Storage Class Diagram)
> **هدف:** نمایش شکل داده‌های متمرکز در `APP_STATE` و نحوه نگه‌داری ساختاریافته آبجکت‌ها درون حافظه.

<p align="center">
  <img src="image-9.png" alt="مدل وضعیت برنامه" width="85%" />
</p>

<details>
<summary><b>🔍 مشاهده سورس کد PlantUML</b></summary>

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

---

### ۶. نقشه درختی اجزای رابط کاربری (Component Hierarchy Diagram)
> **هدف:** تفکیک ماژولار تمامی پنل‌ها، المان‌های شناور و پنجره‌های پاپ‌آپ داخل ساختار صفحه.

<p align="center">
  <img src="image-10.png" alt="ساختار کامپوننت‌های رابط کاربری" width="85%" />
</p>

<details>
<summary><b>🔍 مشاهده سورس کد PlantUML</b></summary>

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

---

### ۷. دیاگرام سفر و جریان کاربری (User Journey Activity Diagram)
> **هدف:** توصیف تمام مسیرهایی که یک مخاطب (از ورود، تغییر شخصی‌سازی، تا مطالعه و ختم) می‌تواند در سامانه طی کند.

<p align="center">
  <img src="image-11.png" alt="دیاگرام سفر کاربری" width="85%" />
</p>

<details>
<summary><b>🔍 مشاهده سورس کد PlantUML</b></summary>

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

---

## 🤝 مشارکت در توسعه (Contributing)

پیشنهادات، گزارش باگ‌ها و افزودن ترجمه‌ها یا قابلیت‌های جدید صمیمانه استقبال می‌شود:

1. این ریپازیتوری را Fork کنید.
2. یک شاخه (Branch) برای قابلیت جدید بسازید:
   ```bash
   git checkout -b feature/NewAwesomeFeature
   ```
3. تغییرات خود را Commit کنید:
   ```bash
   git commit -m 'feat: Add NewAwesomeFeature'
   ```
4. شاخه خود را Push کنید:
   ```bash
   git push origin feature/NewAwesomeFeature
   ```
5. یک Pull Request ارسال کنید.

---

## 📄 لایسنس

این پروژه تحت مجوز **MIT** منتشر شده است. استفاده، بازنشر و شخصی‌سازی آن برای تمامی اهداف غیرتجاری و تجاری کاملاً آزاد و رایگان است.

<p align="center">
  <b>با آرزوی بهره‌مندی و آرامش در تلاوت کلام وحی ✨</b>
</p>

</div>
```