<template>
  <div class="main-container">
    <!-- Navbar section -->
    <HeaderShowcase />

    <!-- Intro -->
    <HeroAppShowcase />

    <!-- 1. Presentacion -->
    <Presentacion />
    <Cartas />

    <!-- 2.	UCDD EE. UU. -->
    <UCDDUS />

    <!-- 3. three step process -->
    <RelacionHistorica />

    <!-- 4. UCDD Chile -->
    <UCDDChile />

    <!-- 5. Nuestra Mision -->
    <NuestraMision />


    <!-- 7. Impacto -->
    <Impacto />

    <!-- 8. Areas de trabajo -->
    <AreasTrabajo />

    <!-- 9. Aporte Simetrico -->
    <AporteSimetrico />

    <!--10. Cifras -->
    <Cifras />

    <!-- 11. Proyectos -->
    <Proyectos />
    <!-- overlay menu section -->
    <OverlayMenu />

    <FooterMain />
  </div>
</template>

<script>
import HeaderShowcase from "@/components/HeaderShowcase";
import Cartas from "@/components/sections/Cartas";
import HeroAppShowcase from "@/components/HeroAppShowcase";
import UCDDUS from "@/components/sections/UCDDUS";
import UCDDChile from "@/components/sections/UCDDChile";
import Cifras from "@/components/sections/Cifras";
import Presentacion from "@/components/sections/Presentacion";
import RelacionHistorica from "@/components/sections/RelacionHistorica";
import OverlayMenu from "@/components/OverlayMenu";
import NuestraMision from "@/components/sections/NuestraMision";
import AreasTrabajo from "@/components/sections/AreasTrabajo.vue";
import Proyectos from "@/components/sections/Proyectos.vue";
import Impacto from "@/components/sections/Impacto.vue";
import AporteSimetrico from "@/components/sections/AporteSimetrico.vue";
import FooterMain from "@/components/FooterMain";
export default {
  name: "app",
  components: {
    HeaderShowcase,
    Cartas,
    Cartas,
    UCDDUS,
    HeroAppShowcase,
    Presentacion,
    RelacionHistorica,
    Cifras,
    OverlayMenu,
    NuestraMision,
    AreasTrabajo,
    Proyectos,
    FooterMain,
    UCDDChile,
    Impacto,
    AporteSimetrico,
  },
};
</script>

