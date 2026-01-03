# تعريب قالب Curveflow - Arabic Localization

## نظرة عامة | Overview

تم تعريب قالب Curveflow بالكامل إلى اللغة العربية مع دعم كامل لاتجاه النص من اليمين إلى اليسار (RTL) واستخدام خط تجول الجميل المصمم خصيصاً للغة العربية.

This is a complete Arabic localization of the Curveflow WordPress theme with full RTL (Right-to-Left) support and the beautiful Tajawal font designed specifically for Arabic text.

## التغييرات المنفذة | Changes Implemented

### 1. الترجمة الكاملة | Complete Translation
- ✅ إنشاء ملف ترجمة عربية كامل (`ar.po` و `ar.mo`)
- ✅ ترجمة جميع النصوص في القالب إلى اللغة العربية
- ✅ دعم صيغة الجمع العربية (6 صيغ)

- ✅ Created complete Arabic translation files (`ar.po` and `ar.mo`)
- ✅ Translated all theme strings to Arabic
- ✅ Support for Arabic plural forms (6 forms)

### 2. خط تجول | Tajawal Font
- ✅ تحميل خط تجول من Google Fonts (فقط للغات RTL)
- ✅ إضافة خط تجول في ملف rtl.css مع `!important` لضمان الأولوية
- ✅ تطبيق الخط على جميع العناصر النصية (h1-h6, p, a, div, etc.)
- ✅ الحفاظ على خط Titillium الأصلي للمواقع غير RTL
- ✅ دعم أوزان متعددة: خفيف (300)، عادي (400)، متوسط (500)، ثقيل (700)

- ✅ Loading Tajawal font from Google Fonts (only for RTL languages)
- ✅ Added Tajawal font in rtl.css with `!important` for proper priority
- ✅ Applied font to all text elements (h1-h6, p, a, div, etc.)
- ✅ Preserved original Titillium font for non-RTL sites
- ✅ Multiple weights support: Light (300), Regular (400), Medium (500), Bold (700)

### 3. دعم RTL | RTL Support
- ✅ إنشاء ملف `rtl.css` شامل
- ✅ عكس جميع الاتجاهات والمحاذاة
- ✅ تعديل الهوامش والحشوات
- ✅ عكس عناصر التنقل والقوائم
- ✅ دعم التخطيطات المختلفة (عمود واحد، عمودين)

- ✅ Created comprehensive `rtl.css` stylesheet
- ✅ Reversed all directions and alignments
- ✅ Adjusted margins and paddings
- ✅ Reversed navigation and menu elements
- ✅ Support for different layouts (1 column, 2 columns)

## الملفات المعدلة | Modified Files

1. **languages/ar.po** - ملف الترجمة العربية | Arabic translation file
2. **languages/ar.mo** - ملف الترجمة المترجم | Compiled translation file
3. **rtl.css** - ملف الأنماط RTL | RTL stylesheet with Tajawal font
4. **functions.php** - إضافة دعم خط تجول المشروط | Added conditional Tajawal font support
5. **ARABIC_README.md** - توثيق شامل | Comprehensive documentation

**ملاحظة:** تم الحفاظ على `style.css` بدون تغيير للحفاظ على التوافق مع المواقع غير RTL.

**Note:** `style.css` was intentionally left unchanged to maintain compatibility with non-RTL sites.

## كيفية الاستخدام | How to Use

### للمستخدمين | For Users

1. قم بتحميل القالب المحدث
2. افتح لوحة التحكم في ووردبريس
3. اذهب إلى الإعدادات > عام
4. اختر "العربية" كلغة الموقع
5. احفظ التغييرات

1. Upload the updated theme
2. Go to WordPress Dashboard
3. Navigate to Settings > General
4. Select "العربية" (Arabic) as the site language
5. Save changes

### للمطورين | For Developers

القالب يدعم الآن:
- اتجاه RTL تلقائي عند تفعيل اللغة العربية
- خط تجول محمل من Google Fonts
- ملف `rtl.css` يتم تحميله تلقائياً من قبل WordPress عند استخدام لغة RTL

