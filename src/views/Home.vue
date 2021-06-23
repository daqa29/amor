<template>
  <div class="home">
      <HelloWorld msg="We made these memories for ourselves"/>
      <h2>I want me by your side</h2>
    <img alt="Vue logo" src="../assets/amor4.jpg" height="350" width="250">
    <h2>Because I love your beautiful smile</h2>
    <img alt="Vue logo" src="../assets/amor1.jpg" height="350" width="250">
    <h2>Because I love your crazy things</h2>
    <img alt="Vue logo" src="../assets/amor6.jpg" height="350" width="250">
    <h2>Because I enjoy the process with you</h2>
    <img alt="Vue logo" src="../assets/amor8.jpg" height="350" width="250">
    <h2>You appear to me so tender and funny</h2>
    <img alt="Vue logo" src="../assets/amor5.jpg" height="350" width="250">
    <h2>You are also my calm</h2>
    <img alt="Vue logo" src="../assets/amor9.jpg" height="350" width="250">
    <h2>You know that I want to be with you all the time, you know that I won't stop until I make you mine</h2>
    <img alt="Vue logo" src="../assets/amor7.jpg" height="350" width="250">
    <h2>So kiss me, babe, that you are gone and I'm a mess</h2>
    <img alt="Vue logo" src="../assets/amor3.jpg" height="350" width="250">
    <h2>You need to know, we'll take it slow</h2>
    <img alt="Vue logo" src="../assets/amor10.jpg" height="350" width="250">
    <h2>¿Can we always be this close forever and ever?
</h2>
    <img alt="Vue logo" src="../assets/amor2.jpg" height="350" width="250">
    <h2> I'm yours</h2>
  <h1>¿Do you want to continue writing this story?</h1>
<button class="btn btn-primary" type="button" aling="left" v-on:click="ale()" >Yes</button>

  <button class="btn btn-danger" type="button" v-on:click="aotro()">No</button>
</div>

  
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  methods:{
    ale(){
        this.$router.push('/About')
    },
    aotro(){
    
      alert("Not available")
    }
  }

 
}
</script>

<style>
body{
  background: #B24592;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #F15F79, #B24592);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #F15F79, #B24592); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

}


</style>