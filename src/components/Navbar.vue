<template>
  <nav class="navbar pt-3 bg-transparent">
    <div class="container-fluid text-center">
      <div class="email">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="20"
          height="20"
          fill="currentColor"
          class="bi bi-envelope"
          viewBox="0 0 20 20"
        >
          <path
            d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2zm13 2.383-4.758 2.855L15 11.114v-5.73zm-.034 6.878L9.271 8.82 8 9.583 6.728 8.82l-5.694 3.44A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.739zM1 11.114l4.758-2.876L1 5.383v5.73z"
          />
        </svg>
        <span class="navbar-brand mb-0 h1 fw-bold"
          >itsme@akbarafriansyah.my.id</span
        >
      </div>
      <div class="content p-2 d-flex justify-content-between">
        <a>Home</a>
        <a>About</a>
        <a>Project</a>
        <a>Contact</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
path {
  line-height: 50%;
}
span {
  line-height: 200%;
}
</style>