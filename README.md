# FaceShift

FaceShift is an integrated project that enables face-swapping using AI across multiple platforms, including web, desktop, and mobile applications. The project contains both frontend and backend files, with settings for the main web page.

## Project Structure

FaceShift/
│
├── backend/              # الملفات الخلفية لتبديل الوجوه
│   ├── app.py            # ملف Flask API
│   ├── model.py          # نماذج تبديل الوجوه باستخدام الذكاء الاصطناعي
│   └── utils.py          # أدوات المساعدة مثل الكشف عن الوجوه
│
├── frontend/             # ملفات واجهة الويب الأمامية
│   ├── public/           # الملفات العامة مثل HTML، صور وأيقونات
│   ├── src/
│   │   ├── App.js        # تطبيق React الرئيسي
│   │   ├── components/   # مكونات React (أزرار، معاينات، إلخ)
│   │   └── styles/       # ملفات CSS
│
├── electron/             # ملفات تطبيق سطح المكتب باستخدام Electron
│   ├── main.js           # ملف تشغيل التطبيق باستخدام Electron
│   └── preload.js        # إعدادات واجهة المستخدم الأصلية
│
├── mobile/               # ملفات تطبيق الموبايل باستخدام React Native
│   ├── App.js            # التطبيق الرئيسي
│   └── components/       # مكونات الموبايل
│
└── website/              # ملفات صفحة الويب (HTML للتنزيل والتعليمات)
    ├── index.html        # الصفحة الرئيسية
    ├── styles.css        # التنسيقات
    └── install-guide.html # دليل التثبيت
