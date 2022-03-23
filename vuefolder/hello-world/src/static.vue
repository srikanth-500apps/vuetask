<template>
    <div>
        hello
     <h2>message:{{message}}</h2>
     <h2>name:{{name}}</h2>
     <h2>number:{{number}}</h2>
    </div>
</template>
<script>
export default {
        name:"SriKanth",
    props :{
 message:String,
 name:String,
 number:Number,
    },
methods:{
   fun(){
       alert("hi")
   }
}
}
</script>
