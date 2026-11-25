# 📖 Quran Portal | بوابة القرآن الكريم

<p align="center">
  <strong>منصة قرآنية رقمية متكاملة تجمع المصحف والتلاوات والتفسير والعبادات في مكان واحد.</strong>
</p>

<p align="center">
  <a href="https://salah-eddine-program.github.io/Quran-Portal-0.2/">
    <img src="https://img.shields.io/badge/🌐_Live_Demo-Visit_Website-198754?style=for-the-badge" alt="Live Demo">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15-black?style=flat-square&logo=next.js" alt="Next.js">
  <img src="https://img.shields.io/badge/TypeScript-Enabled-3178C6?style=flat-square&logo=typescript" alt="TypeScript">
  <img src="https://img.shields.io/badge/PWA-Supported-5A0FC8?style=flat-square" alt="PWA">
  <img src="https://img.shields.io/badge/Deployment-GitHub_Pages-222222?style=flat-square&logo=github" alt="GitHub Pages">
  <img src="https://img.shields.io/badge/Version-0.2-blue?style=flat-square" alt="Version">
</p>

---

## 🌙 نبذة عن المشروع

**Quran Portal** هي بوابة ويب عربية متجاوبة، تهدف إلى توفير تجربة قرآنية رقمية متكاملة وسهلة الاستخدام.

تجمع المنصة بين قراءة القرآن الكريم والاستماع إلى التلاوات، والبحث في الآيات، والتفسير والترجمات، ومتابعة الحفظ والمراجعة، بالإضافة إلى مواقيت الصلاة واتجاه القبلة والأذكار.

تم تطوير المشروع باستخدام **Next.js 15 App Router وTypeScript**، مع اعتماد التصدير الثابت لتوفير إمكانية النشر على GitHub Pages.

## ✨ المميزات الرئيسية

### 📖 المصحف الشريف
- فهرس السور والأجزاء.
- الانتقال المباشر إلى السور والآيات.
- حفظ موضع القراءة الأخير.
- التحكم في حجم الخط وإعدادات القراءة.
- حفظ السور للقراءة دون اتصال.
- إضافة السور والآيات إلى المفضلة.
- نسخ الآيات وإنشاء بطاقات صور لها.

### 🎧 التلاوات القرآنية
- الاستماع إلى تلاوات القراء.
- تشغيل السور والإذاعات القرآنية.
- اختيار القارئ حسب الرواية المتاحة في بيانات المصدر.
- تكرار التلاوة والتحكم في سرعة التشغيل.
- الانتقال التلقائي بين الآيات.

### 🔍 البحث والتفسير
- بحث عربي في السور والآيات والأقسام.
- دعم البحث بصيغة رقم السورة ورقم الآية.
- ترجمات معاني القرآن بعدة لغات:
  - الإنجليزية.
  - الفرنسية.
  - الإسبانية.
  - الأردية.
- اختيار مصادر التفسير العربي المتاحة.

### 📝 الحفظ والمراجعة
- خطة مراجعة يومية وأسبوعية.
- متابعة الآيات المحفوظة.
- اختبارات ذاتية للمراجعة.
- حفظ الملاحظات والتقدم محلياً.

### 🕌 الخدمات الإسلامية
- مواقيت الصلاة.
- التقويم الهجري والميلادي.
- حساب اتجاه القبلة حسب المدينة المختارة.
- عداد التسبيح.
- روابط إلى حصن المسلم.

### ⚙️ تجربة المستخدم
- الوضع الليلي والنهاري.
- واجهة مبسطة اختيارية.
- إعدادات القراءة والصوت.
- دعم تثبيت التطبيق PWA.
- تصدير واستيراد النسخ الاحتياطية.
- تصميم متجاوب مع الهواتف والأجهزة اللوحية والحواسيب.

## 🖼️ لقطات من المشروع

<!-- أضف صور المشروع داخل مجلد screenshots ثم فعّل المسارات التالية -->

<!--
<p align="center">
  <img src="screenshots/homepage.png" width="85%" alt="Quran Portal Homepage">
</p>

<p align="center">
  <img src="screenshots/quran-reader.png" width="85%" alt="Quran Reader">
</p>
-->

## 🛠️ التقنيات المستخدمة

| التقنية | الاستخدام |
|---|---|
| Next.js 15 | إطار عمل التطبيق |
| TypeScript | تطوير الكود |
| HTML5 | بناء الصفحات |
| CSS3 | تصميم الواجهات |
| IndexedDB | تخزين السور والبيانات محلياً |
| Service Worker | التخزين المؤقت |
| PWA | إمكانية تثبيت التطبيق |
| GitHub Actions | البناء والنشر التلقائي |

## 🔗 مصادر البيانات وواجهات API

