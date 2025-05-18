<div>
<h2 class="pub-header">Publications</h2>
<div class="pub-list">
  {% for link in site.data.publications.main %}
    <div class="pub-item">

      <p class="pub-entry">
        {{ link.authors 
          | replace: "Yaoyao Liu*", "<strong>Yaoyao Liu*</strong>" 
          | replace: "Yaoyao Liu", "<strong>Yaoyao Liu</strong>" 
        }}. 
        {% if link.year %}({{ link.year }}).{% endif %}
        {{ link.title }}.
      </p>

      <p class="pub-venue"><em>{{ link.conference }}</em>.</p>

      <p class="pub-links">
        {% if link.pdf %}<a href="{{ link.pdf }}" target="_blank">PDF</a>{% endif %}
        {% if link.code %}<a href="{{ link.code }}" target="_blank">Code</a>{% endif %}
        {% if link.page %}<a href="{{ link.page }}" target="_blank">Project Page</a>{% endif %}
        {% if link.bibtex %}<a href="{{ link.bibtex }}" target="_blank">BibTeX</a>{% endif %}
        {% if link.notes %}<span class="pub-note">{{ link.notes }}</span>{% endif %}
        {% if link.others %}<span class="pub-note">{{ link.others }}</span>{% endif %}
      </p>
    </div>
  {% endfor %}
</div>
