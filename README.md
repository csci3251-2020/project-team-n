# Introduction
This is a repo created for the course project in CSCI 3251. We have 8 tasks, mostly for getting used to how github works, including writing simple codes, trying how to do commit, and review other people's work.
# Code

# Contributors

{% for stu in site.stu %}
  * <img src="{{ student.image }}" style="width: 50px; height: 50px"> @{{ stu.user }} ({{ stu.name }})
    * {{ stu.content | markdownify }}
{% endfor %}

Last Updated: {{ site.time }}
