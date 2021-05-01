---
marp: true
---
---
![help](https://github.com/marp-team/marp-vscode/#readme)

/ * @theme your-theme * /

@import  'default' ;

seção {
   background :  # fc9 ;
}
---
--- 

---

#  Use seu próprio tema

# Slide 1
<!-- paginate: true -->
> vamos Lá

<!-- theme: registered-theme-name -->

- **Paudalho**


<!-- _backgroundColor: white -->

Erison Rosa de Oliveira Barros

---
theme: default
paginate: true
---

---
![bg vertical](https://fakeimg.pl/800x600/0288d1/fff/?text=A)
![bg](https://fakeimg.pl/800x600/02669d/fff/?text=B)
![bg](https://fakeimg.pl/800x600/67b8e3/fff/?text=C)

---
![bg left](https://picsum.photos/720?image=29)

# Split backgrounds

The space of a slide content will shrink to the right side.

---
![bg right](https://picsum.photos/720?image=3)
![bg](https://picsum.photos/720?image=20)

# Split + Multiple BGs

The space of a slide content will shrink to the left side.

---
![bg left:33%](https://picsum.photos/720?image=27)

# Split backgrounds with specified size

---
# Hex color (White BG + Black text)

![bg](#fff)
![](#000)

---

# Named color (rebeccapurple BG + White text)

![bg](rebeccapurple)
![](white)

---

# RGB values (Orange BG + White text)

![bg](rgb(255,128,0))
![](rgb(255,255,255))

---

# Slide 2
<!-- paginate: true -->
bar

----
# Slide 3
<!-- paginate: true -->
Erison Rosa de Oliveira Barros
<!-- theme: registered-theme-name -->
<!-- _backgroundColor: aqua -->
---



---
# Slide 4
<!-- paginate: true -->
<!-- header: Prof. Erison Rosa de Oliveira Barros-->
<!-- footer: Universidade Federal de Pernambuco-->
<!-- class: Universidade Federal de Pernambuco-->
<!-- backgroundColor: red-->
<!-- backgroundImage: [black](https://ibb.co/yXW4SxC)-->
---


---
# Slide 5
<!-- paginate: true -->
<!-- header: Prof. Erison Rosa de Oliveira Barros-->
<!-- footer: Universidade Federal de Pernambuco-->
<!-- class: Universidade Federal de Pernambuco-->
<!-- backgroundImage: [black](https://ibb.co/yXW4SxC)-->
<!--backgroundSize: 4x6-->

---
---
header: '**bold** _italic_'
footer: '![](https://ibb.co/yXW4SxC)'
---

# Slide 6

section.lead h1 {
  text-align: center;
}
---


---
# Slide 7
<!-- backgroundImage: "linear-gradient(to bottom, #67b8e3, #0288d1)" -->

Gradient background

---
# Slide 8
<!--
_backgroundColor: black
_color: white
-->

Black background + White text

---
# slide 9

marpit.customDirectives.global.$theme = (value, marpit) => {
  return { theme: value }
}

---
# Slide 10

<!-- colorPreset: sunset -->

# Sunset color preset

---

<!-- _colorPreset: dark -->

# Dark color preset

---

# Sunset color preset

---
![bg left:33%](https://picsum.photos/720?image=27)

# Split backgrounds with specified size

---

# Hex color (White BG + Black text)

![bg](#fff)
![](#000)

---

# Named color (rebeccapurple BG + White text)

![bg](rebeccapurple)
![](white)

---

# RGB values (Orange BG + White text)

![bg](rgb(255,128,0))
![](rgb(255,255,255))

---
# Bullet list

- One
- Two
- Three

---

# Fragmented list

* One
* Two
* Three
---
<section id="1">
  <h1>Bullet list</h1>
  <ul>
    <li>One</li>
    <li>Two</li>
    <li>Three</li>
  </ul>
</section>
<section id="2" data-marpit-fragments="3">
  <h1>Fragmented list</h1>
  <ul>
    <li data-marpit-fragment="1">One</li>
    <li data-marpit-fragment="2">Two</li>
    <li data-marpit-fragment="3">Three</li>
  </ul>
</section>

---
/* @theme marpit-theme */

:root {
  width: 1280px;
  height: 960px;
  font-size: 40px;
  padding: 1rem;
}

h1 {
  font-size: 1.5rem;
  color: #09c;
}

h2 {
  font-size: 1.25rem;
}
---
/* Change to the classic 4:3 slide */
section {
  width: 960px;
  height: 720px;
}

---
/* Change to the classic 4:3 slide */
section {
  width: 960px;
  height: 720px;
}
---
/* Styling page number */
section::after {
  font-weight: bold;
  text-shadow: 1px 1px 0 #fff;
}

---

section {
  padding: 50px;
}

header,
footer {
  position: absolute;
  left: 50px;
  right: 50px;
  height: 20px;
}

header {
  top: 30px;
}

footer {
  bottom: 30px;
}

---
/* @theme base */

section {
  background-color: #fff;
  color: #333;
}

---
---
theme: base
---

<style>
section {
  background: yellow;
}
</style>

# Tweak style through Markdown

You would see a yellow slide.

---
<!-- Global style -->
<style>
h1 {
  color: red;
}
</style>

# Red text

---

<!-- Scoped style -->
<style scoped>
h1 {
  color: blue;
}
</style>

# Blue text (only in the current slide page)

---

# Red text

---

/* Fit slide page to viewport */
svg[data-marpit-svg] {
  display: block;
  width: 100vw;
  height: 100vh;
}





