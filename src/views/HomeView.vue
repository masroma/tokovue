<template>
  <div class="home">
    <CarouselComponent />
    <SliderProductComponent />
    <InstagramComponent />
    <PartnerComponent />
    <FooterComponent />
  </div>
</template>

<script>
// @ is an alias to /src

import CarouselComponent from '@/components/CarouselComponent.vue';
import SliderProductComponent from '@/components/SliderProductComponent.vue';
import InstagramComponent from '@/components/InstagramComponent.vue';
import PartnerComponent from '@/components/PartnerComponent.vue';
export default {
  name: 'HomeView',
  components: {
    CarouselComponent,
    SliderProductComponent,
    InstagramComponent,
    PartnerComponent,
  }
}
</script>
