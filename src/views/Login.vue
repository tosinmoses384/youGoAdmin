<template>
  <div class="c-access">
    <div class="c-access-img">img here</div>
    <div class="c-access-form">
        <h1>Login</h1>
        <p>Login to continue</p>
        <sui-form>
    <sui-form-field>
      <label>First Name</label>
      <input placeholder="First Name" />
    </sui-form-field>
    <sui-form-field>
      <label>Last Name</label>
      <input placeholder="Last Name" />
    </sui-form-field>
    <sui-form-field>
      <sui-checkbox label="I agree to the Terms and Conditions" />
    </sui-form-field>
    <sui-button type="submit">Submit</sui-button>
  </sui-form>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// export default {
//   name: 'Login',
//   components: {
//     HelloWorld
//   }
// }

</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.c-access {
    width: 100%;
    display: flex;
    position: fixed;
    min-height: 100vh;
    flex-direction: row;
    }

.c-access-img {
    width: 50%;
    height: auto;
    background-color: #10193A;
    background-repeat: no-repeat;
    background-position: center;
    background-image: url('http://supervise.xnyder.com/jmb/img/login.png');
}

.c-access-form {
    width: 50%;
    height: 100%;
    display: flex;
    padding: 0 5%;
    min-height: 100vh;
    flex-direction: column;
    justify-content: center;
}

.c-access-form form {
    width: 100%;
}
</style>
