<template>
  <header class="min-vh-100 bg-image-1 position-relative">
    <nav class="navbar navbar-light p-5">
      <div class="container-fluid px-0">
        <button class="navbar-toggler me-auto" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase">
            <li class="nav-item py-3">
              <router-link class="nav-link fw-bold" aria-current="page" to="#">newsletter</router-link>
            </li>
            <li class="nav-item py-3">
              <router-link class="nav-link fw-bold" to="#">view stories</router-link>
            </li>
            <li class="nav-item py-3">
              <router-link class="nav-link fw-bold" to="#">about</router-link>
            </li>
            <li class="nav-item py-3">
              <router-link class="nav-link fw-bold" to="#">suscribe</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section>
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="wrapper text-center">
              <div class="position-absolute top-50 start-50 translate-middle">
                <h1 class="display-1 px-5 fw-bolder text-uppercase ls-5px mb-5 ff-alatsi">yama</h1>
                <router-link to="#">
                  <i class="fs-1 far fa-play-circle"></i>
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

