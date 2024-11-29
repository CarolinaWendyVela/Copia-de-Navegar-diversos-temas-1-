---
title: "detail-6"
layout: "../../layouts/Layout.astro"
---

<section class="flex items-center flex-wrap text-white px-8% py-20">
  <div class='flex flex-col gap-4 items-start w-full'>
     <h2 class='font-semibold text-5xl'>
        Sistema de órganos
     </h2>
     <h4>El Sistema de Órganos en el Cuerpo Humano</h4>
     <p class='w-full'>
       El cuerpo humano es una máquina increíblemente compleja que depende de la colaboración de diferentes sistemas de órganos para mantenerse vivo y funcionar correctamente. Cada uno de estos órganos tiene un papel específico y está diseñado para llevar a cabo funciones vitales que permiten que todo el cuerpo trabaje de manera coordinada.
       Uno de los sistemas más importantes es el sistema circulatorio, que incluye al corazón y los vasos sanguíneos. El corazón actúa como una bomba, enviando sangre a través de todo el cuerpo. Esta sangre transporta oxígeno y nutrientes a las células, y recoge dióxido de carbono y otros desechos para ser eliminados. Sin este proceso, las células no recibirían el oxígeno necesario para generar energía y funcionar.
       El sistema respiratorio, compuesto principalmente por los pulmones, también juega un papel crucial. Los pulmones se encargan de intercambiar gases con el aire. El oxígeno que inhalamos pasa a la sangre a través de los pulmones, mientras que el dióxido de carbono, un desecho de las células, es expulsado cuando exhalamos. Este intercambio es vital porque el oxígeno es necesario para que las células generen energía, mientras que eliminar el dióxido de carbono previene la acumulación de toxinas en el cuerpo.
       Por otro lado, el sistema digestivo tiene la función de procesar los alimentos que ingerimos. Los alimentos se descomponen en nutrientes como glucosa, proteínas y grasas, que son absorbidos y utilizados por el cuerpo para obtener energía, reparar tejidos y realizar otras funciones vitales. El sistema digestivo está formado por órganos como el estómago, los intestinos y el hígado, cada uno con una tarea específica dentro del proceso de digestión.
       El sistema nervioso, encabezado por el cerebro, es el encargado de coordinar todas las actividades del cuerpo. El cerebro recibe información sobre el entorno y el estado del cuerpo, y luego envía señales a los músculos y otros órganos para que actúen en consecuencia. Este sistema no solo controla funciones automáticas como el ritmo cardíaco, sino también nuestras acciones voluntarias, emociones y pensamientos.
       Todos estos sistemas están interconectados y dependen unos de otros para garantizar el buen funcionamiento del cuerpo. Si uno de ellos falla o no funciona correctamente, puede afectar a todo el organismo. Por eso es esencial cuidar nuestra salud y asegurarnos de que todos nuestros órganos estén en buen estado para mantenernos vivos y activos.
     </p>
  </div>
</section>

<style>
  section {
     width: 100%;
     min-height: calc(100vh - 52px);
     background: linear-gradient(135deg, rgba(138, 43, 226, 0.8), rgba(255, 105, 180, 0.6), rgba(255, 20, 147, 0.7)); /* Colores morados y rosados */
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
     color: #DDA0DD; /* Color morado claro */
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
