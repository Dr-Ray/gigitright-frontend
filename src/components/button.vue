<template>
    <button>
        {{ msg }}
    </button>
</template>
<script>
export default {
  name: 'ButtonElememt',
  props: {
    msg: String,
    color: String,
    background: String
  }
}
</script>>

<style scoped>
  button{
    width: fit-content;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 15px;
    padding-right: 15px;
    border-radius: 50px;
    border: none;
    background-color: #0071ce;
    color: #fff;
  }
</style>