# Lammah bite — الموقع الرسمي

عربة بانكيك وضيافة مناسبات في المدينة المنورة.

موقع ثابت (HTML + CSS + JavaScript) بدون مكتبات أو أدوات بناء — يشتغل مباشرة على GitHub Pages.

## الملفات

```
index.html      الرئيسية
offers.html     العروض
gallery.html    معرض الصور
about.html      من نحن
booking.html    الحجز
faq.html        الأسئلة الشائعة
404.html        صفحة الخطأ
css/style.css   التصميم
js/main.js      السكربت + بيانات العروض
sitemap.xml     خريطة الموقع لمحركات البحث
robots.txt      تعليمات الزواحف
CNAME           النطاق المخصص: lammahbite.com
.nojekyll       تعطيل معالجة Jekyll
```

## تعديل العروض

كل تفاصيل العروض في متغيّر `OFFERS` داخل `js/main.js`. أي تعديل هناك ينعكس على الرئيسية وصفحة العروض والنافذة المنبثقة معاً.

## رقم الواتساب

سطر واحد في أعلى `js/main.js`:

```js
const WHATSAPP_NUMBER = "966593822625";
```

## اللوجو

ملفات اللوجو الحالية خلفيتها بيضاء، وفي `css/style.css` بلوكان معلّمان بـ
`WHITE-BACKGROUND KNOCKOUT` يخفيان البياض بالفلاتر.
عند رفع نسخة PNG بخلفية شفافة، احذف البلوكين وارفع الملف الجديد.

## GitHub Pages

Settings → Pages → Source: Deploy from a branch → Branch: `main` → `/(root)`
