<template>
  <div>
    <Navigation />
    <div class="container" style="margin-top: 10px">
      <h1 class="title">Academic.</h1>

      <h3 class="subtitle" style="text-align: center">
        List of academic experiences.
      </h3>
    </div>
    <div class="container mx-auto row">
      <div
        class="col"
        style="
          background-color: #d9d9d9;
          margin-bottom: 10px;
          border-radius: 10px;
        "
      >
        <div class="container row mx-auto" style="margin-top: 10px">
          <div class="col">
            <h1 class="AcademicTitle">Bachelor of Software Engineering</h1>

            <p class="subtitle">Universiti Teknikal Malaysia Melaka (UTeM)</p>

            <p class="content">February 2020 - Now</p>
          </div>
        </div>
      </div>
    </div>
    <div class="container mx-auto row">
      <div
        class="col"
        style="
          background-color: #d9d9d9;
          margin-bottom: 10px;
          border-radius: 10px;
        "
      >
        <div class="container row mx-auto" style="margin-top: 10px">
          <div class="col" style="text-align: right">
            <h1 class="AcademicTitle">Diploma in Information Technology</h1>

            <p class="subtitle">Universiti Teknikal Malaysia Melaka (UTeM)</p>

            <p class="content">January 2017 - December 2020 : 3 Years</p>
          </div>
        </div>
      </div>
    </div>
    <div class="container mx-auto row">
      <div
        class="col"
        style="
          background-color: #d9d9d9;
          margin-bottom: 10px;
          border-radius: 10px;
        "
      >
        <div class="container row mx-auto" style="margin-top: 10px">
          <div class="col" style="text-align: right">
            <h1 class="AcademicTitle">Sijil Pelajaran Malaysia</h1>

            <p class="subtitle">Sekolah Menengah Kebangsaan Bentong (SMKB)</p>

            <p class="content">January 2012 - December 2016 : 5 Years</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style scoped>
.profile-image {
  border-radius: 50%;
  width: auto;
  height: auto;
}

.title {
  text-align: center;
  margin-top: 30px;
  font-size: 100px;
  font-weight: bold;
}

.AcademicTitle {
  text-align: left;
  font-size: 60px;
  font-weight: bold;
}

.subtitle {
  text-align: left;
  font-size: 36px;
}

.content {
  text-align: justify;
  font-size: 18px;
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