يعتمد المشروع على مصادر خارجية لتوفير البيانات والخدمات:

| المصدر | الاستخدام |
|---|---|
| [Al Quran Cloud](https://alquran.cloud/api) | نص القرآن والتفسير والترجمات |
| [MP3Quran](https://www.mp3quran.net/ar/api) | القراء والتلاوات والإذاعات |
| [AlAdhan](https://aladhan.com/prayer-times-api) | مواقيت الصلاة والتقويم |

## 🔐 البيانات والخصوصية

- لا يتطلب الموقع إنشاء حساب أو تسجيل الدخول.
- تحفظ المفضلة وآخر قراءة والملاحظات والإعدادات محلياً على الجهاز.
- تستخدم IndexedDB لتخزين السور التي تمت قراءتها.
- لا يطلب التطبيق إذن الوصول إلى الموقع الجغرافي.
- ترسل بيانات البحث إلى Al Quran Cloud عند استخدام البحث في الآيات.
- ترسل المدينة وطريقة الحساب إلى AlAdhan عند طلب مواقيت الصلاة.
- لا تتضمن النسخ الاحتياطية ملفات الصوت أو بيانات IndexedDB.
- لا تتوفر المزامنة السحابية أو إدارة الحسابات في النسخة الحالية.

**ملاحظة:** تحتاج البيانات الصوتية والخدمات الخارجية إلى اتصال بالإنترنت عند جلبها. كما أن حفظ السور محلياً لا يعني حفظ جميع التلاوات الصوتية دون اتصال.

## 🚀 التشغيل المحلي

### المتطلبات
- Node.js 20.9 أو أحدث.
- npm.
- Git.

### خطوات التشغيل

1. استنساخ المستودع:

```bash
git clone https://github.com/salah-eddine-program/Quran-Portal-0.2.git
```

2. الدخول إلى مجلد المشروع:

```bash
cd Quran-Portal-0.2
```

3. تثبيت الحزم:

```bash
npm ci
```

4. تشغيل بيئة التطوير:

```bash
npm run dev
```

5. فتح المتصفح على:

```text
http://localhost:3000
```

### فحص وبناء المشروع

```bash
npm run lint
npm run typecheck
npm run build
npm run check:export
```

تُنشأ ملفات الموقع الثابتة داخل مجلد:

```text
out/
```

## 🌐 النشر على GitHub Pages

يعتمد المشروع على GitHub Actions للنشر التلقائي.

ملف سير العمل:

```text
.github/workflows/pages.yml
```

لإعداد النشر:

1. افتح مستودع المشروع على GitHub.
2. انتقل إلى Settings.
3. اختر Pages.
4. ضمن Build and deployment اختر GitHub Actions.

يتولى سير العمل بناء التطبيق ورفع ملفات `out/`، مع ضبط `basePath` تلقائياً حسب المستودع.

## 📁 هيكل المشروع

```text
Quran-Portal-0.2/
│
├── .github/
│   └── workflows/
│       └── pages.yml
│
├── docs/
│   └── reference-summary.md
│
├── public/
│   ├── assets/
│   ├── service-worker.js
│   └── manifest.webmanifest
│
├── scripts/
│   └── check-export.mjs
│
├── src/
│   └── app/
│
├── next.config.ts
├── package.json
├── package-lock.json
└── README.md
```

## 🗺️ التطوير المستقبلي

يهدف المشروع إلى مواصلة التطوير وتحسين التجربة القرآنية الرقمية، مع التركيز على:

- تحسين تجربة قراءة المصحف.
- تطوير أدوات الحفظ والمراجعة.
- تحسين الأداء وتجربة الهواتف.
- توسيع الخدمات والخصائص الإسلامية.
- تحسين إمكانية الوصول والاستخدام.

## 🤝 المساهمة

المساهمات والاقتراحات مرحب بها.

يمكنك المساهمة من خلال:
- فتح Issue للإبلاغ عن مشكلة أو اقتراح ميزة.
- إرسال Pull Request.
- مشاركة أفكار لتحسين تجربة الاستخدام.

يرجى مراجعة `docs/reference-summary.md` للاطلاع على متطلبات الدمج ومصادر البيانات.

## 👨‍💻 المطور

**Salah Eddine Benettouati**

Electronics Engineer | Embedded Systems Developer

- GitHub: [salah-eddine-program](https://github.com/salah-eddine-program)
- Portfolio: [Personal Portfolio](https://bt-salahdine.netlify.app/)
- Project: [Quran Portal 0.2](https://salah-eddine-program.github.io/Quran-Portal-0.2/)

---

<p align="center">
  **﴿ وَقُل رَّبِّ زِدْنِي عِلْمًا ﴾**
</p>

<p align="center">
  Built with ❤️ to serve the Holy Quran.
</p>
