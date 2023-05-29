<script setup>

import SpainMap from "./components/SpainMap.vue";
</script>

<template>
  <h1>Check the Spanish Elections</h1>
<SpainMap/>
  <ul>
    <li>PSOE</li>
    <li>PP</li>
    <li>UPN</li>
  </ul>
</template>

<style scoped>

ul {
  list-style: none;
  display: inline-flex;

  gap: 8px;



  margin-right: auto;
  margin-left: auto;
}

ul li:first-child::before {
  content: "";
  background-color: rgb(220, 18, 34);
  border-radius: 50%;
  display: inline-block;
  width: 16px; /* Increase the width */
  height: 16px; /* Increase the height */
  margin-right: 8px; /* Adjust the spacing between the bullet and the text */
}

ul li:nth-child(2)::before {
  content: "";
  background-color: rgb(48, 166, 223);;
  border-radius: 50%;
  display: inline-block;
  width: 16px; /* Increase the width */
  height: 16px; /* Increase the height */
  margin-right: 8px; /* Adjust the spacing between the bullet and the text */
}
ul li:nth-child(3)::before {
  content: "";
  background-color: rgb(33, 59, 154);;
  border-radius: 50%;
  display: inline-block;
  width: 16px; /* Increase the width */
  height: 16px; /* Increase the height */
  margin-right: 8px; /* Adjust the spacing between the bullet and the text */
}


</style>
