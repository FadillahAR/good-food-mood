<template>
<div>

  <!-- Dekstop -->
  <div class="d-none d-md-none d-lg-block">
    <b-container class="trending justify-content-md-center mt-10">
      <h2>Browse Our Trending<br><span>Recipe </span></h2>
      <b-card-group deck class="container card-trending">
        <b-row>
          <b-card title="Paperoni" img-src="../assets/images/recipes/trending/pizza-paperoni.png" class="pizza" img-alt="Image" img-top>
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
          <b-card title="Meat" img-src="../assets/images/recipes/trending/pizza-meat.png" img-alt="Image" class="pizza" img-top>
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
          <b-card title="Doner Kebab" img-src="../assets/images/recipes/trending/kebab.png" img-alt="Image" class="kebab" img-top>
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
          <b-card title="Salmon Roll" img-src="../assets/images/recipes/trending/salmon-roll.png" img-alt="Image" class="salmon" img-top>
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
          <b-card title="Choco" img-src="../assets/images/recipes/trending/cookies.png" img-alt="Image" class="cupcake" img-top>
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
          <b-card title="Milk" img-src="../assets/images/recipes/trending/doughnut-milk.png" img-alt="Image" class="doughnut" img-top>
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
          <b-card title="Unicorn" img-src="../assets/images/recipes/trending/doughnut-unicorn.png" img-alt="Image" class="doughnut" img-top>
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
          <b-card title="Kathi Kebab" img-src="../assets/images/recipes/trending/kathi.png" img-alt="Image" class="kebab" img-top>
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

  <!-- Tablet -->
  <div class="d-none d-md-block d-lg-none">
    <b-container class="trending justify-content-md-center mt-10">
      <h2>Browse Our Trending<br><span>Recipe </span></h2>
      <b-card-group deck class="container card-trending ">
        <b-row class="mx-auto">
          <b-card title="Paperoni" img-src="../assets/images/recipes/trending/pizza-paperoni.png" class="pizza" img-alt="Image" img-top>
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
          <b-card title="Meat" img-src="../assets/images/recipes/trending/pizza-meat.png" img-alt="Image" class="pizza" img-top>
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

        </b-row>
        <b-row class="mt-5 mx-auto">
           <b-card title="Doner Kebab" img-src="../assets/images/recipes/trending/kebab.png" img-alt="Image" class="kebab" img-top>
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
          <b-card title="Salmon Roll" img-src="../assets/images/recipes/trending/salmon-roll.png" img-alt="Image" class="salmon" img-top>
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
        <b-row class="mt-5 mx-auto">
          <b-card title="Choco" img-src="../assets/images/recipes/trending/cookies.png" img-alt="Image" class="cupcake" img-top>
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
          <b-card title="Milk" img-src="../assets/images/recipes/trending/doughnut-milk.png" img-alt="Image" class="doughnut" img-top>
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

        </b-row>
        <b-row class="mt-5 mx-auto">
           <b-card title="Unicorn" img-src="../assets/images/recipes/trending/doughnut-unicorn.png" img-alt="Image" class="doughnut" img-top>
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
          <b-card title="Kathi Kebab" img-src="../assets/images/recipes/trending/kathi.png" img-alt="Image" class="kebab" img-top>
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
  <div class="mobile d-sm-block d-md-none d-lg-none">
    <b-container class="trending justify-content-md-center mt-10 mb-5">
      <h2>Browse Our Trending<br><span>Recipe </span></h2>
      <b-card-group deck class="container card-trending">
        <b-row class="mx-auto">
          <b-card title="Paperoni" img-src="../assets/images/recipes/trending/pizza-paperoni.png" class="pizza"  img-alt="Image" img-top>
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
          <b-card title="Meat" img-src="../assets/images/recipes/trending/pizza-meat.png" img-alt="Image" class="pizza" img-top>
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
        </b-row>
        <b-row class="mt-5 mx-auto">
           <b-card title="Doner" img-src="../assets/images/recipes/trending/kebab.png" img-alt="Image" class="kebab" img-top>
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
          <b-card title="Salmon Roll" img-src="../assets/images/recipes/trending/salmon-roll.png" img-alt="Image" class="salmon" img-top>
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
        <b-row class="mx-auto">
          <b-card title="Cupcake Choco" img-src="../assets/images/recipes/trending/cookies.png" img-alt="Image" class="cupcake" img-top>
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
          <b-card title="Doughnut Milk" img-src="../assets/images/recipes/trending/doughnut-milk.png" img-alt="Image" class="doughnut" img-top>
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
        </b-row>
        <b-row class="mt-5 mx-auto">
           <b-card title="Doughnut Unicorn" img-src="../assets/images/recipes/trending/doughnut-unicorn.png" img-alt="Image" class="doughnut"  img-top>
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
          <b-card title="Kathi Kebab" img-src="../assets/images/recipes/trending/kathi.png" img-alt="Image" class="kebab" img-top>
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
