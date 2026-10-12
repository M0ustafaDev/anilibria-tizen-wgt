

# 🎌 AniLiberty — AniLibria Client

> Unofficial [AniLibria](https://anilibria.tv) client for **Samsung Smart TV (Tizen)**, **PC**, and **mobile devices**

<img width="128" height="128" alt="icon" src="https://github.com/user-attachments/assets/407c0839-b1e4-42c7-866f-8ce6797173e3" />

[![Release](https://img.shields.io/github/v/release/CoreDip/anilibria-tizen-wgt?label=latest+version&color=red)](https://github.com/CoreDip/anilibria-tizen-wgt/releases/latest)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## ⬇️ Download / Open

| Platform | |
|-----------|---|
| 📦 **Samsung TV (.wgt)** | [Download AniLiberty.wgt →](https://github.com/CoreDip/anilibria-tizen-wgt/releases/latest) |
| 🌐 **Browser / PC / Phone** | [https://coredip.github.io/anilibria-tizen-wgt/ →](https://coredip.github.io/anilibria-tizen-wgt/) |
| 📺 **MediaStationX** | `anilibria-tizen-wgt.dipcoremail.workers.dev` |

---

## 📺 Installation

### Option 1 — Developer Mode (Tizen)
1. On the TV: **Settings → General → System Manager → Developer Mode** → enter the PC IP
2. Restart the TV
3. In Tizen Studio: `Run As → Tizen Web Application` or install the `.wgt` via `Package Manager`

### Option 2 — MediaStationX
1. Open MediaStationX on the TV
2. Add the URL: `anilibria-tizen-wgt.dipcoremail.workers.dev`

### Option 3 — PC / Tablet / Browser / Phone
Just open [https://coredip.github.io/anilibria-tizen-wgt/](https://coredip.github.io/anilibria-tizen-wgt/) — the adaptive interface adjusts itself to the screen

### Option 4 — Android Tablet / Phone
[![Release](https://img.shields.io/github/v/release/CoreDip/anilibria-tizen-wgt?label=latest+version&color=red)](https://github.com/CoreDip/anilibria-tizen-wgt/releases/latest)

---

---

## 📸 Screenshots

![main](https://github.com/user-attachments/assets/e6cde226-fbb3-4a8c-8aee-735f3621fdac)
![anipage](https://github.com/user-attachments/assets/b930a04a-30d3-42f2-a484-f17a1a865517)
![collections](https://github.com/user-attachments/assets/d1ae2dd7-ff49-4937-9ac8-578e03556f11)
![player](https://github.com/user-attachments/assets/8a2510ba-41b0-485e-a948-2229a3d384e2)

---

## ✨ Features

**🏠 Home**
- Rows: new episodes, ongoing series, popular, top rated, by genre
- Watch progress bar directly on the card
- Lazy loading of rows while scrolling
- Context menu on cards (long press / right click)

**🔍 Catalog**
- Search by title
- Filters: genre, year, season, type, release status, voice acting status, age rating, sorting
- On mobile — filters in a bottom sheet
- Infinite loading of results
- Scroll position restoration when returning from the anime page

**📅 Schedule**
- Episode releases by day of the week with posters
- On mobile — vertical list with horizontal day scrolling

**📂 Collections**
- Tabs: Favorite, Watching, Planned, Watched, Dropped, History
- Collection badges on cards — anime status is visible (❤ / 👁 / 📅 / ✔ / ✖) without opening the page
- Progress bars are shown in collections immediately, without opening each anime
- When marked as “Watched”, all episodes are automatically marked as watched
- Add and remove via context menu or anime page
- Remove from history, reset progress

**▶️ Player**
- HLS streaming (native on Tizen, hls.js on other devices)
- Quality selection: 480p / 720p / 1080p
- “⏩ Skip Opening” button — appears automatically and skips in one click
- “⏭ Next Episode” button — appears during the ending, no need to wait for credits
- Fast rewind with long-pressed arrow (5s → 10s → 30s)
- Scrubbing through the timeline
- Auto-transition to the next episode
- Switch aspect ratio mode: fit frame / fill screen
- Fullscreen button (PC and mobile)
- “Back” button in the upper-left corner

**💾 Progress and Sync**
- Auto-save every 8 seconds
- Full two-way synchronization with the AniLibria account
- Local progress migration to the cloud upon login
- Background sync of collections and history every 2 minutes
- “Continue” button from the exact stop point
- Resetting progress deletes data immediately both locally and in the cloud
- Long press on an episode button — remove watched status (mouse, touch, remote control)
- When marking episodes as watched, the progress is synchronized with the server

**👤 Account**
- Login with username and password
- Synchronization of collections and history with the server
- Profile with logout button

**🎮 Remote Control (Samsung Tizen)**
- Full navigation using arrows without a mouse
- Back button — step back in the hierarchy
- Double press Back — app exit menu
- Long press OK on a card — context menu
- Long press OK on an episode — remove watched status
- Support for colored buttons (catalog, schedule, collections)

**🖱️ PC (mouse)**
- Hover, click, right mouse button — context menu
- Arrow buttons on rows to scroll cards
- Fullscreen button

**📱 Mobile (Android / iOS)**
- Adaptive interface for phone screens
- Bottom navigation: Home / Catalog / Schedule / Collections
- Catalog filters in a bottom sheet (swipe down or menu button ☰)
- Long tap on a card — context menu
- Swipe right on the anime page — go back

**⚡ Performance**
- Optimized for Tizen: no heavy animations or blur effects
- Virtualized cards (15 in the DOM per row)
- Data caching in memory
- Interface scaling +30% on Tizen for comfortable viewing from the couch

---

## 🛠️ Development

```bash
git clone https://github.com/CoreDip/anilibria-tizen-wgt.git
# Open index.html in a browser for development
# Or import the tizen/ folder into Tizen Studio as an Existing Project
```

```text
anilibria-tizen-wgt/
├── index.html           ← all app logic in one file
├── config.xml           ← Tizen manifest
├── icon.png
├── js/
│   └── main.js          ← remote control button registration
├── css/
│   └── style.css
├── msx/
│   └── start.json       ← config for MediaStationX
└── .github/workflows/
    └── build.yml        ← auto-build .wgt + GitHub Pages
```

---

## 📄 License

MIT — an unofficial project, not affiliated with the AniLibria team


Arabic version


# 🎌 AniLiberty — عميل AniLibria

> عميل غير رسمي لـ [AniLibria](https://anilibria.tv) لـ **شاشات سامسونغ الذكية (Tizen)** و**الكمبيوتر** و**الأجهزة المحمولة**

<img width="128" height="128" alt="icon" src="https://github.com/user-attachments/assets/407c0839-b1e4-42c7-866f-8ce6797173e3" />

[![Release](https://img.shields.io/github/v/release/CoreDip/anilibria-tizen-wgt?label=أحدث+إصدار&color=red)](https://github.com/CoreDip/anilibria-tizen-wgt/releases/latest)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## ⬇️ تنزيل / فتح

| المنصة | |
|-----------|---|
| 📦 **Samsung TV (.wgt)** | [تحميل AniLiberty.wgt →](https://github.com/CoreDip/anilibria-tizen-wgt/releases/latest) |
| 🌐 **المتصفح / الكمبيوتر / الهاتف** | [https://coredip.github.io/anilibria-tizen-wgt/ →](https://coredip.github.io/anilibria-tizen-wgt/) |
| 📺 **MediaStationX** | `anilibria-tizen-wgt.dipcoremail.workers.dev` |

---

## 📺 التثبيت

### الخيار 1 — وضع المطور (Tizen)
1. على التلفاز: **الإعدادات → العامة → مدير النظام → وضع المطور** → أدخل عنوان IP الخاص بالكمبيوتر
2. أعد تشغيل التلفاز
3. في Tizen Studio: `Run As → Tizen Web Application` أو قم بتثبيت الملف `.wgt` عبر `Package Manager`

### الخيار 2 — MediaStationX
1. افتح MediaStationX على التلفاز
2. أضف الرابط: `anilibria-tizen-wgt.dipcoremail.workers.dev`

### الخيار 3 — الكمبيوتر / اللوحي / المتصفح / الهاتف
فقط افتح [https://coredip.github.io/anilibria-tizen-wgt/](https://coredip.github.io/anilibria-tizen-wgt/) — الواجهة المتجاوبة تتكيف تلقائيًا مع الشاشة

### الخيار 4 — جهاز لوحي / هاتف Android
[![Release](https://img.shields.io/github/v/release/CoreDip/anilibria-tizen-wgt?label=أحدث+إصدار&color=red)](https://github.com/CoreDip/anilibria-tizen-wgt/releases/latest)

---

---

## 📸 لقطات الشاشة

![main](https://github.com/user-attachments/assets/e6cde226-fbb3-4a8c-8aee-735f3621fdac)
![anipage](https://github.com/user-attachments/assets/b930a04a-30d3-42f2-a484-f17a1a865517)
![collections](https://github.com/user-attachments/assets/d1ae2dd7-ff49-4937-9ac8-578e03556f11)
![player](https://github.com/user-attachments/assets/8a2510ba-41b0-485e-a948-2229a3d384e2)

---

## ✨ المميزات

**🏠 الرئيسية**
- الصفوف: الحلقات الجديدة، المسلسلات الحالية، الشائعة، الأعلى تقييمًا، حسب النوع
- شريط تقدم المشاهدة مباشرة على البطاقة
- تحميل الصفوف بشكل كسول أثناء التمرير
- قائمة السياق على البطاقة (ضغط طويل / زر الفأرة الأيمن)

**🔍 الكتالوج**
- البحث حسب العنوان
- المرشحات: النوع، السنة، الموسم، النوع، حالة الإصدار، حالة الدبلجة، التصنيف العمري، الترتيب
- على الهاتف — المرشحات في لوحة من أسفل الشاشة
- تحميل النتائج بلا حدود
- استعادة موضع التمرير عند العودة من صفحة الأنمي

**📅 الجدول**
- إصدارات الحلقات حسب يوم الأسبوع مع الملصقات
- على الهاتف — قائمة رأسية مع تمرير أفقي للأيام

**📂 المجموعات**
- علامات التبويب: المفضلة، أتابعها، مجدولة، تمت مشاهدتها، تم التخلي عنها، السجل
- شارات المجموعة على البطاقات — يظهر حالة الأنمي (❤ / 👁 / 📅 / ✔ / ✖) دون فتح الصفحة
- تظهر أشرطة التقدم في المجموعات فورًا، دون فتح كل أنمي
- عند إضافته إلى «تمت مشاهدته» يتم وضع كل الحلقات تلقائيًا كمشاهدت
- الإضافة والإزالة عبر قائمة السياق أو صفحة الأنمي
- حذف من السجل، إعادة ضبط التقدم

**▶️ المشغل**
- بث HLS (مُدمج natively على Tizen، hls.js على الأجهزة الأخرى)
- اختيار الجودة: 480p / 720p / 1080p
- زر «⏩ تخطي المقدمة» — يظهر تلقائيًا ويُتخطى بنقرة واحدة
- زر «⏭ الحلقة التالية» — يظهر أثناء نهاية الحلقة، لا حاجة للانتظار حتى النهاية
- إعادة التشغيل السريعة بالضغط المطول على السهم (5s → 10s → 30s)
- النقر على الشريط الزمني
- الانتقال التلقائي إلى الحلقة التالية
- تبديل وضع الملاءمة: حسب الإطار / ملء الشاشة
- زر ملء الشاشة (الكمبيوتر والهاتف)
- زر «رجوع» في أعلى اليسار

**💾 التقدم والمزامنة**
- الحفظ التلقائي كل 8 ثوانٍ
- مزامنة ثنائية الاتجاه كاملة مع حساب AniLibria
- نقل التقدم المحلي إلى السحابة عند تسجيل الدخول
- مزامنة خلفية للمجموعات والسجل كل دقيقتين
- زر «متابعة» من نفس نقطة التوقف بالضبط
- إعادة ضبط التقدم يحذف البيانات فورًا محليًا وفي السحابة
- الضغط الطويل على زر الحلقة — إزالة علامة المشاهدة (فأرة، لمس، جهاز تحكم)
- عند وضع علامة مشاهدة على الحلقات، تتم المزامنة مع الخادم

**👤 الحساب**
- تسجيل الدخول باسم المستخدم وكلمة المرور
- مزامنة المجموعات والسجل مع الخادم
- ملف شخصي مع زر تسجيل الخروج

**🎮 جهاز التحكم عن بعد (Samsung Tizen)**
- تنقل كامل باستخدام الأسهم بدون فأرة
- زر Back — العودة خطوة بخطوة في التسلسل الهرمي
- النقر المزدوج على Back — قائمة الخروج من التطبيق
- الضغط الطويل على OK على البطاقة — قائمة السياق
- الضغط الطويل على OK على الحلقة — إزالة علامة المشاهدة
- دعم أزرار الألوان (الكتالوج، الجدول، المجموعات)

**🖱️ الكمبيوتر (الفأرة)**
- التمرير، النقر، الزر الأيمن للفأرة — قائمة السياق
- أزرار الأسهم على الصفوف للتمرير بين البطاقات
- زر ملء الشاشة

**📱 الهاتف (Android / iOS)**
- واجهة متجاوبة تناسب شاشات الهاتف
- تنقل أسفل الشاشة: الرئيسية / الكتالوج / الجدول / المجموعات
- مرشحات الكتالوج في لوحة من أسفل الشاشة (سحب للأسفل أو زر ☰)
- الضغط الطويل على البطاقة — قائمة السياق
- السحب إلى اليمين في صفحة الأنمي — العودة

**⚡ الأداء**
- مُحسّن لـ Tizen: بدون حركات ثقيلة أو تأثيرات blur
- بطاقات افتراضية (15 عنصرًا في DOM لكل صف)
- التخزين المؤقت للبيانات في الذاكرة
- تكبير الواجهة +30% على Tizen لسهولة المشاهدة من الأريكة

---

## 🛠️ التطوير

```bash
git clone https://github.com/CoreDip/anilibria-tizen-wgt.git
# افتح index.html في المتصفح للتطوير
# أو استورد مجلد tizen/ في Tizen Studio كـ Existing Project
```

```text
anilibria-tizen-wgt/
├── index.html           ← كل التطبيق في ملف واحد
├── config.xml           ← ملف Tizen manifest
├── icon.png
├── js/
│   └── main.js          ← تسجيل أزرار التحكم عن بعد
├── css/
│   └── style.css
├── msx/
│   └── start.json       ← إعدادات MediaStationX
└── .github/workflows/
    └── build.yml        ← بناء تلقائي لـ .wgt + GitHub Pages
```

---

## 📄 الترخيص

MIT — مشروع غير رسمي، وغير مرتبط بفريق AniLibria

