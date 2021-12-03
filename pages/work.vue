<template>
  <div>
    <Navigation />

    <div class="container" style="margin-top: 30px">
      <div class="row">
        <div
          class="col-4"
          v-for="repo in repos"
          :key="repo.id"
          style="margin-bottom: 30px"
        >
          <!-- start card -->
          <div class="card text-center">
            <div class="card-header">{{ repo.full_name }}</div>
            <div class="card-body">
              <h5 class="card-title">{{ repo.name }}</h5>
              <p class="card-text">
                {{ repo.description }}
              </p>
              <a href="" class="btn btn-primary">Visit</a>
            </div>
            <div class="card-footer text-muted">{{ repo.updated_at }}</div>
          </div>
          <!-- end card -->
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      repos: [],
    };
  },
  created() {
    this.fetchSomething();
  },
  methods: {
    async fetchSomething() {
      const ip = await this.$axios.$get(
        "https://api.github.com/users/AkmalSab/repos"
      );
      this.repos = ip;
    },
  },
};
</script>

<style scoped>
.title {
  margin-top: 100px;
  font-size: 100px;
  font-weight: bold;
}
</style>