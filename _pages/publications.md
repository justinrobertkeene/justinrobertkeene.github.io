---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

#Research Philosophy

Three large-scale questions drive my research: 1). What effect, if any, does the inclusion or exclusion of message content features, such as emotional tone, camera angles, and social cues, have on cognitive, emotional, and behavioral responses? 2). Do cognitive biases and deficits, such as sports fanship and attentional deficits, affect these responses to mediated messages? 3). Does the context in which the message is consumed (e.g. with or without a peer or parent) affect these responses? Theories of communication, as well as theories drawn from the cognitive neurosciences, and social psychology, motivate this research. 

I utilize several quantitative, self-reported and psychophysiological measures, such as heart rate, skin conductance, facial electromyography (EMG), electroencephalography (EEG), eye tracking, secondary task reaction times, and continuous response measures, to appropriately answer these research questions. However, some research questions necessitate the use of qualitative approaches, such as focus groups and intercept interviews, to better understand the phenomena prior to quantitative testing. My analytical approach is heavily influenced by hypothesis testing, as well as cognitive- and time series-modeling. In addition to my theoretical work, I have also published best practices for the use of scalar and psychophysiological measures within the field of communication. 

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=VMpBzOoAAAAJ&hl=en&oi=ao">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

-----

# Conference Presentations

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
