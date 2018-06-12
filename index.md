---
layout: default
---
Каталог ссылок на ролевые проекты

### LARP (полевые ролевые игры)

<table>
  <tr>
    <th>Project</th>
    <th>Maintainer</th>
    <th>Description</th>
    <th>Repo URL</th>
  </tr>
{% for item in site.larp %}
  <tr>
    <td>{{ item.title }}</td>
    <td>{{ item.author }}</td>
    <td>{{ item.description }} </td>
    <td><a href="{{ item.repo_url }}">{{ item.repo_url }}</a></td>
  </tr>
{% endfor %}
</table>

Github repos by LARP topic: [https://github.com/topics/larp](https://github.com/topics/larp)

### tRPG (настольные ролевые игры)

<table>
  <tr>
    <th>Project</th>
    <th>Maintainer</th>
    <th>Description</th>
    <th>Repo URL</th>
  </tr>
{% for item in site.trpg %}
  <tr>
    <td>{{ item.title }}</td>
    <td>{{ item.author }}</td>
    <td>{{ item.description }} </td>
    <td><a href="{{ item.repo_url }}">{{ item.repo_url }}</a></td>
  </tr>
{% endfor %}
</table>


## Связь и поддержка

- [https://github.com/RPGCodeBase/RPGCodeBase.github.io](https://github.com/RPGCodeBase/RPGCodeBase.github.io)
- Fork, commit, pull-request.
