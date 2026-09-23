---
layout: page
title: بالعربية
permalink: /ar/
lang: ar
description: صفحة التعريف بالعربية — الموقع الرسمي والبوابة الإلكترونية ووسائل التواصل.
---

<div dir="rtl" markdown="1">

## أهلاً بكم

يسعدنا تواصلكم معنا عبر القنوات الرسمية التالية.

### الموقع الرسمي

[{{ site.website_name }}]({{ site.website_url }}){:rel="noopener" target="_blank"}

### البوابة الإلكترونية

للدخول إلى حسابك وإدارة بياناتك:
[{{ site.portal_name }}]({{ site.portal_url }}){:rel="noopener" target="_blank"}

### وسائل التواصل

{% assign c = site.contact %}
<ul>
  {% if c.whatsapp_number != "" %}<li><a href="https://wa.me/{{ c.whatsapp_number }}" rel="noopener" target="_blank">واتساب</a></li>{% endif %}
  {% if c.instagram_url != "" %}<li><a href="{{ c.instagram_url }}" rel="noopener" target="_blank">إنستغرام</a></li>{% endif %}
  {% if c.snapchat_url != "" %}<li><a href="{{ c.snapchat_url }}" rel="noopener" target="_blank">سناب شات</a></li>{% endif %}
  {% if c.tiktok_url != "" %}<li><a href="{{ c.tiktok_url }}" rel="noopener" target="_blank">تيك توك</a></li>{% endif %}
  {% if c.facebook_url != "" %}<li><a href="{{ c.facebook_url }}" rel="noopener" target="_blank">فيسبوك</a></li>{% endif %}
</ul>

> تنبيه: لا ترسل كلمات المرور أو رموز التحقق أو أي تفاصيل طبية عبر واتساب أو
> وسائل التواصل الاجتماعي. استخدم البوابة الإلكترونية لأي معلومات خاصة.

</div>
