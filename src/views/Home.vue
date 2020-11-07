<template>
  <div>
    <Jumbotron/>
    <Search/>
  </div>
</template>

<script>
import Jumbotron from "@/components/Jumbotron.vue";
import Search from "@/components/Search.vue";

export default {
  name: 'Home',
  components: {
    Jumbotron,
    Search
  }
}
</script>
