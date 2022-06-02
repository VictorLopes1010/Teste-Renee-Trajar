<template>
    <div>
      <header-component/>
    </div>
    <div>
      <body-component/>
    </div>
    <div>
      <footer-component/>
    </div>
</template>

<script>
  import HeaderComponent from './components/HeaderComponent.vue'
  import BodyComponent from './components/BodyComponent.vue'
  import FooterComponent from './components/FooterComponent.vue'

  export default {
    name: 'App',
    components: {
      HeaderComponent,
      BodyComponent,
      FooterComponent
  }
}
</script>


