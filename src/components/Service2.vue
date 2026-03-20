<script setup>
import { themeColor } from "../data/items";

import mainPhoto from "../assets/images/rifa.png";

const service1Heading = "Sistema de Rifas";
const service1SubHeading = "Rifas";
function youtubeVideoUrl() {
  const youtubeVideoId = "FzRH7y3LbQE";
  return `https://www.youtube.com/watch?v=${youtubeVideoId}&amp;t=9s`;
}
</script>
<template>
  <div class="untree_co-section" id="rifas">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-4">
          <span class="caption" data-aos="fade-up" data-aos-delay="0" :style="[{ color: themeColor }]">{{
            service1Heading }}</span>
          <h3 class="heading mb-4" data-aos="fade-up" data-aos-delay="100">
            {{ service1SubHeading }}
          </h3>
          <div class="mb-4" data-aos="fade-up" data-aos-delay="200">
            <p>
              Transformamos la participación en un proceso sencillo y transparente. Gracias a una navegación intuitiva y
              pagos seguros, tus clientes compran con total confianza desde cualquier lugar y dispositivo, eliminando
              las barreras de compras de tus clientes. Como administrador, cuentas
              con una infraestructura potente para gestionar ventas, automatizar sorteos y garantizar una trazabilidad
              completa en cada etapa
            </p>
            <ul class="list-unstyled ul-check primary">
              <li><strong>Tickets digitales:</strong> Emisión automática con validación única y seguimiento.</li>
              <li><strong>Sorteos:</strong> Algoritmos de selección aleatoria auditables.</li>
              <li><strong>Panel de control:</strong> Estadísticas en tiempo real, historial de rifas y gestión de
                premios.
              </li>
              <li><strong>Gestión de rifas múltiples:</strong> Puedes tener activa múltiples rifas de manera simultánea.
              </li>
              <li><strong>Notificaciones integradas:</strong> Comunica resultados por correo, SMS o WhatsApp.</li>
              <li><strong>Integración Bancaria:</strong> El sistema sincroniza en tiempo real con la pasarela de Banco
                R4.</li>
            </ul>
          </div>

        </div>
        <div class="col-lg-7" data-aos="fade-up" data-aos-delay="400">
          <!-- <a :href="youtubeVideoUrl()" class="btn-video" data-fancybox>
            <span class="wrap-icon-play">
              <svg class="bi bi-play-fill" width="1em" height="1em" viewBox="0 0 16 16" fill="currentColor"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M11.596 8.697l-6.363 3.692c-.54.313-1.233-.066-1.233-.697V4.308c0-.63.692-1.01 1.233-.696l6.363 3.692a.802.802 0 0 1 0 1.393z" />
              </svg>
            </span>
            <img :src="mainPhoto" alt="Image" class="img-fluid img-shadow" />
          </a> -->
          <img :src="mainPhoto" alt="Image" class="img-fluid img-shadow" />
        </div>
      </div>
    </div>
  </div>
</template>
