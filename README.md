# GITHUB README GUIDE

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

Ceci est un guide non exhaustif des possibilitees de mise en page sur un README.md sur GitHub.

La syntaxe utilisee est du Markdown :

Le Markdown est un langage de balisage léger utilisé pour formater du texte de manière simple et intuitive.

Il permet de créer des documents avec une mise en forme basique, comme des titres, des listes, des liens hypertexte, des images, etc., en utilisant des symboles facilement reconnaissables.

<a id="summary"></a>
<hr>
<details><summary>Sommaire</summary>
<br>

- [Basics](#basics)
- [Headings](#headings)
- [Images](#images)
- [Links](#links)
- [Tableaux](#tableaux)
- [Advanced Syntax](#advanced_syntax)

</details>
<hr>

**Markdown :**
``` text
Texte
```
**Preview :**

Texte

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## BASICS

**Markdown :**
``` text
Ceci est un exemple basique.
Notez la difference entre un seul saut de ligne

et deux sauts de ligne
```
**Preview :**

Ceci est un exemple basique.
Notez la difference entre un seul saut de ligne

et deux sauts de ligne

---

On peut egalement mettre du texte en **gras**, *italique*, **gras _plus italique_**, ***gras et italique*** ~~barré~~...


| Style | Syntax | Raccourci clavier | Example | Output
|----------|----------|----------|----------|----------|
| Texte en gras    | `** **` ou `__ __`   | `Command`+`B`(Mac) or <br>`Ctrl`+`B`(Windows/Linux) | `**Texte en gras**` or <br> `__Texte En gras__` | __Texte en gras__
| Texte en italique            | `* *` ou `_ _`        | `Command`+`I`(Mac) or <br>`Ctrl`+`I`(Windows/Linux)  | `*Texte en italique*` or <br> `_Texte en italique_`   | *Texte en italique*                  |
| Texte barré                  | `~~ ~~`               | Aucun                             | `~~Texte barré~~`                  | ~~Texte barré~~                      |
| Gras et italique imbriqués   | `** **` et `_ _` | Aucun                           | `**Texte _urgent_ et important**`| **Texte _urgent_ et important**    |
| Tout en gras et en italique  | `*** ***`             | Aucun                             | `***Tout en gras et en italique***`| ***Tout en gras et en italique***  |
| Code                         | \` \`  | Aucun | ``` `Ceci est un bout de code` ```| `Ceci est un bout de code` |
| Subscript | `<sub> </sub>` | Aucun | `Ceci est un <sub> subscript </sub> texte` | Ceci est un <sub> subscript </sub> texte |
| Superscript | `<sup> </sup>` | Aucun | `Ceci est un <sup> superscript </sup> texte` | Ceci est un <sup> superscript </sup> texte |

---

Code couleurs :

| Couleur | Syntax | Example | Output
|----------|----------|----------|----------|
HEX | `#RRGGBB` | `#0969DA` | #0969DA
RGB | `rgb(R,G,B)` | `rgb(9, 105, 218)` | rgb(9, 105, 218)
HSL | `hsl(H, S, L)` | `hsl(212, 92%, 45%)` | hsl(212, 92%, 45%)

> [!NOTE]  
> Les codes couleurs fonctionnent uniquement dans les sections `Issues`, `Pull requests` et `Discussions` .

---

Des syntaxes plus poussees sont egalement possibles :

**Markdown :**
``` text
Ceci n'est pas une citation

> Ceci est une deuxieme citation
```
**Preview :**


Ceci n'est pas une citation

> Ceci est une deuxieme citation

---

Bullet points (liste non ordonee)

**Markdown :**
``` text
* Un premier point en utilisant * avec un espace
+ Un deuxieme point en utilisant + avec un espace
- Un troisieme point en utilisant - avec un espace
[Tabulation] - Sous-Point
[Tabulation] [Tabulation] - Sous-sous-Point
```
**Preview :**

* Un premier point en utilisant * avec un espace
+ Un deuxieme point en utilisant + avec un espace
- Un troisieme point en utilisant - avec un espace
  - Sous-Point
    - Sous-sous-Point  

---

Liste ordonees :

**Markdown :**
``` text
1. Un premier point en utilisant 1. avec un espace
2. Un deuxieme point en utilisant 2. avec un espace
3. Un troisieme point en utilisant 3. avec un espace
    - Sous point
    - Encore un sous-point
```
**Preview :**

1. Un premier point en utilisant 1. avec un espace
2. Un deuxieme point en utilisant 2. avec un espace
3. Un troisieme point en utilisant 3. avec un espace
    - Sous point
    - Encore un sous-point

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## HEADINGS

Pour le heading, nous utiliserons le symbole **#**

**Markdown :**
``` text
# HEADING 1
```
**Preview :**

# HEADING 1

**Markdown :**
``` text
## HEADING 2
```
**Preview :**

## HEADING 2

**Markdown :**
``` text
### HEADING 3
```
**Preview :**

### HEADING 3

**Markdown :**
``` text
#### HEADING 4
```
**Preview :**

#### HEADING 4

**Markdown :**
``` text
##### HEADING 5
```
**Preview :**

##### HEADING 5

**Markdown :**
``` text
###### HEADING 6
```
**Preview :**

###### HEADING 6

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## IMAGES

Pour inserer des images, nous pouvons utiliser deux methodes : une balise `HTML`, ou une balise `Markdown` :

**Balise HTML :**

```html
<img src="chemin_vers_votre_image.jpg" alt="Description de l'image">
```

**Balise Markdown :**
```markdown
![Description de l'image](chemin_vers_votre_image.jpg)
```

Exemples :

```html
<img src="assets/pain.png" alt="Hold the Pain Harold">
```

**Preview :**

<img src="assets/pain.png" alt="Hold the Pain Harold">


```markdown
![Hold The Pain Harold](assets/pain.png)
```

**Preview :**

![Hold The Pain Harold](assets/pain.png)

#### CENTRER LES IMAGES :

> [!IMPORTANT]
> Bien que le `Markdown` supporte l'insertion d'image, ce dernier ne permet pas d'alligner les images. Pour remerdier a cela, nous utiliseront les balises `HTML`.

**Center une image :**

```html
<p align="center">
  <img src="assets/middle.gif" alt="center_cockie_monster">
</p>
```
**Preview :**

<p align="center">
  <img src="assets/middle.gif" alt="center_cockie_monster">
</p>

---

**Aligner a gauche :**

```html
<p align="left">
  <img src="assets/left.gif" alt="left_cockie_monster">
</p>
```

**Preview :**

<p align="left">
  <img src="assets/left.gif" alt="left_cockie_monster">
</p>

---

**Aligner a droite :**

```html
<p align="right">
  <img src="assets/right.gif" alt="right_cockie_monster">
</p>
```

**Preview :**

<p align="right">
  <img src="assets/right.gif" alt="right_cockie_monster">
</p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## LINKS

**Markdown :**
``` text
[Lien classique](https://www.google.com)

[Lien classique avec description](https://www.google.com "Ceci est la description du lien : Page d'accueil de Google")

[Je suis une référence relative à un fichier de dépôt](assets/pain.png)

Les URL et les URL entre crochets seront automatiquement transformés en liens. 
http://www.example.com ou <http://www.example.com> et parfois 
exemple.com (mais pas sur Github, par exemple).
```

**Preview :**

[Lien classique](https://www.google.com)

[Lien classique avec description](https://www.google.com "Ceci est la description du lien : Page d'accueil de Google")

[Je suis une référence relative à un fichier de dépôt](assets/pain.png)

Les URL et les URL entre crochets seront automatiquement transformés en liens. 
http://www.example.com ou <http://www.example.com> et parfois 
exemple.com (mais pas sur Github, par exemple).



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## TABLEAUX

Pour creer des tableaux simples, nous allons utiliser deux caracteres principaux : le pipe `|` et le tiret `-`

**Markdown :**
``` text
| Colonne 1  | Colonne 2 |
| ------------- | ------------- |
| Hello World  | Elon Musk is my Daddy  |
| Epitech is over-rated  | Jennifer Lopez is my Mommy  |
```
**Preview :**

| Colonne 1  | Colonne 2 |
| ------------- | ------------- |
| Hello World  | Elon Musk is my Daddy  |
| Epitech is over-rated  | Jennifer Lopez is my Mommy  |


> [!TIP]
> Le formatage est egalement possible dans les cellules d'un tableau :

**Markdown :**
``` text
| Command | Description |
| --- | --- |
| `git push --force` | Commande a tester *SEULEMENT* en production. |
| `git reset --hard HEAD && git push --force` | L'architecture **chaos** |
```
**Preview :**

| Command | Description |
| --- | --- |
| `git push --force` | Commande a tester *SEULEMENT* en production. |
| `git reset --hard HEAD && git push --force` | L'architecture du **chaos** |


> [!TIP]
> Une syntaxe speciale est utilisee pour aligner les cellules d'une meme colonne :

**Markdown :**
``` text
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```
**Preview :**

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## ADVANCED SYNTAX

GitHub supporte egalement la syntaxe les cases cochees :

**Markdown :**
```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```

**Preview :**
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:


---

Github permet egalement d'annoter ses README.md avec 5 balises de couleurs :


**Markdown :**
```
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```

**Preview :**

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.


---

Pour la mise en page de blocs de code, nous utiliseront les triples ```` ```language ``` ```` afin que GitHub puisse appliquer des couleurs de syntaxes propres a chaque language.

**Markdown :**

`````
```python
s = "Hello, World ! This is Python."
print s
```

```javascript
var message = "Hello, World ! This is JavaScript.";
console.log(message);
```

```c
#include <stdio.h>

int main() {
    char message[] = "Hello, World! This is C language.";
    printf("%s\n", message);
    return 0;
}
```

```bash
gcc -Wall -Wextra -Werror && rm -rf */*
```

```
Lorsque non precise, le bloc de code sera affiche sans syntax highlighting
```
`````

**Preview :**

```python
s = "Hello, World ! This is Python."
print s
```

```javascript
var message = "Hello, World ! This is JavaScript.";
console.log(message);
```

```c
#include <stdio.h>

int main() {
    char message[] = "Hello, World! This is C language.";
    printf("%s\n", message);
    return 0;
}
```

```bash
gcc -Wall -Wextra -Werror && rm -rf */*
```

```
Lorsque non precise, le bloc de code sera affiche sans syntax highlighting
```


