---
layout: default
---

{% raw %}
{% if page.lang == 'en' %}
{% assign readme = site.data.readme_en %}
{% else %}
{% assign readme = site.data.readme_pt %}
{% endif %}

{{ readme }}
{% endraw %}
