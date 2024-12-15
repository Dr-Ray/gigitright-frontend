<template>
    <div class="hr-row w-full justify-between" style="height: 58px;">
        <div class="hr-row spacex-2">
            <img src="/logo.png" alt="logo">
            <ul class="hr-row justify-between spacex-2">
                <li>Home</li>
                <li>Find work</li>
                <li>Search for skill</li>
                <li>How it works</li> 
            </ul>
        </div>
        <div class="hr-row spacex-2"> 
            <ButtonElememt msg="Sign up" />
            <ButtonElememt msg="Log in" />
        </div>
    </div>
</template>
<script>
import ButtonElememt from './button.vue';
export default {
  name: 'NavigationHeader',
  components:{
    ButtonElememt
  }
}
</script>
<style scoped>
    img {
        height: 58px;
        width: auto;
    }
</style>