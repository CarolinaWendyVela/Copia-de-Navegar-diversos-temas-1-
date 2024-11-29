---
title: "detail-6"
layout: "../../layouts/Layout.astro"
---

<section class="flex items-center flex-wrap text-white px-8% py-20">
  <div class='flex flex-col gap-4 items-start w-full'>
     <h2 class='font-semibold text-5xl'>
        Evolución
     </h2>
     <h4>El Viaje de la Vida: Comprendiendo la Evolución</h4>
     <p class='w-full'>
        La evolución es el proceso mediante el cual las especies de seres vivos cambian a lo largo del tiempo. Estos cambios ocurren de forma gradual, a lo largo de muchas generaciones, y son el resultado de factores como la selección natural, las mutaciones genéticas y la deriva genética. Este proceso es fundamental para comprender cómo ha surgido la increíble diversidad de seres vivos en la Tierra, y por qué los organismos se adaptan mejor a sus entornos. Por ejemplo, un animal puede desarrollar características que lo ayudan a sobrevivir en un ambiente determinado, como pelaje más grueso en climas fríos o colores que lo hacen invisible a sus depredadores.
        La evolución no es algo que suceda de un día para otro. Es un proceso muy lento que puede tomar miles o millones de años. Los cambios ocurren a nivel genético, es decir, en la información contenida en el ADN de los organismos. Estas modificaciones pueden ser heredadas y pasadas a las siguientes generaciones.
        El concepto clave en la evolución es que todas las especies actuales comparten un ancestro común, lo que significa que la vida en la Tierra ha ido cambiando y diversificándose desde un origen común. Este proceso es lo que ha permitido que existan diferentes tipos de plantas, animales y otros organismos adaptados a los distintos ambientes del planeta.
     </p>
  </div>
</section>

<style>
  section {
     width: 100%;
     min-height: calc(100vh - 52px);
     background: linear-gradient(135deg, rgba(138, 43, 226, 0.8), rgba(147, 112, 219, 0.6), rgba(186, 85, 211, 0.7)); /* Colores morado y lila */
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
     color: #8a2be2; /* Morado */
     background: none;
     -webkit-background-clip: unset;
  }

  /* Estilo del subtítulo */
  h4 {
     font-size: 1.5rem;
     color: #fff; /* Blanco */
  }

  /* El texto del párrafo ocupa todo el ancho */
  p {
     font-size: 1rem;
     line-height: 1.6;
     text-align: justify;
  }
</style>
