<script setup>
import { themeColor } from "../data/items";
import mainPhoto from "../assets/images/about.svg";

const heading = "Acerca";
const subHeading = "Acerca de Nosotros";
const totalMembers = "50";
const totalTeam = "20";
</script>

<template>
  <div class="untree_co-section" id="about-section">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-8" data-aos="fade-up" data-aos-delay="100">
          <img :src="mainPhoto" alt="Image" class="img-fluid" />
        </div>
        <div class="col-lg-4">
          <div class="mb-4" data-aos="fade-up" data-aos-delay="0">
            <span class="caption" :style="[{ color: themeColor }]">{{
              heading
            }}</span>
            <h2 class="heading">{{ subHeading }}</h2>
          </div>
          <div class="mb-4" data-aos="fade-up" data-aos-delay="100">
            <p>
              En DSJ Soft, transformamos ideas en soluciones digitales que impulsan negocios inteligentes. Desarrollamos
              sistemas robustos, intuitivos y adaptados a la realidad de Venezuela y Latinoamérica, combinando
              tecnología de vanguardia con una experiencia de usuario simple y confiable.
            </p>
            <p>
              Nuestros productos —como <strong>SINVAD</strong>, <strong>QRJ Ventas</strong>— están diseñados para facilitar el trabajo
              diario, automatizar procesos clave y ofrecer control total desde cualquier dispositivo. Integramos
              pasarelas de pago como Banco R4, trabajamos con múltiples empresas desde una sola plataforma, y ofrecemos
              compatibilidad con sistemas de facturación como CataSuite.
            </p>
            <p>
              Creemos en soluciones que crecen contigo: escalables, seguras y listas para adaptarse a tus ideas. Ya sea
              que vendas en campo  o administres operaciones complejas, en DSJ Soft te damos las
              herramientas para lograrlo.
            </p>
          </div>
          
          <!-- <div class="row count-numbers">
            <div class="col-lg-6" data-aos="fade-up" data-aos-delay="0">
              <span class="counter d-block"><span :data-number="totalMembers">{{ totalMembers
              }}</span><span>M</span></span>
              <span class="caption-2">Members</span>
            </div>
            <div class="col-lg-6" data-aos="fade-up" data-aos-delay="100">
              <span class="counter d-block"><span :data-number="totalTeam">{{ totalTeam }}</span><span></span></span>
              <span class="caption-2">Team</span>
            </div>
          </div> -->
        </div>
      </div>
    </div>
  </div>
</template>
