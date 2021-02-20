# 	:green_apple: Õunasorteerija

Õunasorteerija OÜ tegeleb õunte sorteerimisega ja selleks on neil automaatne sorteerimismasin. Sorteerimisrobot sorteerib õunu kaalu järgi 3-me klassi.
Väikesed (-50g), keskmised (51-70g) ja suured (71+g)

Programmi sisendiks on õunte suurused.
Programmi põhiülesannesanne anda ülemprogrammile teada millisesse kasti lisada õun kasutades lisaKasti funktsiooni.
Programmi väljundiks on multidimensionaalne massiiv õunte järjekorranumbritega kogumaks statistikat.

Massiivis on numbriliselt kirjas kaalud.
```
var apples = [ 29, 70, 85, 77, 55, 44, 33, 98, 90, 47, 22, 44, 55, 37, 65];
```

### 1. :apple: Algoritm

Koostame kolm erinevat muutujat `small`, `medium`, `big`, nende muutujate algväärtuseks on `0` (null)

Koostame kolm erinevat tühja massiivi `sm`, `med`, `bg`

Kasutame "for" tsüklit, milles muutuja "i" algväärtus on 0 ja protsessi korrates suureneb muutuja väärtus kuni etteantud massiivis olevate elementide arvuni, seejärel koodi tegevus lõpetatakse.

"If","else if", "else" tingimuslauset kasutades loendame õunad järgnevatesse kastidesse `small` (-50g), `medium` (51-70g) ja `big` (71+g) ja lisame kolme erinevasse massiivi, `sm`(-50g), `med`(51-70g), `bg`(71+g), õunte järjekorranumbritega

Väljundiks on massiiv õunte massidega

### 2. :apple: Plokkskeeemi loomine

![Plokkskeem](./Plokkskeem.jpg)

### 3. :apple: Programmi loomine

:green_apple: [sorteerijaJS](./index.js)

:apple: [sorteerijaJava](./index.java)


