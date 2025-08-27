---
layout: default
title: Terapia Cannábica para Mascotas
subtitle: Bienestar natural para tu compañero de vida
include_path: tratamientos/veterinaria
order: 1
---

<main>
  <section id="que-ofrecemos" class="bg-textura-verde">
    {% include {{ page.include_path }}/que_ofrecemos.html %}
  </section>

  <section id="indicaciones" class="bg-textura-verde">
    {% include {{ page.include_path }}/indicaciones.html %}
  </section>

  <section id="banner_follow_us" class="">
    {% include banner_follow_us.html %}
  </section>

  <section id="como-funciona" class="bg-textura-verde-logo">
    {% include {{ page.include_path }}/como_funciona.html %}
  </section>

  <section id="formulario" class="py-5 bg-light">
    {% include {{ page.include_path }}/formulario.html %}
  </section>
</main>