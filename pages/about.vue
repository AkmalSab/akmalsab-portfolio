<template>
  <div>
    <Navigation />

    <div class="row" style="background-color: #f2f2f2">
      <div class="col-sm-12 col-md-6 col-lg-6 col-xl-6">
        <div class="container row mx-auto" style="margin-top: 10px">
          <div class="col">
            <h1 class="title">Personal</h1>

            <p class="subtitle">
              I'm a software engineering student based in Bukit Beruang, Melaka.
            </p>

            <p class="content">
              I enjoy turning complex problems into simple, beautiful and
              intuitive designs. When I'm not pushing pixels, you'll find me
              cooking, gardening or working out in the park.
            </p>
          </div>
        </div>
      </div>
      <div
        class="
          d-none d-md-block
          col-sm-12 col-md-6 col-lg-6 col-xl-6
          text-center
        "
      >
        <img
          src="../assets/icon/win.png"
          width="500"
          height="500"
          alt="win.png"
        />
      </div>
    </div>
    <div class="row" style="background-color: #e6e6e6">
      <div
        class="
          d-none d-md-block
          col-sm-12 col-md-6 col-lg-6 col-xl-6
          text-center
        "
      >
        <img
          src="../assets/icon/selfie.png"
          width="500"
          height="500"
          alt="selfie.png"
        />
      </div>
      <div class="col-sm-12 col-md-6 col-lg-6 col-xl-6">
        <div class="container row mx-auto" style="margin-top: 10px">
          <div class="col" style="text-align: right">
            <h1 class="title">Contact</h1>

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
  text-align: left;
  font-size: 100px;
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
</style>