# مسبحتي — التحديثات الرسمية

هذا هو المستودع العام للتحديثات والإصدارات الموقّعة لتطبيق **مسبحتي**. الكود المصدري محفوظ في المستودع الخاص، ولا تحتوي قناة التحديثات على مفاتيح التوقيع أو كلمات المرور.

## أحدث إصدار رسمي

- **الإصدار:** 1.0.12
- **رقم البناء:** 13
- **الوسم:** `v1.0.12`
- **تنزيل مباشر:** [Masbahati-1.0.12.apk](https://github.com/Eslam-Salah/Masbahati-Updates/releases/download/v1.0.12/Masbahati-1.0.12.apk)
- **صفحة الإصدار:** https://github.com/Eslam-Salah/Masbahati-Updates/releases/tag/v1.0.12
- **SHA-256:** `f5235152eca5e6f69d0eeb566bd699bae4b7ec54fa089d1ec24859aee0fe9103`

يُحسّن الإصدار ظهور التحديثات عبر تقليل فترة الفحص التلقائي إلى 5 دقائق وإعادة جلب بيانات GitHub مباشرة وعرض أخطاء الاتصال بشكل أوضح. نجحت اختبارات Android وLint، وتم بناء Release موقّع بالشهادة الأصلية والتحقق من APK المنشور مستقلاً بواسطة `apksigner` و`aapt` وSHA-256.

**ما زال اختبار التحديث على هاتف فعلي من v1.0.11 إلى v1.0.12 بحاجة إلى تأكيد.** ثبّته فوق الإصدار السابق دون حذف التطبيق للحفاظ على البيانات، واحتفظ بنسخة احتياطية إذا أمكن.

## الإصدارات السابقة

- **1.0.11 — Build 12:** [تحميل APK](https://github.com/Eslam-Salah/Masbahati-Updates/releases/download/v1.0.11/Masbahati-1.0.11.apk) · [ملاحظات الإصدار](https://github.com/Eslam-Salah/Masbahati-Updates/releases/tag/v1.0.11)
- **1.0.10 — Build 11:** [تحميل APK](https://github.com/Eslam-Salah/Masbahati-Updates/releases/download/v1.0.10/Masbahati-1.0.10.apk) · [ملاحظات الإصدار](https://github.com/Eslam-Salah/Masbahati-Updates/releases/tag/v1.0.10)
- **1.0.0 — Build 1:** [تحميل APK](https://github.com/Eslam-Salah/Masbahati-Updates/releases/download/v1.0.0/Masbahati-1.0.0.apk) · [ملاحظات الإصدار](https://github.com/Eslam-Salah/Masbahati-Updates/releases/tag/v1.0.0)

## التحديث من داخل التطبيق

يفحص التطبيق أحدث GitHub Release، ويعرض قائمة التغييرات، ويتحقق من SHA-256 عند تنزيل ملف التحديث. يطلب Android موافقة المستخدم على تثبيت APK من خارج المتجر عند الحاجة. يجب أن يحمل أي إصدار لاحق شهادة التوقيع الأصلية، وبناءً أعلى من الإصدار الحالي.

## الأمان

لا تضع ملفات `.jks` أو كلمات المرور أو رموز الوصول في مستودع عام. ملفات APK منشورة للإتاحة العامة؛ أما مفاتيح توقيع الإصدارات فتظل خاصة.
