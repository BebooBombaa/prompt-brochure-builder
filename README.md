لمستخدم يريد إنشاء ملف README لمشروع مولد برومبت البروشور 3D. سأقوم بإنشاء README احترافي وشامل يغطي:

وصف المشروع
المميزات
كيفية الاستخدام
لقطات الشاشة (وصفية)
التقنيات المستخدمة
التثبيت والتشغيل
هيكل الملفات
المساهمة
الرخصة
سأكتب README باللغة العربية مع بعض المصطلحات الإنجليزية التقنية.
ملف README للمشروع
🎨 مولّد برومبت البروشور 3D المحسَّن
VersionStatusLicenseHTML5CSS3JavaScript

أداة ويب تفاعلية لتوليد برومبتات احترافية لإنشاء بروشورات 3D تعليمية باستخدام الذكاء الاصطناعي

العرض الحي · التوثيق · الإبلاغ عن مشكلة

📸 نظرة عامة
الشاشة الرئيسية	شريط التقدم	نتيجة البرومبت
نموذج منظم بخطوات	تتبع مرئي للتقدم	نسخ وتحميل فوري
✨ المميزات
🎯 المميزات الأساسية
📝 Wizard منظم: نموذج مقسم إلى 6 خطوات منطقية وسهلة المتابعة
💾 حفظ تلقائي: لا تخسر بياناتك أبداً (Auto-save في المتصفح)
📚 قوالب جاهزة: 3 قوالب محددة مسبقاً للبدء السريع
📜 سجل البرومبتات: حفظ آخر 20 برومبت مع إمكانية استرجاعها
🛠️ المميزات التقنية
⚡ أداء محسَّن: Debounce للحفظ التلقائي لتقليل العمليات
🔒 يعمل بدون إنترنت: Offline-first (لا يحتاج اتصال بالإنترنت)
📱 متجاوب بالكامل: يعمل على الجوال والتابلت والكمبيوتر
🎨 تصميم عصري: Dark Theme مع CSS Variables و Animations
🔧 المميزات العملية
✅ تحقق من البيانات: Validation لكل خطوة قبل الانتقال
➕ عناصر ديناميكية: إضافة/حذف غير محدود للمفاهيم والأمثلة والنقاط
📋 نسخ بنقرة واحدة: نسخ للحافظة مع ملاحظات الحالة
💾 تحميل كملف: تصدير البرومبت كملف نصي (.txt)
🚀 البدء السريع
الطريقة 1: فتح مباشر (بدون خادم)
حمل الملف index.html
انقر نقراً مزدوجاً لفتحه في المتصفح
ابدأ الاستخدام! 🎉
الطريقة 2: استخدام خادم محلي (موصى به للتطوير)
# باستخدام Pythonpython -m http.server 8000# أو باستخدام Node.js (npx)npx serve .# أو باستخدام PHPphp -S localhost:8000
ثم افتح: http://localhost:8000

📖 دليل الاستخدام
الخطوة 1: المعلومات العامة
┌─────────────────────────────────────┐
│  🎯 اختر قالباً (اختياري)          │
│  ┌───┐ ┌───┐ ┌───┐ ┌───┐          │
│  │شب│ │علو│ │ريا│ │فا│          │
│  │كا│ │وم│ │ضا│ │رغ│          │
│  │ت  │    │ة  │    │    │          │
│  └───┘ └───┘ └───┘ └───┘          │
│                                     │
│  عنوان الموضوع: ________________   │
│  الفئة المستهدفة: [طلاب ▼]        │
│                                     │
│           [التالي →]               │
└─────────────────────────────────────┘
الخطوة 2-6: ملء النموذج
الخطوة
المحتوى
الحقول
2	الغلاف والمقدمة	العنوان، العنوان الفرعي، المقدمة، التعليق
3	المفاهيم الرئيسية	مفاهيم ديناميكية (عنوان + شرح)
4	الأمثلة المرئية	أمثلة ديناميكية (عنوان + وصف إنجليزي + تعليق)
5	الملخص والنقاط	نقاط ديناميكية
6	التوقيع واللمسات	الاسم، ملاحظات إضافية

