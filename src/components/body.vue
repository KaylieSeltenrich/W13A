<template>

  <div
    class="page-body">
   <side-right />
   <body-meet />
    <side-left />
    </div>
  
</template>


<script>
import SideRight from "./sideright.vue";
import SideLeft from "./sideleft.vue";
import BodyMeet from "./meet.vue";

export default {
  name: "page-body",
  components: {
  SideRight,
  SideLeft,
  BodyMeet

  }
};
</script>

<style scoped>
.page-body {
  display: grid;
  justify-items: center;
  align-items: center;
  grid-template-columns: 1fr 1fr 1fr;
  margin: 10%;
}
</style>