### Vourna Maria-Melina
_______________________ 

### Personal Information

{% for p in site.data.personal.personal %} 
Name: {{p.name}} <br>
Date of Birth: {{p.birth_date}} <br>  
Email: {{p.email}} <br>
City: {{p.city}} <br>
Github Link: https://{{p.link}} 
{% endfor %}
 
_______________________

### Education

{% for edu in site.data.education.education %}
{{edu.years}}<br>
__{{edu.subject}}__ <br>
{{edu.institute}} <br> 
*{{edu.city}}* <br> <br>
{% endfor %}

_______________________

### Languages

Greek: Native Speaker <br>
English: {{ site.data.languages.english }} <br>
French: {{ site.data.languages.french }} <br>

_______________________

### Skills

{% for s in site.data.skills.skills %}
{{s.name1}}  
{{s.name2}}
{{s.name3}}  
{{s.name4}}
{{s.name5}} 
{{s.name6}}
{% endfor %}

_______________________
