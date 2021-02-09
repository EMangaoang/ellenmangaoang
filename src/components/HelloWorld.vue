<template>
  <div class=" flex justify-center items-center h-screen  " >
  <div class=" flex flex-col   w-1/2 border border-collapse" >
    <div class="  flex   flex-col  bg-gray-200  p-8   justify-items-start">  
      <label class=" w-full text-left" for = "department"> Department </label> 
      <input class=" border  py-2 px text-gray-900"   type="text" name="department" id="department">
      </div>
  <div class=" flex  justify-end  p-2  ">
  <button class=" text-white   bg-indigo-500    rounded-md"   type="submit"> Create Department </button>
  </div> 
   </div> 
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
  color: #42b983;
}
</style>
