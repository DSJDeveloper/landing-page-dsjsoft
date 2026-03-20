<script setup>
import { themeColor } from "../data/items";
// import personPhoto from "../assets/images/person_1.jpg";
import mainPhoto from "../assets/images/sinvad.png";

const service1Heading = "Sistema de Facturación";
const service1SubHeading = "S.I.N.V.A.D";
const service1Quote =
  '"Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia."';
const personName = "James Anderson";
const designation = "Facebook, Product Lead";
function youtubeVideoUrl() {
  const youtubeVideoId = "FzRH7y3LbQE";
  return `https://www.youtube.com/watch?v=${youtubeVideoId}&amp;t=9s`;
}
</script>
<template>
  <div class="untree_co-section" id="sinvad">
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
              El Sistema de Inventario, Facturación y Administrativo (SINVAD) es una plataforma web integral
              orientada a optimizar la gestión empresarial. Permite automatizar procesos
              críticos, mejorar el control operativo y acelerar las transacciones comerciales,
              aportando eficiencia, trazabilidad y consistencia en cada etapa del negocio.
            </p>
            <ul class="list-unstyled ul-check primary">
              <li><strong>Automatización:</strong> Reduce tareas manuales y errores, estandarizando flujos clave.</li>
              <li><strong>Control:</strong> Mejora la visibilidad de inventarios, órdenes y movimientos en tiempo real.</li>
              <li><strong>Agilidad:</strong> Acelera ventas, compras y facturación con procesos claros y confiables.</li>
              <li><strong>Trazabilidad:</strong> Registra eventos y cambios para auditoría y toma de decisiones.</li>
              <li><strong>Multiempresa:</strong> Administra múltiples empresas desde una sola plataforma, con total independencia y control centralizado.</li>
            </ul>
          </div>
        
        </div>
        <div class="col-lg-7" data-aos="fade-up" data-aos-delay="400">
        <!--   <a :href="youtubeVideoUrl()" class="btn-video" data-fancybox>
            <span class="wrap-icon-play">
              <svg class="bi bi-play-fill" width="1em" height="1em" viewBox="0 0 16 16" fill="currentColor"
                xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M11.596 8.697l-6.363 3.692c-.54.313-1.233-.066-1.233-.697V4.308c0-.63.692-1.01 1.233-.696l6.363 3.692a.802.802 0 0 1 0 1.393z" />
              </svg>
            </span>
            <img :src="mainPhoto" alt="Image" class="img-fluid img-shadow" />
          </a>-->
          <img :src="mainPhoto" alt="Image" class="img-fluid img-shadow" />
        </div> 
        
      </div>
    </div>
  </div>
</template>
