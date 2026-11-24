Ethmar Storage Location - تطبيق ويب يعمل بدون إنترنت
=====================================================

الملفات:
- index.html          الصفحة الرئيسية
- manifest.webmanifest  إعدادات التطبيق
- sw.js               Service Worker (للعمل بدون إنترنت)
- icon-192.png / icon-512.png / apple-touch-icon.png / favicon-32.png

كيف تستخدمه:
1. ارفع المجلد بالكامل على أي استضافة (Netlify, GitHub Pages, Vercel, أو سيرفرك)
   أو شغّله محلياً عبر خادم بسيط (مثل: python -m http.server 8080)

2. افتح الرابط في Chrome أو Edge أو Safari

3. للتثبيت على سطح المكتب:
   - Chrome/Edge (ويندوز / ماك / لينكس): 
     اضغط على أيقونة التثبيت في شريط العنوان ← "تثبيت"
     أو من القائمة ⋮ ← تثبيت التطبيق / Install app

   - Safari (ماك): 
     ملف ← إضافة إلى Dock  أو Share ← Add to Dock

   - Android: 
     القائمة ← تثبيت التطبيق / Add to Home screen

   - iPhone/iPad: 
     زر المشاركة ← إضافة إلى الشاشة الرئيسية

4. بعد التثبيت يعمل بدون إنترنت بالكامل (البيانات محفوظة محلياً).

ملاحظة: يجب أن يكون الرابط HTTPS (أو localhost) حتى يظهر زر التثبيت.
