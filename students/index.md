---
layout: home
permalink: students
title: "Students"
excerpt: " <br> <br>"
image:
  feature: 20100425_039.jpg
---
<a href="https://docs.google.com/spreadsheets/d/e/2PACX-1vRyVFfzfokaCSDqPi6lNDvPVpCvSmqTusbFEi8BTDBxFlax-4TkQLXIzovC0uF59syXBTvfz3ebf8Cd/pubhtml?gid=1481890826&single=true" class="btn--info">View Potential Honours, Masters and PhD research projects here</a>

<h2 class="post-title">PhD Candidates</h2>
<div class="tiles">
{% for post in site.categories.phd-students %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<div><h2 class="post-title">Masters and Honours students</h2></div>
<div class="tiles">
{% for post in site.categories.masters-students %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
