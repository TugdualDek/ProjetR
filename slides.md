---
title: datascience project
version: 1.0.0
theme: dracula
footer: Projet DataScience
header: <img src="https://upload.wikimedia.org/wikipedia/fr/thumb/2/21/Institut_sup%C3%A9rieur_d%27%C3%A9lectronique_de_Paris.svg/1280px-Institut_sup%C3%A9rieur_d%27%C3%A9lectronique_de_Paris.svg.png" style="width:170px;"/>
paginate: true
marp: true
---

<style>
    h1{
        border-bottom: 1px solid #eea000;
        padding-bottom: 15px;
        color: #1b5fa2;
    }

    h2{
        color: #1b5fa2;
    }

    table{
        margin-left: auto;
        margin-right: auto;
    }

    p{
        color: #e3e3e3;
    }
</style>

<!--_header : "" -->
<!--_class: titlepage -->

# Projet DataScience

## Groupe :

_Guillaume Albouy_
_Benjamin Bordes_
_Tugdual Audren de Kerdrel_

</div>

<style scoped>
h1 {
    font-size: 80px
}
</style>

![bg right:40% 80%](https://upload.wikimedia.org/wikipedia/fr/thumb/2/21/Institut_sup%C3%A9rieur_d%27%C3%A9lectronique_de_Paris.svg/1280px-Institut_sup%C3%A9rieur_d%27%C3%A9lectronique_de_Paris.svg.png)

---

# Présentation des variables

| Nom        | num_reactions | Num_comments | Num_shares |
| ---------- | :-----------: | :----------: | :--------: |
| Moyenne    |     230.1     |    224.4     |   40.02    |
| Médiane    |     59.5      |      4       |     0      |
| Quartile 1 |     17.0      |      0       |     0      |
| Quartile 3 |     219.0     |      23      |     4      |
| Ecart-type |    462.63     |   889 .63    |   131.6    |

---

# Words from the Source

> There are darknesses in life and there are lights, and you are one of the lights, the light of all lights.
>
> -- Bram Stoker, Dracula

<style scoped>
h1 {
    padding-bottom: 1.5em;
}
</style>

---

# Bats - About

- Small

- Fast

- Mammals

- Scientific name: Chiroptera

![bg right](./img/igam-ogam-unsplash.jpg)

---

# Bats - Implementation

```python
class Bat:
    def __init__(name:str, age:int):
        self.__name = name
        self.__age = age
    @property
    def name(self):
        return self.__name
    @property
    def age(self):
        return self.__age
    @property
    def speed(self):
        return 10 - self.age
```

---

test
