<script setup>
import mainPhoto from "../assets/images/hero.svg";
import { themeColor } from "../data/items";

const heroHeading = "Impulsamos tu negocio con software a medida";
const buttonSeeFeature = "Productos";
const buttonPricing = "Precios";
</script>

<template>
  <div class="untree_co-hero" id="home-section">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-12">
          <div class="dots"></div>
          <div class="row align-items-center">
            <div class="col-lg-7 ml-auto order-lg-2" data-aos="fade-right" data-aos-delay="400">
              <img :src="mainPhoto" alt="Image" class="img-fluid" />
            </div>
            <div class="col-lg-5">
              <h1 class="heading" data-aos="fade-up" data-aos-delay="0">
                {{ heroHeading }}
              </h1>
              <div class="excerpt" data-aos="fade-up" data-aos-delay="100">
                <p>
                  Más de 15 años impulsando la transformación digital de tu negocio con software a medida, diseñado para
                  maximizar eficiencia y potenciar el crecimiento
                  <!-- Más de 15 Años Optimizando tu Negocio: Software a Medida para la Eficiencia y el Crecimiento. -->
                  <!-- Somos tu socio tecnológico estratégico, comprometido con el desarrollo de soluciones integrales, eficientes y confiables que se alinean directamente con tus objetivos de crecimiento y escalabilidad. -->
                </p>
                <p>
                  Somos tu socio tecnológico estratégico, comprometido con el desarrollo de soluciones integrales,
                  confiables y escalables que se alinean con tus objetivos y acompañan cada etapa de tu evolución
                  empresarial.
                </p>
              </div>
              <p data-aos="fade-up" data-aos-delay="200">
                <a href="#sinvad" class="btn btn-primary smoothscroll" style="margin-right: 5px" :style="[
                  { background: themeColor },
                  { borderColor: themeColor },
                ]">{{ buttonSeeFeature }}</a>
                <!-- <a href="#pricing-section" class="btn btn-outline-primary smoothscroll pricing"
                  :style="[{ color: themeColor }, { borderColor: themeColor }]">{{ buttonPricing }}</a> -->
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.pricing:hover {
  color: #fff !important;
}
</style>
