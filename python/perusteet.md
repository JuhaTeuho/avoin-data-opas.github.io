---
title: Perusteet
lang: fi
ref: perusteet
category: python
---

## Tervetuloa Pythonin pariin!

Jos haluat päästä käytännönläheisesti alkuun, voit kokeilla datan käsittelyyn laatimaamme johdatusta: 

**Ohjeita Pythonin käyttöön** [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cms-opendata-education/cms-jupyter-materials-finnish/master?filepath=TyokalutTutuiksi%2FOhjeita%20Pythonin%20k%C3%A4ytt%C3%B6%C3%B6n.ipynb) [![Colaboratory](https://github.com/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/Kuvat/colab_icon.png?raw=true)](https://colab.research.google.com/github/cms-opendata-education/cms-jupyter-materials-finnish/blob/master/TyokalutTutuiksi/Ohjeita%20Pythonin%20k%C3%A4ytt%C3%B6%C3%B6n.ipynb)

Mikäli ohjelmointi ei ole sinulle ennestään tuttua ja haluat oppia Pythonia aivan alusta alkaen, netistä löytyy tähän googlaamalla useita tutoriaaleja. Ohjelmointitaidot eivät ole välttämättömiä materiaalipankkimme käyttämiseksi, mutta antavat pohjan omien opetusmateriaalien toteuttamiselle. Alkuun pääsee esimerkiksi osoitteessa [learnpython.org](https://www.learnpython.org/).

Python kielenä pyrkii minimalismiin. Suunnittelufilosofiaa avaava [Zen of Python](https://en.wikipedia.org/wiki/Zen_of_Python) kertoo muun muassa seuraavaa:

- Beautiful is better than ugly.
- Explicit is better than implicit.
- Simple is better than complex.
- Complex is better than complicated.
- Flat is better than nested.
- Sparse is better than dense.
- Readability counts.

Tämä näkyy heti alusta lähtien siinä, ettei käyttäjän tarvitse erityisemmin määritellä luokkia tai sählätä kansiorakenteiden kanssa.

Yksinkertainen Python-skripti voisi esimerkiksi sisältää sopivien työkalujen tuomisen (**import**), halutun datasetin lukemisen ja siitä kuvaajan piirtämisen.

````python
import pandas as pd
import matplotlib.pyplot as plt

datasetti = pd.read_csv("LinkkiKohteeseen")

plt.hist(datasetti, bins = 100)
plt.show()
````

Oleellista on tietää mitä kirjastoja tarvitsee tuoda kulloinkin käytettävään harjoitteeseen ja miten niissä olevia komentoja kutsutaan.
