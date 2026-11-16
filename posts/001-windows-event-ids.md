---
title: Windows Event IDs اللي لازم يتحفظوا
date: 2026-11-05
category: Windows Logs
tags: [windows, event-id, detection]
level: done
summary: قائمة الأحداث الأهم في الـ Security Log وبتدل على إيه.
---

## ليه مهمة؟
أغلب التحقيقات على أجهزة Windows بتبدأ من Security Log.

| Event ID | الوصف |
|---|---|
| 4624 | تسجيل دخول ناجح |
| 4625 | تسجيل دخول فاشل |
| 4672 | صلاحيات خاصة اتمنحت |
| 4688 | عملية جديدة اتعملت |
| 1102 | الـ Audit Log اتمسح |

## نصيحة
أي ظهور لـ **1102** لازم يتعامل معاه كمؤشر خطير لحد ما يتثبت العكس.
