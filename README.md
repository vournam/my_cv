### Vourna Maria-Melina
_______________________ 

### Personal Information

{% for p in site.data.personal.personal %} 
Name: {{p.name}} <br>
Date of Birth: {{p.birth_date}} <br>  
Email: {{p.email}} <br>
City: {{p.city}} <br>
Github Link: [https://{{p.link}}](https://{{p.link}}) <br> <br>
{% endfor %}
 
_______________________

### Education

{% for edu in site.data.education.education %}
{{edu.years}}<br>
__{{edu.subject}}__ <br>
{{edu.institute}} <br> 
{{edu.grade}} <br>
*{{edu.city}}* <br> <br>
{% endfor %}

_______________________

### Languages

{% for l in site.data.languages.languages %}
__Greek__: {{l.greek}} <br>
__English__: {{l.english}} <br>
__French__: {{l.french}} <br> <br>
{% endfor %}

_______________________

### Skills

{% for s in site.data.skills.skills %}
Programming skills: {{s.programming}}  <br>
Machine Learning: {{s.coursera}} <br> <br>
{% endfor %}
_______________________
