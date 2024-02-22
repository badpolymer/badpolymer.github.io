| Programming Language |
| ---- |
{% assign languages = site.data.skills.technical.lang | sort: "title" -%}
{% for lang in languages -%}
| {{lang.title}} |
{% endfor %}

<br>

| Database and related |
| ---- |
{% assign dbs = site.data.skills.technical.db | sort: "title" -%}
{% for db in dbs -%}
| {{db.title}} |
{% endfor %}

<br>

| Framework |
| ---- |
{% assign fws = site.data.skills.technical.fw | sort: "title" -%}
{% for fw in fws -%}
| {{fw.title}} |
{% endfor %}

<br>

| Quality Assurance |
| ---- |
{% assign qas = site.data.skills.technical.qa | sort: "title" -%}
{% for qa in qas -%}
| {{qa.title}} |
{% endfor %}