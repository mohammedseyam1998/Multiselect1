<template>
  <div id="app">
    
    <multi></multi>
    
    <footer>Mohammed a seyam</footer>
  </div>
</template>

<script>
import Vue from 'vue'
import Multi from './components/Multi.vue'
import { MultiSelectPlugin } from "@syncfusion/ej2-vue-dropdowns";
// import PerfectScrollbar from 'perfect-scrollbar';
// const ps = new
//         PerfectScrollbar('.e-multiselect.e-input-group.e-control-wrapper', {
//         wheelSpeed: 2,
//         wheelPropagation: true,
//         minScrollbarLength: 20
//         });
// ps.update();



Vue.use(MultiSelectPlugin);

export default {
  name: 'app',
  
  components: {
    Multi
  }
}
</script>

<style>



@import "../node_modules/@syncfusion/ej2-base/styles/material.css";
@import "../node_modules/@syncfusion/ej2-inputs/styles/material.css";
@import "../node_modules/@syncfusion/ej2-vue-dropdowns/styles/material.css";
footer{
  background-color: brown;
  color: aliceblue;
  text-align: center;
  margin: 2px;
  padding: 5px
}
.control_wrapper{
   position: relative;
    width: 500px;
    height: 300px;
  
}

.e-multi-select-wrapper{
  padding: 1px;
}

.e-multiselect e-input-group e-control-wrapper{
  direction: rtl;
}
.e-multi-select-wrapper .e-searcher{
  float: left;
  width: 100% ;
}
input.e-dropdownbase{
  direction: rtl;
}

</style>

