<template>
  <div class="login">
    <router-link to="/">
      <img
        class="login__logo"
        src="../assets/login_logo.webp"
        alt="amazon__logo"
      />
    </router-link>

    <div class="login__container">
      <h1>Sign-in</h1>

      <form>
        <h5>E-mail</h5>
        <input type="text" />

        <h5>Password</h5>
        <input type="password" />

        <button type="submit" class="login__signInButton">
          Sign In
        </button>
      </form>

      <p>
        By signing-in you agree to the AMAZON FAKE CLONE Conditions of Use &
        Sale. Please see our Privacy Notice, our Cookies Notice and our
        Interest-Based Ads Notice.
      </p>

      <button class="login__registerButton">
        Create your Amazon Account
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Login"
};
</script>

<style scoped>
.login {
  background-color: white;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.login__logo {
  margin: 20px auto;
  object-fit: contain;
  width: 100px;
}

.login__container {
  width: 300px;
  height: fit-content;
  display: flex;
  flex-direction: column;
  border-radius: 5px;
  border: 1px solid lightgray;
  padding: 20px;
}

.login__container > h1 {
  font-weight: 500;
  margin: 0 0 20px;
}

.login__container > form > h5 {
  margin: 0 0 5px;
}

.login__container > form > input {
  height: 30px;
  margin: 0 0 10px;
  background-color: white;
  width: 98%;
}

.login__container > p {
  margin: 15px 0 0;
  font-size: 12px;
}

.login__signInButton {
  background: #f0c14b;
  border-radius: 2px;
  width: 100%;
  height: 30px;
  border: 1px solid;
  margin: 10px 0 0;
  border-color: #a88734 #9c7e31 #846a29;
}

.login__registerButton {
  border-radius: 2px;
  width: 100%;
  height: 30px;
  border: 1px solid #a9a9a9;
  margin: 10px 0 0;
}
</style>
