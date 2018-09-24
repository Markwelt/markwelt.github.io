---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Fuscà, Marco; Neuling, Toralf; Ruhnau, Philipp; Weisz, Nathan (2018) Local network-level integration mediates effects of transcranial Alternating Current Stimulation. Brain Connectivity, 8(4), 212-219. - DOI: 10.1101/216176
Ruhnau, Philipp; Neuling, Toralf; Fuscà, Marco; Herrmann, Christoph S.; Demarchi, Gianpaolo; Weisz, Nathan (2016) Eyes wide shut: Transcranial alternating current stimulation drives alpha rhythm in a state dependent manner Scientific Reports, 6, 27138. - DOI: 10.1038/srep27138
Gregory, Sarah; Fuscà, Marco; Rees, Geraint; Schwarzkopf, D. Samuel; Barnes, Gareth (2016) Gamma frequency and the spatial tuning of primary visual cortex Plos One 11(6), e0157374. - DOI: 10.1371/journal.pone.0157374
Neuling, Toralf; Ruhnau, Philipp; Fuscà, Marco; Demarchi, Gianpaolo; Herrmann, Christoph S.; Weisz, Nathan (2015) Friends, not foes: Magnetoencephalography as a tool to uncover brain dynamics during transcranial alternating current stimulation NeuroImage 118, 406-413. - DOI: 10.1016/j.neuroimage.2015.06.026

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
