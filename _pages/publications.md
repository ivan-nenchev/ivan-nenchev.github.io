---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}](https://scholar.google.com/citations?hl=en&user=kjmxxD0AAAAJ&sortby=pubdate&view_op=list_works&citft=1&citft=2&email_for_op=ivan.nenchev.nenchev%40gmail.com&gmla=ABOlHizWsn0-gbKndDwb9tKn6xCF-yv0OEcJZeqcHXPpwMqyB4qEWF4chka6_WbRs9kVa45fXAwSv651I_0a_23ZfOdbOMyqHXyuzH2rmr_IJfVqmMQMAoQT6gTWzARHfGBbbYpbUU7tJ8hIoVVg0MBJY8YhvMOsO_UuOqP-UAiIWoqN_7RnOZ_WbJGpk7WkvGh9HIxOgGuz0H8BvtLq8lAlr_vJ5aLH1Wk87T45T0NmF5I3ovx25qjFbTzFlA}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
