<template>
  <div>
    <h1>{{ pageTitle }}</h1>
  </div>
</template>

<script>
export default {
  name: 'JavaScript',
  data() {
    return {
      pageTitle: ''
    };
  },
  created() {
    this.pageTitle = this.$route.name;
  }
}
</script>
