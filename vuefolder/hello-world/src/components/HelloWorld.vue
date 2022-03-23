<template>
  <div class="hello">
   
  <stati :message="message" :name="name" ref="num" :number="number"></stati>
  <stati :message="message" :name="name" ref="numb" :number="number"></stati>
   <button @click="buttonClick()">submit</button>
  </div>
</template>

<script>

import stati from '../static.vue'

export default {
  name: 'HelloWorld',
components:{  
  stati,
  
},
  data(){
    return{
      message:"hi",
      name:"Naveen",
      number:123,
    }
  },
methods:{
   buttonClick(){
     this.$refs.num.fun();
    
       
     }
   }
}
</script>
