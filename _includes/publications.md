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
      <div class="title">
        {% if link.pdf %}
        <a href="{{ link.pdf }}" target="_blank" rel="noopener">{{ link.title }}</a>
        {% else %}
        {{ link.title }}
        {% endif %}
      </div>
      <div class="author">{{ link.authors | replace: "Xiaofei Zhang", "<strong>Xiaofei Zhang</strong>" }}</div>
      <div class="periodical"><em>{{ link.conference }}</em>
      </div>
    <div class="links">
      {% if link.pdf %} 
      <a href="{{ link.pdf }}" class="btn" target="_blank" rel="noopener">paper</a>
      {% endif %}
      {% if link.code %} 
      <a href="{{ link.code }}" class="btn" target="_blank" rel="noopener">code</a>
      {% endif %}
      {% if link.page %} 
      <a href="{{ link.page }}" class="btn" target="_blank" rel="noopener">project</a>
      {% endif %}
      {% if link.bibtex %} 
      <a href="{{ link.bibtex }}" class="btn" target="_blank" rel="noopener">bibtex</a>
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
