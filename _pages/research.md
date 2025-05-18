---
layout: default
title: "Research"
permalink: /research/
---

<h2 class="pub-header">Publications</h2>

<div class="pub-list">
  {% for link in site.data.publications.main %}
    <div class="pub-item">

      <p class="pub-authors">
      <p class="pub-entry">
        {{ link.authors 
          | replace: "Yaoyao Liu*", "<strong>Yaoyao Liu*</strong>" 
          | replace: "Yaoyao Liu", "<strong>Yaoyao Liu</strong>" 
        }}
        {% if link.year %} ({{ link.year }}){% endif %}.
        {% if link.year %} ({{ link.year }}){% endif %}. {{ link.title }}.
      </p>

      <p class="pub-title">
        {{ link.title }}. <em>{{ link.conference }}</em>.
      <p class="pub-venue">
        <em>{{ link.conference }}</em>.
      </p>

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

## Presentations

**Upadhye S.** & Futrell, R. (2025). Examining Future Context Predictability Effects in Word-form Variation and Word Choice (2025). <br>
*47th Annual Meeting of the Cognitive Science Society.* San Francisco, CA, USA. *Upcoming.* (**Talk**)

**Upadhye S.**, Yeaton, JD., Yi, E., & Hickok, G. (2025). Typing Fluency reveals Psycholinguistic Dynamics of Sentence Production. <br>
*The 38th Annual Conference on Human Sentence Processing.* College Park, MD, USA. (**Poster**)

Li J., **Upadhye S.**,* & Futrell, R. (2025). SPACER: A Parallel Dataset of Speech Production And Comprehension of Error Repairs. <br>
*The 38th Annual Conference on Human Sentence Processing.* College Park, MD, USA. (**Poster**)

Li Y., Li J., **Upadhye S.**, & Scontras, G. (2025). Language models prefer ambiguous utterances following informative contexts. <br>
*The 38th Annual Conference on Human Sentence Processing.* College Park, MD, USA. (**Poster**)

Yeaton, JD, **Upadhye, S.**, Futrell, R., & Hickok, G. (2024). The (Non-)Sentence Repetition Task: A novel assessment of expressive and receptive syntactic competence. <br> *16th Annual Meeting of the Society for the Neurobiology of Language.* Brisbane, Australia. (**Poster**)

**Upadhye S.**, Attali N. & Scontras, G. (2023). The role of world knowledge for interpreting aspect ambiguity. <br>
*Tenth Biennial Meeting of Experimental Pragmatics.* Paris, France. (**Poster**)

**Upadhye S.***, Li, J.* & Futrell, R. (2023). Bridging production and comprehension: Toward an integrated computational model of error correction. <br> *Society for Computation in Linguistics (SCiL 2023)*. Amherst, MA, USA. (**Poster**).

Li, J.*, **Upadhye, S**.* & Futrell, R. (2023) Bridging production and comprehension: A computational model of error generation and correction. <br>
*The 36th Annual Conference on Human Sentence Processing.* Pittsburgh, PA, USA. (**Poster**)

**Upadhye S.** & Futrell R. (2022). Information-theoretic analysis of disfluencies in speech. <br>
*NeurIPS 2022 Workshop on Information Theoretic Principles in Cognitive Systems.* New Orleans, LA, USA. **(Poster)**
