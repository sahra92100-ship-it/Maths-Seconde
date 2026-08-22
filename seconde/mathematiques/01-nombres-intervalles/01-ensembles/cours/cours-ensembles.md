---
marp: true
theme: maths-premium-v2.0
paginate: true
math: katex
---

<!-- _class: page-chapitre -->

# Chapitre 1
## Ensembles de nombres

---

<!-- _class: page-objectifs -->

# Objectifs

<div class="bloc bloc-objectifs">

## À la fin de cette notion, je sais :

- Reconnaître et utiliser les ensembles $\mathbb{N}$, $\mathbb{Z}$, $\mathbb{D}$, $\mathbb{Q}$ et $\mathbb{R}$.
- Placer un nombre dans le plus petit ensemble qui le contient.
- Utiliser correctement les symboles $\in$, $\notin$ et $\subset$.
- Comprendre les inclusions entre les différents ensembles de nombres.
- Justifier l'appartenance d'un nombre à un ensemble.

</div>

---

<!-- _class: page-echauffement -->

# Échauffement

<div class="bloc bloc-echauffement">

## Avant de commencer

- $-3$ est-il un nombre entier ? Peut-il être négatif et entier à la fois ?
- $\dfrac{1}{2}$ peut-il s'écrire avec une virgule ? Combien de chiffres après la virgule ?
- $\sqrt{2}$ a-t-il une écriture décimale qui s'arrête ?
- $0$ appartient-il à l'ensemble des nombres naturels ?

</div>

---

<!-- _class: page-cours -->

# L'ensemble $\mathbb{N}$

<div class="bloc bloc-cours">

## Définition

$\mathbb{N}$ est l'ensemble des **entiers naturels**, c'est-à-dire les nombres utilisés pour compter :

$$
\mathbb{N}=\{0\,;\,1\,;\,2\,;\,3\,;\,4\,;\,\dots\}
$$

- $\mathbb{N}$ contient une infinité de nombres.
- Les nombres naturels sont **entiers et positifs ou nuls**.
- $\mathbb{N}^*$ désigne $\mathbb{N}$ privé de $0$.

### Exemples

$$
0\in\mathbb{N}
\qquad
7\in\mathbb{N}
\qquad
-3\notin\mathbb{N}
$$

</div>

---

<!-- _class: page-cours -->

# L'ensemble $\mathbb{Z}$

<div class="bloc bloc-cours">

## Définition

$\mathbb{Z}$ est l'ensemble des **entiers relatifs** : les entiers naturels et leurs opposés.

$$
\mathbb{Z}
=
\{\dots\,;\,-3\,;\,-2\,;\,-1\,;\,0\,;\,1\,;\,2\,;\,3\,;\,\dots\}
$$

Tout entier naturel est un entier relatif :

$$
\mathbb{N}\subset\mathbb{Z}
$$

### Exemples

$$
-7\in\mathbb{Z}
\qquad
0\in\mathbb{Z}
\qquad
12\in\mathbb{Z}
$$

Mais :

$$
2{,}5\notin\mathbb{Z}
$$

</div>

---

<!-- _class: page-cours -->

# L'ensemble $\mathbb{D}$

<div class="bloc bloc-cours">

## Définition

Un nombre **décimal** est un nombre dont l'écriture décimale comporte un **nombre fini de chiffres après la virgule**.

Un nombre décimal peut s'écrire sous la forme :

$$
\frac{a}{10^n}
\qquad
\text{avec }a\in\mathbb{Z}
\text{ et }n\in\mathbb{N}
$$

### Exemples

$$
3{,}25=\frac{325}{100}
$$

donc $3{,}25\in\mathbb{D}$.

De même :

$$
-7=\frac{-7}{10^0}
$$

donc $-7\in\mathbb{D}$.

En revanche :

$$
\frac13=0{,}3333\ldots
$$

Son écriture décimale ne s'arrête jamais : 

$$
\frac13\notin\mathbb{D}
$$

</div>

---

<!-- _class: page-cours -->

# L'ensemble $\mathbb{Q}$

<div class="bloc bloc-cours">

## Définition

$\mathbb{Q}$ est l'ensemble des **nombres rationnels**.

Un nombre rationnel peut s'écrire comme le quotient de deux entiers, avec un dénominateur non nul :

$$
\mathbb{Q}
=
\left\{
\frac{a}{b}
\;\middle|\;
a\in\mathbb{Z},
\ b\in\mathbb{Z},
\ b\neq0
\right\}
$$

### Exemples

$$
\frac13\in\mathbb{Q}
\qquad
\frac57\in\mathbb{Q}
\qquad
-\frac29\in\mathbb{Q}
$$

Tout nombre décimal est rationnel :

$$
\mathbb{D}\subset\mathbb{Q}
$$

</div>

---

<!-- _class: page-cours -->

# L'ensemble $\mathbb{R}$

