<template>
  <footer>
    <div class="container">
      <div class="row align-items-center h-vh-30 py-5">
        <div class="col-lg-12">
          <div class="wrapper">
            <div class="copyright d-block d-lg-flex justify-content-lg-between align-items-lg-center text-center">
              <div class="mb-5 mb-lg-0">
                <router-link class="text-decoration-none mx-2" to="#"><i class="fab fa-instagram"></i></router-link>
                <router-link class="text-decoration-none mx-2" to="#"><i class="fab fa-twitter"></i></router-link>
                <router-link class="text-decoration-none mx-2" to="#"><i class="fab fa-facebook-f"></i></router-link>
                <router-link class="text-decoration-none mx-2" to="#"><i class="fab fa-pinterest"></i></router-link>
              </div>
              <ul class="text-uppercase d-inline mp-0">
                <li class="d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">newsletter</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">view stories</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">about</router-link>
                </li>
                <li class="d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block" to="#">subscribe</router-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>