<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container"> 
      <a class="navbar-brand" href="#">My Portfolio</a>
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
            style="color: white; font-size: 20px"
          >
            <path
              fill-rule="evenodd"
              d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5zm0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5z"
            />
          </svg>
        </span>
      </button>
      <div class="collapse navbar-collapse" id="navbarText">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
              <NuxtLink class="nav-link active" aria-current="page" :to="{name: 'index'}">Home</NuxtLink>
          </li>
          <li class="nav-item">
                <NuxtLink class="nav-link" :to="{name: 'about'}">About</NuxtLink>
          </li>
          <li class="nav-item">
              <NuxtLink class="nav-link" :to="{name: 'service'}">Services</NuxtLink>
          </li>
          <li class="nav-item">
              <NuxtLink class="nav-link" :to="{name: 'work'}">Work</NuxtLink>
          </li>
          <li class="nav-item">
              <NuxtLink class="nav-link" :to="{name: 'contact'}">Contact</NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style>
a {
  color: white;
  font-size: 20px;
}

a:hover {
  color: black;
}
</style>