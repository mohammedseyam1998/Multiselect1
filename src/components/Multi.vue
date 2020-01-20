<template>
  <div class="Multi">
    <h2>This is a MultiSelect</h2>
    <div  class="control_wrapper" style="margin:100px auto ; width:300px"   >
        <ejs-multiselect id='multiselect' :dataSource='sportsData' placeholder="Select Your Languages" ></ejs-multiselect>
    </div>
  </div>
</template>

<script>



export default {
  name: 'Multi',
  data(){
    return{
      sportsData: ['Arabic', 'English', 'French', 'chinease', 'spanish','germane','italy','maxican','ggermane','iitaly','mmaxican']
    }

  },
 
}
</script >

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
div{
  margin: 50px ;
  text-align: center;
}
h2{
  color: brown;
}



</style>
