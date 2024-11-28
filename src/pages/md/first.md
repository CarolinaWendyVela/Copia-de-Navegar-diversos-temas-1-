---
title: "detail-1"
layout: "../../layouts/Layout.astro"
---

<section transition:animate="slide"  class='flex gap-7 justify-center items-center flex-wrap text-white px-8% py-20'>
   <img class='rounded-xl' src="/images/image copy.png" alt="camiseta" />
   <div class='flex flex-col gap-4'>
   <h2 class='text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 from-10% via-primary via-30% to-green-600 font-semibold'>Cuerpo humano</h2>
   <h4>Explorando la Complejidad del Cuerpo Humano</h4>
   <p class='max-w-md'>El cuerpo humano es una máquina compleja compuesta por sistemas que funcionan en conjunto. El esqueleto, formado por 206 huesos, proporciona soporte y protege órganos vitales. Con más de 600 músculos, el cuerpo es capaz de moverse. El corazón, que pertenece al sistema circulatorio, bombea sangre para transportar oxígeno y nutrientes. El sistema respiratorio se encarga de captar oxígeno y expulsar dióxido de carbono. El sistema digestivo descompone los alimentos para obtener nutrientes, mientras que el sistema nervioso, liderado por el cerebro, coordina todas las funciones del cuerpo.  </p>
<button class='w-20 h-7 border-gray-50 border-2 rounded-md flex justify-center items-center hover:bg-blue-900 transition'>Buy</button>

   </div>
</section>

<style>
   section{
      width:100%;
      min-height: calc(100vh - 52px)
   }

</style>
