# Roster

| Name         | Number       | Positions    | Social Media |
| ---          | ---          | ---          | ---          |
{% for team_member in site.data.roster -%}
| {{ team_member.name }} | {{ team_member.number }} | {{ team_member.positions }} | {{ team_member.instagram }} |
{% endfor -%}
