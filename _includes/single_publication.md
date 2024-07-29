<li>
<div class="pub-row">
  <div class="col-sm-3 abbr" style="position: relative;padding-right: 15px;padding-left: 15px;">
    {% if include.pub.image %} 
    <img src="{{ include.pub.image }}" class="teaser img-fluid z-depth-1" style="max-width=100%;max-height=100%">
    {% endif %}
    {% if include.pub.conference_short %} 
    <abbr class="badge">{{ include.pub.conference_short }}</abbr>
    {% endif %}
  </div>
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title"><a href="{{ include.pub.pdf }}">{{ include.pub.title }}</a></div>
      <div class="author">{{ include.pub.authors }}</div>
      <div class="periodical"><em>{{ include.pub.conference }}</em>
      </div>
    <div class="links">
      {% if include.pub.pdf %} 
      <a href="{{ include.pub.pdf }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">PDF</a>
      {% endif %}
      {% if include.pub.code %} 
      <a href="{{ include.pub.code }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Code</a>
      {% endif %}
      {% if include.pub.page %} 
      <a href="{{ include.pub.page }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">Project Page</a>
      {% endif %}
      {% if include.pub.bibtex %} 
      <a href="{{ include.pub.bibtex }}" class="btn btn-sm z-depth-0" role="button" target="_blank" style="font-size:12px;">BibTex</a>
      {% endif %}
      {% if include.pub.notes %} 
      <strong> <i style="color:#e74d3c">{{ include.pub.notes }}</i></strong>
      {% endif %}
      {% if include.pub.others %} 
      {{ include.pub.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>