<div class="bloc bloc-cours">

## Définition

$\mathbb{R}$ est l'ensemble des **nombres réels**.

Ce sont tous les nombres que l'on peut placer sur une **droite graduée**.

Il contient :

- les nombres rationnels ;
- les nombres irrationnels.

### Nombres irrationnels

Un nombre irrationnel ne peut pas s'écrire comme le quotient de deux entiers.

Par exemple :

$$
\sqrt2=1{,}41421356\ldots
$$

et

$$
\pi=3{,}14159265\ldots
$$

Leur écriture décimale est **infinie et non périodique**.

</div>

---

<!-- _class: page-cours -->

# Les inclusions

<div class="bloc bloc-cours">

## L'emboîtement des ensembles

Les ensembles de nombres sont emboîtés :

$$
\boxed{
\mathbb{N}
\subset
\mathbb{Z}
\subset
\mathbb{D}
\subset
\mathbb{Q}
\subset
\mathbb{R}
}
$$

Cela signifie notamment que :

$$
\mathbb{N}\subset\mathbb{Z}
$$

$$
\mathbb{Z}\subset\mathbb{D}
$$

$$
\mathbb{D}\subset\mathbb{Q}
$$

$$
\mathbb{Q}\subset\mathbb{R}
$$

**Chaque ensemble contient tous les ensembles situés avant lui.**

</div>

---

<!-- _class: page-cours -->

# Les inclusions en image

<div class="bloc bloc-cours">

<svg viewBox="0 0 640 460" xmlns="http://www.w3.org/2000/svg" style="display:block;margin:0 auto;max-width:520px;width:100%;height:auto;">

  <ellipse cx="320" cy="230" rx="300" ry="195"
           fill="#F0F9FF" stroke="#0369A1" stroke-width="3"/>

  <ellipse cx="320" cy="230" rx="225" ry="145"
           fill="#DBEFFD" stroke="#0369A1" stroke-width="3"/>

  <ellipse cx="320" cy="230" rx="155" ry="100"
           fill="#B9E1FA" stroke="#0369A1" stroke-width="3"/>

  <ellipse cx="320" cy="230" rx="95" ry="60"
           fill="#8ED0F5" stroke="#0369A1" stroke-width="3"/>

  <ellipse cx="320" cy="230" rx="42" ry="28"
           fill="#4FB6E8" stroke="#0369A1" stroke-width="3"/>

  <text x="320" y="70"
        text-anchor="middle"
        font-size="28"
        font-weight="800"
        fill="#0B4F6C">
    ℝ — Réels
  </text>

  <text x="320" y="120"
        text-anchor="middle"
        font-size="22"
        font-weight="800"
        fill="#0B4F6C">
    ℚ — Rationnels
  </text>

  <text x="320" y="160"
        text-anchor="middle"
        font-size="19"
        font-weight="800"
        fill="#0B4F6C">
    𝔻 — Décimaux
  </text>

  <text x="320" y="195"
        text-anchor="middle"
        font-size="16"
        font-weight="800"
        fill="#0B4F6C">
    ℤ — Relatifs
  </text>

  <text x="320" y="226"
        text-anchor="middle"
        font-size="12"
        font-weight="800"
        fill="#0B4F6C">
    ℕ — Naturels
  </text>

  <text x="320" y="248"
        text-anchor="middle"
        font-size="15"
        font-weight="600"
        fill="#0369A1">
    0 ; 7
  </text>

  <text x="320" y="278"
        text-anchor="middle"
        font-size="18"
        fill="#0369A1">
    -4 ; -12
  </text>

  <text x="320" y="315"
        text-anchor="middle"
        font-size="18"
        fill="#0369A1">
    2,5 ; -0,75
  </text>

  <text x="320" y="360"
        text-anchor="middle"
        font-size="18"
        fill="#0369A1">
    1/3 ; 5/7
  </text>

  <text x="320" y="405"
        text-anchor="middle"
        font-size="20"
        fill="#0369A1">
    π ; √2
  </text>

</svg>

</div>

---

<!-- _class: page-exemple -->

# Déterminer le plus petit ensemble

<div class="bloc bloc-exemple">

## Exemple guidé

On cherche le **plus petit ensemble** parmi $\mathbb{N}$, $\mathbb{Z}$, $\mathbb{D}$, $\mathbb{Q}$ et $\mathbb{R}$ qui contient chaque nombre.

### $8$

$$
8\in\mathbb{N}
$$

### $-5$

$$
-5\in\mathbb{Z}
\qquad
-5\notin\mathbb{N}
$$

### $4{,}2$

$$
4{,}2\in\mathbb{D}
\qquad
4{,}2\notin\mathbb{Z}
$$

### $\dfrac23$

$$
\frac23\in\mathbb{Q}
\qquad
\frac23\notin\mathbb{D}
$$

### $\sqrt5$

