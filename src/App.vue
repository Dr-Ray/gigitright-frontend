<template>
  <div class="container">
    <NavigationHeader />
    <div class="banner">
      <div class="relative text-center mx-auto w-500">
        <h2>Connection between <span>gigs</span> and <span>Freelancers</span> <br /> starts from here</h2>
        <p class="text-center">
          Connection between Companies and Freelancers starts from here
          Connection between Companies and Freelancers starts from here
        </p>
        <div class="hr-row justify-center">
          <ButtonElememt msg="Find a job" />
          <ButtonElememt msg="Find a talent" />
        </div>
        <img src="/u1.png" class="img img-1" alt="">
        <img src="/u2.png" class="img img-2" alt="">
      </div>
    </div>
  </div>
  <div class="h-150 mt-8 bg-blue hr-row justify-evenly bg-underBanner">
    <div class="text-center">
      <h2 class="text-white text-bold">100,000</h2>
      <p class="text-white">Jobs gotten</p>
    </div>
    <div class="text-center">
      <h2 class="text-white text-bold">100,000</h2>
      <p class="text-white">Active Freelancers</p>
    </div>
    <div class="text-center">
      <h2 class="text-white text-bold">100,000</h2>
      <p class="text-white">Employers</p>
    </div>
    <div class="text-center">
      <h2 class="text-white text-bold">100,000</h2>
      <p class="text-white">Current Jobs Openings</p>
    </div>
  </div>
  <div class="container">
    <div class="">
      
    </div>
  </div>
</template>

<script>
import NavigationHeader from './components/navigation.vue';
import ButtonElememt from './components/button.vue';
export default {
  name: 'App',
  components: {
    NavigationHeader,
    ButtonElememt
  }
}
</script>

<style>
*,
html {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: sans-serif;
}
li {
  list-style-type: none;
}

.banner {
  display: flex;
  flex-direction: column;
  height: 350px;
  justify-content: center;
}
.bg-underBanner {
  background-color: #147cd0;
}
.h-100 {
  height: 100px;
}
.h-150 {
  height: 150px;
}
.h-200 {
  height: 200px;
}
.mt-8{
  margin-top: 32px;
}
a {
  text-decoration: none;
}

.relative {
  position: relative;
}

.img {
  object-fit: cover;
}
.text-white {
  color:#fff;
}
.text-bold {
  font-weight: bold;
}
.img-1 {
  position: absolute;
  top: -20px;
  right: -100px;
  width: 100px;
  height: auto;
}

.img-2 {
  position: absolute;
  bottom: -100px;
  left: -100px;
}

.container {
  width: 90%;
  padding-right: 10px;
  padding-left: 10px;
  margin: 0 auto;
  display: block;
}

.text-center {
  text-align: center !important;
}

.flex {
  display: flex;
}

.d-col {
  display: flex;
  flex-direction: column;
}

.justify-between {
  justify-content: space-between;
}

.justify-around {
  justify-content: space-around;
}

.justify-center {
  justify-content: center;
}
.justify-evenly {
  justify-content: space-evenly;
}

.hr-row {
  display: flex;
  flex-direction: row;
  align-items: center;
}

.spacex-1 {
  gap: .5rem;
}

.spacex-2 {
  gap: 1rem;
}

.spacex-3 {
  gap: 1.5rem;
}

.mx-auto {
  margin-left: auto;
  margin-right: auto;
}

.w-500 {
  width: 500px;
}

@media screen and(max-width:400px) {
  .container {
    width: 98%;
  }
}
</style>
