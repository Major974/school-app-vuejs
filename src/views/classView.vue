<template>
  <div class="header">
    <headerDashboard />
  </div>
  <body>
    <div class="body">
      <h1>Toutes les classes</h1>
      <classForm />
    </div>
  </body>
</template>

<script>
import headerDashboard from "../components/headerDashboardComponent.vue";
import classForm from "../components/classFormComponent.vue";

export default {
  components: {
    headerDashboard,
    classForm,
  },
};
</script>

<style scoped>
body {
  width: 70%;
}
.body {
  width: 100%;
  margin-top: -60%;
  margin-left: 35%;
  display: flex;
  flex-direction: column;
}
.header {
  display: flex;
  width: 1%;
  margin-left: 5%;
}
</style>
