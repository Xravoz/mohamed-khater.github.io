# SOC Log

مدونة شخصية لتوثيق مذاكرة الـ SOC. كل مقال ملف `.md` داخل فولدر `posts/`.

## إضافة مقال
1. انسخ `posts/_template.md` باسم جديد مثل `004-kql-basics.md`.
2. عدّل الهيدر (title, date, category, tags, level) واكتب المحتوى.
3. أضف اسم الملف في `posts/index.json`.
4. اعمل commit و push، والموقع يتحدث لوحده.

level: easy | medium | hard | done

## التشغيل محليًا
python -m http.server  ثم افتح http://localhost:8000

## النشر
Settings > Pages > Deploy from branch > main > / (root)
