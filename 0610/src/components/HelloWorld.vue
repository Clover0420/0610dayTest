<template>
  <div>
    <header>首页</header>
    <main>首页</main>
    <footer>首页</footer>
  </div>
</template>
<script>
export default {
  props:{

  },
  components:{

  },
  data(){
    return {

    }
  },
  computed:{

  },
  methods:{

  },
  created(){

  },
  mounted(){

  }
}
</script>
<style scoped lang="">

div{
  width:100%;
  height:100%;
  display:flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
header,footer{
  width: 100%;
  height: 50px;
  line-height: 50px;
  text-align: center;
  background-color: #444;
  color: #fff;
}

main{
  width: 100%;
  height: 100%;
  overflow: hidden;
}
</style>