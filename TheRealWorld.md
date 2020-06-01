---
title: TheRealWorld
layout: page
---

The Real world.

~~~
...
To gaze down on the city below, ablaze with wonderous things
...
Reality is a lovely place, but I would not want to live there
...
With a stary brush, paint the dusk venetian blue
because in the evening hush, you'll never believe the view.
...
Can you feel the silk embrace in the satin air?
If we dissolve without a trace, would the real world even care?
~~~

Following are posts related to the real world.

{% for category in site.categories %}

{% if category[0] contains page.title %}
{% for ps in category[1] %}
1. [{{ps.title}}]({{site.baseurl}}{{ps.url}}) 
{% endfor %}
{% endif %}
 
{% endfor %}

