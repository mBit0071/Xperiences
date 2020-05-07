---
title: Xperiences
layout: default
---

# {{ page.title }}

This is my space where I can jot down my thoughts, dreams, experiences.

A little about me first. I am an computer science student who is an automotive enthusiast. You can call me **Petrolhead**, **Gearhead** or **car guy**. I support 'Save the Manuals'. I also write code for fun. Recently I have been working on some graphs for Coronavirus stats.

Strengths:
- Focused
- Can think deeply

Weaknesses:
- I lose motivation pretty quickly if I do not see the big picture.
- Communication - been working on improving this
- Sometimes, I can be forgetful. Note: This generally means the detail is not very important, or to bring that details to my working memory is not worth the effort. 

I do not have a pet. But if I had a dog I would name it **Zeus**.

Getting to the posts. They might have some side-stories or tangents. Do not let them confuse you with the main storyline. To make it easy, I will try to mark them. 

I am using numbers instead of names to protect identities of people in my surrondings. Each person gets a unique number.
### Landing page links

{% for ps in site.categories %}
1. [{{ps | first | strip_html}}]({{site.baseurl}}/{{ps | first | strip_html}})
{% endfor %}



