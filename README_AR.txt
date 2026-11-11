MIDO NOVA - مشروع Android

المشروع يفتح موقع https://elite-store-ug21.onrender.com/ داخل تطبيق Android مستقل بواجهة WebView، مع الاحتفاظ بجلسة الموقع وملفات تعريف الارتباط وزر الرجوع.

البناء من التابلت باستخدام GitHub Actions:
1) فك ضغط الملف ZIP.
2) أنشئ مستودع GitHub جديدًا باسم MIDO-NOVA-Android واجعله Public أو Private.
3) ارفع محتويات مجلد MIDO_NOVA_Android إلى جذر المستودع (لا ترفع مجلدًا متداخلًا إضافيًا).
4) افتح تبويب Actions في المستودع وفعّل Actions إذا طلب GitHub ذلك.
5) اختر workflow باسم Build MIDO NOVA APK ثم Run workflow.
6) انتظر حتى تنتهي العملية بعلامة خضراء.
7) افتح تشغيل workflow الناجح، وانزل إلى Artifacts، ثم نزّل MIDO-NOVA-debug-apk.
8) فك ضغط ملف Artifact، وثبّت app-debug.apk على جهاز Android.

ملاحظات:
- هذا غلاف Android للموقع وليس إعادة كتابة أصلية للموقع؛ قاعدة البيانات والحسابات والطلبات تظل على السيرفر.
- يحتاج إنترنت. إشعارات Push غير مفعلة في هذا الإصدار.
- APK الناتج Debug للتجربة والتثبيت الشخصي، وليس إصدار متجر Google Play موقّعًا للنشر.
