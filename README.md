### Vourna Maria-Melina
_______________________

### Personal Information

{% for p in site.data.personal.personal %} 
<dl>
<dt> Name: </dt>
<dd> {{p.name}} </dd> 
<dt> Date of Birth: </dt>
<dd> {{p.birth_date}} </dd>  
<dt> Email: </dt>
<dd> {{p.email}} </dd> 
<dt> City: </dt>
<dd> {{p.city}} </dd>
<dt> Github Link: </dt> 
<dd> https://{{p.link}} </dd>
</dl>
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

{% for l in site.data.languages.languages %}
{{l.langA}} :  {{l.levelA}} <br> 
{{l.langB}} :  {{l.levelB}} <br> <br>
{% endfor %}

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
