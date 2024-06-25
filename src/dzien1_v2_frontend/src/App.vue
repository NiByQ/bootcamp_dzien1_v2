
<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <br>
    hello world 
    <br>
    {{ licznik }}
    <button @click="iteruj">iteruj</button>
  </main>
</template>

<script>

export default{
  data(){
    return{
      licznik: 0
    }
  },
  methods: {
    iteruj() {
      this.licznik++
      console.log("a");
    }
  },
}
</script>