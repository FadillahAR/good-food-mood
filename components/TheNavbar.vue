<template>
  <div>

    <!-- Dekstop -->
    <b-container class="d-none d-md-none d-lg-block">
      <b-navbar >
        <img src="../assets/images/elemes.png" class="logo ml-1" alt="">
        <b-navbar-nav class="mx-auto">
            <b-nav-item href="#">
                <router-link class="nav-link" to="/">Home</router-link>
            </b-nav-item>
            <b-nav-item href="#">
                <router-link class="nav-link" to="/foods">About</router-link>
            </b-nav-item>
            <b-nav-item href="#">
                <b-badge variant="danger" class="hot">
                    HOT
                </b-badge>
                <router-link class="nav-link" to="/foods">Promotions</router-link>

            </b-nav-item>
            <b-nav-item href="#">
                <router-link class="nav-link" to="/foods">Blogs</router-link>
            </b-nav-item>
            <b-nav-item href="#">
                <router-link class="nav-link" to="/foods">Contact Us</router-link>
            </b-nav-item>
        </b-navbar-nav>

        <b-navbar-nav>
            <b-nav-item href="#">
                <router-link class="nav-link" to="/">
                  <strong>Masuk</strong>
                </router-link>
            </b-nav-item>
            <b-nav-item href="#">
                <button class="btn btn-success">Daftar Sekarang</button>
            </b-nav-item>
        </b-navbar-nav>
      </b-navbar>
    </b-container>

      <!-- Mobile -->
    <b-container class="mobile d-sm-block d-md-block d-lg-none" >
      <b-navbar >
        <img src="../assets/images/elemes.png" class="logo ml-1" alt="">
          <b-navbar-nav class="ml-auto">
              <b-nav-item href="#">
                  <button class="btn btn-success">Daftar Sekarang</button>
              </b-nav-item>
          </b-navbar-nav>
      </b-navbar>
    </b-container>
  </div>
</template>
