# Introduction
This is a repo created for the course project in CSCI 3251. We have 8 tasks, mostly for getting used to how github works, including writing simple codes, trying how to do commit, and review other people's work.
# Code
# Contributors
{% for stu in site.stus %}
  <h2>{{ stu.user }} - {{ stu.name }}</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}
