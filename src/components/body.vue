<template>

  <div
    class="page-body">
   <side-right />
    </div>
  
</template>


<script>
import SideRight from "./sideright.vue"

export default {
  name: "page-body",
  components: {
  SideRight
  }
};
</script>

<style scoped>
.page-body {
  display: grid;
  justify-items: center;
  align-items: center;
  grid-template-columns: 1fr;
  margin: 10%;
}
</style>