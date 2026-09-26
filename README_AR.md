# خدمة الأسر — نسخة Android

هذه النسخة تغلف التطبيق المحلي الحالي داخل Android WebView مع أصل آمن لدعم Web Crypto.

- نفس بيانات التطبيق ومنطق التشفير AES-GCM/PBKDF2.
- التخزين يظل محليًا على الجهاز.
- اختيار ملفات الاستعادة يعمل من Android.
- النسخ الاحتياطي يُحفظ في مجلد Downloads.
- القفل التلقائي 5 دقائق كما في نسخة المتصفح.

## بناء APK
يمكن فتح المشروع في Android Studio ثم Build > Build APK(s)، أو استخدام GitHub Actions المرفق في `.github/workflows/build-apk.yml`.
