<template>
  <div class="row">
    <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
      <div class="body1">
        <div class="card">
          <div class="img-list">
            <div class="card1">
              <img  src="../assets/orangeshoe.jpg" height="400px" width="400px"/>
            </div>
            <div class="row">
              <div class="col-xs- col-sm-12 col-lg-12 col-md-12 footer-product">
                <a href="#" rel="p1"  class="thumbnail_img">
                  <img src="../assets/orangeshoe.jpg">
                  <span><img src="../assets/orangeshoe.jpg"></span>
                </a>
                <a href="#" rel="p1"  class="thumbnail_img">
                  <img src="../assets/orangeshoe2.jpg">
                  <span><img src="../assets/orangeshoe2.jpg"></span>
                </a>
                <a href="#" rel="p1"  class="thumbnail_img">
                  <img src="../assets/orangeshoe3.jpg">
                  <span><img src="../assets/orangeshoe3.jpg"></span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.card {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  margin-left: 150px;
  width: 80%;
  height: 550px;
}
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}
.card img{
  width: 200px;
  height: 200px;
}
.card1 {
  margin-top: -35%;
}
.thumbnail_img img{
  position: relative;
  width: 80px;
  height: 80px;
  margin-top: 150px;
  margin-bottom: 0px;
  margin-right: 0px;
  margin-left: 0px;
  padding: 10px;
  border: 1px solid transparent;
  border-color: rgb(207, 203, 203);
  opacity: 0.4;
  filter: alpha(opacity=50);
}
.thumbnail_img img:hover{
  opacity: 1;
  filter: alpha(opacity=100);
  border: 3px solid transparent;
  border-color: #000;
}
.thumbnail_img  span img{
  position: relative;
  width: 400px;
  height: 400px;
  margin-top: -300px;
  margin-bottom: 0px;
  margin-right: 150px;
  margin-left: 200px;
  border:none;
  opacity: 1.0;
  filter: alpha(opacity=100);
}
.img-list{
  padding-top: 300px;
}
.thumbnail_img:hover{
  background-color: transparent;
  z-index: 100;
}
.thumbnail_img span{
  position: absolute;
  visibility: hidden;
  color: black;
  text-decoration: none;
  -webkit-transform:scale(0.4);
  -moz-transform:scale(0.4);
  -o-transform:scale(0.9);
  -webkit-transition-duration: 0.5s;
  -moz-transition-duration: 0.5s;
  -o-transition-duration: 0.5s;
  opacity: 0.7;
}
.thumbnail_img:hover span {
  visibility: visible;
  background: transparent;
  top: 0px;
  left:5px;
  -webkit-transform:scale(1.2);
  -moz-transform:scale(1.2);
  -o-transform:scale(1.2);
  opacity: 3;
  height:auto; width:auto;
  border:0;
  margin-left: 20%;
}
.thumbnail_img {
  margin-top:2%;
}
</style>
