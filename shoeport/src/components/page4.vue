<template>
  <div class="row">
    <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 topnav">
          <div class="row">
            <div class="col-xs-6 col-sm-6 col-lg-6 col-md-6 menu">
              <h4>&#9776;MENU</h4>
            </div>
            <div class="col-xs-6 col-sm-6 col-lg-6 col-md-6 cart">
              <h4>CART</h4>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-6 col-sm-6 col-lg-6 col-md-6 part1">
          <div class="card1">
            <img  src="../assets/orangeshoe.jpg" height="400px" width="400px"/>
          </div>
          <div class="row">
            <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
              <div class="row">
                <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
                  <div class="cards">
                    <img  src="../assets/orangeshoe.jpg" height="50px" width="50px"/>
                  </div>
                </div>
                <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
                  <div class="cards">
                    <img  src="../assets/orangeshoe2.jpg" height="50px" width="50px"/>
                  </div>
                </div>
                <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
                  <div class="cards">
                    <img  src="../assets/orangeshoe3.jpg" height="50px" width="50px"/>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xs-6 col-sm-6 col-lg-6 col-md-6 part2">
          <div class="card2">
            <p>Tony Stark does it all,but does all, but does he have a sweet paire of his own roshe this Roshe? nm gets the iron man treatment, and man would it make tony proud</p>
            <br>
            <div class="row">
              <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
                <div class="row">
                  <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
                    <div class="btn-small">ADD</div>
                  </div>
                  <div class="col-xs-8 col-sm-8 col-lg-8 col-md-8">
                    <div class="btn-medium">+ ADD TO CART</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
              <div class="row">
                <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
                  <div class="cards2">
                    <!-- <i class="fa fa-facebook-square fb"></i> -->
                  </div>
                </div>
                <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4 tw">
                  <div class="cards2">
                    <h6>SHARE</h6>
                    <i class="fa fa-facebook-square fb"></i>
                    <i class="fa fa-twitter"></i>
                    <i class="fa fa-pinterest"></i>
                  </div>
                </div>
                <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4 pin">
                  <div class="cards2">
                    <!-- <i class="fa fa-pinterest"></i> -->
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
}
.cart h4 {
  float: right;
  margin-top: -5px;
}
.part1 {
  background-color:#fff;
}
.part2 {
  background-color: #fff;
}
.card1 {
  background-color: #fff;
  background-image: url('');
  background-repeat: no-repeat;
  text-align: center;
  height:450px;
  width:400px;
  border: #000;
  border-radius: 1em;
  border:0px solid #000;
  border-radius: .1em;
  padding-right: 5%;
  padding-top: 5%;
  padding-left: 5%;
  padding-bottom: 5%;
  float: right;
  color: #000;
  font: 1em sans-serif;
  margin-right: 10%;
  margin-left: 10%;
  margin-top: -5%;
}
.cards {
  background-color:  #fff;
  background-image: url('');
  background-repeat: no-repeat;
  text-align: center;
  height:100px;
  width:100px;
  border: #000;
  border-radius: 1em;
  border:0px solid #000;
  border-radius: .1em;
  padding-right: 5%;
  padding-top: 5%;
  padding-left: 5%;
  padding-bottom: 5%;
  float: right;
  color: #000;
  font: 1em sans-serif;
  margin-right: 10%;
  margin-left: 10%;
  margin-top: 3%;
  opacity: 0px;
  border: solid 0.2px rgb(179, 175, 175);
}
.cards:hover {
  border: solid #000;
}
.cards2 {
  background-color:  #fff;
  background-image: url('');
  background-repeat: no-repeat;
  text-align: center;
  height:150px;
  width:150px;
  border: #000;
  border-radius: 1em;
  border:0px solid #000;
  border-radius: .1em;
  padding-right: 5%;
  padding-top: 5%;
  padding-left: 5%;
  padding-bottom: 5%;
  float: right;
  color: rgb(136, 132, 132);
   font-family: 'Anton', sans-serif;
  margin-right: 10%;
  margin-left: 10%;
  margin-top: -45%;
}

.card2 {
  background-color: #fff;
  background-image: url('');
  background-repeat: no-repeat;
  text-align: center;
  height:450px;
  width:350px;
  border: #000;
  border-radius: 1em;
  border:0px solid #000;
  border-radius: .1em;
  padding-right: 5%;
  padding-top: 5%;
  padding-left: 5%;
  padding-bottom: 5%;
  float: right;
  color: rgb(204, 196, 196);
  font-size: 1em;
  font-family: 'Anton', sans-serif;
  margin-right: 10%;
  margin-left: 10%;
  margin-top: 20%;
}
.btn-medium {
  background-color:#000;
  font-size: 12px;
  font-family: 'Roboto';
  text-align :center;
  color: white;
  width:200px;
  padding:10px;
  cursor: pointer;
  text-decoration: none;
  box-shadow: 0 4px 2px 0 rgba(0.1,0.1,0.1,0.2);
}
.btn-small {
  background-color:grey;
  font-size: 12px;
  font-family: 'Roboto';
  text-align :center;
  color: white;
  width:100px;
  padding:10px;
  cursor: pointer;
  text-decoration: none;
  box-shadow: 0 4px 2px 0 rgba(0.1,0.1,0.1,0.2);
}
.fb {
  background-color: #fff;
  color:gray;
}
.tw {
  background-color: #fff;
  color:gray;
}
.pin {
  background-color: #fff;
  color:gray;
}
</style>
