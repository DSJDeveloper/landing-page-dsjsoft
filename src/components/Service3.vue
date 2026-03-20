<script setup>
import { themeColor } from "../data/items";

import mainPhoto from "../assets/images/qrjventas.png";

const service1Heading = "Sistema de Fuerza de Ventas";
const service1SubHeading = "QRJ Ventas";
function youtubeVideoUrl() {
  const youtubeVideoId = "FzRH7y3LbQE";
  return `https://www.youtube.com/watch?v=${youtubeVideoId}&amp;t=9s`;
}
</script>
<template>
  <div class="untree_co-section" id="qrjventas">
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
              Potencia la labor de tu equipo comercial con una aplicación móvil diseñada para ser sencilla, rápida y
              confiable. Con nuestro sistema, los vendedores pueden cargar pedidos directamente en el cliente, realizar
              cobranzas al instante y registrar toda la información en el sistema de manera automática.

              <!-- Potencia tu Fuerza de Ventas: Sin Límites, Sin Interrupciones "Optimiza la labor de tus vendedores con nuestra solución móvil de alto rendimiento. Registra pedidos y gestiona cobranzas en tiempo real con una interfaz diseñada para la velocidad. Gracias a nuestra tecnología Smart-Sync, el equipo puede trabajar en zonas sin cobertura sin perder un solo dato: la aplicación almacena todo localmente y sincroniza automáticamente al recuperar la conexión. Mantén la operatividad de tu empresa activa las 24 horas, en cualquier lugar." -->
            </p>
            <ul class="list-unstyled ul-check primary">
              <li><strong>Pedidos inmediatos:</strong> Registra órdenes en el momento, reduciendo errores y tiempos de
                gestión.</li>
              <li><strong>Cobranzas integradas:</strong> Procesa pagos y registra cobranzas directamente en el sistema.
              </li>
              <li><strong>Trabajo sin conexión:</strong> Guarda todo localmente y sincroniza al recuperar la conexión.
              </li>
              <li><strong>Plataforma administrativa:</strong> Visualiza en tiempo real todos los pedidos realizados.
              </li>
              <li><strong>Multiintegración:</strong> Se conecta con cualquier sistema de facturación y actualmente está
                integrado con <strong>CataSuite</strong>.</li>

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
