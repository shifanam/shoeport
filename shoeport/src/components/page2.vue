<template>
  <div class="row">
    <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12" id="main">
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 topnav">
          <div class="row">
            <div class="col-xs-6 col-sm-6 col-lg-6 col-md-6 menu">
              <span style="font-size:20px;cursor:pointer" v-on:click="openNav()">&#9776; MENU</span>
            </div>
            <div class="col-xs-6 col-sm-6 col-lg-6 col-md-6 cart">
              <h4>CART</h4>
            </div>
          </div>
          <div class="row">
            <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 sidenavess">
              <div id="mySidenav" class="sidenav">
                <a href="javascript:void(0)" class="closebtn" v-on:click="closeNav()">&times;</a>
                <a href="#">HOME</a>
                <a href="#">SHOP</a>
                <a href="#">ABOUT</a>
                <a href="#">CONTACT</a>
                <div>
                </div>
              </div>
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
<script>
export default {
  data () {
    return {
    }
  },
  methods: {
    openNav: function () {
      document.getElementById('mySidenav').style.width = '380px'
      document.getElementById('main').style.marginLeft = '380px'
      document.body.style.backgroundColor = 'rgba(0,0,0,0.2)'
    },
    closeNav: function () {
      document.getElementById('mySidenav').style.width = '0'
      document.getElementById('main').style.marginLeft = '0'
      document.body.style.backgroundColor = 'white'
    }
  }
}
</script>
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
  .menu span {
    float: left;
    margin-top: -16px;
  }
  .cart h4 {
    float: right;
    margin-top: -3px;
  }
  .brand h5 {
    margin-top: -90px;
    letter-spacing: 7px;
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
  .logo {
    margin-top: -40px;
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
    margin-left: 40%;
    margin-top: -6%;
  }
.sidenav {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: #111;
  overflow-x: hidden;
  transition: 0.5s;
  padding-top: 60px;
}

.sidenav a {
  padding: 8px 8px 8px 32px;
  text-decoration: none;
  font-size: 35px;
  font-family: 'Anton', sans-serif;
  color: #f1f1f1;
  display: block;
  transition: 0.3s;
  text-align: left;
}

.sidenav a:hover {
  color: #818181;
}
.sidenav a:hover:not(.active) {
  color: #818181;
}

.sidenav a.active {
  color:rgb(245, 71, 71);
}

.sidenav .closebtn {
  position: absolute;
  top: 0;
  right: 25px;
  font-size: 36px;
  margin-left: 50px;
}

#main {
  transition: margin-left .5s;
  padding: 16px;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
/* .sidenav a:active {
  color:red;
} */
</style>
