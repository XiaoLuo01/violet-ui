<template>
  <div style="margin: 30px 0">
    <v-pagination :total-page='5' :current-page.sync="currentPage"></v-pagination>
  </div>
</template>

<script>
import Pagination from "../../../src/navigation/pagination/pagination";
export default {
  name: "",
  data() {
    return {
      currentPage: 1
    };
  },
  components: {
    "v-pagination": Pagination
  }
};
</script>
<style lang="scss" scoped>
</style>
