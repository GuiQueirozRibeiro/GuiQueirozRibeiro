---
layout: default
---

<div>
  <a href="{{ page.url | replace: '/en/', '/pt/' }}">Português</a>
  <a href="{{ page.url | replace: '/pt/', '/en/' }}">English</a>
</div>

{% raw %}
{% if page.lang == 'en' %}
{% assign readme = site.data.readme_en %}
{% else %}
{% assign readme = site.data.readme_pt %}
{% endif %}

{{ readme }}
{% endraw %}
