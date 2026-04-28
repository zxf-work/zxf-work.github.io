<h2 id="publications">Selected Publications</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}

<li>
<div class="pub-row">
  {% if link.image or link.conference_short %}
  <div class="abbr">
    {% if link.image %} 
    <img src="{{ link.image }}" class="teaser" alt="{{ link.title }} teaser">
    {% endif %}
    {% if link.conference_short %} 
    <abbr class="badge">{{ link.conference_short }}</abbr>
    {% endif %}
  </div>
  {% endif %}
  <div class="publication-details">
      <div class="title"><a href="{{ link.pdf }}">{{ link.title }}</a></div>
      <div class="author">{{ link.authors }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn" role="button" target="_blank" rel="noopener">PDF</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn" role="button" target="_blank" rel="noopener">Code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn" role="button" target="_blank" rel="noopener">Project Page</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn" role="button" target="_blank" rel="noopener">BibTex</a>
      {% endif %}
      {% if link.notes %} 
      <strong class="publication-note">{{ link.notes }}</strong>
      {% endif %}
      {% if link.others %} 
      {{ link.others }}
      {% endif %}
    </div>
  </div>
</div>
</li>

{% endfor %}

</ol>
</div>

{% if site.google_scholar %}
<p class="publication-more">Please see my <a href="{{ site.google_scholar }}" target="_blank" rel="noopener">Google Scholar profile</a> for the full list of publications.</p>
{% endif %}
