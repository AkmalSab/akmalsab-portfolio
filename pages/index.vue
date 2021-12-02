<template>
  <div class="container-fluid">
    <Navigation />

    <div class="container mx-auto text-center">
      <h1 class="title">I am Akmal Sab</h1>

      <div class="typewriter">
        <h3>Student, Developer, Cat Lover</h3>
      </div>
    </div>

    <Footer />
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
      crossorigin="anonymous"
    ></script>
  </div>
</template>
<script>
export default {};
</script>

<style scoped>
/* .img{
  background-image: url("../assets/img/bg.jpg");
  height: 100vh;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-position: center center;
} */

.title {
  margin-top: 100px;
  font-size: 100px;
  font-weight: bold;
}

.typewriter h3 {
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: 0.15em solid black; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: 0.15em; /* Adjust as needed */
  animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from,
  to {
    border-color: transparent;
  }
  50% {
    border-color: orange;
  }
}
</style>