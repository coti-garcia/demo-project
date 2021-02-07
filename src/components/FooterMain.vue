<template>
  <div class="footer-area-wrapper" :class="FooterStyle">
    <div class="footer-area section-space--ptb_90">
      <div class="container">
        <div class="row footer-widget-wrapper">
          <div class="col-lg-4 col-md-6 footer-widget">
            <ul class="footer-widget__list">
              <li>
                Av. Santa María 2670, oficina 206 <br />Providencia, Santiago •
                Chile
              </li>
              <li>
                <a
                  href="mailto:UCDDchile@UCDD.edu"
                  class="hover-style-link"
                  >UCDDchile@UCDD.edu</a
                >
              </li>
              <li>
                <a
                  href="https://chile.UCDD.edu/en"
                  target="_blank"
                  class="hover-style-link"
                  >chile.UCDD.edu</a
                >
              </li>
            </ul>
          </div>
          <div class="col-lg-2 col-md-6 footer-widget">
            <ul class="footer-widget__list">
              <li>
                <router-link
                  :to="{ name: 'UCDDEEEUU' }"
                  class="hover-style-link"
                  >UCDD EE.UU</router-link
                >
              </li>
              <li>
                <router-link
                  :to="{ name: 'RelacionHistorica' }"
                  class="hover-style-link"
                  >Relación histórica</router-link
                >
              </li>
              <li>
                <router-link
                  :to="{ name: 'UCDDChile' }"
                  class="hover-style-link"
                  >UCDD Chile</router-link
                >
              </li>
              <li>
                <router-link :to="{ name: 'Mision' }" class="hover-style-link"
                  >Nuestra misión</router-link
                >
              </li>
              <li>
                <router-link
                  :to="{ name: 'QuienesSomos' }"
                  class="hover-style-link"
                  >Quiénes somos</router-link
                >
              </li>
            </ul>
          </div>
          <div class="col-lg-3 col-md-6 footer-widget">
            <ul class="footer-widget__list">
              <li>
                <router-link :to="{ name: 'Impacto' }" class="hover-style-link"
                  >Impacto</router-link
                >
              </li>
              <li>
                <router-link
                  :to="{ name: 'AreasTrabajo' }"
                  class="hover-style-link"
                  >Áreas de trabajo</router-link
                >
              </li>
              <li>
                <router-link
                  :to="{ name: 'AporteSimetrico' }"
                  class="hover-style-link"
                  >Aporte simétrico</router-link
                >
              </li>
              <li>
                <router-link :to="{ name: 'Cifras' }" class="hover-style-link"
                  >Cifras</router-link
                >
              </li>
              <li>
                <router-link
                  :to="{ name: 'Proyectos' }"
                  class="hover-style-link"
                  >Principales proyectos</router-link
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-copyright-area border-top section-space--ptb_30">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-md-6 text-center text-md-left">
            <span class="copyright-text"> © All rights reserved.</span>
          </div>
     
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterMain",
  props: ["FooterStyle"],
};
</script>
<style lang="scss" scoped>
.logo-dark {
  max-width: 250px;
}
</style>