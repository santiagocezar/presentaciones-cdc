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
fonts:
  sans: Comic Neue
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
<img width="100" class="m-10 inline-block shadow-2" src="/intro/icon.png"/>

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
  width="500"
  :initial="{ x: 0, y: 0, scale: 1, transition: {
    duration: 600,
    type: 'spring'
  }}"
  :click-1="{ x: 600, y: 100, scale: 3}"
  :click-2="{ x: -800, y: -100, scale: 5}"
  :click-3="{ x: 300, y: 200, scale: 4}"
  :click-4="{ x: 1100, y: 600, scale: 6}"
  :click-5="{ x: 0, y: 0, scale: 1 }"
  :leave="{ x: 0 }"
  />

---
layout: two-cols
---

## ¿Como funciona?

Cuando le damos ▶️, miniBloq traduce nuestras instrucciones. Del lenguaje de bloques, ¡a un lenguaje *solo nuestro robot* puede entender!

<v-click>

Digamos, *código binario*

![](/intro/binario.png)

</v-click>

::right::

<v-click>

Una vez traduce el código, lo transfiere a nuestro robot mediante un **cable serial** conectado a la computadora:

![](/intro/serial.png)

</v-click>

<style>
.slidev-layout {
  background-image: linear-gradient(0deg, #0008, #0008), url(/intro/bichito.png);
  background-size: 100%;
  color: white;

}
</style>

---
layout: image-right
image: /intro/minisim.png
class: background-size-30
---

## miniSim

Ahora, antes meternos en el mundo físico, vamos a empezar con algo Similar a un robot, pero mucho mas Simple


<video loop src="/intro/scratch.webm" autoplay />

---
layout: center
class: text-center
---

## Vamos a trabajar con los siguientes bloques
![](/intro/bloqs.svg)
