| Programming Language | Level |
| ---- | ---- |
{% assign languages = site.data.skills.technical.lang | sort: "title" -%}
{% for lang in languages -%}
| {{lang.title}} | {{lang.level}} |
{% endfor %}

<br>

| Database and related | Level |
| ---- | ---- |
{% assign dbs = site.data.skills.technical.db | sort: "title" -%}
{% for db in dbs -%}
| {{db.title}} | {{db.level}} |
{% endfor %}

<br>

| Framework | Level |
| ---- | ---- |
{% assign fws = site.data.skills.technical.fw | sort: "title" -%}
{% for fw in fws -%}
| {{fw.title}} | {{fw.level}} |
{% endfor %}

<br>

| Quality Assurance | Level |
| ---- | ---- |
{% assign qas = site.data.skills.technical.qa | sort: "title" -%}
{% for qa in qas -%}
| {{qa.title}} | {{qa.level}} |
{% endfor %}