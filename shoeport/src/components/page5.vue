<template>
  <div class="row">
    <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 part1">
          <div class="card1">
            <img  src="../assets/orangeshoe.png" height="400px" width="400px"/>
            <div class="mytest" id="slideshow-carousel"></div>
          </div>
          <div class="row">
            <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
              <div class="row">
                <div id="carousel" class="jcarousel jcarousel-skin-tango">
                  <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
                    <div class="cards">
                      <img  src="../assets/orangeshoe.png" height="100px" width="100px"/>
                      <span><img src="../assets/orangeshoe.png" style="height:50px; width:50px"/></span>
                    </div>
                  </div>
                  <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
                    <div class="cards">
                      <img  src="../assets/orangeshoe2.jpg" height="100px" width="100px"/>
                      <span><img src="../assets/orangeshoe2.jpg" style="height:50px; width:50px"/></span>
                    </div>
                  </div>
                  <div class="col-xs-4 col-sm-4 col-lg-4 col-md-4">
                    <div class="cards">
                      <img  src="../assets/orangeshoe3.jpg" height="100px" width="100px"/>
                      <span><img src="../assets/orangeshoe3.jpg" style="height:50px; width:50px"/></span>
                    </div>
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
.cards {
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
  color: #000;
  font: 1em sans-serif;
  margin-right: 10%;
  margin-left: 10%;
  margin-top: 3%;
  opacity: 0px;
  border: solid 0.2px #000;
}
.cards:hover {
  border: solid #000;
  background-color: transparent;
  z-index: 100;
}
.cards span img {
  display: inline-block;
  /* margin:-13px 17px 2px -13px; */
}
.cards span {
  margin-top: -50%;
  /* padding-left: 60px; */
  margin-left: 60px;
  position: absolute;
  visibility: hidden;
  color: black;
  text-decoration: none;
  -webkit-transform:scale(0.8);
  -moz-transform:scale(0.8);
  -o-transform:scale(0.8);
  -webkit-transition-duration: 0.5s;
  -moz-transition-duration: 0.5s;
  -o-transition-duration: 0.5s;
  opacity: 0.7;
  width: 400px;
  height:400px;
}
.cards:hover span {
  visibility: visible;
  background: transparent;
  top: 5px;
  left:30px;
  -webkit-transform:scale(5);
  -moz-transform:scale(5);
  -o-transform:scale(5);
  opacity: 3;
  height:auto; width:auto;
  border:0;
}
.cards img:hover {
  -webkit-transform: scale(1.5);
  -moz-transform: scale(1.5);
  -o-transform: scale(1.5);
  -ms-transform: scale(1.5);
  transform: scale(1.5);
}
.cards {
  overflow: hidden;
}
</style>
