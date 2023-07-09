## About Me

Hello! I enjoy CS stuff and mathematics. I'm currently unemployed taking a break from work but typically work in tech as a software engineer.

## Contact

You can reach me via email at <contact@ryanrose.me> or [Linkedin](https://www.linkedin.com/in/ryanthrose).

## Blog

{% for post in site.posts %}
  * [{{ post.title }} ({{ post.date | date: "%-d %B %Y" }})]({{ post.url }})
{% endfor %}

