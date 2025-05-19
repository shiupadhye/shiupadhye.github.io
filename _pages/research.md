---
layout: default
title: "Research"
permalink: /research/
---

*= Equal Contribution

<h1 class="pub-header">Publications</h1>

<div class="pub-list">
  {% for link in site.data.publications.main %}
    <div class="pub-item">

      <p class="pub-entry">
        {{ link.authors 
          | replace: "Yaoyao Liu*", "<strong>Yaoyao Liu*</strong>" 
          | replace: "Yaoyao Liu", "<strong>Yaoyao Liu</strong>" 
        }}
        {% if link.year %} ({{ link.year }}){% endif %}. {{ link.title }} <em>{{ link.conference }}</em>
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

<h1 class="pub-header"> Conference Presentations</h1>

<div class="presentation-entry">

<p><strong>Upadhye S.</strong> and Futrell, R. (2025). Examining Future Context Predictability Effects in Word-form Variation and Word Choice. <em>47th Annual Meeting of the Cognitive Science Society.</em> San Francisco, CA, USA. <strong>Upcoming.</strong> (<strong>Talk</strong>)</p>

<p><strong>Upadhye S.</strong>, Yeaton, JD., Yi, E., and Hickok, G. (2025). Typing Fluency reveals Psycholinguistic Dynamics of Sentence Production. <em>The 38th Annual Conference on Human Sentence Processing.</em> College Park, MD, USA. (<strong>Poster</strong>)</p>

<p>Li J.*, <strong>Upadhye S.</strong>*, and Futrell, R. (2025). SPACER: A Parallel Dataset of Speech Production And Comprehension of Error Repairs <em>The 38th Annual Conference on Human Sentence Processing. </em> College Park, MD, USA. (<strong>Poster</strong>)</p>

<p>Li Y., Li J., <strong>Upadhye S.</strong>, and Scontras, G. (2025). Language models prefer ambiguous utterances following informative contexts <em>The 38th Annual Conference on Human Sentence Processing. </em> College Park, MD, USA. (<strong>Poster</strong>)</p>

<p>Yeaton, JD, <strong>Upadhye, S.</strong>, Futrell, R., and Hickok, G. (2024). The (Non-)Sentence Repetition Task: A novel assessment of expressive and receptive syntactic competence. <em>16th Annual Meeting of the Society for the Neurobiology of Language.</em> Brisbane, Australia. (<strong>Poster</strong>)</p>

<p><strong>Upadhye S.</strong>, Attali N. and Scontras, G. (2023). The role of world knowledge for interpreting aspect ambiguity. <em>Tenth Biennial Meeting of Experimental Pragmatics. </em> Paris, France. (<strong>Poster</strong>)</p>

<p><strong>Upadhye S.</strong>*, Li, J.* and Futrell, R. (2023). Bridging production and comprehension: Toward an integrated computational model of error correction. <em>Society for Computation in Linguistics (SCiL 2023).</em> Amherst, MA, USA. (<strong>Poster</strong>)</p>

<p>Li, J.*, <strong>Upadhye, S</strong>.* and Futrell, R. (2023). Bridging production and comprehension: A computational model of error generation and correction. <em>The 36th Annual Conference on Human Sentence Processing.</em> Pittsburgh, PA, USA. (<strong>Poster</strong>)</p>

<p><strong>Upadhye S.</strong> and Futrell R. (2022). Information-theoretic analysis of disfluencies in speech. <em>NeurIPS 2022 Workshop on Information Theoretic Principles in Cognitive Systems.</em> New Orleans, LA, USA. (<strong>Poster</strong>)</p>
</div>


