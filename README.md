### Vourna Maria-Melina
_______________________ 

### Personal Information

{% for p in site.data.personal.personal %} 
Name: {{p.name}} <br>
Date of Birth: {{p.birth_date}} <br>  
Email: {{p.email}} <br>
City: {{p.city}} <br>
{% endfor %}
[Github Link]: (https://{{site.data.personal.personal.link}}) <br> <br>
 
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

__Greek__: Native Speaker <br>
__English__: {{site.data.languages.languages.english}} <br>
__French__: {{site.data.languages.languages.french}} <br> <br>

_______________________

### Skills

{{site.data.skills.skills.name}}  

_______________________
