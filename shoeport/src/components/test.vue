<template>
  <div class="row">
    <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12">
      <div class="row">
        <div class="col-xs-12 col-sm-12 col-lg-12 col-md-12 topnav">
          <div id="main">
            <span style="font-size:20px;cursor:pointer" v-on:click="openNav()">&#9776; MENU</span>
            <div class="button">0</div>
          </div>
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
</template>
<script>
export default {
  data () {
    return {
    }
  },
  methods: {
    openNav: function () {
      document.getElementById('mySidenav').style.width = '500px'
      document.getElementById('main').style.marginLeft = '500px'
      document.body.style.backgroundColor = 'rgba(0,0,0,0.4)'
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
  font-size: 25px;
  color: #818181;
  display: block;
  transition: 0.3s;
}

.sidenav a:hover {
  color: #f1f1f1;
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
.button {
  background-color: rgba(44, 43, 44, 0.336);
  border: none;
  color: #000;
  padding: 5px;
  padding-left: 8px;
  padding-right: 8px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 15px;
  margin: 4px 2px;
  border-radius: 50%;
}
.button {
  border-radius: 50%;
}
</style>
