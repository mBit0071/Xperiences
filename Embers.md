---
title: Embers
layout: page
---

Following are posts related to Lucid dreams.

~~~
There were days when each hour was a war I fought to survive
..
But the world took a spark like a match in the dark and the fire brought me back to life.
So, I'm fanning the flames so high 'cause there is no other way we can stay alive. 
..
And you'll find, there be morning when the ashes and embers are cold,
But you'll fight with a passion and you'll never stop 'cause you know,
Yeah you know it get's better..
Every push, every shove, every war, every love 
Yeah the coals are beginning to glow
..
Don't let the fire die,
It gets better.
..
~~~

Hope these days pass soon. The idea is to do as many positive or neutral changes as possible on these days.

Following are posts related to embers.

{% for category in site.categories %}

{% if category[0] contains page.title %}
{% for ps in category[1] %}
1. [{{ps.title}}]({{site.baseurl}}{{ps.url}}) 
{% endfor %}
{% endif %}
 
{% endfor %}

