# AEO Test Site — Agent Guide

موقع GitHub Pages ثابت يختبر قابلية الاكتشاف في الذكاء الاصطناعي (AEO).

## Structure

- `/index.html`, `/about.html`, `/faq.html` — صفحات محتوى (HTML ثابت، بدون JavaScript)
- `/llms.txt`, `/llms-full.txt` — ملفات اكتشاف الذكاء الاصطناعي
- `/robots.txt` — سياسة وصول روبوتات AI (جميع الروبوتات الرئيسية مسموحة)
- `/sitemap.xml` — خريطة الموقع
- `/agent-permissions.json` — إعلان قدرات الموقع

## Rules

- المحتوى بالعربية (RTL). لا تترجم بصمت.
- لا تعدّل قائمة السماح في robots.txt دون موافقة المالك.
- الموقع محتوى فقط — لا توجد إجراءات تنفيذية (execute/transact = false).
- نقطة الدخول المفضلة للوكلاء: `/llms.txt`