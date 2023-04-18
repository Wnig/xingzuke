<template>
  <footer>
  	<div class="pc">
	  	<div class="footer">
	  		<h1>猩租客（厦门）智能科技有限公司</h1>
	  		<h3><span style="margin-right:3vw">地址：中国自贸区厦门片区华美空间C2栋4D-E</span><span>服务电话：400-9969-732 ( AM9:00-PM18:00 ）</span></h3>
	  		<p>闽ICP备18016692号</p>
	  	</div>
  	</div>
  	<div class="mob">
  		<h1>猩租客（厦门）智能科技有限公司</h1>
  		<h3><span>地址：中国自贸区厦门片区华美空间C2栋4D-E</span><br/><span>服务电话：400-9969-732 ( AM9:00-PM18:00 ）</span></h3>
  		<p>闽ICP备18016692号</p>
  	</div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	footer {
		display: flex;
		justify-content: center;
		align-items: center;
		text-align: center;
		height: 21.39vh;
		background: #454545;
	}
	h1 {
		margin-bottom: 1.02vh;
		color: #FFFFFF;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Light';
	}
	h3 {
		margin-bottom: 3.8vh;
		color: #BDBDBD;
		font-size: 0.94vw;
		font-family: 'PingFangSC-Light';
	}
	p {
		color: #848484;
		font-size: 0.63vw;
		font-family: 'PingFangSC-Light';
	}

	.mob {
		display: none;
	}

	@media screen and (max-width: 750px) {
		.mob {
	      	display: block;
	    }

		footer {
			height: 27.89vh;
		}

		h3 {
			margin-bottom: 4.35vh;
			color: #7A7A7A;
			font-size: 3.2vw;
			font-family: 'PingFangSC-Regular';
		}
		h1 {
			margin-bottom: 2.1vh;
			font-size: 4.27vw;
		}
		p {
			font-size: 3.2vw;
		}
	}

</style>
