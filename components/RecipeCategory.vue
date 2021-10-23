<template>
  <div>
    <!-- Dekstop -->
    <b-container class="justify-content-md-center mt-10 category">
      <div class="d-none d-md-block">
        <h2>Browse Our Category <br><span>Recipe </span></h2>
        <b-row>
          <b-col>
            <b-card-group deck class="category-card">
            <b-card title="Cupcake" img-src="../assets/images/recipes/category/cupcake.png" img-alt="Image" img-top>
              <b-card-text>
                22 items
              </b-card-text>
            </b-card>

            <b-card title="Pizza" img-src="../assets/images/recipes/category/pizza.png" img-alt="Image" img-top>
              <b-card-text>
                25 items
              </b-card-text>
            </b-card>

            <b-card title="Kebab" img-src="../assets/images/recipes/category/kebab.png" img-alt="Image" img-top>
              <b-card-text>
                12 items
              </b-card-text>
            </b-card>

            <b-card title="Salmon" img-src="../assets/images/recipes/category/salmon.png" img-alt="Image" img-top>
              <b-card-text>
                12 items
              </b-card-text>
            </b-card>
            <b-card title="Doughnut" img-src="../assets/images/recipes/category/doughnut.png" img-alt="Image" img-top>
              <b-card-text>
                12 items
              </b-card-text>
            </b-card>
            </b-card-group>
          </b-col>

        </b-row>
        <b-row class="card-button">
          <b-col >
            <button class="btn btn-success">
              <span>
                <fa :icon="['fas', 'arrow-left']" />
              </span>
                Prev
              </button>
            <button class="btn btn-success">
              Next
              <span>
                <fa :icon="['fas', 'arrow-right']" />
              </span>
            </button>
          </b-col>
        </b-row>
      </div>
    </b-container>

      <!-- Mobile -->
      <b-container class="mobile justify-content-md-center mt-10 category">
        <div class="d-sm-block d-md-none">
          <h2>Browse Our Category <br><span>Recipe </span></h2>
          <b-row >
            <b-col>
              <b-card-group deck class="category-card">
                <b-card title="Cupcake" img-src="../assets/images/recipes/category/cupcake.png" img-alt="Image" img-top>
                  <b-card-text>
                    22 items
                  </b-card-text>
                </b-card>

                <b-card title="Pizza" img-src="../assets/images/recipes/category/pizza.png" img-alt="Image" img-top>
                  <b-card-text>
                    25 items
                  </b-card-text>
                </b-card>

          <!-- <b-card title="Kebab" img-src="../assets/images/recipes/category/kebab.png" img-alt="Image" img-top>
                  <b-card-text>
                    12 items
                  </b-card-text>
                </b-card>

                <b-card title="Salmon" img-src="../assets/images/recipes/category/salmon.png" img-alt="Image" img-top>
                  <b-card-text>
                    12 items
                  </b-card-text>
                </b-card>
                <b-card title="Doughnut" img-src="../assets/images/recipes/category/doughnut.png" img-alt="Image" img-top>
                  <b-card-text>
                    12 items
                  </b-card-text>
                </b-card> -->
              </b-card-group>
            </b-col>

          </b-row>
        </div>
      </b-container>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
  }
</script>
