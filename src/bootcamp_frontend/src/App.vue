<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Siema!
    <br/>
    <button @click="podbij">podbij</button>
    <button @click="zbij">zbij</button>
    {{ licznik }}
  </main>
</template>

<script>
export default{
  data(){
    return{
      licznik: 0
    }
  },
  methods:{
    podbij(){
      this.licznik++
    },
    zbij(){
      this.licznik--
    }
  }
}
</script>
