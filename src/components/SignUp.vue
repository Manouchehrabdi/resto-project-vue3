<template>
  <img class="logo" src="../assets/detailed-chef-logo.png" alt="Logo-Resto" />
  <h1>SignUp</h1>
  <div class="register">
    <input type="text" placeholder="Enter Name" />
    <input type="email" placeholder="Enter Email" />
    <input type="password" placeholder="Enter Password" />
    <button>Sign Up</button>
  </div>
</template>
<script>
export default {
  name: "SignUp",
};
</script>
<style>
.logo {
  width: 250px;
}
.register input {
  width: 300px;
  height: 40px;
  padding-left: 20px;
  display: block;
  margin-bottom: 20px;
  margin-right: auto;
  margin-left: auto;
  border: 1px solid purple;
  border-radius: 5px;
}
.register button {
  width: 320px;
  height: 40px;
  border: 1px solid;
  border-radius: 5px;
  background: purple;
  color: #fff;
  font-size: 15px;
  cursor: pointer;
}
</style>
