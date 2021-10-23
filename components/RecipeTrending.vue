<template>
<div>

  <!-- Dekstop -->
  <div class="d-none d-md-block">
    <b-container class="trending justify-content-md-center mt-10">
      <h2>Browse Our Trending<br><span>Recipe </span></h2>
      <b-card-group deck class="card-trending">
        <b-row>
          <b-card title="Pizza Paperoni" img-src="../assets/images/recipes/trending/pizza-paperoni.png" img-alt="Image" img-top>
            <b-card-text>
              Pizza
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
          <b-card title="Pizza Meat" img-src="../assets/images/recipes/trending/pizza-meat.png" img-alt="Image" img-top>
            <b-card-text>
              Pizza
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
          <b-card title="Doner Kebab" img-src="../assets/images/recipes/trending/kebab.png" img-alt="Image" img-top>
            <b-card-text>
              Kebab
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
            </span>
          </b-card>
          <b-card title="Salmon Roll" img-src="../assets/images/recipes/trending/salmon-roll.png" img-alt="Image" img-top>
            <b-card-text>
              Salmon
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
        </b-row>
        <b-row class="mt-5">
          <b-card title="Cupcake Choco" img-src="../assets/images/recipes/trending/cookies.png" img-alt="Image" img-top>
            <b-card-text>
              Cupcake
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
          <b-card title="Doughnut Milk" img-src="../assets/images/recipes/trending/doughnut-milk.png" img-alt="Image" img-top>
            <b-card-text>
              Doughnut
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
            </span>
          </b-card>
          <b-card title="Doughnut Unicorn" img-src="../assets/images/recipes/trending/doughnut-unicorn.png" img-alt="Image" img-top>
            <b-card-text>
              Doughnut
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
          <b-card title="Kathi Kebab" img-src="../assets/images/recipes/trending/kathi.png" img-alt="Image" img-top>
            <b-card-text>
              Kebab
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
        </b-row>
        <b-row class="trending-button mt-10 mx-auto">
          <button class="btn btn-success">All Recipes</button>
        </b-row>
      </b-card-group>
    </b-container>
  </div>

  <!-- Mobile -->
  <div class="mobile d-sm-block d-md-none">
    <b-container class="trending justify-content-md-center mt-10 mb-5">
      <h2>Browse Our Trending<br><span>Recipe </span></h2>
      <b-card-group deck class="card-trending">
        <b-row>
          <b-card title="Pizza Paperoni" img-src="../assets/images/recipes/trending/pizza-paperoni.png" img-alt="Image" img-top>
            <b-card-text>
              Pizza
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
          <b-card title="Pizza Meat" img-src="../assets/images/recipes/trending/pizza-meat.png" img-alt="Image" img-top>
            <b-card-text>
              Pizza
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
          <b-card title="Doner Kebab" img-src="../assets/images/recipes/trending/kebab.png" img-alt="Image" img-top>
            <b-card-text>
              Kebab
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
            </span>
          </b-card>
          <b-card title="Salmon Roll" img-src="../assets/images/recipes/trending/salmon-roll.png" img-alt="Image" img-top>
            <b-card-text>
              Salmon
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
        </b-row>
        <b-row class="mt-5">
          <b-card title="Cupcake Choco" img-src="../assets/images/recipes/trending/cookies.png" img-alt="Image" img-top>
            <b-card-text>
              Cupcake
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
          <b-card title="Doughnut Milk" img-src="../assets/images/recipes/trending/doughnut-milk.png" img-alt="Image" img-top>
            <b-card-text>
              Donut
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
            </span>
          </b-card>
          <b-card title="Doughnut Unicorn" img-src="../assets/images/recipes/trending/doughnut-unicorn.png" img-alt="Image" img-top>
            <b-card-text>
              Donut
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
          <b-card title="Kathi Kebab" img-src="../assets/images/recipes/trending/kathi.png" img-alt="Image" img-top>
            <b-card-text>
              Kebab
            </b-card-text>
            <span class="icon is-left fa-xs">
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['fas', 'star']" />
                <fa :icon="['far', 'star']" />
            </span>
          </b-card>
        </b-row>
      </b-card-group>
    </b-container>
  </div>
</div>

</template>
