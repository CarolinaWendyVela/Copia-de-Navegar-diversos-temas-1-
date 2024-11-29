---
title: "detail-6"
layout: "../../layouts/Layout.astro"
---

<section class="flex items-center flex-wrap text-white px-8% py-20">
  <div class='flex flex-col gap-4 items-start w-full'>
     <h2 class='font-semibold text-5xl'>
        Origen de la Vida
     </h2>
     <h4>Conoce más sobre el origen de la vida</h4>
     <p class='w-full'>
        El origen de la vida es un tema fascinante y complejo, que ha generado diversas teorías en la biología y la geología. Los científicos han logrado estimar que la Tierra se formó hace aproximadamente 4.500 millones de años, gracias a la datación radiométrica de las rocas más antiguas de nuestro planeta, de la Luna y de meteoritos. Sin embargo, el ambiente en la Tierra primitiva era muy diferente al actual, ya que estaba constantemente bombardeada por asteroides y atravesaba ciclos de calentamiento y enfriamiento. 
        Aunque sabemos más o menos cuándo se formó la Tierra, la pregunta clave sigue siendo: ¿cuándo surgieron los primeros seres vivos? El estudio de los fósiles ha sido fundamental para tratar de responder a esta cuestión. Los fósiles más antiguos encontrados hasta ahora, como los estromatolitos en Australia Occidental, tienen aproximadamente 3.500 millones de años. Los estromatolitos son formaciones rocosas creadas por la actividad de microorganismos unicelulares, lo que indica que los primeros seres vivos eran bacterias o organismos similares. 
        No obstante, estos fósiles no corresponden a animales complejos, sino a formas de vida simples. Los primeros animales pluricelulares aparecieron mucho después, hace unos 500 millones de años. Esto sugiere que la vida comenzó con organismos muy simples que no dejaron huellas fósiles fácilmente, lo que hace difícil determinar con precisión el momento exacto en que la vida comenzó.
        A pesar de que las bacterias son organismos relativamente complejos, lo que indica que la vida probablemente surgió mucho antes, no existen fósiles de organismos más simples, lo que dificulta aún más la investigación. En resumen, aunque hemos logrado desentrañar muchos aspectos del origen de la vida, aún hay muchas preguntas sin responder sobre cómo las primeras moléculas orgánicas se convirtieron en los primeros seres vivos.
     </p>
  </div>
</section>

<style>
  section {
     width: 100%;
     min-height: calc(100vh - 52px);
     background: linear-gradient(135deg, rgba(0, 191, 255, 0.8), rgba(0, 255, 255, 0.6), rgba(70, 130, 180, 0.7)); /* Colores tropicales azul y aqua */
     background-size: 300% 300%;
     animation: gradientAnimation 3s ease infinite;
  }

  /* Animación de gradiente para simular luces moviéndose */
  @keyframes gradientAnimation {
     0% {
        background-position: 0% 50%;
     }
     50% {
        background-position: 100% 50%;
     }
     100% {
        background-position: 0% 50%;
     }
  }

  /* Estilo para el título */
  h2 {
     font-size: 5rem;
     text-align: left;
     font-weight: bold;
     line-height: 1.2;
     margin-bottom: 15px;
     color: #003366; /* Azul marino */
     background: none;
     -webkit-background-clip: unset;
  }

  /* Estilo del subtítulo */
  h4 {
     font-size: 1.5rem;
     color: #d1d1d1; /* Color gris claro */
  }

  /* El texto del párrafo ocupa todo el ancho */
  p {
     font-size: 1rem;
     line-height: 1.6;
     text-align: justify;
  }
</style>
