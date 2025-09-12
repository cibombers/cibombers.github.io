# Roster

 The following people are members of our research team:

 {% for team_member in site.data.roster %}
 - {{ team_member.name }}, position: {{ team_member.position }}
 {% endfor %}