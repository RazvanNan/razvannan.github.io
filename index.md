# Header 1

## Content

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

## Pages

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

----
{{site.pages}}


Text cu **bold**

![Me]([https://github.com/RazvanNan/razvannan.github.io/blob/main/3A7888A1-8256-4835-9C6A-060C36BDF92A.jpeg?raw=true](https://avatars.githubusercontent.com/u/29168778?v=4))


Un post: [aici](https://razvannan.github.io/Post1)
