---
layout: blocks/working-session
title: OWASP Project Summit
type: workshop
track: OWASP Projects
status: featured
description: The Summit will contain a number of Working-Sessions focused on OWASP Projects
#status: done
---

The Summit will contain a number of Working-Sessions focused on OWASP Projects

### Participating

If you are an active OWASP Project Leader or want to help leading this Working-Sessions, please register ASAP (and indicate if you [need expenses support](../Logistics/Participants-need-support.html)).

### Current projects/Working-Sessions represented at the Summit:

<ul>
    <ol>
        {% for page in site.pages %}
            {% if page.track == 'project-summit' or page.owasp-project   %}
                <li><a href="{{page.url}}">{{page.title}}</a></li>
            {% endif %}
        {% endfor %}
    </ol>
</ul>