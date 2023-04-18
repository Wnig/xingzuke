<template>
  	<header>
	  	<div class="pc">
		    <div class="cont">
				<a class="logo" @click="jump" ><img src="../assets/001.png" alt=""></a>
			  	<nav>
			  		<ul>
			  			<li v-for="(navs, index) in navData" v-bind:class="{'btn_sel': index == num}" @click="selMenus(index)">
			              <a :href="navs.links">{{navs.tit}}</a>
			            </li>
			            <li class="backstage">
			              <a href="#">后台登录</a>
			            </li>
			  		</ul>
			  	</nav>
		  	</div>
	  	</div>
	  	<div class="mob">
	  		<div class="cont">
	  			<div class="cont_">
					<div class="nav-btn-con">
						<div @click="isShow" class="nav-btn"></div>
					</div>	
					<a class="logo" @click="jump" ><img src="../assets/001.png" alt=""></a>
					<transition name='fade'>
						<div class="nav" v-show="selShow" @click="isShow">
							<transition name='slide'>
							  	<nav v-if="selShow">
							  		<ul>
										<li v-for="(navs, index) in nav" v-bind:class="{'btn_sel': index == num}" @click="selMenus(index)">
							              <a :href="navs.links">{{navs.tit}}</a>
							            </li>
							            <li>
							              <a href="#">后台登录</a>
							            </li>
							  		</ul>
							  		<div class="hot">
							            <p>服务电话</p>
							            <h2>400-9969-732</h2>
							        </div>
							  	</nav>
							</transition>
						</div>
					</transition>
	  			</div>
		  	</div>
	  	</div>
    </header>
</template>

<script>
let storage = window.sessionStorage;
export default {
  name: 'Header',
  data () {
    return {
    	navData: [
	        {tit: '首页', links:'/'},
	        {tit: '招商加盟', links:'#15'},
        ],
        nav: [
	        {tit: '首页', links:'/'},
	        {tit: '招商加盟', links:'#015'},
        ],
      	num: '',
      	selShow: false
    }
  },
  created: function() {
    if(storage['selNumspaik']) {
      this.num= storage['selNumspaik'];
    } else {
      this.num = 0;
    };
  },
  methods: {
    selMenus(index) {
      storage['selNumspaik'] = index;
      this.selShow = false;
    },
    isShow() {
      //点击：左侧菜单栏 收起-展开
      this.selShow = ! this.selShow;
    },
    jump() {
      storage['selNumspaik'] = 0;
      this.selShow = false;
      this.$router.push({path: '/'});
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	header {
		display: flex;
		justify-content: center;
		height: 10.36vw;
	}
	.pc {
		display: flex;
		width: 88%;
	}
	.cont {
		display: inline-flex;
		align-items: center;
		width: 100%;
	}
	.logo {
		width: 9.95vw;
		cursor: pointer;
	}
	.logo img {
		display: block;
		width: 100%;
	}
	nav {
		flex: 1;
		display: flex;
    	justify-content: flex-end;
	}
	
	nav ul {
		display: flex;
		justify-content: flex-end;
		width: 70%;
	}
	nav li {
		width: 30%;
	}
	nav li a {
		display: block;
		color: #FFFFFF;	
		line-height: 2.4vw;
		text-align: center;	
		font-size: 1.3vw;
		font-family: 'PingFangSC-Regular';
	}
	nav .btn_sel a {
		color: #FF9A20;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Medium';
	}

	nav .backstage {
		flex: 1;
		display: flex;
		justify-content: flex-end;
	}
	nav .backstage a {
		width: 8.54vw;
		height: 2.4vw;
		border-radius: 100px;
		background: #FF9A20;
	}

	@media screen and (max-width: 750px) {
		.pc {
			display: none;
		}
		.mob {
			display: flex;
			width: 85%;
		}
		header {
			height: 50.36vw;
		}
		.cont {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 100%;
		}
		.cont_ {
			width: 100%;
		}
		.logo {
			display: block;
			width: 34.67vw;
			margin: 0 auto;
		}

		.nav {
			position: fixed;
			left: 0;
			top: 0;
			width: 100%;
			height: 100vh;
			background: rgba(0, 0, 0, 0.65);
			z-index: 9999;
			opacity: 1;
		}
		.nav-btn-con {
			display: flex;
			justify-content: flex-end;
		}
		.nav-btn {
			width: 8.53vw;
			height: 3.47vw;
			background: url('../assets/001.svg') center center no-repeat;
			background-size: 100% 100%;
		}

		.fade-enter-active, .fade-leave-active {
		    transition: all .3s
		}

		.fade-enter, .fade-leave-to {
		    opacity: 0;
		}

		nav {
			width: 62.93vw;
			height: 100vh;
			background: #fff;
			transform: translate3d(0, 0, 0);
		}
		.slide-enter-active, .slide-leave-active {
		    transition: all .3s
		}

		.slide-enter, .slide-leave-to {
		    transform: translate3d(-100%, 0, 0);
		}

		nav ul {
			display: block;
			padding-top: 14.33vh;
			padding-left: 9.07vw;
			/*width: 100%;*/
		}
		nav li {
			display: block;
			width: 100%;
			margin-bottom: 13.34vh;
		}
		nav p {
	      margin-bottom: 1.05vh;
	      color: #797979;
	      font-size: 3.2vw;
	    }
	    nav h2 {
	      color: #000000;
	      line-height: 6.67vw;
	      font-size: 6.67vw;
	      font-family: 'PingFangSC-Semibold';
	    }
	    nav .hot {
	      position: absolute;
	      left: 9.2vw;
	      bottom: 7.95vh;
	    }
	    nav li a {
	    	color: #000;
	    	text-align: left;
	    	line-height: 7.33vw;
			font-size: 5.33vw;
		}
		nav .btn_sel a {
			color: #FF9A20;
			font-size: 6.67vw;
			font-family: 'PingFangSC-Medium';
		}

	}

	@media screen and (min-width: 751px) {

	}
</style>
