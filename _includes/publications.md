<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}
{% include single_publication.md pub=link %}

<br>

{% endfor %}
</ol>

</div>

