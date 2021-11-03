### Vourna Maria-Melina
_______________________ 

### Personal Information

{% for p in site.data.personal.personal %} 
Name: {{p.name}} <br>
Date of Birth: {{p.birth_date}} <br>  
Email: {{p.email}} <br>
City: {{p.city}} <br>
[Github Link]: (https://{{p.link}}) <br> <br>
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

__Greek__: Native Speaker <br>
{% for lang in site.data.languages.languages %}
__English__: {{lang.english}} <br>
__French__: {{lang.french}} <br> <br>
{% enfor %}

_______________________

### Skills

{% for s in site.data.skills.skills %}
{{s.name}}  
{% endfor %}

_______________________
