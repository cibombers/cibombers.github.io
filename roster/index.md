# Roster

| Name         | Graduation  |Number       | Positions    | Social Media |
| ---          | ---         |---          | ---          | ---          |
{% for team_member in site.data.roster -%}
| {{ team_member.name }} | {{ team_member.grad_year }} | {{ team_member.number }} | {{ team_member.positions }} | {% if team_member.email %}{% include email.html %}{% endif %}{% if team_member.instagram %}{% include instagram.html %}{% endif %}{% if team_member.x %}{% include x.html %}{% endif %}{% if team_member.facebook %}{% include facebook.html %}{% endif %} |
{% endfor -%}
