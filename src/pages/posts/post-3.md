---
title: "Mi primer componente en Astro"
description: "Aprendiendo a crear componentes reutilizables en Astro."
pubDate: "2025-07-04"
author: "Tu Nombre"
tags: ["Astro", "Componentes", "Frontend"]
---

# 🧱 Mi primer componente en Astro

Hoy creé mi primer componente en Astro: una tarjeta de presentación para mis posts.

```astro
---
// src/components/PostCard.astro
const { title, description } = Astro.props;
---
<article class="card">
  <h2>{title}</h2>
  <p>{description}</p>
</article>
