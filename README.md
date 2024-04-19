# GITHUB README GUIDE

Ceci est un guide non exhaustif des possibilitees de mise en page sur un README.md sur GitHub.

La syntaxe utilisee est du Markdown :

Le Markdown est un langage de balisage léger utilisé pour formater du texte de manière simple et intuitive.

Il permet de créer des documents avec une mise en forme basique, comme des titres, des listes, des liens hypertexte, des images, etc., en utilisant des symboles facilement reconnaissables.

<a id="summary"></a>
<hr>
<details><summary>Sommaire</summary>
<br>

- [Basics](#basics)
- [Heading](#heading)

</details>
<hr>

**Markdown :**
``` text
Texte
```
**Preview :**

Texte

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
+ Un premier point en utilisant + avec un espace
- Un premier point en utilisant - avec un espace
[Tabulation] - Sous-Point
[Tabulation] [Tabulation] - Sous-sous-Point
```
**Preview :**

* Un premier point en utilisant * avec un espace
+ Un premier point en utilisant + avec un espace
- Un premier point en utilisant - avec un espace
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
2. Un premier point en utilisant 2. avec un espace
3. Un premier point en utilisant 3. avec un espace
    - Sous point
    - Encore un sous-point


## HEADING

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


ADVANCES SYNTAX :

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:




