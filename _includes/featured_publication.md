{% for link in site.data.publications.main %}
{% if link.featured %} 
<div class="featured-pub">
  <div class="pub-row">
    <div class="col-sm-12">
      <div class="title">{{ link.title }}</div>
      <div class="authors">{{ link.authors }}</div>
    </div>
  </div>
  <div class="pub-row">
    <div class="content-links">
      <div class="content-link">
        <a href="{{ link.pdf}}">View paper here!</a>
      </div>
      <div class="content-link">
        <a href="{{ link.code}}">View code here!</a>
      </div>
    </div>
  </div>
  <div class="pub-row">
      <img src="{{ link.image_big }}" class="featured-pub-img img-fluid z-depth-1" style="margin: auto;">
  </div>
  <div class="pub-row">
    <div class="col-sm-12" style="position: relative;padding-right: 15px;padding-left: 20px;">
      {{ link.description }}
    </div>
  </div>
</div>
<br>
{% endif %}
{% endfor %}