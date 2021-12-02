<template>
  <nav class="navbar navbar-expand-lg">
    <a class="navbar-brand" href="#">My Portfolio</a>
    <!-- toggler button -->
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="collapse"
      data-bs-target="#navbarText"
      aria-controls="navbarText"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="currentColor"
          class="bi bi-list"
          viewBox="0 0 16 16"
          style="color: black; font-size: 20px"
        >
          <path
            fill-rule="evenodd"
            d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"
          />
        </svg>
      </span>
    </button>
    <!-- toggler button -->

    <!-- navbar -->
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <NuxtLink
            class="nav-link active"
            aria-current="page"
            :to="{ name: 'index' }"
            >Home</NuxtLink
          >
        </li>
        <li class="nav-item">
          <NuxtLink
            class="nav-link"
            :to="{ name: 'about' }"
            >About</NuxtLink
          >
        </li>
        <li class="nav-item">
          <NuxtLink
            class="nav-link"
            :to="{ name: 'academic' }"
            >Academic</NuxtLink
          >
        </li>
        <li class="nav-item">
          <NuxtLink
            class="nav-link"
            :to="{ name: 'work' }"
            >Work</NuxtLink
          >
        </li>
        <li class="nav-item">
          <NuxtLink
            class="nav-link"
            :to="{ name: 'contact' }"
            >Contact</NuxtLink
          >
        </li>
      </ul>
    </div>
    <!-- navbar -->
  </nav>
</template>

<script>
export default {};
</script>

<style>
a {
  color: black;
  font-size: 24px;
}

a.navbar-brand {
  font-size: 36px;
  font-weight: bolder;
}

a.nav-link.active {
  font-size: 24px;
  font-weight: bold;
  color: #404040;
}

a.nav-link:hover {
  font-size: 24px;
  color: white;
  background-color: black;
  border-radius: 5px;
}

a.nav-link:active {
  font-size: 24px;
  color: grey;
}
</style>