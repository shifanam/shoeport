<template>
  <div class="row">
    <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 topnav">
          <div class="row">
            <div class="col-xs-6 col-sm-6 col-lg-6 col-md-6 menu">
              <h4>&#9776; MENU</h4>
            </div>
            <div class="col-xs-6 col-sm-6 col-lg-6 col-md-6 cart">
              <h4>CART</h4>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 logo">
          <img  src="../assets/logomain.png" height="200px" width="150px"/>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 brand">
          <h5>BRAND BY</h5>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 kicks">
          <h1>KICKASSO</h1>
          <img  src="../assets/b4.png" height="600px" width="650px"/>
          <div class="btn-medium">SHOP NOW</div>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
          <!-- <div class="btn-medium">SHOP NOW</div> -->
        </div>
      </div>
    </div>
  </div>
</template>
<style>
  .topnav {
    background-color: rgba(196, 197, 199, 0.089);
    text-decoration: none;
    position:fixed;
    z-index: 40;
    width:1320px;;
    height:50px;
    margin-top: -70px;
    padding-top: 20px;
    margin-left: 0px;
    background-attachment: fixed;
    background-size: cover;
  }
  .menu h4 {
    float: left;
    margin-top: -5px;
  }
  .cart h4 {
    float: right;
    margin-top: -5px;
  }
  .brand h5 {
    margin-top: -90px;
    letter-spacing: 7px;
    font-family: 'Anton', sans-serif;
  }
  .logo {
    margin-top: -40px;
  }
  .kicks h1 {
    color: white;
    font-family: 'Anton', sans-serif;
    font-size: 200px;
    margin-top: -90px;
    padding-top: 5%;
    text-shadow: 5px 15px 15px rgba(240, 236, 236, 0.959);
  }
  .kicks img {
    margin-top: -25%;
  }
  .btn-medium {
    background-color:#000;
    font-size: 12px;
    font-family: 'Anton', sans-serif;
    text-align :center;
    color: white;
    width:200px;
    padding:10px;
    cursor: pointer;
    text-decoration: none;
    box-shadow: 0 4px 2px 0 rgba(0.1,0.1,0.1,0.2);
    margin-left: 40%;
    margin-top: -6%;
    letter-spacing: 2px
  }
</style>
