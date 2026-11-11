# الكايس – Caisse (نقطة بيع للمقاهي والمطاعم)

## النشر على GitHub Pages
```bash
cd caisse
git init && git add . && git commit -m "Première version"
git branch -M main
git remote add origin https://github.com/mohamedrezzoug/caisse.git
git push -u origin main
```
GitHub → Settings → Pages → Source: `main` / root.
الرابط: https://mohamedrezzoug.github.io/caisse/

## التثبيت فالبيسي (Windows / Mac)
1. حل الرابط فـ Chrome أو Edge.
2. كليكي على أيقونة التثبيت فاليمين ديال شريط العنوان (أو الزر الأخضر "تثبيت" فالتطبيق).
3. غادي يبان فالـ Start / Bureau بحال برنامج عادي ويخدم حتى بلا إنترنت.

## ملاحظات
- المعطيات كتتسجل فنفس البيسي (localStorage). دير "تصدير النسخة" من الإعدادات بين الفينة والأخرى.
- لتغيير المنتجات/الأثمنة/الألوان/عدد الطاولات: زر الإعدادات.
- الطباعة: كتخدم مع أي طابعة تذاكر 80mm (اختار الطابعة فنافذة الطباعة).
- عند كل تحديث غير الرقم فـ `sw.js` (`caisse-v1` → `caisse-v2`).

- الإعدادات ← قوائم جاهزة: مقهى / مطعم / الاثنين. وكل منتج عندو ⚙ لتعديل الأيقونة والأنواع والإضافات.
