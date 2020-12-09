<template>
  <div class="login">
    <b-container fluid>
      <div class="log-wrapper w-100">
        <div class="log-box float-md-right mt-3 mr-2 mb-3 ">
          <img
            src="../assets/alpha morgan 1.svg"
            alt=""
            class="brand-logo mt-5 mb-5"
          />
          <form action="#" class="d-flex flex-column mt-2">
            <input
              type="text"
              name="username"
              id="username"
              placeholder="Username"
              class="log-input"
            />
            <input
              type="password"
              name="password"
              id="password"
              placeholder="Password"
              class="log-input"
            />

            <p class="mt-5">
              Dont't have an account ?
              <router-link to="/register" class="text-orange"
                >Sign Up</router-link
              >
            </p>
            <button class="btn-log">Login</button>
          </form>
          <div class="login-svg mt-5">
            <svg
              width="354"
              height="199"
              viewBox="0 0 354 199"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M188.947 89.583C190.974 88.864 192.9 87.8865 194.676 86.6746L314.913 4.66144C331.507 -6.65788 354 5.22674 354 25.3144V174C354 187.807 342.807 199 329 199H25.753C-2.3333 199 -9.07521 159.828 17.395 150.439L188.947 89.583Z"
                fill="#FE630E"
              />
            </svg>
          </div>
        </div>
      </div>
    </b-container>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style>
.login {
  background-image: linear-gradient(
      0deg,
      rgba(254, 99, 14, 0.3),
      rgba(254, 99, 14, 0.3)
    ),
    url("./../assets/img/bg.jpg");
  background-size: cover;
  background-position: center top;
  height: 100vh;
}

.log-wrapper {
  /* background-image: url("../assets/bg.jpg"); */
  background-size: cover;
  background-position: center top;
}

.log-box {
  background: #fcfcfc;
  border-radius: 30px;
  /* width: 350px;
  height: 548px; */
}

.log-input {
  border-width: 0px;
  border: none;
  outline: none;
  border-bottom: 2px solid #103595;
  margin: 18px 18px 0 8px;
  color: #103595;
  background: #fcfcfc;
}

.btn-log {
  background: #000000;
  border-radius: 7px;
  color: #ffff;
  width: 108px;
  height: 25px;
  outline: none;
  border: none;
  margin: 20px auto 70px auto;
}
</style>
