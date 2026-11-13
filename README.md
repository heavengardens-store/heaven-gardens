# Heaven Gardens

موقع عرض وطلب منتجات Heaven Gardens — صفحة ثابتة (Static) بدون أي خطوات build.

## الملفات

| المسار | الوصف |
| --- | --- |
| `index.html` | الموقع كله: التصميم، بيانات المنتجات، والسلة |
| `assets/products/` | صور المنتجات (`name.jpg` للحجم الكامل و `name-sm.webp` للمصغّرة) |
| `assets/heaven-foods.jpg` | شعار Heaven Foods |

## تعديل الأسعار أو إضافة منتج

افتح `index.html` وابحث عن `const P=[` — كل سطر منتج:

- `pr` سعر الكرتونة، `pu` سعر القطعة
- `cat` لازم يطابق اسم قسم موجود في `CATS`
- `imgs` أسماء ملفات الصور داخل `assets/products` (بدون الامتداد) مع العرض `w` والارتفاع `h`

رقم WhatsApp موجود في `const WA` وفي روابط الهيدر والفوتر.

## النشر على GitHub Pages

Settings → Pages → Source: **Deploy from a branch** → اختر الفرع والمجلد `/ (root)` → Save.
