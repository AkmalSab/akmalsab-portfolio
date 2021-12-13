<template>
  <div>
    <Navigation />
    <div class="container" style="margin-top: 10px">
      <h1 class="title">Experience.</h1>

      <h3 class="subtitle">List of my past experiences.</h3>

      <div class="button">
        <a class="btn btn-primary" href="/AkmalSab_Resumes.pdf">My Resume</a>
        <a class="btn btn-primary" href="/AkmalSab_Cvs.pdf">My CVs</a>
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
          <div class="col">
            <h1 class="AcademicTitle">UTeMXpress</h1>
            <p class="AcademicSubtitle">
              Universiti Teknikal Malaysia Melaka (UTeM)
            </p>
            <p class="content">2020 - 2021</p>
            <p class="content">
              UTeM Xpress is an application that allows the user even if they do
              not own a vehicle, university communities can easily manage their
              things by enlisting the aid of a runner to bring their items to
              the desired spot.
            </p>
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
          <div class="col">
            <h1 class="AcademicTitle">Internship IT Shared Service Centre</h1>
            <p class="AcademicSubtitle">Sunway Group</p>
            <p class="content">June 2019 - August 2019 : 10 Weeks</p>
            <p class="content">
              Study and manage the business architecture of Sunway Pals system
            </p>
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
          <div class="col">
            <h1 class="AcademicTitle">The Code: Code Hunt</h1>
            <p class="AcademicSubtitle">
              Universiti Teknikal Malaysia Melaka (UTeM)
            </p>
            <p class="content">2017 - 2018</p>
            <p class="content">
              Competition solving issue based on C++ programming language
            </p>
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

.AcademicSubtitle {
  text-align: left;
  font-size: 36px;
}

.subtitle {
  text-align: center;
  font-size: 36px;
}

.content {
  text-align: justify;
  font-size: 18px;
}

.button{
  text-align: center;
  margin: auto;
  margin-bottom: 5px;
}

@media screen and (max-width: 414px) {
  .title {
    text-align: center;
    margin-top: 30px;
    font-size: 80px;
    font-weight: bold;
  }

  .AcademicTitle {
    text-align: center;
    font-size: 60px;
    font-weight: bold;
  }

  .AcademicSubtitle {
    text-align: center;
    font-size: 36px;
  }
  .content {
    text-align: center;
    font-size: 18px;
  }
}
</style>