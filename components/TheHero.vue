<template>
  <div class="hero">
    <!-- Dekstop -->
    <div class="d-none d-md-block">
      <b-container class="justify-content-md-center">
          <b-row class="mt-10">
            <b-col>
              <h1>Good Food Us<br>Good Mood</h1>
              <p class="mt-4">I would think that conserving our natural resources <br>should be a conservative position: Not to waste food, and not to throw away a lot of the food that we buy.</p>
              <b-navbar-nav class="d-flex flex-row nav-hero mt-4">
                <b-nav-item href="#" class="pr-4">
                    <button class="btn btn-success">Daftar Sekarang</button>
                </b-nav-item>
                <b-nav-item href="#">
                    <router-link class="nav-link" to="/">
                      <h5>About us</h5>
                    </router-link>
                </b-nav-item>
            </b-navbar-nav>
            </b-col>
            <b-col>
              <img src="../assets/images/greenSaladTomato.png" class="justify-content-md-center ml-6" alt="">
              <b-card img-src="../assets/images/greensaladsmall.png" img-alt="Card image" img-left title="Green Salad Tomato" class="card-tomato" >
                <b-card-text>
                  Tomato
                </b-card-text>
                <span class="icon is-left fa-xs">
                  <fa :icon="['fas', 'star']" />
                  <fa :icon="['fas', 'star']" />
                  <fa :icon="['fas', 'star']" />
                  <fa :icon="['fas', 'star']" />
                  <fa :icon="['far', 'star']" />
                </span>
              </b-card>
            </b-col>
          </b-row>
      </b-container>
    </div>

    <!-- Mobile -->
    <div class="d-sm-block d-md-none">
      <b-container class="mobile justify-content-md-center">
          <b-row >
            <b-col>
              <h1>Good Food Us<br>Good Mood</h1>
              <img src="../assets/images/greenSaladTomato.png" class="justify-content-md-center hero-img" alt="">
              <b-card img-src="../assets/images/greensaladsmall.png" img-alt="Card image" img-left title="Green Salad Tomato" class="card-tomato" >
                <b-card-text>
                  Tomato
                </b-card-text>
                <span class="icon is-left fa-xs">
                  <fa :icon="['fas', 'star']" />
                  <fa :icon="['fas', 'star']" />
                  <fa :icon="['fas', 'star']" />
                  <fa :icon="['fas', 'star']" />
                  <fa :icon="['far', 'star']" />
                </span>
              </b-card>
            </b-col>
            <b-col>

              <p class="mt-5">I would think that conserving our natural resources should be a conservative position: Not to waste food, and not to throw away a lot of the food that we buy.</p>
              <b-navbar-nav class="d-flex flex-row nav-hero mt-4">
                <b-nav-item href="#" class="pr-4">
                    <button class="btn btn-success">Daftar Sekarang</button>
                </b-nav-item>
                <b-nav-item href="#">
                    <router-link class="nav-link" to="/">
                      <h5>About us</h5>
                    </router-link>
                </b-nav-item>
              </b-navbar-nav>
            </b-col>
          </b-row>
    </b-container>
      </div>
  </div>
</template>
