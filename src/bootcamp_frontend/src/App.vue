<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
   Witaj!!!!
     <br>
     <button @click="increase">Dodaj</button><br>
   <span>{{ licznik }}</span>
  </main>
</template>
<script>
export default {
data(){
  return {
    licznik: 0
  }
},
  methods: {
    increase(){
      this.licznik++;
    }
  }
  }

</script>
