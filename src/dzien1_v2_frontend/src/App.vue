
<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <br />
    <br />
    <p>hello world</p>
    <br>
    {{ licznik }}
    <input type="text" id="button1">
  </main>
</template>

<script>
let but1 = document.getElementById('button1').addEventListener('click', function(){
  iteruj();
})
export default{
  date(){
    return{
      licznik: 0
    }
  },
  methods: {
    iteruj() {
      this.licznik++
    }
  },
}
</script>