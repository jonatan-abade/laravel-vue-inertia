<template>
  <layout>
    <div>Olá eu s ou a home {{ user }}</div>
  </layout>
</template>

<script>
import Layout from "../Layout";
export default {
  props: {
    user: String,
  },
  components: { Layout },
};
</script>

<style>
</style>