---
title: Volta, pour mieux gérer nos projets
theme: aneo
layout: cover
background: https://images.unsplash.com/photo-1487424439918-bc6b5bef0380?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1933&q=80
---

# Volta, pour mieux gérer nos projets

---
---
<!-- Need to use a summary layout -->

# Sommaire

- Quel est le sujet ?
- Quelles sont nos problématiques ?
- Quels sont nos outils à disposition ?
- Des questions ?
- Le Récap

---
layout: section
---

# Quel est le sujet ?

---
layout: center
---

# Gestion des issues sur le projet ArmoniK

<v-clicks>

- **Centralisation des issues** au sein d'un repository
- Centralisation au sein d'un **unique board**
- Déplacement des issues **manuellement**

</v-clicks>

<!--
On parle de la gestion des issues sur le projet ArmoniK mais en vrai, on peut l'étendre à la gestion des projets au sein d'Aneo.

On centralise au sein d'un repository pour pouvoir ensuite centraliser au sein d'un même projet.
-->

---
layout: section
---

# Quelles sont nos problématiques ?

<!-- 
Les problématiques sont multiples et liées les unes aux autres.
-->

---
layout: center
---

# Centralisation des issues au sein d'un unique repository
<v-clicks>

- Difficulté de comprendre les issues et leur gestion dans le repository principal
- Difficulté de comprendre, pour un nouveau, de savoir où poster une issue 

</v-clicks>

<!-- 
- Difficulté de comprendre les issues dans le repository principal
  1. Les issues parlent de tous les repositories alors qu'on s'attend à n'avoir que du ArmoniK et inversement
  2. Obligation de naviguer entre les issues d'ArmoniK et les différentes repositories pour s'y retrouver
- Difficulté de comprendre, pour un nouveau, de savoir où poster une issue
  1. Pas d'issue d'exemple, ni d'archiges pour la recherche, dans les repositories
  2. Si une issue est postée dans un repository autre que ArmoniK, comment on le gère ?
  3. Pas forcément connaissance de toute l'architecture d'ArmoniK
-->

---
layout: center
---

# Pas d'automatisation de la board

<v-clicks>

- Difficulté de réellement suivre le développement
- Besoin de temps pour gérer les issues

</v-clicks>

<!-- 
- Difficulté de réellement suivre le développement
  1. Les issues font de `todo` à `done` donc clairement, ça ne sert à rien
  2. Une partie des issues ne sont pas ajoutée au board
- Besoin de temps pour gérer les issues
  1. Cela nous fait retomber sur les éléments précédemment cités
-->

---
layout: section
---

# Quels sont nos outils à disposition ?

---
layout: two-cols
---
<!-- Retravailler pour avoir un gap entre les 2 -->
<!-- Bien faire attention à ce que sous un h1, on puisse y glisser un subtitle -->

# Project
Le nouvel outil de GitHub pour gérer les projets

<br />

<v-clicks>

<div>
  <fluent-emoji-flat-check-mark-button /> Avantages
</div>

</v-clicks>

<v-clicks>

- Permet de conserver la centralisation des issues dans une unique board
- Permet de ramener les issues au sein de chacun des repositories
- Permet une automatisation simple

</v-clicks>

<br />

<v-clicks>

<div>
  <fluent-emoji-flat-cross-mark /> Inconvénients
</div>

</v-clicks>

<v-clicks>

- Automatisation trop simple et trop complexe à la fois

</v-clicks>

<br />
<br />

<v-clicks>

<div class="flex flex-row justify-start items-start gap-2">
  <fluent-emoji-flat-right-arrow /> 
  <a href="https://github.com/features/issues"> Project </a> 
</div>

</v-clicks>

::right::

<v-clicks>

# Volta
L'outil de NuxtLabs qui ré-imagine la gestion des issues

</v-clicks>

<br />

<v-clicks>

<div>
  <fluent-emoji-flat-check-mark-button /> Avantages
</div>

</v-clicks>

<v-clicks>

- Centralise l'ensemble des issues au sein d'un unique outil
- Permet de ramener les issues au sein de chacun des repositories
- Automatisation puissante

</v-clicks>

<br />

<v-clicks>

<div>
  <fluent-emoji-flat-cross-mark /> Inconvénients
</div>

</v-clicks>

<v-clicks>

- Outil externe à Github
- Plus de board globale à proprement parler

</v-clicks>

<br />
<br />

<v-clicks>

<div class="flex flex-row justify-start items-start gap-2">
  <fluent-emoji-flat-right-arrow />
  <a href="https://volta.net">Volta</a>
</div>

</v-clicks>

<!--
Project de GitHub

Avantages et inconvénients par rapport à notre manière de faire actuelle

L'automatisation est tellement simple qu'il faut ajouter à la main les issues dans la board. Mais elle est trop complexe parce que pour commencer à jouer avec, il faut passer par des actions et le faire dans des requêtes GraphQL.

Du coup, ça ne vaut pas le coup de l'essayer et clairement, on peut trouver mieux

Volta

Avantages et inconvénients par rapport à notre manière de faire actuellement

L'automatisation est complète et donc il n'y a plus besoin de toucher au board. Il reflète automatiquement l'état de développement et d'avancement des issues.

En prime, l'outil permet de gérer tous les repositories que l'on souhaite. Ainsi, ceux qui travail sur plusieurs, au sein d'un même projet ou de projets différents vont adorer. Il y a aussi un système d'inbox qui permet de canaliser clairement les notifications (contrairement au système de GitHub).
-->

---
layout: section
---

# Des questions ?

---
layout: section
---

# Démonstration

[Volta](https://volta.net)

---
layout: section
---

# Proposition
