<template>
  <div>
    <NavbarComponent style="background-color:hotpink;"></NavbarComponent> <br>
   <HeaderComponent></HeaderComponent> <br>
   <CardComponent></CardComponent> <br>
   <CardComponent2></CardComponent2> <br>
   <CardComponent3></CardComponent3> <br>
   <FooterComponent></FooterComponent> <br>
  </div>
</template>

<script setup>
import NavbarComponent from './components/NavbarComponent.vue';
import CardComponent from './components/CardComponent.vue';
import HeaderComponent from './HeaderComponent.vue';
import CardComponent2 from './components/CardComponent2.vue';
import CardComponent3 from './components/CardComponent3.vue';
import FooterComponent from './components/FooterComponent.vue';
</script>