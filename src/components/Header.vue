<template>
	<header class="header">
    <nav class="header-nav">
      <div class="toolbar-content">
        <a href="" class="logo" @click="jump">
          <img src="../assets/1.svg">
        </a>
        <a href="" class="logo_mob" @click="jump">
          <img src="../assets/01.svg">
        </a>
        <div class="sider-list" :class="{nav_left: show}" @click="isShow">
          <ul class="header-btns">
      		  <li class="header-btn icon-3" v-for="(navs, index) in navData" v-bind:class="{'header-btn-active': index == num}" @click="selMenus(index)">
      		  	<router-link :to="navs.links">{{navs.tit}}</router-link>
      		  </li>
          </ul>
          <div class="hot_tel">
            <h4>游艇预订及会员服务热线：</h4>
           <p class="hot"><i class="icon-41"></i>4008-931-898 </p>
          </div>
        </div>
        <i class="list-ico icon-66" @click="isShow"></i>
      </div>
    </nav>
  </header> 
</template>

<script>
import '../font/style.css'
let storage = window.sessionStorage;

export default {
  name: 'app-header',
  data () {
    return {
    	navData: [
    		{tit: '首页', links:'/'},
    		{tit: '服务平台', links:'/Service'},
    		{tit: '招商联盟', links:'/Join'},
    	],
    	num: '',
      show: false,
    }
  },
  created: function() {
  	if(storage['selNum']) {
		  this.num= storage['selNum'];
  	} else {
  		this.num = 0;
  	};
  },
  methods: {
  	selMenus(index) {
  		storage['selNum'] = index;
      this.selShow = false;
  	},
    isShow() {
      //点击：左侧菜单栏 收起-展开
      this.show = ! this.show;
    },
    jump() {
      storage['selNum'] = 0;
      this.selShow = false;
      this.$router.push({path: '/'});
    }
  }
}
</script>

<style scoped>
  /*头部LOGO导航*/
  .header {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
  }
  .logo, .logo_mob {
    display: block;
    padding-top: 4.81vh;
    padding-bottom: 5.83vh;
  }
  .logo img, .logo_mob img {
    width: 15.42vw;
  }
  .header-btns {
    position: absolute;
    padding: 4.81vh 0 5.93vh 0;
    right: 5vw;
    top: 0;
    bottom: 0;
    text-align: center;
  }
  .header-btns a {
  	display: block;
  	color: #fff;
  }
  .header-btns .header-btn-active a {
    color: #46B5D8;
  }
  .header-btns li:hover a {
    color: #46B5D8;
  }
  .header-nav .header-btns .header-btn {
      display: inline-block;
      float: left;
      width: 7vw;
      height: 5.26vh;
      margin-left: 6.95vw;
      color: #fff;
      line-height: 7.17vh; 
      text-align: center;     
      font-size: 1.3vw;
      cursor: pointer;
  }
  .header-nav .header-btns .header-btn-active {
      position: relative;
      color: #46B5D8;
      font-weight: 600;
  }
  
  .header-nav .header-btns .login-backstage {
    position: relative;
    display: inline-block; 
    width: 10vw;
    height: 5.26vw;
    margin: 0 0 0 15.51vw;
    padding-left: 2.95vw;
    line-height: 4.17vw;      
    color: #46B5D8;
    font-size: 1.3vw;
    cursor: pointer;
  }
  .header-nav .header-btns i {
    position: absolute;
    left: 1vw;
    top: 1.58vh;
    color: #fff;
    font-size: 2vw;
  }
  .header-nav {
    padding: 0 5.36vw;
  }
  .logo_mob {
    display: none;
  }
  .hot_tel {
    display: none;
  }
  .list-ico {
    display: none;
  }
  @media screen and (max-width: 750px) {
    .hot_tel {
      display: block;
      position: absolute;
      left: 0;
      bottom: 0;
      width: 100%;
      padding-left: 5vw;
      padding-bottom: 5.81vh;
    }
    .hot_tel h4 {
      color: #999999;
      line-height: 7vw;
      font-size: 3vw;
    }
    .hot_tel i {
      margin-right: 2vw;
    } 
    .hot_tel p {
      color: #999999;
      line-height: 7vw;
      font-size: 5.8vw;
      font-weight: 600;
    }
    
    .header {
      position: fixed;
      z-index: 9999999;
      -webkit-box-shadow: 2px 10px 10px rgba(0, 0, 0, .2);
      box-shadow: 2px 10px 10px rgba(0, 0, 0, .2);
    }
        
    .header-nav {
      background-color: #fff;
    }
    .logo {
      display: none;
    }
    .logo_mob {
      display: block;
      padding-top: 2.81vh;
      padding-bottom: 2.83vh;
    } 
    .logo_mob img {
        width: 45.42vw;
    }
    .sider-list {
      position: absolute;
      left: 0;
      right: auto;
      top: 0;
      bottom: 0;
      width: 100%;
      height: 100vh;
      background-color: rgba(0, 0, 0, 0.4);
      z-index: 1000;
      -webkit-transform: translate3d(-9999px, 0, 0);
      transform: translate3d(-9999px, 0, 0);
      transition: all .5s;
      -moz-transition: all .5s;
      -webkit-transition: all .5s; 
    }
    .nav_left {
      transform: translateX(0px);
      transition: all .3s;
      -moz-transition: all .3s;
      -webkit-transition: all .3s; 
    }
    .header-nav .header-btns .header-btn {
        display: block;
        width: 100%;
        height: 7.52vh;
        margin-left: 0;
        margin-bottom: 2vh;
        line-height: 7.52vh;
        font-size: 5.3vw;
    }
    .header-btns {
        position: absolute;
        padding: 8.81vh 5vw 5.93vh 5vw;
        right: 0vw;
        left: 0vw;
        top: 0;
        bottom: 0;
        width: 66%;
        text-align: left;
        background-color: #fff;
    }
    .header-btns .header-btn-active a {
        text-align: left;
    }
    .header-btns a {
        color: #000;
        text-align: left;
    }
    .list-ico {
      display: block;
      position: absolute;
      right: 5.36vw;
      top: 6vh;
      color: #000;
      font-size: 6vw;
    }
  
  }
  @media screen and (min-width: 751px) {
    .header-nav .header-btns .header-btn:hover {
      position: relative;
      color: #46B5D8;
      font-weight: 600;
    }
    .header-nav .header-btns .header-btn:hover:after {
      content: "\e900";
      position: absolute;
      bottom: -4.44vh;
      left: 0;
      width: 100%;
      height: 0.37vh;
      color: #46b5d8;
      font-size: 2vw;
      font-weight: 100;
    }
    .header-nav .header-btns .header-btn-active:after {
      content: "\e900";
      position: absolute;
      bottom: -4.44vh;
      left: 0;
      width: 100%;
      height: 0.37vh;
      color: #46b5d8;
      font-size: 2vw;
      font-weight: 100;
    }
  }
</style>