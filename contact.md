---
layout: page
title: Contact
permalink: /contact/
description: How to reach us online — website, patient portal, WhatsApp and social media.
---

## Website

Visit [{{ site.website_name }}]({{ site.website_url }}){:rel="noopener" target="_blank"}.

## Online portal

Sign in to the [{{ site.portal_name }}]({{ site.portal_url }}){:rel="noopener" target="_blank"}
to manage your account.

{% assign c = site.contact %}
{% if c.whatsapp_number != "" %}
## WhatsApp

[Message us on WhatsApp](https://wa.me/{{ c.whatsapp_number }}){:rel="noopener" target="_blank"}
{% endif %}

{% assign has_social = false %}
{% if c.facebook_url != "" or c.instagram_url != "" or c.snapchat_url != "" or c.linkedin_url != "" or c.x_url != "" %}
  {% assign has_social = true %}
{% endif %}
{% if has_social %}
## Social media

<ul>
  {% if c.facebook_url != "" %}<li><a href="{{ c.facebook_url }}" rel="noopener" target="_blank">Facebook</a></li>{% endif %}
  {% if c.instagram_url != "" %}<li><a href="{{ c.instagram_url }}" rel="noopener" target="_blank">Instagram</a></li>{% endif %}
  {% if c.snapchat_url != "" %}<li><a href="{{ c.snapchat_url }}" rel="noopener" target="_blank">Snapchat</a></li>{% endif %}
  {% if c.linkedin_url != "" %}<li><a href="{{ c.linkedin_url }}" rel="noopener" target="_blank">LinkedIn</a></li>{% endif %}
  {% if c.x_url != "" %}<li><a href="{{ c.x_url }}" rel="noopener" target="_blank">X</a></li>{% endif %}
</ul>
{% endif %}

> Never share passwords, one-time codes or medical details over WhatsApp or
> social media. Use the online portal for anything private.
