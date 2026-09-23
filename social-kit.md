---
layout: page
title: Social media kit
permalink: /social-kit/
sitemap: false
description: Ready-to-use captions and a publishing checklist for the reception team.
---

<p><em>For internal use by the reception team. Copy a caption, replace anything
in CAPITALS, and post it from the official account.</em></p>

{% assign c = site.contact %}

## Before you post

1. Post only from the official accounts listed on the [contact page]({{ '/contact/' | relative_url }}).
2. Do not publish photos of patients, documents, or anything that identifies a
   person — not even with the face covered — unless you have written consent.
3. Do not promise results, name medicines, or state prices for treatments.
   Health advertising in the UAE must follow the rules of the local health
   authority; when in doubt, ask the manager before posting.
4. Never reply to a public comment with personal or medical details. Move the
   conversation to WhatsApp or the portal.
5. Check spelling in both Arabic and English before publishing.

## Captions you can reuse

### 1. Welcome / introduction

> English: Welcome to {{ site.website_name }}. Book, message us, or manage your
> account online — all the links are in our bio.
>
> العربية: أهلاً بكم في {{ site.website_name }}. تواصلوا معنا أو أديروا حسابكم
> إلكترونياً — جميع الروابط في الوصف.

### 2. Online portal is live

> English: Our online portal is live. Sign in any time to manage your account.
> Link in bio.
>
> العربية: البوابة الإلكترونية متاحة الآن. سجّل الدخول في أي وقت لإدارة حسابك.
> الرابط في الوصف.

### 3. Opening hours

> English: We are open DAY–DAY, TIME–TIME. Message us on WhatsApp for anything
> you need.
>
> العربية: نستقبلكم من اليوم إلى اليوم، من الساعة كذا إلى كذا. راسلونا على
> واتساب لأي استفسار.

### 4. Reply to a public enquiry

> English: Thank you for reaching out. Please send us a message on WhatsApp so
> we can help you privately.
>
> العربية: شكراً لتواصلكم. يُرجى مراسلتنا على واتساب لنتمكن من مساعدتكم بشكل خاص.

### 5. Closed / holiday notice

> English: We will be closed on DATE and back on DATE. You can still reach us
> through the online portal.
>
> العربية: سنكون مغلقين بتاريخ كذا ونعود بتاريخ كذا. يمكنكم التواصل معنا عبر
> البوابة الإلكترونية.

## Links to put in the bio

<ul>
  <li>{{ site.website_name }}: <code>{{ site.website_url }}</code></li>
  <li>{{ site.portal_name }}: <code>{{ site.portal_url }}</code></li>
  {% if c.whatsapp_number != "" %}<li>WhatsApp: <code>https://wa.me/{{ c.whatsapp_number }}</code></li>{% endif %}
</ul>

## Hashtags

`#RasAlKhaimah` `#RAK` `#راس_الخيمة` `#الامارات`

Add a few that describe the specific post. Ten or fewer is enough.
