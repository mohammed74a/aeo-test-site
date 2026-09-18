# AEO Lab — موقع AEO التجريبي

> موقع تجريبي متكامل لاختبار تحسين محركات الذكاء الاصطناعي (AEO): llms.txt، robots.txt، Schema، قابلية القراءة الآلية، وميزانية التوكنات.

**الرابط المباشر**: https://mohammed74a.github.io/aeo-test-site/

## 🎯 ما هذا المشروع؟

موقع تجريبي عربي (RTL) مبني على GitHub Pages لاختبار **تحسين محركات الذكاء الاصطناعي (AEO)** — كيف تجعل موقعك مكتشفاً ومقروءاً ومفهوماً لروبوتات الذكاء الاصطناعي مثل GPTBot وClaudeBot وPerplexityBot.

## 📄 المحتوى

| الصفحة | الوصف |
|---|---|
| الرئيسية | نظرة عامة + إحصائيات + أحدث المقالات |
| المدونة | 5 مقالات عن AEO |
| الأسئلة الشائعة | 6 أسئلة (FAQ تفاعلي بدون JS) |
| عن الموقع | الأهداف والبنية |
| تواصل | GitHub + Issues |

### المقالات
- [دليل AEO الشامل](https://mohammed74a.github.io/aeo-test-site/blog/aeo-guide.html)
- [دليل llms.txt](https://mohammed74a.github.io/aeo-test-site/blog/llms-txt-guide.html)
- [AEO مقابل SEO](https://mohammed74a.github.io/aeo-test-site/blog/aeo-vs-seo.html)
- [معجم مصطلحات AEO](https://mohammed74a.github.io/aeo-test-site/blog/aeo-glossary.html)
- [حالة دراسية: بنيت موقعاً لاختبار AEO](https://mohammed74a.github.io/aeo-test-site/blog/aeo-case-study.html)

## 🧠 ملفات AEO

- `llms.txt` — خريطة الموقع للذكاء الاصطناعي
- `llms-full.txt` — المحتوى الكامل
- `robots.txt` — سياسة الزحف لـ 16 روبوت AI
- `sitemap.xml` — خريطة الموقع (10 صفحات HTML)
- `AGENTS.md` — دليل الوكلاء
- `agent-permissions.json` — إعلان القدرات
- `aeo-baseline-queries.md` — حزمة قياس Baseline (50 استعلاماً عربياً)

## 🏗️ البنية

- HTML ثابت 100% — بدون JavaScript
- CSS موحد واحد (`style.css`)
- Schema JSON-LD: 8 أنواع
- ميزانية التوكنات: كل صفحة أقل من 400 توكن
- اللغة: العربية (RTL)

## 📊 نتائج التدقيق

| البعد | قبل | بعد |
|---|---|---|
| قابلية الاكتشاف | 3/6 | 6/6 |
| قابلية القراءة | 4/6 | 5/6 |
| القدرات | 0/3 | 2/3 |
| **الإجمالي** | **7/15 (47%)** | **13/15 (87%)** |

## 🚀 التشغيل محلياً

```bash
# الموقع HTML ثابت — فقط افتح index.html أو شغّل خادماً بسيطاً
python -m http.server 8000
# ثم افتح http://localhost:8000
```

## 📝 الترخيص

مشروع تجريبي مفتوح — استخدمه بحرية للتعلم والاختبار.