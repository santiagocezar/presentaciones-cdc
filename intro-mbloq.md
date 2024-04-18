---
title: Introducción a miniBloq
theme: default
background: https://cover.sli.dev
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
layout: cover
---

# Club de Ciencias
## Presentando: miniBloq

---
layout: center
class: text-center
---

# ¿Qué es un miniBloq?

<div v-click>

## Es un entorno de programación gráfico de código abierto
</div>

<div v-click>
Osea, es un programa para hacer programas, a partir de bloques!
</div>

<img v-click v-motion v-motion-roll-left src="/intro/eminem.jpg" class="mx-auto mt-lg"/>


---
layout: center
class: text-center
clicks: 5
---

<h1 v-click.hide="[1,5]"> Nuestro entorno de trabajo</h1>

<br/>

<img src="/intro/minibloq.png"
  v-motion
  :initial="{ x: 0, y: 0, scale: 1, transition: {
    duration: 600,
    type: 'spring'
  }}"
  :click-1="{ x: 200, y: -50, scale: 1.25}"
  :click-2="{ x: -400, y: -50, scale: 1.5}"
  :click-3="{ x: 0, y: -50, scale: 1.25}"
  :click-4="{ x: 600, y: 450, scale: 3}"
  :click-5="{ x: 0, y: 0, scale: 1 }"
  :leave="{ x: 0 }"
  />

---

bye
