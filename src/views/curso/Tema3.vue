<template lang="pug">
.curso-main-container
  BannerInterno(titulo="Tema 3 adipiscing elit. Nunc lacinia risus non nisl tincidunt condimentum")
  .container.tarjeta--blanca.p-4.p-md-5.mb-5
    
    #t_3_1.pb-5.h2 tema 3.1
    .pb-5(v-for="item of 15")

    #t_3_3.pb-5.h2 tema 3.2
    .pb-5(v-for="item of 15")

    #t_3_3.pb-5.h2 tema 3.3
    .pb-5(v-for="item of 15")

    #t_3_4.pb-5.h2 tema 3.4
    .pb-5(v-for="item of 15")

    #t_3_5.pb-5.h2 tema 3.5
    .pb-5(v-for="item of 15")

    #t_3_6.pb-5.h2 tema 3.6
    .pb-5(v-for="item of 15")

</template>

<script>
import BannerInterno from '../../components/plantilla/BannerInterno'
export default {
  name: 'Tema1',
  components: {
    BannerInterno,
  },
}
</script>

<style lang="sass" scoped></style>
