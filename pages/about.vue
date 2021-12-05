<template>
  <div>
    <Navigation />
    <div class="container" style="margin-top: 10px">
      <h1 class="title">About.</h1>

      <h3 class="subtitle">A little story about me.</h3>
    </div>
    <div class="row" style="background-color: #f2f2f2">
      <div class="col-sm-12 col-md-12 col-lg-12 col-xl-12">
        <div class="container row mx-auto" style="margin-top: 10px">
          <div class="col text-center">
            <h1 class="PersonalTitle">Personal</h1>

            <p class="subtitle">
              I'm a software engineering student based in Bukit Beruang, Melaka.
            </p>

            <p class="content">
              I have always wanted to learn and thirsted knowledge that will
              improve the progress of the company I am working for. My objective
              is to learn more knowledge and apply and improve the skills I
              achieved at university for my future career growth.
            </p>

            <img
              class="d-none d-md-block mx-auto"
              src="../assets/icon/win.png"
              width="500"
              height="500"
              alt="win.png"
            />
          </div>
        </div>
      </div>
    </div>
    <div class="row" style="background-color: #e6e6e6">
      <div class="col-sm-12 col-md-12 col-lg-12 col-xl-12">
        <div class="container row mx-auto" style="margin-top: 10px">
          <div class="col text-center" style="text-align: right">
            <h1 class="PersonalTitle">Contact</h1>

            <p class="subtitle">You can reach me via...</p>

            <p class="content">
              <img src="../assets/icon/email.png" alt="" /> akmalsab14@gmail.com
              <br />

              <img src="../assets/icon/phone-call.png" alt="" /> 011-2062-4714
              <br />

              <img src="../assets/icon/linkedin.png" alt="" />
              <a
                style="font-size: 18px"
                href="https://www.linkedin.com/in/muhammad-akmal-mohd-sabri-6b9398145/"
                target="blank"
                >Click me</a
              >
              <br />

              <img src="../assets/icon/github.png" alt="" />
              <a
                style="font-size: 18px"
                href="https://github.com/AkmalSab"
                target="blank"
                >Click me</a
              >
              <br />
            </p>
            <img
              class="d-none d-md-block mx-auto"
              src="../assets/icon/selfie.png"
              width="500"
              height="500"
              alt="selfie.png"
            />
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

.PersonalTitle {
  text-align: center;
  font-size: 60px;
  font-weight: bold;
}

.subtitle {
  text-align: center;
  font-size: 36px;
}

.content {
  text-align: center;
  font-size: 18px;
}
</style>