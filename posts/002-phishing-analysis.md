---
title: تحليل إيميل Phishing خطوة بخطوة
date: 2026-11-10
category: Incident Response
tags: [phishing, email, analysis]
level: easy
summary: طريقة منظمة لفحص إيميل مشبوه من الهيدر لحد الـ URL.
---

## خطوات الفحص
1. افحص **Header**: `From` و `Return-Path` و `Received`.
2. شوف نتيجة **SPF / DKIM / DMARC**.
3. افحص الروابط من غير ما تضغط عليها.
4. حلل المرفقات في بيئة معزولة (Sandbox).

## أدوات استخدمتها
- VirusTotal للروابط والـ hashes
- URLScan لتحليل الصفحة
- MXToolbox لقراءة الـ Header
