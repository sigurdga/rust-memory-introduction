---
marp: true
title: Marp CLI example
description: Hosting Marp slide deck on the web
theme: uncover
paginate: true
_paginate: false
---

# <!--fit--> Rust og minnesikkerhet

---

![bg](#123)
![](#fff)

##### <!--fit--> [Marp CLI](https://github.com/marp-team/marp-cli) + [GitHub Pages](https://github.com/pages) | [Netlify](https://www.netlify.com/) | [ZEIT Now](https://zeit.co/now)

##### <!--fit--> 👉 The easiest way to host<br />your Marp deck on the web

---

# Safety and performance

* Automatisk minnehåndtering
* Ingen GC
* Ved hjelp av: Ownership, borrowing, references, lifetimes
  * I C-språk gjør du dette selv

---

# Ingen runtime

* Ingen initialiseringskost, som i f.eks i Python
* Kan få «Parity» med C/C++
  * Kan kalle Rust fra C og motsatt

---

# Safe concurrent programming

Alt du må gjennom for å bruke minne riktig, gjør også at
du og Rust holder orden på hvilken tråd som eier hvilket
objekt

---

# Historie

* 1.0 kom for fire år siden
* Men språket er ca åtte-ni år nå
* Kommer ny versjon hver sjette uke
* Vi er på versjon 1.39 nå
  * Med `async!`/`.await` stabilisert

---

# Hvem bruker Rust i dag

* Mozilla
* Microsoft
* Facebook
* Google
* Intel
* Amazon
* Dropbox
* Chef
* Fastly
* Baidu
* ...

---

# «Most loved» (Stack overflow)

TODO

---

# Binærstørrelse

* Ofte et negativt punkt at f.eks «Hello World» blir flere megabyte.
* Kan få det ned i 504 bytes, med en masse triks.

---

# Referanser

* [Intel and Rust: the Future of Systems Programming: Josh Triplett](https://www.youtube.com/watch?v=l9hM0h6IQDo&feature=youtu.be)
* [Bringing Rust home to meet the parents, Jeremmy Fitzhange](https://www.youtube.com/watch?v=kylqq8pEgRs)
* [70 percent](https://www.zdnet.com/article/microsoft-70-percent-of-all-security-bugs-are-memory-safety-issues/)
* [Mozilla 74%](https://hacks.mozilla.org/2019/02/rewriting-a-browser-component-in-rust/)
