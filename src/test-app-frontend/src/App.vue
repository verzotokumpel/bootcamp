
<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    GMGMGMGMGMGM
    <br/>
    {{ counter }}
    <button @click="increment">Increment</button>
  </main>
</template>

<script>
  export default {
    data(){
      return {
        counter: 0
      }
    },
    methods: {
      increment(){
        this.counter++;
      }
    }
  };
</script>