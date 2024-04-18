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
<div v-click>

<img src="/intro/eminem.jpg" class="mx-auto mt-lg"/>

</div>

---
layout: center
class: text-center
---

<h1 v-click.hide> Nuestro entorno de trabajo</h1>
<h1 v-after v-click.hide> Panel hardware</h1>

***

<img src="/intro/minibloq.png"
  v-motion
  :initial="{ x: 0 }"
  :click-2="{ x: 200 }"
  :leave="{ x: 0 }"
  />
