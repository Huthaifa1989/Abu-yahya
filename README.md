# مشروع أبو يحيى - إدارة الإرساليات والسائقين

## وصف المشروع
منصة ويب متكاملة لإدارة السائقين والإرساليات، تتيح:
- رفع صور الإرساليات وربطها برقم الهوية.
- إضافة وتعديل بيانات السائقين مع رفع صور الوثائق.
- حفظ البيانات في Firebase Firestore وتخزين الصور في Cloudinary.
- تصميم متجاوب وسهل الاستخدام يدعم الجوال والكمبيوتر.

---

## محتويات المشروع

```
abu-yahya-project/
├── public/
│   ├── index.html                  # الصفحة الرئيسية
│   ├── upload-shipment.html        # رفع الإرساليات للسائقين
│   ├── manage-drivers.html         # إدارة وإضافة السائقين
│   ├── drivers.html                # قائمة السائقين
│   ├── driver-profile.html         # تفاصيل السائق
│   ├── trucks.html                 # قائمة الشاحنات
│   ├── truck-profile.html          # تفاصيل الشاحنة
│   ├── shipments.html              # قائمة الإرساليات
│   ├── shipments-by-driver.html    # إرساليات حسب السائق
│   ├── dashboard.html              # لوحة التحكم
│   ├── ... (صفحات وصور وأيقونات أخرى)
│   └── manifest.json               # إعدادات PWA
├── firebase.json                   # إعدادات استضافة Firebase
├── firestore.rules                 # قواعد أمان قاعدة البيانات
├── storage.rules                   # قواعد أمان التخزين
├── .gitignore                      # ملفات مستثناة من Git
├── README.md                       # ملف التوثيق
└── ... (ملفات إعداد أخرى)
```

---

## شرح الملفات المهمة

- **upload-shipment.html**  
  صفحة رفع الإرساليات للسائقين مع دعم رفع عدة صور ومعاينتها.

- **manage-drivers.html**  
  صفحة إضافة وتعديل بيانات السائقين مع رفع صور الوثائق وعرض التفاصيل بعد الحفظ.

- **firebase.json / firestore.rules / storage.rules**  
  إعدادات وقواعد الأمان الخاصة بـ Firebase.

- **manifest.json / sw.js**  
  دعم تطبيق ويب تقدمي (PWA).

---

## طريقة الاستخدام

1. افتح الصفحة المناسبة من مجلد `public` (مثلاً: `upload-shipment.html` أو `manage-drivers.html`).
2. أدخل البيانات المطلوبة وارفع الصور.
3. اضغط زر الحفظ أو رفع الإرسالية.
4. ستظهر رسالة نجاح أو تفاصيل السائق/الإرسالية بعد الحفظ.

---

## التقنيات المستخدمة

- HTML, CSS, JavaScript
- Firebase Firestore & Storage
- Cloudinary API
- Google Fonts (Cairo)
- PWA (manifest, sw.js)

---

## أوامر النشر على Firebase Hosting

```bash
firebase login
firebase deploy --only hosting
```

---

## أوامر رفع المشروع إلى GitHub

```bash
git init
git add .
git commit -m "أول رفع للمشروع"
git remote add origin https://github.com/Huthaifa1989/-.git
git push -u origin main
```

---

## حقوق الاستخدام

هذا المشروع مفتوح المصدر ويمكن تعديله واستخدامه بحرية.

---