$$
\sqrt5\in\mathbb{R}
\qquad
\sqrt5\notin\mathbb{Q}
$$

</div>

---

<!-- _class: page-methode -->

# Méthode — Classer un nombre

<div class="bloc bloc-methode">

## Étape 1 — Observer le nombre

Est-il **entier naturel** ?

→ Si oui, il appartient à $\mathbb{N}$.

## Étape 2 — Vérifier s'il est entier relatif

S'il est entier mais négatif :

$$
x\in\mathbb{Z}
$$

mais

$$
x\notin\mathbb{N}
$$

## Étape 3 — Observer son écriture décimale

Si son écriture décimale **s'arrête**, alors :

$$
x\in\mathbb{D}
$$

## Étape 4 — Chercher une écriture fractionnaire

S'il peut s'écrire comme quotient de deux entiers :

$$
x\in\mathbb{Q}
$$

## Étape 5 — Sinon

Il peut être réel irrationnel :

$$
x\in\mathbb{R}
\setminus
\mathbb{Q}
$$

</div>

---

<!-- _class: page-exemple -->

# Exemple — Classer plusieurs nombres

<div class="bloc bloc-exemple">

| Nombre | Plus petit ensemble |
|---|---|
| $12$ | $\mathbb{N}$ |
| $-6$ | $\mathbb{Z}$ |
| $3{,}5$ | $\mathbb{D}$ |
| $\dfrac25=0{,}4$ | $\mathbb{D}$ |
| $\dfrac17$ | $\mathbb{Q}$ |
| $\sqrt7$ | $\mathbb{R}$ |

### Attention

Un nombre peut appartenir à **plusieurs ensembles**.

Par exemple :

$$
3\in\mathbb{N}
$$

mais aussi :

$$
3\in\mathbb{Z},\quad
3\in\mathbb{D},\quad
3\in\mathbb{Q},\quad
3\in\mathbb{R}
$$

On cherche généralement **le plus petit ensemble** auquel il appartient.

</div>

---

<!-- _class: page-astuce -->

# Astuce mnémotechnique

<div class="bloc bloc-astuce">

## Retenir l'ordre N-Z-D-Q-R

**N**ina **Z**appe **D**es **Q**uestions **R**apidement

$$
\mathbb{N}
\subset
\mathbb{Z}
\subset
\mathbb{D}
\subset
\mathbb{Q}
\subset
\mathbb{R}
$$

### À retenir

**N → Z → D → Q → R**

Chaque ensemble contient tous les précédents.

</div>

---

<!-- _class: page-attention -->

# Attention aux pièges

<div class="bloc bloc-attention">

## Erreur 1 — Les nombres négatifs

$-3$ est un entier, mais :

$$
-3\notin\mathbb{N}
$$

Il appartient à $\mathbb{Z}$.

---

## Erreur 2 — Une fraction peut être décimale

$$
\frac42=2
$$

Donc :

$$
\frac42\in\mathbb{N}
$$

Il faut **simplifier avant de classer**.

---

## Erreur 3 — Une écriture décimale infinie

$$
\frac13=0{,}3333\ldots
$$

n'est pas décimale, mais reste rationnelle :

$$
\frac13\in\mathbb{Q}
$$

---

## Erreur 4 — Toutes les racines ne sont pas irrationnelles

$$
\sqrt{16}=4
$$

donc :

$$
\sqrt{16}\in\mathbb{N}
$$

</div>

---

<!-- _class: page-exemple -->

# Exemple — Une racine carrée

<div class="bloc bloc-exemple">

On considère :

$$
x=\frac{\sqrt{16}}{2}
$$

### 1. Simplifier

$$
\sqrt{16}=4
$$

donc :

$$
x=\frac42=2
$$

### 2. Classer

$$
2\in\mathbb{N}
$$

Donc le plus petit ensemble contenant $x$ est :

$$
\boxed{\mathbb{N}}
$$

### À retenir

La présence d'une racine carrée **ne signifie pas automatiquement** que le nombre est irrationnel.

Il faut d'abord **simplifier**.

</div>

---

<!-- _class: page-bilan -->

# À retenir

<div class="bloc bloc-cours">

## Les cinq ensembles

$$
\boxed{
\mathbb{N}
\subset
\mathbb{Z}
\subset
\mathbb{D}
\subset
\mathbb{Q}
\subset
\mathbb{R}
}
$$

### Je dois savoir :

- reconnaître un entier naturel ;
- reconnaître un entier relatif ;
- reconnaître un nombre décimal ;
- reconnaître un nombre rationnel ;
- reconnaître un nombre irrationnel ;
- utiliser les symboles $\in$, $\notin$ et $\subset$ ;
- déterminer le **plus petit ensemble** contenant un nombre ;
- simplifier un nombre avant de le classer.

### Le réflexe essentiel

**Je simplifie → j'observe → je classe dans le plus petit ensemble.**

</div>