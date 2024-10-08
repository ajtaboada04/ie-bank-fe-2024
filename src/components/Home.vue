<template>
    <div class="jumbotron vertical-center">
      <div class="container">
        <div class="row">
          <div class="col-sm-12 text-center">
            <h1>Welcome to the IE Bank</h1>
            <p class="lead">The best bank in the world</p>
            <br />
            <!-- Button to navigate to the Accounts page -->
            <router-link to="/accounts" class="btn btn-primary btn-lg">
              Go to Accounts
            </router-link>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "Home",
  };
  </script>
  
  <style scoped>
  .jumbotron {
    margin-top: 50px;
    background-color: #f8f9fa;
  }
  </style>
  