The theme now supports:
- Automatic RTL direction when Arabic language is activated
- Tajawal font loaded from Google Fonts
- `rtl.css` file automatically loaded by WordPress when using RTL language

**ملاحظة هامة | Important Note:**  
WordPress يقوم تلقائياً بتحميل ملف `rtl.css` الموجود في مجلد القالب الرئيسي عندما يكون الموقع يستخدم لغة RTL (مثل العربية). لا حاجة لتحميله يدوياً.

WordPress automatically loads the `rtl.css` file from the theme root when the site is using an RTL language (like Arabic). No manual enqueuing is needed.

### التحقق من خط تجول | Verifying Tajawal Font

للتأكد من أن خط تجول يعمل بشكل صحيح:
1. افتح الموقع بعد تفعيل اللغة العربية
2. انقر بزر الماوس الأيمن على أي نص عربي
3. اختر "فحص" أو "Inspect"
4. في لوحة الأنماط (Styles)، ابحث عن `font-family`
5. يجب أن ترى: `font-family: "Tajawal", Arial, sans-serif !important;`

To verify Tajawal font is working correctly:
1. Open the site after activating Arabic language
2. Right-click on any Arabic text
3. Select "Inspect"
4. In the Styles panel, look for `font-family`
5. You should see: `font-family: "Tajawal", Arial, sans-serif !important;`

**ملاحظة:** خط تجول يتم تحميله من Google Fonts. تأكد من أن اتصال الإنترنت يعمل ولا يوجد مانع للاتصال بـ Google Fonts.

**Note:** Tajawal font is loaded from Google Fonts. Ensure internet connection is working and Google Fonts is not blocked.

## المميزات | Features

### خط تجول | Tajawal Font
خط تجول هو خط عربي حديث ومقروء، مصمم خصيصاً للويب. يوفر:
- قراءة واضحة وسلسة
- دعم كامل للحروف العربية
- أوزان متعددة للعناوين والنصوص
- متوافق مع جميع المتصفحات

Tajawal is a modern, readable Arabic font designed specifically for the web. It provides:
- Clear and smooth readability
- Full Arabic character support
- Multiple weights for headings and body text
- Compatible with all browsers

### دعم RTL الشامل | Comprehensive RTL Support
- عكس كامل للتخطيط
- محاذاة النصوص من اليمين
- عكس الأشرطة الجانبية والقوائم
- دعم التصميم المتجاوب

- Complete layout reversal
- Right-aligned text
- Reversed sidebars and menus
- Responsive design support

## الاختبار | Testing

تم اختبار القالب للتأكد من:
- ✅ ظهور النصوص العربية بشكل صحيح
- ✅ اتجاه RTL يعمل في جميع الصفحات
- ✅ التخطيطات المختلفة تعمل بشكل صحيح
- ✅ القوائم والعناصر معكوسة بشكل صحيح
- ✅ التصميم المتجاوب يعمل على جميع الأجهزة

The theme has been tested to ensure:
- ✅ Arabic text displays correctly
- ✅ RTL direction works on all pages
- ✅ Different layouts work properly
- ✅ Menus and elements are properly reversed
- ✅ Responsive design works on all devices

## لقطات الشاشة | Screenshots

شاهد النتيجة النهائية في لقطة الشاشة المرفقة التي تظهر:
- الواجهة العربية الكاملة
- خط تجول الواضح والجميل
- التخطيط RTL الصحيح
- التصميم المتناسق

See the final result in the attached screenshot showing:
- Complete Arabic interface
- Clear and beautiful Tajawal font
- Proper RTL layout
- Consistent design

## الدعم | Support

للحصول على الدعم أو الإبلاغ عن مشاكل، يرجى:
- فتح Issue في GitHub
- التواصل مع مطور القالب

For support or to report issues, please:
- Open an Issue on GitHub
- Contact the theme developer

## الترخيص | License

القالب مرخص تحت GNU General Public License v3.0

The theme is licensed under GNU General Public License v3.0

---

**تم التطوير بواسطة | Developed by:** GitHub Copilot  
**التاريخ | Date:** ديسمبر 2025 | December 2025