النتيجة النهائية
┌─────────────────────────────────────────────────────┐
│  ✅ البرومبت النهائي                                │
│                                                     │
│  [📋 نسخ]  [💾 تحميل]  [🔄 جديد]                   │
│                                                     │
│  ┌─────────────────────────────────────────────┐   │
│  │ Act as a top-tier prompt engineer...         │   │
│  │                                             │   │
│  │ TASK:                                       │   │
│  │ Create a 3D tri-fold infographic brochure... │   │
│  │                                             │   │
│  │ PANEL 1: COVER / INTRODUCTION               │   │
│  │ ...                                         │   │
│  └─────────────────────────────────────────────┘   │
│                                                     │
│  ✓ تم النسخ إلى الحافظة!                            │
└─────────────────────────────────────────────────────┘
🏗️ التقنيات المستخدمة
┌────────────────────────────────────────────────────────────┐
│                      Frontend Stack                        │
├────────────────────────────────────────────────────────────┤
│                                                            │
│   ┌─────────┐   ┌─────────┐   ┌─────────────────────┐     │
│   │  HTML5  │   │  CSS3   │   │   JavaScript ES6+   │     │
│   │  Semantic│   │  Grid   │   │   • LocalStorage    │     │
│   │  Markup │   │  Flexbox│   │   • Clipboard API   │     │
│   │         │   │ Vars    │   │   • DOM Manipulation│     │
│   └─────────┘   └─────────┘   └─────────────────────┘     │
│                                                            │
│   ⚡ No Frameworks  |  📦 No Dependencies  |  🔒 Offline  │
│                                                            │
└────────────────────────────────────────────────────────────┘

المتصفحات المدعومة
المتصفح
الإصدار الأدنى
Chrome	80+
Firefox	75+
Safari	13+
Edge	80+
Opera	67+

📁 هيكل المشروع
brochure-prompt-generator/
│
├── index.html          # ← الملف الرئيسي (كل شيء في ملف واحد!)
├── README.md           # ← هذا الملف
│
└── assets/             # ← مجلد اختياري للصور المستقبلية
    ├── screenshots/
    └── icons/
	
	لماذا ملف واحد؟
	✅ سهولة النشر (ما عليك سوى نقل ملف واحد)
✅ لا حاجة لبناء أو تجميع (No Build Process)
✅ يعمل مباشرة من نظام الملفات
✅ مثالي للمشاركة السريعة
🎨 التصميم ونظام الألوان
Design Tokens
/* الألوان الرئيسية */
--bg-primary: #0f172a;      /* خلفية داكنة */
--accent-primary: #10b981;  /* أخضر للإجراءات */
--accent-secondary: #3b82f6;/* أزرق للثانوية */
--accent-warning: #f59e0b;  /* برتقالي للعناوين */

/* الخطوط */
font-family: 'Segoe UI', Tahoma, sans-serif;

/* الأبعاد */
border-radius: 12px;
spacing: 16px - 24px;
💾 التخزين المحلي (LocalStorage)
البيانات المحفوظة تلقائياً
المفتاح
المحتوى
الحجم التقريبي
brochurePromptData	جميع حقول النموذج	~5-10 KB
promptHistory	آخر 20 برومبت	~100 KB

مسح البيانات
// عبر Console المتصفح
localStorage.clear();

// أو عبر زر "جديد" في التطبيق
🔧 التخصيص
إضافة قالب جديد
// ابحث عن كائن templates في الكود
const templates = {
  // ... القوالب الحالية
  
  // أضف قالبك هنا
  myTemplate: {
    topic: 'عنوان الموضوع',
    audience: 'students',
    p1_title: 'العنوان الرئيسي',
    // ... باقي الحقول
    concepts: [
      { title: 'مفهوم 1', desc: 'شرح 1' }
    ],
    examples: [],
    bullets: ['نقطة 1'],
    signature: 'اسمك'
  }
};

تغيير الألوان
:root {
  --accent-primary: #YOUR_COLOR;
  --bg-primary: #YOUR_BG_COLOR;
}

🤝 المساهمة
نرحب بمساهماتك! إليك كيف يمكنك المساعدة:

كيف تساهم
Fork المشروع
أنشئ branch جديد (git checkout -b feature/AmazingFeature)
Commit التغييرات (git commit -m 'Add AmazingFeature')
Push إلى الفرع (git push origin feature/AmazingFeature)
افتح Pull Request
أفكار للمساهمة
 إضافة Mode فاتح/داكن
 دعم لغات أخرى (English, French)
 تصدير PDF
 مشاركة البرومبت برابط
 إضافة المزيد من القوالب
📄 الرخصة
هذا المشروع مرخص تحت رخصة MIT - راجع ملف LICENSE للتفاصيل.

MIT License

Copyright (c) 2024 Prompt Generator Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

👨‍💻 المؤلف
باسم السيد - مطور ومهندس برومبت

🙏 شكر وتقدير
Emoji Cheatsheet - للرموز التعبيرية
CSS Tricks - لأفكار التصميم
مجتمع المطورين العرب على الدعم المستمر
<div align="center">

** إذا أعجبك المشروع، لا تنسَ أن تترك ⭐ star! **

Made with ❤️ and ☕

