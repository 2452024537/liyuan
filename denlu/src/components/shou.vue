<template>
  <div class="shou">
   
  </div>
</template>
<script>
export default {
  name: 'shou',
  data(){
      return{
         node:[
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"},
                  {name:"1111111111111111111111111111"}
              ]
      }
  },
  mounted(){
     window.addEventListener('scroll',this.watchscroll)
  },
  methods:{
     watchscroll:function(){
         var scrollTop = window.pageYOffset||document.documentElement.scrollTop||document.body.scrollTop;
         if(scrollTop>50){
            
         }
     }
  },
}
</script>
<style>
.heads{
  width:100%;
  height:50px;
  background: #000;
}
.active{
   position: fixed;
   top:50px;
   z-index: 999;
}
.liu{
  width:100%;
  height:60px;
  line-height: 40px;
  text-align: center;
}
</style>
