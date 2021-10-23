<template>
  <div>
    <div class="d-none d-md-block">
      <div class="footer mt-11">
        <b-row>
          <b-col class="elemes-footer">
            <img src="../assets/images/elemes.png" alt="">
            <address>
              Jl. Prof. DR. Satrio No.7, RT.3/RW.3, Karet Kuningan,<br>
              Kecamatan Setiabudi, Kota Jakarta Selatan, <br>
              Daerah Khusus Ibukota Jakarta 12950
            </address>
            <b-col>
              <b-row class="media">
                <b-card>
                <fa :icon="['far', 'envelope']" />
                </b-card>
                <b-card>
                <fa :icon="['fas', 'phone-alt']" />
                </b-card>
                <b-card>
                <fa :icon="['fab', 'instagram']" />
                </b-card>
              </b-row>
            </b-col>

          </b-col>

          <b-col class="categories">
            <h3>Categories</h3>
            <h6>Cupcake</h6>
            <h6>Pizza</h6>
            <h6>Kebab</h6>
            <h6>Salmon</h6>
            <h6>Doughnut</h6>
          </b-col>
          <b-col class="about">
            <h3>About Us</h3>
            <h6>About Us</h6>
            <h6>FAQ</h6>
            <h6>Report Problem</h6>
          </b-col>
          <b-col class="newsletter">
            <h3>Newsletter</h3>
            <h6>Get now free 50% discount for alll products on your first order</h6>
            <b-input-group size="sm" class="mt-3">
              <b-form-input placeholder="Your email address" class="rounded-cicle"></b-form-input>
              <b-input-group-append>
                <b-button class="btn-email">SEND</b-button>
              </b-input-group-append>
            </b-input-group>
            <b-col>
              <b-row>
                <fa :icon="['far', 'envelope']" class="mt-1" />
                <h6 class="ml-1"> elemesid@gmail.com</h6>
              </b-row>
            </b-col>
            <b-col>
              <b-row>
                <fa :icon="['fas', 'phone-alt']" />
                <h6 class="ml-1">0888 1111 2222</h6>
              </b-row>
            </b-col>
          </b-col>
        </b-row>
      </div>
      <b-row class="justify-content-md-center mt-5 copyright">
        <p>© 2021 ELEMES ID. ALL RIGHTS RESERVED</p>
      </b-row>
    </div>

    <div class="d-sm-block d-md-none " >
      <b-row class="ml-auto toogle-menu fixed-bottom">
        <b-col >
          <fa :icon="['fas', 'bars']" />
          <p>Home</p>
        </b-col>

        <b-col>
          <fa :icon="['fas', 'bars']" />
          <p>Promotions</p>
        </b-col>

        <b-col>
          <fa :icon="['fas', 'bars']" />
          <p>Others</p>
        </b-col>
      </b-row>
    </div>
  </div>
</template>
