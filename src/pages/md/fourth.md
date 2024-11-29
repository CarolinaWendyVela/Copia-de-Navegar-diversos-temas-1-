---
title: "detail-6"
layout: "../../layouts/Layout.astro"
---

<section class="flex items-center flex-wrap text-white px-8% py-20">
  <div class='flex flex-col gap-4 items-start w-full'>
     <h2 class='font-semibold text-5xl'>
        Niveles de organización
     </h2>
     <h4>Explorando los Niveles de Organización en la Biología</h4>
     <p class='w-full'>
        La biología estudia la vida y está organizada en distintos niveles, cada uno de los cuales es más complejo que el anterior. El primer nivel es el átomo, que es la unidad básica de la materia. Los átomos se combinan para formar moléculas, que son estructuras químicas más complejas. Estas moléculas se agrupan para formar células, que son la unidad fundamental de los seres vivos.
        Las células no trabajan solas; se agrupan en tejidos, que son conjuntos de células similares que realizan una función específica. Los tejidos, a su vez, se combinan para formar órganos, como el corazón o los pulmones, que tienen funciones más especializadas dentro del organismo.
        Cuando varios órganos trabajan juntos para realizar tareas específicas, forman un sistema de órganos, como el sistema digestivo o el sistema circulatorio. El conjunto de todos estos sistemas de órganos constituye un organismo, que es un ser vivo completo y funcional.
        Los organismos de la misma especie se agrupan en poblaciones, que interactúan entre sí dentro de una comunidad, un espacio donde diferentes especies conviven y se relacionan. Finalmente, varias comunidades, junto con su entorno físico (agua, aire, tierra, etc.), forman un ecosistema.
        Cada uno de estos niveles refleja la complejidad de la vida, mostrando cómo los organismos están organizados en sistemas interconectados, desde las partículas más pequeñas hasta las grandes interacciones ecológicas.
  </div>
</section>

<style>
  section {
     width: 100%;
     min-height: calc(100vh - 52px);
     background: linear-gradient(135deg, rgba(0, 128, 0, 0.8), rgba(60, 179, 113, 0.6), rgba(34, 139, 34, 0.7)); /* Colores de verde suave */
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
     color: #2e8b57; /* Verde bosque */
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
