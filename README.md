# ENSAA × MNU Nursing — موقع الجمعية

## النشر على GitHub Pages
1. افتح github.com وأنشئ repository جديد (مثلًا `ensaa-mnu`)، ويفضّل Public.
2. اضغط **Add file ← Upload files**، واسحب كل محتويات هذا المجلد (ملفات `index.html` و`style.css` و`script.js` ومجلدا `images` و`data`).
3. اضغط **Commit changes**.
4. من **Settings ← Pages**: اختر **Deploy from a branch**، والفرع `main`، والمجلد `/ (root)`، ثم **Save**.
5. بعد دقيقة تقريبًا يظهر الرابط في نفس الصفحة.

## تعديل المحتوى
- **أسماء البورد:** افتح `data/board.json` على GitHub، اضغط أيقونة القلم، عدّل الاسم، ثم Commit changes.
- **الأخبار:** افتح `data/news.json` وأضف عنصرًا داخل `items` بهذا الشكل:
  `{"date":"2026-10-24","title":"عنوان الخبر","text":"نص قصير","link":"https://رابط-البوست"}`
  وافصل بين الأخبار بفاصلة.
- **الصور:** استبدل الملف داخل مجلد `images` بملف جديد بنفس الاسم.

## ملاحظة
فتح `index.html` بالضغط المزدوج على الجهاز لن يحمّل ملفات `data`، لأن المتصفح يمنع ذلك. الموقع يعمل بشكل كامل من GitHub Pages.
