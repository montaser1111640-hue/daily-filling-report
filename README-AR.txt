تطبيق Daily Filling Report - ملفات النشر المجاني

محتويات المجلد:
- index.html: التطبيق الأصلي.
- manifest.webmanifest: تعريف التطبيق القابل للتثبيت.
- service-worker.js: تشغيل التطبيق بعد أول زيارة دون إنترنت (حسب دعم المتصفح).
- icons/: أيقونات التطبيق.

النشر المجاني المقترح باستخدام GitHub Pages:
1) أنشئ حسابًا مجانيًا على https://github.com إذا لم يكن لديك حساب.
2) أنشئ Repository جديدًا باسم daily-filling-report واجعله Public.
3) ارفع كل الملفات الموجودة داخل هذا المجلد إلى جذر المستودع (وليس المجلد نفسه).
4) افتح Settings ثم Pages.
5) من Build and deployment اختر Deploy from a branch، ثم Branch: main و Folder: /(root)، ثم Save.
6) انتظر ظهور رابط الموقع في صفحة Pages. سيكون غالبًا بالشكل:
   https://YOUR-USERNAME.github.io/daily-filling-report/

التثبيت:
- Android: افتح الرابط في Chrome ثم القائمة ⋮ ثم Install app أو Add to Home screen.
- iPhone: افتح الرابط في Safari ثم Share ثم Add to Home Screen.

ملاحظات:
- يلزم HTTPS لكي تعمل خصائص PWA وService Worker؛ GitHub Pages يوفر HTTPS.
- التقارير والقوائم محفوظة محليًا في المتصفح على كل جهاز، ولا تتم مزامنتها تلقائيًا بين الأجهزة.
- لا ترفع أي بيانات تقارير فعلية إلى المستودع؛ ارفع ملفات التطبيق فقط.
