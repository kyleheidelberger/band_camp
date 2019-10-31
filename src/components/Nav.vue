<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand flex-grow-1 font-weight-bold" href="/"
      >Mid-Atlantic Camps</a
    >
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNavAltMarkup"
      aria-controls="navbarNavAltMarkup"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-item nav-link active" href="/"
          >Home <span class="sr-only">(current)</span></a
        >
        <a class="nav-item nav-link" href="info.html">Info</a>
        <a class="nav-item nav-link" href="contact.html">Contact</a>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Nav",
  props: {}
};
</script>