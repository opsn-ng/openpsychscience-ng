---
layout: page
title: Journal Club
subtitle: Discussing articles on Open Science
---

The OPSN Journal Club Meeting is monthly-scheduled.

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
    <div class="actions">
      {% if site.data.next_meeting.meeting_link %}
        <a class="btn-opsn" href="{{ site.data.next_meeting.meeting_link }}">Join the meeting</a>
      {% endif %}
      {% if site.data.next_meeting.calendar_link %}
        <a class="btn-opsn-quiet" href="{{ site.data.next_meeting.calendar_link }}">Add to calendar</a>
      {% endif %}
    </div>
  {% else %}
    <p class="session-next-paper">To be announced</p>
    <p>Email us to be told as soon as it's scheduled, or to suggest a paper.</p>
  {% endif %}
</div>

## Previous sessions

<ul class="sessions">
  <li>
    <span class="session-date">Late July 2026</span>
    <span class="session-paper">Simmons, Nelson &amp; Simonsohn (2011), <em>"False-Positive Psychology: Undisclosed Flexibility in Data Collection and Analysis Allows Presenting Anything as Significant"</em></span>
    <span class="session-note">On researcher degrees of freedom and questionable research practices.</span>
  </li>
  <li>
    <span class="session-date">Date TBC</span>
    <span class="session-paper">Ioannidis (2005), <em>"Why Most Published Research Findings Are False"</em></span>
    <span class="session-note">With interactive teaching materials, including positive predictive value calculators and icon arrays for non-technical audiences.</span>
  </li>
</ul>


## Join a session

Email us at [{{ site.data.global.contact.general }}](mailto:{{ site.data.global.contact.general }}) to be told about the next one, or to propose a paper.
