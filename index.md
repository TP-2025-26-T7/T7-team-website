---
layout: page
title: "Virtuálna križovatka"
permalink: /
---

# Virtuálna križovatka  
### _Koordinovaný systém pre autonómne vozidlá v pohybe_

---

## Vedúci projektu 🫡
Ing. Jozef Juraško

---

## Tím 7️⃣

Sme partia technicky nadšených študentov z FIIT STU, ktorí spájajú kreativitu, vývojárske skúsenosti a lásku k inováciám.  
Spolupracujeme na vývoji inteligentného systému, ktorý pomáha autonómnym vozidlám komunikovať, predvídať a bezpečne prechádzať križovatkami. 


| Meno                   | GitHub                                         |
| :--------------------- | :--------------------------------------------- |
| Dominik Hajko          | [@XDhajko](https://github.com/XDhajko)         |
| Martin Horský          | [@MartinH2k3](https://github.com/MartinH2k3)   |
| Samuel Gabriel Galgóci | [@SamoGG](https://github.com/SamoGG)           |
| Maryna Kolesnykova     | [@maryna0107](https://github.com/maryna0107)   |
| Bruno Kristián         | [@Brunokristi](https://github.com/Brunokristi) |
| Anna Skosar            | [@annaskosar](https://github.com/annaskosar)   |

---

## Týždenné zápisnice 🥱

### Team meetings
<ul>
  {% for post in site.categories.team %}
    <li>
      <a href="{{ post.url | relative_url }}">
        {{ post.date | date: "%Y-%m-%d" }} – {{ post.title }}
      </a>
    </li>
  {% endfor %}
</ul>

### Supervisor meetings
<ul>
  {% for post in site.categories.supervisor %}
    <li>
      <a href="{{ post.url | relative_url }}">
        {{ post.date | date: "%Y-%m-%d" }} – {{ post.title }}
      </a>
    </li>
  {% endfor %}
</ul>