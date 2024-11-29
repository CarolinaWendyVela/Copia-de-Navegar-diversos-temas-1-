---
title: "detail-6"
layout: "../../layouts/Layout.astro"
---

<section class="flex items-center flex-wrap text-white px-8% py-20">
  <div class='flex flex-col gap-4 items-start w-full'>
     <h2 class='font-semibold text-5xl'>
        Cuerpo humano
     </h2>
     <h4>Explorando la Complejidad del Cuerpo Humano</h4>
     <p class='w-full'>
        El cuerpo humano es una máquina compleja compuesta por diferentes sistemas de órganos, los cuales trabajan en conjunto para mantener la vida y garantizar el correcto funcionamiento del organismo. Cada uno de estos sistemas tiene una función específica, pero todos dependen de la interacción entre ellos para que el cuerpo pueda llevar a cabo sus actividades diarias.
        Uno de los sistemas más importantes es el esquelético, formado por 206 huesos que no solo proporcionan soporte al cuerpo, sino que también protegen órganos vitales como el cerebro, el corazón y los pulmones. Los huesos también funcionan como un lugar de almacenamiento de minerales y como una reserva de células sanguíneas, que se producen en la médula ósea.
        El sistema muscular, compuesto por más de 600 músculos, permite que el cuerpo se mueva. Los músculos están conectados al esqueleto y trabajan en conjunto para realizar movimientos, desde caminar hasta hablar o respirar. Además, algunos músculos, como el corazón, no solo nos permiten movernos, sino que desempeñan funciones esenciales, como bombear sangre.
        El corazón, que forma parte del sistema circulatorio, es un órgano fundamental para el transporte de oxígeno y nutrientes a todo el cuerpo. Este órgano bombea la sangre a través de los vasos sanguíneos, asegurándose de que todos los tejidos reciban los recursos que necesitan para funcionar correctamente.
        El sistema respiratorio está encargado de captar oxígeno del aire y expulsar el dióxido de carbono que produce el cuerpo como desecho. Los pulmones son el órgano principal de este sistema y permiten que el oxígeno pase a la sangre para ser transportado por todo el cuerpo. Al mismo tiempo, ayudan a eliminar el dióxido de carbono, un gas que debe ser expulsado para mantener el equilibrio en el organismo.
        El sistema digestivo es responsable de descomponer los alimentos que consumimos para obtener nutrientes. Estos nutrientes, como carbohidratos, proteínas y grasas, son absorbidos por el cuerpo y utilizados para obtener energía, crecer y reparar tejidos. El sistema digestivo incluye órganos como el estómago, los intestinos y el hígado, que trabajan juntos para procesar los alimentos y extraer sus componentes útiles.
        Finalmente, el sistema nervioso, liderado por el cerebro, coordina todas las funciones del cuerpo. El cerebro recibe información de los órganos y del entorno, y luego envía señales a los músculos y otros sistemas para regular las actividades, como el movimiento, el pensamiento, las emociones y las funciones automáticas, como la respiración y el ritmo cardíaco.
        Cada uno de estos sistemas juega un papel fundamental en el funcionamiento del cuerpo humano. Gracias a su trabajo conjunto, podemos realizar actividades cotidianas y mantenernos saludables. La clave para un cuerpo sano es asegurar que todos estos sistemas estén funcionando adecuadamente y se mantengan equilibrados.
     </p>
  </div>
</section>

<style>
  section {
     width: 100%;
     min-height: calc(100vh - 52px);
     background: linear-gradient(135deg, rgba(255, 165, 0, 0.8), rgba(255, 99, 71, 0.6), rgba(255, 69, 0, 0.7)); /* Colores naranja, rojo y anaranjado oscuro */
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
     color: #ff6347; /* Rojo tomate */
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
