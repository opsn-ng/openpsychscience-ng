---
layout: page
title: Journal Club
subtitle: Discussing articles on Open Science
---

The OPSN Journal Club Meetings are scheduled for every last Friday of the month.

Sessions are open to anyone. You don't need to have read the paper in advance, and you don't need a background in statistics or methods to follow along.

## Next session

<div class="session-next">
  <span class="session-next-label">Next session</span>
  {% if site.data.next_meeting.scheduled %}
    <p class="session-next-paper">{{ site.data.next_meeting.paper_citation }}</p>
    <p>{{ site.data.next_meeting.display_date }} · {{ site.data.next_meeting.display_time }}</p>
    {% if site.data.next_meeting.paper_note %}
      <p>{{ site.data.next_meeting.paper_note }}</p>
    {% endif %}
    {% include next-meeting-actions.html %}
  {% else %}
    <p class="session-next-paper">To be announced</p>
    <p>Email us to be told as soon as it's scheduled, or to suggest a paper.</p>
  {% endif %}
</div>

## Previous sessions

<ul class="sessions">
  <li>
    <span class="session-date">September 25, 2026</span>
    <span class="session-paper">Nagy et al. (2025), <a href="https://doi.org/10.1177/25152459251348431"><em>"Bestiary of Questionable Research Practices in Psychology"</em></a></span>
  </li>
  <li>
    <span class="session-date">August 28, 2026</span>
    <span class="session-paper">Stricker &amp; Günther (2019), <a href="https://doi.org/10.1027/2151-2604/a000356"><em>"Scientific Misconduct in Psychology: A Systematic Review of Prevalence Estimates and New Empirical Data"</em></a></span>
  </li>
  <li>
    <span class="session-date">July 31, 2026</span>
    <span class="session-paper">Simmons, Nelson &amp; Simonsohn (2011), <a href="https://doi.org/10.1177/0956797611417632"><em>"False-Positive Psychology: Undisclosed Flexibility in Data Collection and Analysis Allows Presenting Anything as Significant"</em></a></span>
  </li>
  <li>
    <span class="session-date">June 19, 2026</span>
    <span class="session-paper">Ioannidis (2005), <a href="https://doi.org/10.1371/journal.pmed.0020124"><em>"Why Most Published Research Findings Are False"</em></a></span>
  </li>
</ul>

## Join a session

Email us at [{{ site.data.global.contact.general }}](mailto:{{ site.data.global.contact.general }}) to be told about the next one, or to propose a paper.
