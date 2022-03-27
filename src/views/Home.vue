<template>
  <div class="home">
    <Header/>
    <CarouselComponent/>
    <ItemsComponent/>
    <InstaComponent/>
    <PartnerComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/HeaderComponent.vue'
import CarouselComponent from '@/components/CarouselComponent.vue'
import ItemsComponent from '@/components/ItemsComponent.vue'
import InstaComponent from '@/components/InstaComponent.vue'
import PartnerComponent from '@/components/PartnerComponent.vue'
import FooterComponent from '@/components/FooterComponent.vue'


export default {
  name: 'Home',
  components: {
    Header,
    CarouselComponent,
    ItemsComponent,
    InstaComponent,
    PartnerComponent,
    FooterComponent

  }
}
</script>
