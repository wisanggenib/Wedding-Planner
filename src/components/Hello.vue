<template>
<div>
  <div class="paralax">
    <div class="nav-template">
      <div class="nav-logo"><img src="../assets/logo.svg" alt="Vue.js PWA" width="40"></div>
      <div class="nav-item">Venue</div>
      <div class="nav-item">Our Story</div>
      <div class="nav-item">Dresscode</div>
      <div class="nav-item">Wishes</div>
    </div>
    <div class="main">
      <div class="left-side">
        <span style="font-size:36px">Alex & Andriane</span>
        <div class="title">We Are <br> Tying <br> The Knot!</div>
        <span style="padding-top:40px;font-size:18px">Choose a seat, not a side. <br>We're all family once the knot is tied.</span>
      </div>
      <div class="date" style="align-self: flex-start;padding-top:7.5%;">
        <span>21</span>
        <span>02</span>
        <span>21</span>
      </div>
      <div class="date" style="align-self: flex-end;position:relative;bottom:26%;">
        <span>21</span>
        <span>02</span>
        <span>21</span>
      </div>
    </div>
  </div>
  <div class="venue">
    <div class="layer0">
      <div class="details">
        <hr style="width:80%;margin-bottom:30px">
        <span style="font-size:36px">Ceremony & Receipt</span>
        <span style="font-size:60px; font-family: 'Gilda Display';">04:00 PM</span>
        <span style="font-size:40px; font-family: 'Gilda Display';">21 February 2021</span>
        <span style="font-size:24px">at</span>
        <span style="font-size:40px;text-align:center;padding-left:10px;padding-right:10px">Legion Beach Hotel <br>Jalan Melasti, Legian, Kuta, Badung, Bali, 80361, Indonesia</span>
        <span style="font-size:16px;font-style:italic;color: #5E6B7B;">Click here for maps</span>
      </div>
      <div class="couple-images"></div>
    </div>
    <div class="layer1" style="position:absolute;z-index:19;">
      <span class="half-circle"></span>
    </div>
  </div>
  <div class="btn-place">
    <button>See how it all began &nbsp <img src='../assets/icons/arrow-right.svg' alt=""></button>
  </div>
  
</div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'xxx'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.paralax{
  background-image: url('../assets/background/bg.png');
  /* Create the parallax scrolling effect */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 113vh;
}
.nav-template{
  display: flex;
  align-items: stretch;
  margin-left: 12vh;
  margin-right: 12vh;
}
.nav-logo{
  display: flex;
  align-items: center;
  align-self: center;
  align-content: center;
  justify-content: center;
  width: 15vh;
  padding: 20px;
  padding-right: 100px;
}
.nav-item{
  display: flex;
  align-items: center;
  padding: 20px;
}
.main{
    /* The image used */
  /* background-image: url('../assets/background/bg.png'); */
  /* Full height */
  height: 100vh; 
  display: flex;
  padding-left: 10%;
  padding-right: 10%;
}
.title{
  color: black;
  font-size: 100px;
  display: flex;
  flex-direction: column;
    font-family: 'Gilda Display';
}

.left-side{
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.date{
  display: flex;
  flex-direction: column;
  font-size: 60px;
  align-self: flex-start;
  /* margin-top: -100px; */
  padding-left:10%;
}

.date > span{
  padding: 15px;
}

.venue{
  display: flex;
}

.layer0{
  display: flex;
  margin-left: 20vh;
  margin-right: 14vh;
  justify-content: space-between;
  width: 100%;
}
.layer1{
  display: flex;
  flex-direction: row-reverse;
  width: 100%;
}
.half-circle{
  width: 44.6vh;
  height: 35vh;
  background: rgba(94, 107, 123, 0.45);
}
.details{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 85vh;
}
.details > span{
  padding-bottom: 17px;
}
.couple-images{
  width:111vh;
  height: 85vh;
  background-image: url('../assets/marry.png');
    background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.btn-place{
  display: flex;
  flex-direction: row-reverse;
  height: 15vh;
  margin-left: 20vh;
  margin-right: 14vh;
  align-items: center; 
}
.btn-place > button{
  height: 8vh;
  font-size: 14px;
  padding-left: 25px;
  padding-right: 25px;
  border: 1px solid #5E6B7B;
  background: white;
  color: #5E6B7B;
  font-family: 'Gilda Display';
}
/* h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #35495E;
} */
</style>
