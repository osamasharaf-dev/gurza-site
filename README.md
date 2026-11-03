<div align="center">

# غُرزة — Ghurza Couture

**دار أزياء راقية في الرياض · فساتين سهرة وزفاف تُفصَّل على المقاس وتُخاط يدوياً**

[![الموقع المباشر](https://img.shields.io/badge/Live-ghurza.vercel.app-F2361D?style=for-the-badge&logo=vercel&logoColor=white)](https://ghurza.vercel.app)

📍 المشغل: الرياض، حي الياسمين

<img src="screenshots/01-hero.jpg" alt="الصفحة الرئيسية لموقع غرزة" width="100%">

</div>

---

## عن الموقع

موقع دار **غُرزة** مصمم كمجلة أزياء تتصفحها بالتمرير — كل قسم صفحة تنفتح من حافة مختلفة فوق التي قبلها، مع معرض فساتين تفاعلي يفتح كل فستان بتفاصيله وقماشه وقصته.

## لقطات من الموقع

| غلاف العدد | الدوّامة |
| :---: | :---: |
| <img src="screenshots/02-issue.jpg" alt="غلاف العدد"> | <img src="screenshots/03-tunnel.jpg" alt="دوامة الفساتين"> |
| **المجموعة** | **المشغل** |
| <img src="screenshots/04-collection.jpg" alt="مجموعة الفساتين"> | <img src="screenshots/05-atelier.jpg" alt="مراحل التفصيل في المشغل"> |

<div align="center">
<img src="screenshots/06-footer.jpg" alt="تذييل الموقع" width="100%">
</div>

### على الجوال

<div align="center">
<img src="screenshots/mobile-hero.jpg" alt="الصفحة الرئيسية على الجوال" width="260">
&nbsp;&nbsp;
<img src="screenshots/mobile-collection.jpg" alt="المجموعة على الجوال" width="260">
</div>

### صورة المشاركة

هذه الصورة تظهر عند مشاركة الرابط في واتساب وتويتر وغيرها:

<div align="center">
<img src="og-image.png" alt="صورة مشاركة الرابط" width="600">
</div>

## المميزات

- واجهة عربية بالكامل (RTL) بخط عرض مخصص
- فيديو افتتاحي بنسختين (سطح المكتب والجوال)
- تمرير سلس وحركات مرتبطة بالتمرير
- «الدوّامة»: نفق تفاعلي تقترب فيه الفساتين كلما مرّرت
- معرض لستة فساتين: طماطم، ليل نجد، لؤلؤة، سدو، همس، مطر
- قسم المشغل يشرح رحلة الفستان: الحوار، القماش، الخياطة، اللحظة
- صور WebP بحجمين للتحميل السريع
- متجاوب مع جميع الشاشات
- أيقونة للتبويب والجوال، وصورة معاينة عند مشاركة الرابط (Open Graph)

## التقنيات

| الأداة | الاستخدام |
| --- | --- |
| HTML / CSS / JavaScript | بدون أي build أو إطار عمل |
| [GSAP](https://gsap.com) + ScrollTrigger | الحركات المرتبطة بالتمرير |
| [Lenis](https://lenis.darkroom.engineering) | التمرير السلس |
| IBM Plex Sans Arabic | خط النصوص |
| [Vercel](https://vercel.com) | الاستضافة |

## هيكل المشروع

```
.
├── index.html      # الصفحة كاملة (HTML + CSS + JS)
├── assets/         # الصور، الفيديو، والخط
├── libs/           # GSAP و ScrollTrigger و Lenis
└── screenshots/    # لقطات README
```

## التشغيل محلياً

الموقع ملفات ثابتة، يكفي أي سيرفر محلي:

```bash
npx serve .
```

ثم افتح http://localhost:3000

## النشر

مستضاف على Vercel: **https://ghurza.vercel.app**

---

<div align="center">

© ٢٠٢٦ غُرزة للأزياء الراقية · الرياض

</div>
