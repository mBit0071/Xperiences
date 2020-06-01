---
title: LucidDreams
layout: page
---

Following are posts related to Lucid dreams.

~~~
I am a light sleeper, but I am a heavy dreamer.
My imagination gives me wings
..
Where passenger trains catch fire and fill the sky with flames
..
Do you believe, sleep is a time machine?
~~~

Following are posts related to lucid dreams.

{% for category in site.categories %}

{% if category[0] contains page.title %}
{% for ps in category[1] %}
1. [{{ps.title}}]({{site.baseurl}}{{ps.url}}) 
{% endfor %}
{% endif %}
 
{% endfor %}

