<template>
  <div class="portal">
    <div class="container-fluid">
      <div class="row">
        <nav
          id="sidebarMenu"
          class="col-md-3 col-lg-2 d-md-block bg-light sidebar collapse"
        >
          <div
            class="sidebar-sticky pt-3 d-flex flex-column justify-content-between"
          >
            <div class="client-box mt-4 mb-4">
              <img src="./../assets/img/user.png" alt="" class="client-img" />
              <h2 class="text-white">Username</h2>
              <h4 class="text-orange">ID 23J66</h4>
            </div>
            <br />
            <br />
            <br />
            <router-link to="/login" class="signout mt-4">Sign out</router-link>
          </div>
        </nav>

        <main role="main" class="col-md-9 ml-sm-auto col-lg-10 px-md-4">
          <div class="align-items-center mb-3 border-bottom portal-nav">
            <ul class="nav nav-fill">
              <li class="nav-item">
                <a class="nav-link active text-black" href="#">Investment</a>
              </li>
              <li class="nav-item">
                <a class="nav-link text-black" href="#">3 Accounts</a>
              </li>
              <li class="nav-item">
                <a class="nav-link text-black" href="#">Account Balance</a>
              </li>
              <li class="nav-item">
                <a class="nav-link text-black" href="#">Day Change</a>
              </li>
            </ul>
          </div>

          <b-row>
            <b-col>
              <div class="card">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                  <a href="#" class="card-link">Card link</a>
                  <a href="#" class="card-link">Another link</a>
                </div>
              </div>
            </b-col>
            <b-col>
              <div class="card">
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                  <a href="#" class="card-link">Card link</a>
                  <a href="#" class="card-link">Another link</a>
                </div>
              </div>
            </b-col>
          </b-row>

          <b-row class="mt-4">
            <b-col>
              <div class="card">
                <div class="card-body">
                  This is some text within a card body.
                </div>
              </div>
            </b-col>
          </b-row>
        </main>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.portal-nav {
  background: var(--color-orange);
}

.sidebar {
  background: linear-gradient(0deg, rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("./../assets/img/clientportal.png");
  height: 100vh;
}

.client-img {
  width: 189px;
  height: 189px;
  border-radius: 50%;
}

.signout {
  color: var(--color-white);
  background-color: var(--color-orange);
  padding: 3px 8px;
  border-radius: 15px;
}
</style>
