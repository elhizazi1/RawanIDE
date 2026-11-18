<div align="center">

<a href="https://rawanide.elhizazi.me"><img src="app_icon_original.png" alt="أيقونة RawanIDE" width="100" /></a>

# RawanIDE — روان IDE

### جهازك الأندرويد. مساحة عملك. بيئة تطويرك.

**حرّر مشاريعك وشغّلها وعاينها مباشرةً من هاتفك أو جهازك اللوحي.**

<img src="assets/typing-banner.svg" alt="Code. Build. Preview. Anywhere." width="760" />

<p>
<a href="https://github.com/elhizazi1/RawanIDE/releases/latest"><img alt="آخر إصدار" src="https://img.shields.io/github/v/release/elhizazi1/RawanIDE?style=for-the-badge&color=19b9ad&label=Release" /></a>
<img alt="Android 8.0+" src="https://img.shields.io/badge/Android-8.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
<a href="https://github.com/elhizazi1/rawanide-extension-sdk"><img alt="Extension SDK" src="https://img.shields.io/badge/Extension%20SDK-v1.0.0-19b9ad?style=for-the-badge" /></a>
</p>

**[تنزيل APK](https://github.com/elhizazi1/RawanIDE/releases/latest)** · **[مركز المساعدة](https://rawanide.elhizazi.me/help)** · **[SDK الإضافات](https://github.com/elhizazi1/rawanide-extension-sdk)** · **[English](README.md)**

<img src="feature_graphic.png" alt="واجهة RawanIDE" width="100%" />

</div>

---

## نبذة

RawanIDE مساحة عمل لتطوير المشاريع على هاتف أو جهاز لوحي يعمل بنظام Android، تجمع إدارة المشاريع والملفات وتحرير الشيفرة وتكامل الطرفية والمعاينة المحلية ووظائف Git والإضافات الاختيارية.

## الإمكانات

- إنشاء المشاريع وفتحها وإدارة ملفاتها.
- تحرير ملفات المصدر والتنقل بين المجلدات.
- التكامل مع Termux لتشغيل أوامر التطوير المحلية بعد إعداده.
- معاينة المشاريع عبر Android WebView، بما في ذلك مشاريع Vite وNuxt عند إعداد الخادم والاعتماديات.
- أوضاع معاينة للهاتف واللوحي وسطح المكتب، وأدوات المطور ولوحة اللمس في الوضع المناسب.
- وظائف مرتبطة بمستودعات Git.
- إضافات اختيارية عبر Marketplace، مع ضرورة مراجعة مصادرها وصلاحياتها.
- خيارات تخصيص وحزم لغات اختيارية.
- تكاملات اختيارية مع Shizuku وDhizuku بحسب الجهاز والإعداد.

> بعض الإمكانات تحتاج تطبيقات خارجية أو صلاحيات أو إضافات أو إعدادًا خاصًا بالمشروع، ولا تعمل بالضرورة على جميع الأجهزة مباشرة.

## تنزيل التطبيق

1. افتح [صفحة الإصدارات](https://github.com/elhizazi1/RawanIDE/releases/latest).
2. نزّل الملف **`RawanIDE-release-signed.apk`** من مرفقات الإصدار.
3. تحقق من بصمة SHA-256 المنشورة.
4. ثبّت APK، واسمح بالتثبيت من المصدر المختار عند طلب Android ذلك.
5. افتح التطبيق وأكمل إعداد المكونات التي تحتاجها.

## بدء الاستخدام

1. أنشئ مشروعًا أو افتح مشروعًا موجودًا.
2. امنح صلاحيات الملفات اللازمة فقط.
3. لمشاريع Node.js، جهّز Termux واعتماديات المشروع.
4. شغّل خادم التطوير ثم افتح المعاينة المدمجة.
5. اختر وضع المعاينة الملائم.

للتفاصيل: [مركز المساعدة](https://rawanide.elhizazi.me/help).

## 🧩 تطوير الإضافات باستخدام SDK الرسمي

يمكن للمطورين إنشاء إضافات `.r1` وفحصها وتجهيز حزمها باستخدام **[RawanIDE Extension SDK](https://github.com/elhizazi1/rawanide-extension-sdk)**، وهي أداة تطوير مستقلة عن تطبيق أندرويد.

| المورد | الرابط |
| :-- | :-- |
| 🛠 مستودع SDK | [rawanide-extension-sdk](https://github.com/elhizazi1/rawanide-extension-sdk) |
| 📦 الحزمة المنشورة | [GitHub Packages](https://github.com/elhizazi1/rawanide-extension-sdk/packages) · `@elhizazi1/extension-sdk` |
| 📖 توثيق المطورين | [بوابة المطورين](https://rawanide.elhizazi.me/developers) |

> [!NOTE]
> SDK أداة لإنشاء الإضافات وليست مكونًا يجب تثبيته داخل تطبيق RawanIDE. ويُدار إصدارها بشكل مستقل.

## الروابط الرسمية

| المورد | الرابط |
| --- | --- |
| SDK الإضافات | https://github.com/elhizazi1/rawanide-extension-sdk |
| المساعدة | https://rawanide.elhizazi.me/help |
| حول التطبيق | https://rawanide.elhizazi.me/about |
| سياسة الخصوصية | https://rawanide.elhizazi.me/privacy |
| Marketplace | https://rawanide.elhizazi.me/ |
| الإصدارات | https://github.com/elhizazi1/RawanIDE/releases |
| الإبلاغ عن الأخطاء | https://github.com/elhizazi1/RawanIDE/issues |

## الأمان والمساهمة

لا تنشر مفاتيح API أو كلمات المرور أو بيانات مشاريعك الخاصة في البلاغات العامة. راجع [SECURITY.md](SECURITY.md) للإبلاغ عن المشكلات الأمنية، و[CONTRIBUTING.md](CONTRIBUTING.md) لإرشادات المساهمة.

## الترخيص

يرجى الرجوع إلى ملف **LICENSE** في المستودع إن كان منشورًا. لا تضيف هذه الحزمة ترخيصًا جديدًا ولا تغيّر الترخيص القائم.
