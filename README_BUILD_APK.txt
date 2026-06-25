A_NAES APK Build

التغييرات:
- اسم التطبيق: A_NAES
- package جديد: com.anaes.app
- أيقونة مكتوب عليها عبدالله بالعربية
- WebView محسن
- مفاتيح تخزين جديدة حتى لا تتعارض مع CashBook
- تصدير الملفات عبر AndroidBridge إلى التنزيلات
- workflow جاهز لبناء A_NAES.apk

طريقة البناء:
1) ارفع محتويات هذا المجلد إلى GitHub، وليس المجلد نفسه.
2) تأكد أن الملفات في جذر الريبو:
   app
   .github
   build.gradle
   settings.gradle
3) افتح Actions.
4) شغّل Build A_NAES APK.
5) حمّل Artifact باسم A_NAES-APK.
6) فك الضغط وستجد A_NAES.apk.
