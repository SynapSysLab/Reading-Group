---
layout: default
---

<div class="intro" markdown="1">

# SynapSys Reading Group

An open academic reading group where researchers and practitioners present and discuss papers in:

- Distributed Systems
- Cloud Computing
- LLM Inference & Fine-tuning
- AI Agents & Agentic AI
- AI Systems

</div>

{% for track in site.data.sessions %}
<h2 id="{{ track.id }}">{{ track.title }}</h2>
<div class="table-wrap">
{% include sessions-table.html track=track %}
</div>
{% endfor %}
