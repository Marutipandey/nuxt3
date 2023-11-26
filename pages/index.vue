<template>
  <div>
    <NuxtLink to="/about">About Page</NuxtLink>
    <Tutorial/>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  head(){
    return{
      meta:[
        {
          title:"Index Page",
          name:"Description detail about test about data",
          content:"XYZ SDFRG SDFG DFGH DFG"
        }
      ]
    }
  }
};
</script>
