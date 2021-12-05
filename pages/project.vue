<template>
  <div>
    <Navigation />

    <div class="container" style="margin-top: 10px">
      <h1 class="title">Showcase.</h1>

      <h3 class="subtitle">
        Check out some of my latest web development project.
      </h3>
    </div>

    <div
      class="container mx-auto"
      style="padding-top: 20px; background-color: #e6e6e6; border-radius: 10px"
    >
      <div class="row mx-auto">
        <div
          class="col-sm-12 col-md-6 col-lg-4 col-xl-4"
          v-for="repo in repos"
          :key="repo.id"
          style="margin-bottom: 30px"
        >
          <!-- start card -->
          <div class="card text-center h-100">
            <div class="card-header h-auto" v-if="repo.language">
              {{ repo.language }}
            </div>
            <div class="card-header h-auto" v-else>Undefined</div>
            <div class="card-body d-flex flex-column">
              <h5 class="card-title">{{ repo.name }}</h5>
              <p class="card-text" v-if="repo.description">
                {{ repo.description }}
              </p>
              <p class="card-text" v-else>No Description</p>
              <a
                :href="repo.html_url"
                target="_blank"
                style="margin-top: auto"
                class="btn btn-primary"
                >Visit</a
              >
            </div>
            <div class="card-footer text-muted">
              Updated at: {{ myDateFormat(repo.updated_at) }}
            </div>
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
    myDateFormat(d) {
      var a = new Date(d);
      return (
        ("0" + a.getDate()).slice(-2) +
        "/" +
        ("0" + (a.getMonth() + 1)).slice(-2) +
        "/" +
        a.getFullYear()
      );
    },
  },
};
</script>

<style scoped>
.title {
  text-align: center;
  margin-top: 30px;
  font-size: 100px;
  font-weight: bold;
}
.subtitle {
  text-align: center;
  font-size: 36px;
}
@media screen and (max-width: 414px) {
  .title {
    text-align: center;
    margin-top: 30px;
    font-size: 80px;
    font-weight: bold;
  }
}
</style>