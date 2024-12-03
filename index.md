---
title: التعليمات المستضافة عبر الإنترنت
permalink: index.html
layout: home
---

# MS-4008: تجربة تفاعلية مع Microsoft 365 Copilot للمديرين التنفيذيين 

## دليل المحتوى

تستند العروض التوضيحية لهذه الدورة التدريبية إلى العروض التوضيحية من مجموعة أدوات المسرّع [Demo Guide and Talking Points.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG).

من المهم أن تتعرف على العروض التوضيحية قبل تقديم هذا التدريب. بالنسبة للعديد من الأنشطة العملية، ستستخدم مستندات نموذجية واجتماعات Teams ورسائل البريد الإلكتروني المعدة مسبقًا.

- نزّل كافة نماذج المستندات مسبقًا من [هنا](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/tree/master/ResourceFiles).
- قم بإعداد اجتماعات Teams وسلاسل البريد الإلكتروني باتباع الإرشادات [هنا](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG).
- تعرف على التجربة التفاعلية:
    - الخيار 1: [aka.ms/CopilotEE](https://aka.ms/CopilotEE)
    - الخيار 2: [aka.ms/TeamsEE](https://aka.ms/TeamsEE)

    > **ملاحظة:** إذا لم يكن لدى المشاركين ترخيص Microsoft 365 Copilot، فيمكنهم الاستفادة من الإصدار التجاري المجاني من التجربة الموجود على [aka.ms/CopilotWebEE](https://aka.ms/CopilotWebEE).

## وصف الدورة التدريبية

اكتشف كيف يعمل Microsoft 365 Copilot على تعزيز الإنتاجية والابتكار في مكان العمل. تُوفر هذه التجربة، المصممة خصيصًا لرائد الأعمال الحديث، رؤى حول صياغة المطالبات السياقية لـ Copilot وتتضمن تمارين حالات استخدام جذابة تعرض التكامل السلس في سير العمل اليومي.

تتمثل الأهداف الأساسية لهذا التسليم في:

- تعريف المشاركين ببرنامج Microsoft 365 Copilot وتعليمهم كيفية صياغة مطالبة فعالة
- عرض Microsoft 365 Copilot في تطبيقات Office (ما يصل إلى 3 عروض توضيحية)
- توجيه المشاركين من خلال تجربة تفاعلية
- دعوة المشاركين لتنزيل وتجربة Microsoft Copilot للأجهزة المحمولة

## توقيت الدورة التدريبية (تقدير) 

| # | الموضوع                                 | الوقت الإجمالي      |
|---|---------------------------------------|-----------------|
| 1 | مقدمة إلى Microsoft 365 Copilot | 10 دقيقة    |
| 2 | دليل المديرين التنفيذيين لصياغة المطالبات الفعّالة | 30 دقيقة      |
| 3 | تجربة Microsoft 365 Copilot التفاعلية  | 20 دقيقة      |
|   |                                       | **الوقت الإجمالي 60 دقيقة** |


تجد أدناه الروابط التشعبية لكل العروض التوضيحية.

## العروض التوضيحية

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| العرض التوضيحي |
| --- |
{% للنشاط في العرض التوضيحي %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
