<template>
  <div class="row">
    <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
      <div class="row">
        <div class="row">
          <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 topnav">
            <div class="row">
              <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4 menu">
                <h4>&#9776;MENU</h4>
              </div>
              <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4 logo">
                <!-- <img  src="../assets/logomain.png" height="100px" width="100px"/> -->
              </div>
              <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4 cart">
                <h4>CART</h4>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 body1">
          <div class="row">
            <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
              <div class="cards">
                <div class="row">
                  <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
                    <img  src="../assets/shoe9.jpg" height="150px" width="150px"/>
                    <h5>JOKER ROSHE NM</h5>
                    <h6>$245.00</h6>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
              <div class="cards">
                <div class="row">
                  <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
                    <img  src="../assets/shoe7.jpg" height="150px" width="150px"/>
                    <h5>JOKER ROSHE NM</h5>
                    <h6>$245.00</h6>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
              <div class="cards">
                <div class="row">
                  <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
                    <img  src="../assets/shoe10.jpg" height="150px" width="150px"/>
                    <h5>JOKER ROSHE NM</h5>
                    <h6>$245.00</h6>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 body1">
          <div class="row">
            <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
              <div class="cards">
                <div class="row">
                  <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
                    <img  src="../assets/shoe17.jpg" height="150px" width="150px"/>
                    <h5>JOKER ROSHE NM</h5>
                    <h6>$245.00</h6>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
              <div class="cards">
                <div class="row">
                  <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
                    <img  src="../assets/shoe18.jpg" height="150px" width="150px"/>
                    <h5>JOKER ROSHE NM</h5>
                    <h6>$245.00</h6>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
              <div class="cards">
                <div class="row">
                  <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
                    <img  src="../assets/shoe13.jpg" height="150px" width="150px"/>
                    <h5>JOKER ROSHE NM</h5>
                    <h6>$245.00</h6>
                  </div>
                </div>
              </div>
            </div>
          </div>
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
    margin-top: -60px;
    padding-top: 20px;
    margin-left: 0px;
    background-attachment: fixed;
    background-size: cover;
  }
  .menu h4 {
    float: left;
    margin-top: -5px;
    padding-left: 15px;
  }
  .cart h4 {
    float: right;
    margin-top: -5px;
  }
  .cards {
    background-color: #fff;
    background-image: url('');
    background-repeat: no-repeat;
    text-align: center;
    height:250px;
    width:300px;
    border: #000;
    border-radius: 1em;
    border:0px solid #000;
    border-radius: .1em;
    padding-right: 5%;
    padding-top: 5%;
    padding-left: 5%;
    padding-bottom: 5%;
    float: right;
    color: #fff;
    font: 1em sans-serif;
    margin-right: 10%;
    margin-left: 10%;
    margin-top: 3%;
  }

  .cards:hover {
    color:#000;
    cursor: pointer;
    box-shadow: 0 10px 20px 0 rgba(0,0,0,0.4);
  }
  .cards h5 h6 {
    margin-top: -8px;
  }
  .cards:hover h6 {
    color:red;
  }
</style>
