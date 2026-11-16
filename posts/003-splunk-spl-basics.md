---
title: أساسيات SPL في Splunk من البحث للإحصائيات
date: 2026-11-15
category: SIEM
tags: [splunk, spl, queries]
level: medium
summary: أهم أوامر البحث اللي بتحتاجها في أول يوم شغل على Splunk.
---

## الأوامر الأساسية
```
index=wineventlog EventCode=4625
| stats count by src_ip, user
| sort - count
| head 10
```

- `stats` للتجميع والعدّ.
- `sort - count` ترتيب تنازلي.
- `head` لأول N نتيجة.

> **ملاحظة:** حدد الـ time range دايمًا قبل ما تشغّل البحث.

## اللي عملته النهارده
- [x] جربت الأوامر على بيانات تجريبية
- [ ] أعمل Dashboard صغير للمحاولات الفاشلة
