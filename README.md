# Introduction
This is a repo created for the course project in CSCI 3251. We have 8 tasks, mostly for getting used to how github works, including writing simple codes, trying how to do commit, and review other people's work.
# Code
# Contributors
{% for stu in site.stu %}

  <h2>{{ stu.image }}</h2>
  <p>{{ stu.user }}</p>
  <p>{{ stu.name }}</p>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
