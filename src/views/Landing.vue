<template>
  <div class="landing">
    <navbar />
    <section class="nav-bg">
      <b-row>
        <ul class="nav float-left pl-4">
          <li class="nav-item">
            <a class="nav-link text-white" href="#">All</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Asset Management</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Equities</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Others</a>
          </li>
        </ul>
      </b-row>
    </section>
    <div class="container-fluid">
      <b-row class="mt-4">
        <b-col xl="3" md="6">
          <figure class="figure">
            <img
              src="./../assets/img/fixed.png"
              class="figure-img img-fluid
          rounded"
              alt="..."
            />
            <figcaption class="figure-caption text-left text-black">
              Fixed deposit
            </figcaption>
          </figure>
        </b-col>
        <b-col xl="3" md="6">
          <figure class="figure">
            <img
              src="./../assets/img/mutual.png"
              class="figure-img img-fluid rounded"
              alt="..."
            />
            <figcaption class="figure-caption text-left text-black">
              Mutual funds
            </figcaption>
          </figure>
        </b-col>
        <b-col xl="3" md="6">
          <figure class="figure">
            <img
              src="./../assets/img/equities.png"
              class="figure-img img-fluid rounded"
              alt="..."
            />
            <figcaption class="figure-caption text-left text-black">
              Equities trading
            </figcaption>
          </figure>
        </b-col>
        <b-col xl="3" md="6">
          <figure class="figure">
            <img
              src="./../assets/img/securities.png"
              class="figure-img img-fluid rounded"
              alt="..."
            />
            <figcaption class="figure-caption text-left text-black">
              Security dealings
            </figcaption>
          </figure>
        </b-col>
      </b-row>

      <b-row class="mb-4">
        <b-col xl="3" md="6">
          <figure class="figure">
            <img
              src="./../assets/img/land.png"
              class="figure-img img-fluid rounded"
              alt="..."
            />
            <figcaption class="figure-caption text-left text-black">
              Land banking
            </figcaption>
          </figure>
        </b-col>
        <b-col xl="3" md="6">
          <figure class="figure">
            <img
              src="./../assets/img/private.png"
              class="figure-img img-fluid rounded"
              alt="..."
            />
            <figcaption class="figure-caption text-left text-black">
              Private banking
            </figcaption>
          </figure>
        </b-col>
        <b-col xl="3" md="6">
          <figure class="figure">
            <img
              src="./../assets/img/placement.png"
              class="figure-img img-fluid rounded"
              alt="..."
            />
            <figcaption class="figure-caption text-left text-black">
              Placement
            </figcaption>
          </figure>
        </b-col>
        <b-col xl="3" md="6">
          <figure class="figure">
            <img
              src="./../assets/img/banking.png"
              class="figure-img img-fluid rounded"
              alt="..."
            />
            <figcaption class="figure-caption text-left text-black">
              Land banking
            </figcaption>
          </figure>
        </b-col>
      </b-row>

      <b-row class="mx-2 my-2">
        <b-col xl="12" md="12"
          ><div class="card-group">
            <div class="card orange">
              <div class="card-body px-5 py-3">
                <h2 class="card-title">Why choose us</h2>
                <p class="card-text">
                  We are a leading asset management and investment banking firm,
                  providing expert advice and a wide range of financial products
                  and services to grow wealth for our clients and to support
                  achievement of their financial goals.
                </p>
              </div>
            </div>
            <div class="card blue">
              <div
                class="card-body d-flex justify-content-center align-items-center px-5 py-3"
              >
                <h1 class="card-title display-1">52</h1>
                <div class="divider"></div>
                <h4 class="card-text text-left">
                  Years <br />
                  Combined <br />
                  Experience
                </h4>
              </div>
            </div>
            <div class="card orange">
              <div
                class="card-body d-flex justify-content-center align-items-center px-5 py-3"
              >
                <h1 class="card-title display-1">2</h1>
                <div class="divider"></div>
                <h4 class="card-text text-left">Investment <br />Products</h4>
              </div>
            </div>
          </div>
        </b-col>
      </b-row>

      <section class="my-4">
        <b-row class="ml-4 mr-2">
          <b-col xl="7" md="6" class="p-5 text-left asset-text">
            We are a leading asset management and investment banking firm,
            providing expert advice and a wide range of financial products and
            services to grow wealth for our clients and to support achievement
            of their financial goals.
          </b-col>
          <b-col xl="5" md="6">
            <div class="card">
              <img
                src="./../assets/img/headshot-bg.png"
                class="card-img-top"
                alt="..."
              />
            </div>
          </b-col>
        </b-row>
      </section>
    </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from "../components/Navbar.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "Landing",
  components: {
    Navbar,
    Footer
  }
};
</script>
<style>
.nav-bg {
  background: linear-gradient(0deg, rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("./../assets/img/bar-bg.png");
}

.orange {
  background-color: var(--color-orange);
  color: var(--color-white);
}

.blue {
  background-color: var(--color-blue);
  color: var(--color-white);
}

.divider {
  margin: 1rem 0.5rem;
  border-left: 1px solid #ffffff;
  height: 100%;
}

.asset-text {
  background: #ccc;
}
</style>
