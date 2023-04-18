<template>
  <div class="home">
  	<div class="pc">
  		<div id="top" class="top"></div>
  		<div class="selection selection-1">
			<video class="video1" src="../assets/video_01.mp4" autoplay="autoplay" loop="loop"></video>
			<div class="con">
				<app-header></app-header>
			  	<div class="cont">
				  	<div class="cont_">
				  		<p>房屋管理利器</p>
				  		<h1>一天<strong>1</strong><span>元</span>管理费，轻松拥有您的<br/>
						专属AI智慧公寓！</h1>
						<h3>软硬件终身维保，终身免费更换！</h3>
				  		<div class="code-con">
				  			<div class="code-con_">
				  				<img class="codes" src="../assets/2.png" alt="">
					  			<p>扫描小程序码立即体验</p>
				  			</div>
				  		</div>
				  		<div class="down" @click="slideDown">
				  			<svg xmlns="http://www.w3.org/2000/svg" width="10" height="620" viewBox="0 0 10 620">
							  <g fill="none" fill-rule="evenodd">
							    <path fill="#FF9A20" d="M-27.756,519.764 C-26.796,519.764 -26.028,519.98 -25.476,520.424 C-24.9,520.88 -24.576,521.564 -24.492,522.464 L-25.464,522.464 C-25.572,521.84 -25.812,521.384 -26.184,521.084 C-26.568,520.772 -27.108,520.628 -27.804,520.628 C-28.44,520.628 -28.932,520.724 -29.292,520.94 C-29.7,521.18 -29.904,521.54 -29.904,522.032 C-29.904,522.464 -29.664,522.812 -29.172,523.076 C-28.956,523.196 -28.428,523.376 -27.6,523.616 C-26.472,523.952 -25.728,524.228 -25.368,524.444 C-24.66,524.876 -24.3,525.476 -24.3,526.256 C-24.3,527 -24.6,527.6 -25.2,528.032 C-25.8,528.452 -26.604,528.668 -27.624,528.668 C-28.632,528.668 -29.424,528.452 -30,528.02 C-30.672,527.504 -31.044,526.724 -31.116,525.668 L-30.144,525.668 C-30.06,526.412 -29.796,526.964 -29.364,527.312 C-28.968,527.624 -28.392,527.792 -27.624,527.792 C-26.928,527.792 -26.352,527.66 -25.92,527.396 C-25.488,527.132 -25.272,526.772 -25.272,526.316 C-25.272,525.776 -25.56,525.356 -26.124,525.056 C-26.364,524.912 -26.976,524.708 -27.936,524.432 C-28.968,524.12 -29.628,523.88 -29.904,523.736 C-30.564,523.352 -30.888,522.8 -30.888,522.08 C-30.888,521.336 -30.576,520.748 -29.94,520.34 C-29.376,519.956 -28.644,519.764 -27.756,519.764 Z M-21.542,519.932 L-15.47,519.932 L-15.47,520.784 L-20.558,520.784 L-20.558,523.652 L-15.758,523.652 L-15.758,524.504 L-20.558,524.504 L-20.558,527.648 L-15.266,527.648 L-15.266,528.5 L-21.542,528.5 L-21.542,519.932 Z M-12.388,519.932 L-6.31600002,519.932 L-6.31600002,520.784 L-11.404,520.784 L-11.404,523.652 L-6.60400002,523.652 L-6.60400002,524.504 L-11.404,524.504 L-11.404,527.648 L-6.11200002,527.648 L-6.11200002,528.5 L-12.388,528.5 L-12.388,519.932 Z M2.27199996,519.932 L3.49599996,519.932 L6.68799996,527.24 L6.72399996,527.24 L9.90399996,519.932 L11.128,519.932 L11.128,528.5 L10.144,528.5 L10.144,521.684 L10.108,521.684 L7.14399996,528.5 L6.25599996,528.5 L3.29199996,521.684 L3.25599996,521.684 L3.25599996,528.5 L2.27199996,528.5 L2.27199996,519.932 Z M18.11,519.764 C19.382,519.764 20.402,520.184 21.146,521.048 C21.842,521.864 22.202,522.92 22.202,524.228 C22.202,525.524 21.842,526.568 21.146,527.384 C20.402,528.236 19.382,528.668 18.098,528.668 C16.814,528.668 15.806,528.236 15.062,527.384 C14.354,526.568 14.006,525.512 14.006,524.228 C14.006,522.932 14.354,521.876 15.062,521.06 C15.806,520.196 16.814,519.764 18.11,519.764 Z M18.11,520.64 C17.126,520.64 16.346,520.976 15.782,521.66 C15.254,522.308 14.99,523.16 14.99,524.228 C14.99,525.284 15.254,526.136 15.782,526.784 C16.334,527.456 17.114,527.792 18.098,527.792 C19.082,527.792 19.862,527.456 20.414,526.808 C20.942,526.16 21.218,525.308 21.218,524.228 C21.218,523.136 20.942,522.272 20.414,521.624 C19.862,520.964 19.094,520.64 18.11,520.64 Z M25.0799999,519.932 L28.7759999,519.932 C29.6279999,519.932 30.2999999,520.124 30.7919999,520.52 C31.2959999,520.928 31.5599999,521.528 31.5599999,522.32 C31.5599999,522.8 31.4279999,523.22 31.1639999,523.592 C30.8759999,523.976 30.4919999,524.216 29.9999999,524.336 L29.9999999,524.36 C30.8159999,524.54 31.2719999,525.056 31.3679999,525.92 L31.4999999,527.24 C31.5479999,527.768 31.7039999,528.188 31.9559999,528.5 L30.8879999,528.5 C30.6959999,528.212 30.5759999,527.84 30.5399999,527.36 L30.4319999,526.22 C30.3839999,525.716 30.2039999,525.344 29.8919999,525.128 C29.6039999,524.912 29.1959999,524.816 28.6559999,524.816 L26.0639999,524.816 L26.0639999,528.5 L25.0799999,528.5 L25.0799999,519.932 Z M26.0639999,520.784 L26.0639999,523.964 L28.6559999,523.964 C29.2799999,523.964 29.7719999,523.808 30.1079999,523.52 C30.4079999,523.244 30.5639999,522.86 30.5639999,522.356 C30.5639999,521.828 30.4079999,521.432 30.1199999,521.18 C29.8079999,520.916 29.3159999,520.784 28.6559999,520.784 L26.0639999,520.784 Z M34.7019999,519.932 L40.7739999,519.932 L40.7739999,520.784 L35.6859999,520.784 L35.6859999,523.652 L40.4859999,523.652 L40.4859999,524.504 L35.6859999,524.504 L35.6859999,527.648 L40.9779999,527.648 L40.9779999,528.5 L34.7019999,528.5 L34.7019999,519.932 Z" transform="rotate(-90 4.931 524.216)"/>
							    <path class="paths" stroke="#FFF" d="M5 .983313753L5 472.216092M4 575.502481L4 612.216092"/>
							    <polygon fill="#FFF" points="4 620 0 612 8 612"/>
							  </g>
							</svg>
				  		</div>
				  	</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-2">
	        <div class="section-row">
		        <div class="section-col col-bg1">
		            <div class="card-bg">
		            </div>
		            <div class="card-content">
		              <img alt="" class="card-img" src="../assets/3.svg">
		              <p class="text1">成本／<strong>太高</strong></p>
					  <p class="text2">
						1.运营成本高<br/>
						2.人力成本高<br/>
						3.能耗成本高<br/>
						4.沟通成本高
					  </p>
		            </div>
		        </div>
	          	<div class="section-col col-bg2">
		            <div class="card-bg" style="border-color: #fff;">
		            </div>
		            <div class="card-content">
		              <img alt="" class="card-img" src="../assets/4.svg">
		              <p class="text1">效率／<strong>太低</strong></p>
					  <p class="text2">
						1.签约效率低<br/> 
						2.带看效率低<br/>
						3.获客效率低<br/>
						4.收费效率低<br/>
						5.服务效率低<br/>
						6.入住效率低
					  </p>
		            </div>
	          	</div>
	          	<div class="section-col col-bg3">
	            	<div class="card-bg">
		            </div>
		            <div class="card-content">
		              <img alt="" class="card-img" src="../assets/5.svg">
		              <p class="text1">风险／<strong>太高</strong></p>
					  <p class="text2">
						1.飞房风险高<br/>
						2.不良租客风险高<br/>
						3.偷电风险高<br/>
						4.财务管理风险高<br/>
						5.恶意欠费风险高<br/>
						6.产品安装风险高
					  </p>
		            </div>
	          	</div>
	          	<div class="section-col col-bg4">
		            <div class="card-bg" style="border-color: #fff;">
		            </div>
		            <div class="card-content">
		              <img alt="" class="card-img" src="../assets/6.svg">
		              <p class="text1">品牌竞争力/<strong>太小</strong></p>
					  <p class="text2">
						1.公寓没有产品化<br/>
						2.服务没有规范化<br/>
						3.管理手段太原始<br/>
						4.管理没有流程化<br/>
						5.智能设备和管理系统割裂<br/>
						6.增房不增效
					  </p>
		            </div>
	          	</div>
	        </div>
	        <div class="section-tit">
	        	原始公寓<strong>管理的缺陷？</strong>
	        </div>
      	</div>
      	<div class="selection selection-3">
			<div class="con">
				<div class="letf-div">
					<div class="letf-div-con">
						<h3><strong>猩租客</strong>为您解决<br/>
						公寓管理难题！</h3>
						<p>租房合同自动生成，未租房源实时展示<br/>
						逾期房租实时提醒，收支盈亏一目了然</p>
					</div>
				</div>
				<div class="right-div">
					<div class="right-div_">
						<div class="list_div">
							<div class="list_div_">
								<div class="iconfont icon-13-bg">
								</div>
								<h3>收租提醒</h3>
								<p>应收房租自动生成报表，从此告别手工统计、每天自动提醒财务自动给租客发送催租短信。</p>
							</div>					
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="iconfont icon-14-bg">
								</div>
								<h3>电子签约</h3>
								<p>直接用手机APP在线签约，无需纸质合同，方便快捷,还不用担心员工胡乱填写合同。</p>
							</div>					
						</div>	
					</div>
					<div class="right-div_">
						<div class="list_div">
							<div class="list_div_">
								<div class="iconfont icon-15-bg">
								</div>
								<h3>微信报修</h3>
								<p>租客登录您的公司公众号即可在线报修，还可拍照上传，彻底解决维修疏漏、不及时等问题。</p>
							</div>					
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="iconfont icon-16-bg">
								</div>
								<h3>微信交租</h3>
								<p>租客登录您的公司公众号在线支付房租，系统自动获取租客房间号,再不用天天核对谁转的房租。</p>
							</div>					
						</div>
					</div>
				</div>
			</div>
      	</div>
      	<div class="selection selection-4">
			<div class="con">
				<div class="con_bg"></div>
				<div class="list_div">
					<div class="list_div_">
						<h2><strong>什么是</strong>猩租客公寓综合管理系统？</h2>
						<p>猩租客公寓综合管理系统，专注解决传统公寓的痛点和难题，推出具备行业领先水平的智能物联服务平台，配套具有顶级安全水准的智能门锁和门禁等设备，提出公寓综合管理系统一站式解决方案。用户手持手机就可以完成门锁开关、水电缴费、房租交费、物业报修、订单查看、消息通知等功能。用户足不出户便可完成缴费、报修等操作。有效增强租户粘性、打造品牌形象、提高管房效率。</p>
						<div class="e-mail">
		  					<a href="mailto:smartmap@smartmapdt.com">
			  					<div class="e-mail-bg"></div>
		  						<i class="icon-10"></i>
		  					</a>
		  				</div>
					</div>
				</div>
			</div>
      	</div>
      	<div class="selection selection-10">
      		<div class="con">
      			<div class="con_">
      				<h2>猩租客公寓管理系统<strong>VS</strong>其他公寓管理系统</h2>
      				<img src="../assets/102.png" alt="">
      			</div>
      		</div>
      	</div>
      	<div class="selection selection-6">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<h2>平台<strong>优势</strong></h2>
						<p>房屋管理利器——猩租客公寓综合管理系统为公寓管理而生</p>
					</div>
					<div class="list-con">
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/30.svg" alt="">
								<h3>综合管理系统</h3>
								<p>出租-收租-退租<br/>
								管房流程自动化</p>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/31.svg" alt="">
								<h3>综智能硬件（智能门锁）</h3>
								<p>告别钥匙管理，让公寓更智慧<br/>
								让管理更智能</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-7">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<h2>平台产品<strong>功能亮点</strong></h2>
						<p>房源管理+移动审批+数据统计+财务审核</p>
					</div>
					<div class="list-con">
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/33.svg" alt="">
								<p>门锁管理</p>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/34.svg" alt="">
								<p>在线缴费</p>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/104.svg" alt="">
								<p>房屋挂租</p>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/35.svg" alt="">
								<p>订单推送</p>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/36.svg" alt="">
								<p>消息推送</p>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/37.svg" alt="">
								<p>联系物业</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
      	<div class="selection selection-5">
			<div class="con">
			  	<div class="cont">
			  		<h2>平台<strong>展示</strong></h2>
			  		<div class="pictureSlider poster-main list-con">
						<div class="poster-btn poster-prev-btn"></div>
						<ul id="zturn" class="poster-list clearfix">
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/22.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/24.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/26.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/25.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/23.png" alt="">
					  			</div>
							</li>
						</ul>
					</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-11">
			<div class="con">
				<div class="con_">
					<h2>平台<strong>功能介绍</strong></h2>
					<div class="list_con">
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_01">
									<p>1.租户管理</p>
								</div>
								<div class="list_bottom">
									<p>
										1.租户管理<br/>
										2.房间租期管理<br/>
									</p>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_02">
									<p>2.门锁管理</p>
								</div>
								<div class="list_bottom">
									<p>
										1.开关门管理<br/>
										2.门锁设置<br/>
										3.门锁锁定与解锁
									</p>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_03">
									<p>3.在线缴费</p>
								</div>
								<div class="list_bottom">
									<p>
										1.费用设置<br/>
										2.在线缴费<br/>
										3.账单管理<br/>
										4.财务管理
									</p>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_04">
									<p>4.消息管理</p>
								</div>
								<div class="list_bottom">
									<p>
										1.账单消息<br/>
										2.欠费消息<br/>
										3.平台消息<br/>
										4.物业消息
									</p>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_05">
									<p>5.联系物业</p>
								</div>
								<div class="list_bottom">
									<p>
										1.物业报修<br/>
										2.意见反馈
									</p>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-12">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<p>
							智能硬件<br/>
							<strong>优势</strong>	
						</p>
					</div>
				</div>
				<div class="list-con">
					<div class="list_con">
						1、分组供电超长备电<br/>
						2、防偷窥虚位密码<br/>
						3、防鳄鱼剪强磁开锁<br/>
						4、底板硅胶良好固位<br/>
						5、进口ST芯片<br/>
						6、电路板防水防尘防静电<br/>
						7、双轴承执手强度高<br/>
						8、产品磨损件硬度高<br/>
						9、离合器安全隔离仓设计<br/>
						10、官方认证C级锁芯
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-8">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<h2>智能硬件<strong>配套方案</strong></h2>
					</div>
					<div class="list-con">
						<div class="list_div list_bg_01">
							<p>猩租客互联网智能锁</p>
						</div>
						<div class="list_div list_bg_02">
							<p>电子水表</p>
						</div>
						<div class="list_div list_bg_03">
							<p>电子电表</p>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-13">
			<div class="con">
				<div class="tit">
					<p>
						硬件网络<br/>
						<strong>拓扑图</strong>
					</p>
				</div>
				<img src="../assets/114.svg" alt="">
			</div>
		</div>
		<div class="selection selection-14">
			<div class="con">
				<div class="con_">
					<div class="tit">猩租客<strong>背景依托</strong></div>
					<div class="list_con">
						<h4>司马图集团</h4>
						<p>
							集团致力于产业化互联网项目改造，是行业领先的一站式产业化互联网项目服务商。旗下包括：司马图（厦门）科技有限公司；司马图（厦门）信息科技有限公司；司马图（厦门）电子商务有限公司；创物云（厦门）网络科技有限公司；司马图（厦门）文化传媒有限公司；司马图（厦门）影视广告有限公司；互联网商会。拥有完整的物联网项目、聚合电商、大数据服务等自营平台。专业提供：强大的互联网技术研发、全方位的互联网运营策划、专业的品牌策划设计、个性化定制的产业升级改造方案、精准的大数据服务、庞大的互联网商会资源对接。
						</p>
						<p>
							司马图集团从2012年起深耕于产业化互联网项目，本着宏伟的战略眼光和专业的投资理念，投资建成了完整的产业生态链，包括：大数据、电商、旅游、大健康、物联网、新零售、互联网金融、新农业、文创、文化传媒、餐饮、游艇、教育、生物科技、医疗、众创空间等产业。打造了全行业化领先的产业生态系统，成为了新互联网经济体系下新兴的产业模式。已为多个政企项目及大中型企业提供了相关服务，建立了良性的合作模式。代理及合作伙伴遍布北、上、广及河南、四川、福建、浙江等中国互联网经济发达区域。
						</p>
						<p style="margin-bottom: 4.35vh;">
							司马图集团秉持科技引领创新，数据创造价值的价值理念。坚信小企业也可以有大生态。我们将一如既往与合作伙伴和谐共进，实现效益双赢。
						</p>
						<h4>尊爵物联</h4>
						<p>
							GENGET®尊爵®物联是一家专业从事智能控制应用领域研究的高科技企业，公司拥有各种专利和软件著作权等多项知识产权。产品已涵盖酒店客控系统、灯控系统、定制面板、指纹锁、智慧灯具等，未来也将根据用户需求，陆续推出各种提升生活品质的智能产品。
						</p>
						<p>
							尊爵物联研发团队由撒元功博士领衔，通过三年多的技术攻关，推出了全新的DLS®智能控制系统（完全取代传统RCU客控系统），它拥有综合布线少、全场景调光、安装简单、维护方便等特点，已广泛地应用在各种高端酒店、智能家居、高端商业等智能控制领域。
						</p>
						<p>
							尊爵物联通过云计算、物联网等技术，将尊爵物联的各种智能产品智联互通。尊爵物联陆续成立了上海、北京、厦门、成都、重庆等地区服务团队，更加快速的服务全国用户。
						</p>
					</div>	
				</div>
			</div>
		</div>
		<div class="selection selection-9">
			<div class="con">
				<div class="con_">
					<div class="pre-btn">
		          		<span>Back</span>
		          		<i class="pre"></i>
		          	</div>
		          	<div class="next-btn">
		          		<span>Next</span>
		      			<i class="next"></i>
				    </div>
					<div class="tit">
						<h2>优秀<strong>案例</strong></h2>
					</div>
					<div id="swiper" class="swiper-container clearfix">
			          	<div class="swiper-wrapper">
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/44.jpg" alt="">
			          				<p>福州凤翔国际酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/45.jpg" alt="">
			          				<p>福州宏亮花园酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/46.jpg" alt="">
			          				<p>福清创元千禧国际酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/47.jpg" alt="">
			          				<p>福州聚春园会展酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/48.jpg" alt="">
			          				<p>厦门五缘湾凯悦酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/49.jpg" alt="">
			          				<p>福州融信凯悦酒店</p>
			          			</div>
			          		</div>
			          	</div>
			        </div>
				</div>
			</div>
		</div>
		<div id="15" class="selection selection-15">
			<div class="con">
				<div class="list_con">
					<div class="list_con_">
						<img src="../assets/116.jpg" alt="">
						<p>猩租客公寓智能锁</p>
						<h2>一天<strong>1</strong>元管理费，轻松拥有您的<br/>
						专属AI智慧公寓！</h2>
						<h4>软硬件终身维保，终身免费更换！</h4>
					</div>
				</div>
				<div class="con_">
					<h2>收费<strong>标准</strong></h2>
				</div>
			</div>
		</div>
		<div class="selection selection-16">
			<div class="con">
				<div class="left">
					<h2>盈利<strong>模式</strong></h2>
					<div class="list_div">
						<p>城市合伙人获得<strong>15%</strong>的分成，城市独家代理获得<strong>30%</strong>的分成，</p>
						<p>猩租客为广大合作商创造一个持续性收益共享平台，在未来合作空间里，猩租客给代理商带来几大盈利模式。</p>
						<h4>1、年服务费收益分成：</h4> 
						<p>只要客户使用一天猩租客智慧平台，就产生一天的收益分成。</p>
						<h4>2、广告植入分成：</h4>
						<p>一把智能锁就是一台广告入户机，一台直接掌握客户真实数据的AI智能机，一把锁一天至少产生1元的广告效益。</p>
						<h4>3、服务租赁分成：</h4>
						<p>系统支持房屋挂租，不收取挂租费，平台根据租金比例获得相应租金分成。</p>
					</div>
				</div>
				<div class="right">
					<h4>4、举例：<p>假设一个城市独家代理商一年销售了<strong>5000</strong>把锁，产生的收益分析为。</p></h4>
					<img src="../assets/119.png" alt="">
				</div>
			</div>
		</div>
		<div class="selection selection-17">
			<div class="con">
				<div class="con_">
					<div class="tit">招商<strong>政策</strong></div>
					<div class="list_con">
						<div class="list_div">
							<div class="list_div_">
								<h2>1、城市合伙人</h2>
								<div class="list_div_con">
									<div class="list_div_con_">
										<h3>A、<strong>1</strong>万元平台代理费</h3>        
										<h3>B、自身有很强的销售拓展能力	</h3>
									</div>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<h2>2、城市独家代理人</h2>
								<div class="list_div_con">
									<div class="list_div_con_">
										<h4>A、城市独家平台代理费</h4>
										<p>特大城市<span>20</span>万：北京市、上海市、广州市、深圳市；</p>
										<p>一线城市<span>15</span>万：成都市、杭州市、武汉市、重庆市、南京市、天津市、苏州市、西安市、长沙市、沈阳市、青岛市、郑州市、大连市、东莞市、宁波市</p>
										<p>二线城市<span>10</span>万：厦门市、福州市、无锡市、合肥市、昆明市、哈尔滨市、济南市、佛山市、长春市、温州市、石家庄市、南宁市、常州市、泉州市、南昌市、贵阳市、太原市、烟台市、嘉兴市、南通市、金华市、珠海市、惠州市、徐州市、海口市、乌鲁木齐市、绍兴市、中山市、台州市、兰州市</p>
										<p>三四线城市<span>5</span>万：除以上所述城市以外的城市</p>
										<h4>B、 当地拥有独立公司及销售拓展团队</h4>
										<h4>C、拥有2至5人的技术服务团队</h4>
									</div>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<h2>3、OEM定制开发</h2>
								<div class="list_div_con">
									<div class="list_div_con_">
										<h3>软件开发费<strong>30</strong>万（硬件另计）</h3>
										<h3>让您可以拥有自己的公寓智慧管理平台，根据自己的经营方向做定制</h3>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-18">
			<div class="con">
				<div class="tit">
					<p>
						服务<br/>
						<strong>支持</strong>
					</p>
				</div>
				<ul class="list-con">
					<li><strong>一、产品使用培训：</strong>指派专人进行产品的现场使用培训，保障每一位客户都能正常使用。</li>
					<li><strong>二、硬件维护及更换：</strong>智能门锁等硬件设施免费维护和更换，保障管理安全。</li>
					<li><strong>三、7*24小时客户服务：</strong>客服热线全天候解决用户系统和硬件问题，解决客户紧急问题。</li>
					<li><strong>四、后期运维复盘：</strong>维护人员上门复盘部署系统运维情况，并给出优化建议。</li>
					<li><strong>五、季度健康检查：</strong>定期对部署后的系统全面检查，保障系统稳定运行。</li>
					<li><strong>六、年度系统升级：</strong>根据客户需求，对部署系统进行定期升级服务。</li>
				</ul>
			</div>
			<app-footer></app-footer>
		</div>
	</div>
	<div class="mob">
		<div id="tops" class="top"></div>
		<div class="selection selection-1">
			<img class="video1" src="../assets/video_01.gif"></img>
			<div class="con">
				<app-header></app-header>
			  	<div class="cont">
				  	<div class="cont_">
				  		<p>房屋管理利器</p>
				  		<h1>一天<strong>1元</strong>管理费，轻松拥有您的<br/>
							专属AI智慧公寓！</h1>
						<h3>软硬件终身维保，终身免费更换！</h3>
						<div class="weixin-con">
							<img class="codes" src="../assets/2.png" alt="">
					  		<p style="text-align:center">长按识别小程序码<br/>立即体验</p>
						</div>
						<div class="down" @click="slideDown">
							<svg xmlns="http://www.w3.org/2000/svg" width="8" height="45" viewBox="0 0 8 45">
							  <g fill="none" fill-rule="evenodd">
							    <path stroke="#FFF" d="M4,0.502481078 L4,37.2160924"/>
							    <polygon fill="#FFF" points="4 45 0 37 8 37"/>
							  </g>
							</svg>
						</div>
				  	</div>
			  	</div>
			</div>
		</div>	
		<div class="selection selection-2">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<h2>原始公寓<strong>管理的缺陷？</strong></h2>
					</div>
					<div id="swiper01" class="swiper-container clearfix">
			          	<div class="swiper-wrapper">
			          		<div class="swiper-slide">
			          			<div class="list_div col-bg1">
			          				<div class="list_div_">
				          				<img alt="" class="card-img" src="../assets/3.svg">
					              		<p class="text1">成本／<strong>太高</strong></p>
										<p class="text2">
										    1.运营成本高<br/>
										    2.人力成本高<br/>
										    3.能耗成本高<br/>
										    4.沟通成本高
										</p>
			          				</div>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div col-bg2">
			          				<div class="list_div_">
				          				<img alt="" class="card-img" src="../assets/4.svg">
					              		<p class="text1">效率／<strong>太低</strong></p>
									  	<p class="text2">
											1.签约效率低<br/> 
											2.带看效率低<br/>
											3.获客效率低<br/>
											4.收费效率低<br/>
											5.服务效率低<br/>
											6.入住效率低
									  	</p>
			          				</div>			          			
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div col-bg3">
			          				<div class="list_div_">
			          					<img alt="" class="card-img" src="../assets/5.svg">
				              			<p class="text1">风险／<strong>太高</strong></p>
									  	<p class="text2">
											1.飞房风险高<br/>
											2.不良租客风险高<br/>
											3.偷电风险高<br/>
											4.财务管理风险高<br/>
											5.恶意欠费风险高<br/>
											6.产品安装风险高
									  	</p>
			          				</div>			          			
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div col-bg4">
			          				<div class="list_div_">
				          				<img alt="" class="card-img" src="../assets/6.svg">
					              		<p class="text1">品牌竞争力/<strong>太小</strong></p>
									  	<p class="text2">
											1.公寓没有产品化<br/>
											2.服务没有规范化<br/>
											3.管理手段太原始<br/>
											4.管理没有流程化<br/>
											5.智能设备和管理系统割裂<br/>
											6.增房不增效
									  	</p>
			          				</div>			          			
			          			</div>
			          		</div>
			          	</div>
			          	<div class="swiper-pagination"></div>
			        </div>
				</div>
			</div>
		</div>
		<div class="selection selection-3">
			<div class="con">
				<div class="con_">
					<div class="letf-div">
						<div class="letf-div-con">
							<h3><strong>猩租客</strong>为您解决<br/>
							公寓管理难题！</h3>
							<p>租房合同自动生成，未租房源实时展示<br/>
							逾期房租实时提醒，收支盈亏一目了然</p>				
						</div>
					</div>
					<div class="right-div">
						<div class="right-div_">
							<div class="list_div">
								<div class="list_div_">
									<div class="iconfont icon-13-bg">
										<i class="path1"></i>
										<i class="path2"></i>
									</div>
									<h3>收租提醒</h3>
									<p>应收房租自动生成报表，从此告别手工统计、每天自动提醒财务自动给租客发送催租短信。</p>
								</div>					
							</div>
							<div class="list_div">
								<div class="list_div_">
									<div class="iconfont icon-14-bg">
										<i class="path1"></i>
										<i class="path2"></i>
										<i class="path3"></i>
									</div>
									<h3>电子签约</h3>
									<p>直接用手机APP在线签约，无需纸质合同，方便快捷,还不用担心员工胡乱填写合同。</p>
								</div>					
							</div>	
						</div>
						<div class="right-div_">
							<div class="list_div">
								<div class="list_div_">
									<div class="iconfont icon-15-bg">
									</div>
									<h3>微信报修</h3>
									<p>租客登录您的公司公众号即可在线报修，还可拍照上传，彻底解决维修疏漏、不及时等问题。</p>
								</div>					
							</div>
							<div class="list_div">
								<div class="list_div_">
									<div class="iconfont icon-16-bg">
									</div>
									<h3>微信交租</h3>
									<p>租客登录您的公司公众号在线支付房租，系统自动获取租客房间号,再不用天天核对谁转的房租。</p>
								</div>					
							</div>
						</div>
					</div>
				</div>
			</div>
      	</div>
      	<div class="selection selection-4">
			<div class="con">
				<div class="con_bg"></div>
				<div class="list_div">
					<div class="list_div_">
						<h2><strong>什么是</strong><br/>猩租客公寓综合管理系统？</h2>
						<p>猩租客公寓综合管理系统，专注解决传统公寓的痛点和难题，推出具备行业领先水平的智能物联服务平台，配套具有顶级安全水准的智能门锁和门禁等设备，提出公寓综合管理系统一站式解决方案。用户手持手机就可以完成门锁开关、水电缴费、房租交费、物业报修、订单查看、消息通知等功能。用户足不出户便可完成缴费、报修等操作。有效增强租户粘性、打造品牌形象、提高管房效率。</p>
						<div class="e-mail">
		  					<a href="mailto:smartmap@smartmapdt.com">
			  					<div class="e-mail-bg"></div>
		  						<i class="icon-10"></i>
		  					</a>
		  				</div>
					</div>
				</div>
			</div>
      	</div>
      	<div class="selection selection-10">
      		<div class="con">
      			<div class="con_">
      				<h2>猩租客公寓管理系统<br/><strong>VS</strong><br/>其他公寓管理系统</h2>
      				<img src="../assets/207.png" alt="">
      			</div>
      		</div>
      	</div>
      	<div class="selection selection-6">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<h2>平台<strong>优势</strong></h2>
						<p>房屋管理利器<br/>
						   ——<br/>
						   猩租客公寓综合管理系统为公寓管理而生</p>
					</div>
					<div class="list-con">
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/30.svg" alt="">
								<h3>综合管理系统</h3>
								<p>出租-收租-退租<br/>
								管房流程自动化</p>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<img src="../assets/31.svg" alt="">
								<h3>综智能硬件</h3>
								<p>告别钥匙管理，让公寓<br/>
								更智慧，让管理更智能</p>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-7">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<h2>平台产品<strong>功能亮点</strong></h2>
						<p>房源管理+移动审批+数据统计+财务审核</p>
					</div>
					<div id="swiper02" class="swiper-container clearfix">
			          	<div class="swiper-wrapper">
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<div class="list_div_">
			          					<img src="../assets/33.svg" alt="">
										<p>门锁管理</p>
			          				</div>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<div class="list_div_">
				          				<img src="../assets/34.svg" alt="">
										<p>在线缴费</p>
			          				</div>			          			
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
				          		<div class="list_div">
									<div class="list_div_">
										<img src="../assets/104.svg" alt="">
										<p>房屋挂租</p>
									</div>
								</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<div class="list_div_">
			          					<img src="../assets/35.svg" alt="">
										<p>订单推送</p>
			          				</div>			          			
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<div class="list_div_">
				          				<img src="../assets/36.svg" alt="">
										<p>消息推送</p>
			          				</div>			          			
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<div class="list_div_">
				          				<img src="../assets/37.svg" alt="">
										<p>联系物业</p>
			          				</div>			          			
			          			</div>
			          		</div>
			          	</div>
			          	<div class="swiper-pagination"></div>
			        </div>
				</div>
			</div>
		</div>
      	<div class="selection selection-5">
			<div class="con">
			  	<div class="cont">
			  		<h2>平台<strong>展示</strong></h2>
			  		<div class="pictureSlider poster-main list-con">
						<div class="poster-btn poster-prev-btn"></div>
						<ul id="zturn02" class="poster-list clearfix">
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/22.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/24.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/26.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/25.png" alt="">
					  			</div>
							</li>
							<li class="poster-item  zturn-item">
					  			<div class="list_div">
					  				<img src="../assets/23.png" alt="">
					  			</div>
							</li>
						</ul>
					</div>
			  	</div>
			</div>
		</div>
		<div class="selection selection-11">
			<div class="con">
				<div class="con_">
					<h2>平台<strong>功能介绍</strong></h2>
					<div id="swiper05" class="swiper-container clearfix">
			          	<div class="swiper-wrapper">
			          		<div class="swiper-slide">
			          			<div class="list_div">
									<div class="list_div_">
										<div class="list_bg list_bg_01">
											<p>1.租户管理</p>
										</div>
										<div class="list_bottom">
											<p>
												1.租户管理<br/>
												2.房间租期管理<br/>
											</p>
										</div>
									</div>
								</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
									<div class="list_div_">
										<div class="list_bg list_bg_02">
											<p>2.门锁管理</p>
										</div>
										<div class="list_bottom">
											<p>
												1.开关门管理<br/>
												2.门锁设置<br/>
												3.门锁锁定与解锁
											</p>
										</div>
									</div>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
								<div class="list_div">
									<div class="list_div_">
										<div class="list_bg list_bg_03">
											<p>3.在线缴费</p>
										</div>
										<div class="list_bottom">
											<p>
												1.费用设置<br/>
												2.在线缴费<br/>
												3.账单管理<br/>
												4.财务管理
											</p>
										</div>
									</div>
								</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
									<div class="list_div_">
										<div class="list_bg list_bg_04">
											<p>4.消息管理</p>
										</div>
										<div class="list_bottom">
											<p>
												1.账单消息<br/>
												2.欠费消息<br/>
												3.平台消息<br/>
												4.物业消息
											</p>
										</div>
									</div>
								</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
									<div class="list_div_">
										<div class="list_bg list_bg_05">
											<p>5.联系物业</p>
										</div>
										<div class="list_bottom">
											<p>
												1.物业报修<br/>
												2.意见反馈
											</p>
										</div>
									</div>
								</div>
			          		</div>
			          	</div>
			          	<div class="swiper-pagination"></div>
			        </div>
					<!-- <div class="list_con">
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_01">
									<p>1.租户管理</p>
								</div>
								<div class="list_bottom">
									<p>
										1.租户管理<br/>
										2.房间租期管理<br/>
									</p>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_02">
									<p>2.门锁管理</p>
								</div>
								<div class="list_bottom">
									<p>
										1.开关门管理<br/>
										2.门锁设置<br/>
										3.门锁锁定与解锁
									</p>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_03">
									<p>3.在线缴费</p>
								</div>
								<div class="list_bottom">
									<p>
										1.费用设置<br/>
										2.在线缴费<br/>
										3.账单管理<br/>
										4.财务管理
									</p>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_04">
									<p>4.消息管理</p>
								</div>
								<div class="list_bottom">
									<p>
										1.账单消息<br/>
										2.欠费消息<br/>
										3.平台消息<br/>
										4.物业消息
									</p>
								</div>
							</div>
						</div>
						<div class="list_div">
							<div class="list_div_">
								<div class="list_bg list_bg_05">
									<p>5.联系物业</p>
								</div>
								<div class="list_bottom">
									<p>
										1.物业报修<br/>
										2.意见反馈
									</p>
								</div>
							</div>
						</div>
					</div> -->
				</div>
			</div>
		</div>
		<div class="selection selection-12">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<p>
							智能硬件<br/>
							<strong>优势</strong>	
						</p>
					</div>
					<div class="list-con">
						<div class="list_con">
							1、分组供电超长备电<br/>
							2、防偷窥虚位密码<br/>
							3、防鳄鱼剪强磁开锁<br/>
							4、底板硅胶良好固位<br/>
							5、进口ST芯片<br/>
							6、电路板防水防尘防静电<br/>
							7、双轴承执手强度高<br/>
							8、产品磨损件硬度高<br/>
							9、离合器安全隔离仓设计<br/>
							10、官方认证C级锁芯
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-8">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<h2>智能硬件<strong>配套方案</strong></h2>
					</div>
					<div id="swiper03" class="swiper-container clearfix">
			          	<div class="swiper-wrapper">
			          		<div class="swiper-slide">
			          			<div class="list_div list_bg_01">
									<p>猩租客互联网智能锁</p>
								</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div list_bg_02">
									<p>电子水表</p>
								</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div list_bg_03">
									<p>电子电表</p>
								</div>
			          		</div>
			          	</div>
			          	<div class="swiper-pagination"></div>
			        </div>
				</div>
			</div>
		</div>
		<div class="selection selection-13">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<p>
							硬件网络<br/>
							<strong>拓扑图</strong>
						</p>
					</div>
					<img src="../assets/300.svg" alt="">
				</div>
			</div>
		</div>
		<div class="selection selection-14">
			<div class="con">
				<div class="con_">
					<div class="tit">猩租客<strong>背景依托</strong></div>
					<div class="list_con">
						<h4>司马图集团</h4>
						<p>
							集团致力于产业化互联网项目改造，是行业领先的一站式产业化互联网项目服务商。旗下包括：司马图（厦门）科技有限公司；司马图（厦门）信息科技有限公司；司马图（厦门）电子商务有限公司；创物云（厦门）网络科技有限公司；司马图（厦门）文化传媒有限公司；司马图（厦门）影视广告有限公司；互联网商会。拥有完整的物联网项目、聚合电商、大数据服务等自营平台。专业提供：强大的互联网技术研发、全方位的互联网运营策划、专业的品牌策划设计、个性化定制的产业升级改造方案、精准的大数据服务、庞大的互联网商会资源对接。
						</p>
						<p>
							司马图集团从2012年起深耕于产业化互联网项目，本着宏伟的战略眼光和专业的投资理念，投资建成了完整的产业生态链，包括：大数据、电商、旅游、大健康、物联网、新零售、互联网金融、新农业、文创、文化传媒、餐饮、游艇、教育、生物科技、医疗、众创空间等产业。打造了全行业化领先的产业生态系统，成为了新互联网经济体系下新兴的产业模式。已为多个政企项目及大中型企业提供了相关服务，建立了良性的合作模式。代理及合作伙伴遍布北、上、广及河南、四川、福建、浙江等中国互联网经济发达区域。
						</p>
						<p style="margin-bottom: 5.7vh;">
							司马图集团秉持科技引领创新，数据创造价值的价值理念。坚信小企业也可以有大生态。我们将一如既往与合作伙伴和谐共进，实现效益双赢。
						</p>
						<h4>尊爵物联</h4>
						<p>
							GENGET®尊爵®物联是一家专业从事智能控制应用领域研究的高科技企业，公司拥有各种专利和软件著作权等多项知识产权。产品已涵盖酒店客控系统、灯控系统、定制面板、指纹锁、智慧灯具等，未来也将根据用户需求，陆续推出各种提升生活品质的智能产品。
						</p>
						<p>
							尊爵物联研发团队由撒元功博士领衔，通过三年多的技术攻关，推出了全新的DLS®智能控制系统（完全取代传统RCU客控系统），它拥有综合布线少、全场景调光、安装简单、维护方便等特点，已广泛地应用在各种高端酒店、智能家居、高端商业等智能控制领域。
						</p>
						<p>
							尊爵物联通过云计算、物联网等技术，将尊爵物联的各种智能产品智联互通。尊爵物联陆续成立了上海、北京、厦门、成都、重庆等地区服务团队，更加快速的服务全国用户。
						</p>
					</div>	
				</div>
			</div>
		</div>
		<div class="selection selection-9">
			<div class="con">
				<div class="con_">
					<div id="pre_02" class="pre-btn">
		          		<i class="pre"></i>
		          		<span>Back</span>
		          	</div>
		          	<div id="next_02" class="next-btn">
		          		<span>Next</span>
		      			<i class="next"></i>
				    </div>
					<div class="tit">
						<h2>优秀<strong>案例</strong></h2>
					</div>
					<div id="swiper04" class="swiper-container clearfix">
			          	<div class="swiper-wrapper">
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/44.jpg" alt="">
			          				<p>福州凤翔国际酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/45.jpg" alt="">
			          				<p>福州宏亮花园酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/46.jpg" alt="">
			          				<p>福清创元千禧国际酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/47.jpg" alt="">
			          				<p>福州聚春园会展酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/48.jpg" alt="">
			          				<p>厦门五缘湾凯悦酒店</p>
			          			</div>
			          		</div>
			          		<div class="swiper-slide">
			          			<div class="list_div">
			          				<img src="../assets/49.jpg" alt="">
			          				<p>福州融信凯悦酒店</p>
			          			</div>
			          		</div>
			          	</div>
			        </div>
				</div>
			</div>
		</div>
		<div id="015" class="selection selection-15">
			<div class="con">
				<div class="con_">
					<h2>收费<strong>标准</strong></h2>
					<div class="list_con">
						<div class="list_con_">
							<img src="../assets/116.jpg" alt="">
							<p>猩租客公寓智能锁</p>
							<h2>一天<strong>1</strong>元管理费，轻松拥有<br/>您的专属AI智慧公寓！</h2>
							<h4>软硬件终身维保，终身免费更换！</h4>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-16">
			<div class="con">
				<div class="con_">
					<div class="left">
						<h2>盈利<strong>模式</strong></h2>
						<div class="list_div">
							<p>城市合伙人获得<strong>15%</strong>的分成，城市独家代理获得<strong>30%</strong>的分成猩租客为广大合作商创造一个持续性收益共享平台，在未来合作空间里，猩租客给代理商带来几大盈利模式</p>
							<h4>1、年服务费收益分成：</h4> 
							<p>只要客户使用一天猩租客智慧平台，就产生一天的收益分成。</p>
							<h4>2、广告植入分成：</h4>
							<p>一把智能锁就是一台广告入户机，一台直接掌握客户真实数据的AI智能机，一把锁一天至少产生1元的广告效益。</p>
							<h4>3、服务租赁分成：</h4>
							<p>系统支持房屋挂租，不收取挂租费，平台根据租金比例获得相应租金分成。</p>
							<h4>4、举例：<p>假设一个城市独家代理商一年销售了<strong>5000</strong>把锁，产生的收益分析为。</p></h4>
						</div>
					</div>
					<div class="right">
						<img src="../assets/220.png" alt="">
					</div>
				</div>
			</div>
		</div>
		<div class="selection selection-17">
			<div class="con">
				<div class="con_">
					<div class="tit">招商<strong>政策</strong></div>
					<div id="swiper06" class="swiper-container clearfix">
			          	<div class="swiper-wrapper">
			          		<div class="swiper-slide">
								<div class="list_div">
									<div class="list_div_">
										<h2>1、城市合伙人</h2>
										<div class="list_div_con">
											<div class="list_div_con_">
												<h3>A、<strong>1</strong>万元平台代理费</h3>        
												<h3>B、自身有很强的销售拓展能力	</h3>
											</div>
										</div>
									</div>
								</div>
			          		</div>
			          		<div class="swiper-slide">
								<div class="list_div">
									<div class="list_div_">
										<h2>2、城市独家代理人</h2>
										<div class="list_div_con">
											<div class="list_div_con_">
												<h4>A、城市独家平台代理费</h4>
												<p>特大城市<span>20</span>万：北京市、上海市、广州市、深圳市；</p>
												<p>一线城市<span>15</span>万：成都市、杭州市、武汉市、重庆市、南京市、天津市、苏州市、西安市、长沙市、沈阳市、青岛市、郑州市、大连市、东莞市、宁波市</p>
												<p>二线城市<span>10</span>万：厦门市、福州市、无锡市、合肥市、昆明市、哈尔滨市、济南市、佛山市、长春市、温州市、石家庄市、南宁市、常州市、泉州市、南昌市、贵阳市、太原市、烟台市、嘉兴市、南通市、金华市、珠海市、惠州市、徐州市、海口市、乌鲁木齐市、绍兴市、中山市、台州市、兰州市</p>
												<p>三四线城市<span>5</span>万：除以上所述城市以外的城市</p>
												<h4>B、 当地拥有独立公司及销售拓展团队</h4>
												<h4>C、拥有2至5人的技术服务团队</h4>
											</div>
										</div>
									</div>
								</div>
			          		</div>
			          		<div class="swiper-slide">
								<div class="list_div">
									<div class="list_div_">
										<h2>3、OEM定制开发</h2>
										<div class="list_div_con">
											<div class="list_div_con_">
												<h3>软件开发费<strong>30</strong>万（硬件另计）</h3>
												<h3>让您可以拥有自己的公寓智慧管理平台，根据自己的经营方向做定制</h3>
											</div>
										</div>
									</div>
								</div>
			          		</div>
			          	</div>
			          	<div class="swiper-pagination"></div>
			        </div>
				</div>
			</div>
		</div>
		<div class="selection selection-18">
			<div class="con">
				<div class="con_">
					<div class="tit">
						<p>
							服务<br/>
							<strong>支持</strong>
						</p>
					</div>
					<ul class="list-con">
						<li><strong>一、产品使用培训：</strong>指派专人进行产品的现场使用培训，保障每一位客户都能正常使用。</li>
						<li><strong>二、硬件维护及更换：</strong>智能门锁等硬件设施免费维护和更换，保障管理安全。</li>
						<li><strong>三、7*24小时客户服务：</strong>客服热线全天候解决用户系统和硬件问题，解决客户紧急问题。</li>
						<li><strong>四、后期运维复盘：</strong>维护人员上门复盘部署系统运维情况，并给出优化建议。</li>
						<li><strong>五、季度健康检查：</strong>定期对部署后的系统全面检查，保障系统稳定运行。</li>
						<li><strong>六、年度系统升级：</strong>根据客户需求，对部署系统进行定期升级服务。</li>
					</ul>
				</div>
			</div>
			<app-footer></app-footer>
		</div>
	</div>
  </div>
</template>

<script>
import Header from './Header'
import Footer from './Footer'

import '../../static/js/zturn.js'

export default {
  name: 'Home',
  data () {
    return {

    }
  },
  created() {

  },
  methods: {
  	slideDown() {
      let downHeight = document.documentElement.clientHeight || document.body.clientHeight;
      window.scrollTo(0, downHeight);
      this.slideShow = true;
	}
  },
  components: {
    'app-header': Header,
    'app-footer': Footer
  },
  mounted() {
  	var _hmt = _hmt || [];
	(function() {
	  var hm = document.createElement("script");
	  hm.src = "https://hm.baidu.com/hm.js?abce954e370fc0041bf56408409f5ebd";
	  var s = document.getElementsByTagName("script")[0]; 
	  s.parentNode.insertBefore(hm, s);
	})();

  	$('#top, #tops').on('click', function() {
    	$('html, body').animate({scrollTop: '0px'}, 800);
    });

    $(window).scroll(function() {
	　　 var scrollTop = $(this).scrollTop();
	　　 var scrollHeight = $(document).height();
	　　 var windowHeight = $(this).height();

		if(scrollTop < scrollHeight / 9) {
			$('#top, #tops').css({
				'display': 'none'
			});
		} else {
			$('#top, #tops').css({
				'display': 'block'
			});
		}
	});

  	// 图片轮播
	let zTurn = new zturn({
		id: "zturn",
		opacity: 1,
		width: 18.73,
		Awidth: 51,
		scale: 0.9
	});

	let timer = setInterval(function(){
	    zTurn.next_();
	},2000);

	$('.list-con').hover(function() {
		clearTimeout(timer);
	}, function() {
		timer = setInterval(function(){
		    zTurn.next_();
		},5000);
	});

	let zTurn2 = new zturn({
		id: "zturn02",
		opacity: 1,
		width: 45.33,
		Awidth: 65,
		scale: 0.9
	});

	let timer2 = setInterval(function(){
	    zTurn2.next_();
	},2000);

	$('.list-con').hover(function() {
		clearTimeout(timer2);
	}, function() {
		timer2 = setInterval(function(){
		    zTurn2.next_();
		},5000);
	});


	let swiper = new Swiper('#swiper', {
	  autoplay: 1000,
	  loop: 1,
      slidesPerView: 6,
      spaceBetween: 45,
      speed: 500,
      mousewheelControl: true,
      releaseOnEdges: true,
      paginationClickable: true,
      prevButton: '.pre-btn',
      nextButton: '.next-btn',
    });

    let swiper04 = new Swiper('#swiper04', {
	  autoplay: 1000,
	  loop: 1,
      slidesPerView: 2.02,
      spaceBetween: 45,
      speed: 500,
      mousewheelControl: true,
      releaseOnEdges: true,
      paginationClickable: true,
      prevButton: '#pre_02',
      nextButton: '#next_02',
    });

    let swiper01 = new Swiper('#swiper01, #swiper02, #swiper03, #swiper05, #swiper06', {
	  autoplay: 1000,
	  loop: 1,
      slidesPerView: 1,
      spaceBetween: 45,
      speed: 1000,
      mousewheelControl: true,
      releaseOnEdges: true,
      paginationClickable: true, 
      pagination: '.swiper-pagination',   
  	});
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
	#top {
		display: none;
		position: fixed;
		right: 1.93vw;
		bottom: 15.38vw;
		width: 2.92vw;
		height: 2.92vw;
		background: url('../assets/7.svg') center center no-repeat;
		background-size: 100% 100%;
		z-index: 99999;
		cursor: pointer;
	}

	.video1 {
	    position: relative;
	    left: 0;
	    top: 0;
	    z-index: -1;
	    width: 100%;
	    height: 100%;
	    -o-object-fit: fill;
	    object-fit: fill;
	}
	/*selection-1*/
	.selection-1 .con {
		position: absolute;
		left: 0;
		top: 0;
		width: 100%;
		height: 100vh;
		background: rgba(0, 0, 0, 0.6);
	}
	.selection-1 .cont_ {
		position: relative;
	}
	.selection-1 h1 {
		margin-bottom: 4.07vh;
		color: #FFFFFF;
		text-align: center;
		line-height: 4.39vw;
		font-size: 3.2vw;
		font-family: 'PingFangSC-Regular';
		font-weight: 600;
	}
	.selection-1 h1 strong {
		display: inline-block;
		color: #FF973F;
		line-height: 4.53vw;
		font-size: 5.21vw;
		font-family: 'PingFangSC-Regular';
	}
	.selection-1 h1 span {
		display: inline-block;
		color: #FF973F;
		line-height: 4.53vw;
		font-size: 3.91vw;
		font-family: 'PingFangSC-Regular';
	}
	.selection-1 h3 {
		color: #BDBDBD;	
		font-family: 'PingFangSC-Light';
		font-size: 2.34vw;
	}
	
	.selection-1 p {
		margin-bottom: 3.46vh;
		color: #FFFFFF;
		text-align: center;
		line-height: 2.34vw; 
		font-size: 1.3vw;
		font-family: 'PingFangSC-Thin';
	}
	.selection-1 p span {
		display: inline-block;
		width: 2vw;
	}
	.selection-1 .code-con {
		display: flex;
		justify-content: flex-end;
		width: 88vw;
		margin-top: 6.57vh;
	}
	.selection-1 .code-con_ {
	}
	.selection-1 .code-con p {
		color: #FFFFFF;
		text-align: center;
		font-size: 1.04vw;
		font-family: 'PingFangSC-Light';
	}

	.selection-1 .codes {
		width: 10.26vw;
		margin: 0 auto 1.85vh;
	}
	
	.selection-1 .cont {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 80%;
		color: #FFFFFF;
		text-align: center;
		line-height: 2.34vw;
		font-size: 1.3vw;
	}
	.selection-1 .down {
		position: absolute;
		left: 0;
		top: 0;
		width: 10vw;
		height: 31.87vw;
	}
	.selection-1 .down svg {
		height: 100%;
		cursor: pointer;
	}


	/*selection-2*/
	.selection-2 {

	}
	  .selection-2 .discr-con {
	    position: relative;
	    padding-left: 12.97vw;
	    background: #FFFFFF;
	  }
	  .selection-2 .discr-con:after {
	    content: "";
	    position: absolute;
	    bottom: 0;
	    left: 0;
	    width: 100%;
	    height: 2.22vh;
	    box-shadow: 0px 16px 24px 0px rgba(0, 0, 0, 0.14);
	    z-index: 100;
	  }
	  
	  .selection-2 .discr-con .tit {
	    padding-top: 7.04vh;
	    text-align: left;
	    color: #161519;
	    font-size: 1.82vw;
	  }
	  .selection-2 .discr-con .tit:after {
	    content: "\e900";
	    color: #46b5d8;
	  }
	  .selection-2 .discr-con .discr {
	    padding-top: 6.48vh;
	    padding-bottom: 7.65vh;
	    text-align: left;
	    color: #161519;
	    font-size: 1.3vw;
	  }
	  .selection-2 .discr-con .discr strong {
	    font-weight: 700;
	  }
	  img {
	    max-width: 100%;
	  }
	  .selection-2 .section-row {
	    display: -webkit-box;
	    display: -webkit-flex;
	    display: -ms-flexbox;
	    display: flex;
	    -webkit-box-align: center;
	    -webkit-align-items: center;
	    -ms-flex-align: center;
	    align-items: center;
	    -webkit-box-pack: center;
	    -webkit-justify-content: center;
	    -ms-flex-pack: center;
	    justify-content: center;
	    height: 100%;
	  }
	  .selection-2 .section-row .col-bg1 {
	    background: url('../assets/8.jpg') center no-repeat padding-box;
	    background-size: cover;
	  }
	  .selection-2 .section-row .col-bg2 {
	    background: url('../assets/9.jpg') center no-repeat padding-box;
	    background-size: cover;
	  }
	  .selection-2 .section-row .col-bg3 {
	    background: url('../assets/10.jpg') center no-repeat padding-box;
	    background-size: cover;
	  }
	  .selection-2 .section-row .col-bg4 {
	    background: url('../assets/11.jpg') center no-repeat padding-box;
	    background-size: cover;
	  }
	  .selection-2 .section-row .section-col {
	    -webkit-box-flex: 1;
	    -webkit-flex: 1;
	    -ms-flex: 1;
	    flex: 1;
	    height: 100%;
	    position: relative;
	    overflow: hidden;
	    cursor: pointer;
	  }
	  .selection-2 .section-row .card-bg {
	    position: absolute;
	    width: 8vw;
	    height: 8vw;
	    border-radius: 100%;
	    overflow: hidden;
	    top: -84vw;
	    left: -91.6vw;
	    margin: auto;
	    border: 100vw solid #f5f5f5;
	    -webkit-box-sizing: content-box;
	    box-sizing: content-box;
	    background-size: cover;
	    background-origin: border-box;
	  }
	  .selection-2 .section-row .section-col:hover .card-bg {
	    -webkit-transform: scale(30);
	    transform: scale(30);
	    -webkit-transition: all .6s;
	    transition: all .6s;
	  }
	  .selection-2 .section-row .card-content {
	    position: absolute;
	    z-index: 100;
	    width: 80%;
	    height: 100%;
	    top: 18.2vw;
	    left: 0;
	    right: 0;
	    margin: 0 auto;
	    -webkit-transition: all .6s;
	    transition: all .6s;
	  }
	  .selection-2 .section-row .card-content:hover  {
	    margin-top: -10vh;
	    -webkit-transition: all .6s;
	    transition: all .6s;
	  }
	  .selection-2 .section-row .section-col .card-content {
	    -webkit-transition: all .6s;
	    transition: all .6s;
	  }
	  .selection-2 .section-row .card-content .card-img {
	  	display: block;
	    width: 4vw;
	    margin: 0 auto;
	  }
	  .selection-2 .section-row .card-content .title {
	    padding-top: 5.09vh;
	    color: #46b5d8;
	    font-size: 1.3vw;
	    font-weight: 600;
	    -webkit-transition: all .6s;
	    transition: all .6s;
	  }
	  .selection-2 .section-row .section-col * {
	    -webkit-transition: all .6s;
	    transition: all .6s;
	  }
	  .selection-2 .section-row .card-content .text1 {
	    text-align: justify;
	    line-height: 1.6vw;
	    margin: 6.2vh auto 3vh;
	    padding-top: 2.41vh;
	    width: 88%;
	    text-align: center;
	    color: #000;
		font-size: 1.67vw;
	    font-family: 'PingFangSC-Regular';
	    -webkit-transition: all .6s;
	    transition: all .6s;
	  }
	  .selection-2 .section-row .card-content .text1 strong {
	  	font-family: 'PingFangSC-Semibold';
	  }
	  .selection-2 .section-row .section-col:hover .text1 {
	  	color: #fff;
	    -webkit-transition: all .6s;
	    transition: all .6s;
	  }
	  .selection-2 .section-row .section-col:hover .text1 strong {
	  	color: #fff;
	  }


	  .selection-2 .section-row .card-content .text2 {
		color: #000;
		text-align: center;
		line-height: 1.67vw;
		font-family: 'PingFangSC-Regular';
		font-size: 1.04vw;
	  }

	  .selection-2 .section-row .section-col:hover .text2 {
	  	color: #fff;
	    -webkit-transition: all .6s;
	    transition: all .6s;
	  }

	  .section-tit {
	  	position: absolute;
	  	left: 0;
	  	bottom: 0;
	  	display: flex;
	  	justify-content: center;
	  	align-items: center;
	  	width: 100%;
	  	height: 21.85vh;
		color: #FFFFFF;
		font-size: 2.86vw;
	  	font-family: 'PingFangSC-Regular';
	  	background: rgba(0, 0, 0, 0.66);
	  	z-index: 10;
	  }
	  .section-tit strong {
		color: #FF9A20;
		line-height: 4.01vw;	
		font-family: 'PingFangSC-Regular';
		font-size: 2.86vw;
	  }


	/*selection-3*/
	.selection-3 {
		background: url('../assets/17.jpg') center center no-repeat;
		background-size: cover;
	}

	.selection-3 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
	}
	 
	.selection-3 .letf-div {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 33.18vw;
    	height: 30.02vw;
		color: #000000;
		text-align: center;
		line-height: 4.01vw;
		font-size: 2.86vw;
		background: url('../assets/12.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-3 .letf-div h3 {
		margin-top: 5vw;
		margin-bottom: 2.13vh;
		font-family: 'PingFangSC-Regular';
	}

	.selection-3 .letf-div strong {
		color: #FF9A20;
		font-family: 'PingFangSC-Medium';
	}
	.selection-3 .letf-div p {
		color: #000000;
		line-height: 1.82vw;
		font-family: PingFangSC-Regular;
		font-size: 1.2vw;
	}
	.selection-3 .iconfont {
		width: 4.95vw;
		height: 4.95vw;
		margin: 0 auto 2.13vh;
		font-size: 4.95vw;
	}
	.selection-3 .icon {
		position: relative;
	}
	.selection-3 .icon i {
		position: absolute;
		left: 0;
		top: 0;
		font-style: normal; 
	}
	.selection-3 .icon .path2, .selection-3 .icon .path3 {
		color: #fff;
	}
	.selection-3 .right-div {
		margin-left: 10.36vw;
	}
	.selection-3 .right-div_ {
		display: flex;
		justify-content: center;
		padding: 3.89vh 0;
	}
	.selection-3 .list_div {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 16.82vw;
		height: 17.34vw;
		margin: 0 2.19vw;
		border: 1px solid #DEDEDE;
		background: #FFFFFF;
		cursor: pointer;
	}
	.selection-3 .list_div_ {
		width: 86%;
		margin: 0 auto;
	}
	.selection-3 .list_div h3 {
		margin-bottom: 1.11vh;
		color: #FF9A20;
		text-align: center;
		font-family: 'PingFangSC-Regular';
		font-size: 1.46vw;
	}

	.selection-3 .list_div p {
		color: #000000;
		line-height: 1.67vw;
		font-family: PingFangSC-Regular;
		font-size: 0.83vw;
	}
	
	.selection-3 .list_div:hover {
		border: 1px solid #979797;
		background: #000000;
		box-shadow: 0 12px 32px 0 rgba(0,0,0,0.34);
		-webkit-transition: all .6s;
	    transition: all .6s;
	}
	.selection-3 .list_div:hover .icon .path1 {
		color: #fff;
		-webkit-transition: all .6s;
	    transition: all .6s;
	}

	.selection-3 .list_div:hover p {
		color: #fff;
		-webkit-transition: all .6s;
	    transition: all .6s;
	}
	.selection-3 .list_div:hover .iconfont {
		color: #fff;
		-webkit-transition: all .6s;
	    transition: all .6s;
	}
	.selection-3 .list_div .icon-13-bg {
		background: url('../assets/13.png') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-3 .list_div .icon-14-bg {
		background: url('../assets/144.png') center center no-repeat;
		background-size: 100% 100%;
	}

	.selection-3 .list_div:hover .icon-13-bg {
		background: url('../assets/133.png') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-3 .list_div:hover .icon-14-bg {
		background: url('../assets/14.png') center center no-repeat;
		background-size: 100% 100%;
	}

	.selection-3 .list_div .icon-15-bg {
		background: url('../assets/15.png') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-3 .list_div .icon-16-bg {
		background: url('../assets/16.png') center center no-repeat;
		background-size: 100% 100%;
	}

	.selection-3 .list_div:hover .icon-15-bg {
		background: url('../assets/155.png') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-3 .list_div:hover .icon-16-bg {
		background: url('../assets/166.png') center center no-repeat;
		background-size: 100% 100%;
	}

	/*selection-4*/
	.selection-4 {
		background: #fff;
		
	}
	.selection-4 .con_bg {
		position: absolute;
		right: 0;
		top: 0;
		width: 78.65vw;
		height: 100vh;
		background: url('../assets/19.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-4 .list_div {
		position: absolute;
		left: 8.54vw;
		top: 0;
		bottom: 0;
		margin: auto;
		display: flex;
		justify-content: center;
		align-items: center;
		width: 47.19vw;
		height: 33.91vw;
		background: url('../assets/20.png') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-4 .list_div_ {
		width: 36.15vw;
	}
	.selection-4 .list_div h2 {
		margin-bottom: 3.61vh;
		color: #000;
		font-size: 2.34vw;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-4 .list_div h2 strong {
		color: #FF9A20;
		font-family: PingFangSC-Semibold;
		font-size: 2.34vw;
	}
	
	.selection-4 .list_div p {
		margin-bottom: 5.19vh;
		color: #000000;
		line-height: 2.34vw;		
		font-size: 1.04vw;
		font-family: 'PingFangSC-Regular';
	}

	.selection-4 .e-mail {
		
	}
	.selection-4 .e-mail a {
		position: relative;
		display: flex;
		justify-content: center;
		align-items: center;
		width: 2.55vw;
		height: 2.55vw;
		border-radius: 50%;
		border: 0.1vw solid #000000;
	}
	.selection-4 .e-mail-bg {
		position: absolute;
		left: -0.03vw;
		top: -0.01vw;
		margin: 0 auto;
		width: 2.65vw;
		height: 2.65vw;
		border-radius: 50%;
		background: #777;
		z-index: 0;
		-webkit-transition: all .4s;
    	transition: all .4s;
		-webkit-transform: scale(0);
	    transform: scale(0);
	}
	.selection-4 .e-mail i {
		position: absolute;
		left: 0;
		right: 0;
		top: 0;
		bottom: 0;
		margin: auto;
		height: 1.2vw;
		text-align: center;
		color: #000;
		font-size: 1.2vw;
		-webkit-transition: all .8s;
    	transition: all .8s;
    	z-index: 1;
	}
	
	/*selection-5*/
	.selection-5 {
		background: url('../assets/21.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-5 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
	}
	.selection-5 .cont  {
		position: relative;
		width: 100%;
	}
	.selection-5 h2 {
		color: #FF9A20;
		text-align: center;
		font-size: 2.34vw;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-5 h2 strong {
		color: #fff;
		font-family: 'PingFangSC-Semibold';
	}

	.selection-5 .list-con {
		position: relative;
		width: 100%;
		height: 32.24vw;
		margin-top: 8.33vh;
	}
	.selection-5 .list-con .list_div {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.selection-5 .list-con img {
		width: 19.22vw;
		height: 32.24vw;
	}

	.pictureSlider {
	    height: 59.07vh;
	}
	.selection-5 .poster-list {
		width: 100%;
		height: 50vh;
	}
	.poster-item {
		position: relative;
		width: 19.22vw;
		transition: all 0.5s;
		-moz-transition: all 0.5s;
		-webkit-transition: all 0.5s;
		-o-transition: all 0.5s;
		cursor: pointer;
	}

	/*selection-6*/
	.selection-6 {
		background: url(../assets/103.jpg) center center no-repeat;
		background-size: cover;
	}

	.selection-6 .con {
		display: flex;
		align-items: center;
		height: 100%;
	}
	.selection-6 .con_ {
		width: 80%;
		margin: 0 auto;
	}

	.selection-6 .tit {
		margin-bottom: 10.37vh;
	}

	.selection-6 .tit h2 {
		margin-bottom: 0.83vh;
		color: #FF9A20;
		text-indent: 0.5em;
		font-size: 2.34vw;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-6 .tit h2 strong {
		color: #fff;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-6 .tit p {
		text-indent: 1em;
		color: #FFFFFF;
		font-size: 1.3vw;
	}

	.selection-6 .list-con {
		display: flex;
		align-items: center;
	}

	.selection-6 .list_div {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 21.93vw;
		height: 21.67vw;
		background: url('../assets/28.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-6 .list_div img {
		display: block;
		width: 5.57vw;
		margin: 0 auto 1.3vh;
	}
	.selection-6 .list_div h3 {
		margin-bottom: 1.3vh;
		color: #FFFFFF;
		text-align: center;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Regular';
	}
	
	.selection-6 .list_div p {
		color: #FFFFFF;
		text-align: center;
		line-height: 1.56vw;
		font-size: 0.94vw;
	}

	/*selection-7*/
	.selection-7 {
		background: url(../assets/32.jpg) center center no-repeat;
		background-size: cover;
	}
	.selection-7 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
	}
	.selection-7 .con_ {
		height: 62%;
	}
	.selection-7 .tit {
		margin-bottom: 16.67vh;
	}
	
	.selection-7 .tit h2 {
		margin-bottom: 3.8vh;
		color: #FF9A20;
		text-align: center;
		font-size: 2.34vw;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-7 .tit h2 strong {
		color: #fff;
		font-family: 'PingFangSC-Semibold';	
	}
	
	.selection-7 .tit p {
		text-align: center;
		color: #FFFFFF;
		font-size: 1.3vw;
	}
	.selection-7 .list-con {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.selection-7 .list_div {
		margin: 0 3.31vw;
	}
	.selection-7 .list_div img {
		display: block;
		width: 10.52vw;
		margin: 0 auto 2.4vw;
	}
	.selection-7 .list_div p {
		text-align: center;
		color: #FFFFFF;
		font-size: 1.3vw;
	}
 
	.selection-8 {
		background: url(../assets/112.jpg) center center no-repeat;
		background-size: cover;
	}
	.selection-8 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100%;
	} 
	.selection-8 .tit h2 {
		margin-bottom: 8.89vh;
		color: #FF9A20;
		text-align: center;
		font-family: 'PingFangSC-Semibold';
		font-size: 2.34vw;
	}
	.selection-8 .tit h2 strong {
		color: #fff;	
		font-family: 'PingFangSC-Semibold';
	}
	
	.selection-8 .list-con {
		display: flex;
		justify-content: center;
	}
	.selection-8 .list_div {
		display: flex;
		justify-content: center;
		align-items: flex-end;
		width: 15.94vw;
		height: 24.22vw;
		margin: 0 3.59vw;
		cursor: pointer;
		-webkit-transition: all .8s;
	    transition: all .8s;
	}
	.selection-8 .list_div p {
		margin-bottom: 1.61vw;
		color: #000000;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Light';
	}

	.selection-8 .list_bg_01 {
		background: url(../assets/39.jpg) center center no-repeat;
		background-size: 100% 100%;
	}
	
	.selection-8 .list_bg_02 {
		background: url(../assets/40.jpg) center center no-repeat;
		background-size: 100% 100%;
	}	
	.selection-8 .list_bg_03 {
		background: url(../assets/41.jpg) center center no-repeat;
		background-size: 100% 100%;
	}

	
	/*selection-9*/
	.selection-9 {
		background: #F0F0F0;
	} 
	.selection-9 .con {
		position: relative;
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.selection-9 .tit {
		margin-bottom: 19.81vh;
	}
	.selection-9 .tit h2 {
		text-align: center;
		color: #FF9A20;
		font-size: 2.34vw;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-9 .tit strong {
		color: #000;
		font-family: 'PingFangSC-Semibold';
	}

	.selection-9 .pre-btn, .selection-9 .next-btn {
		position: absolute;
		color: #000;
		text-align: center;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Thin';
		z-index: 9999;
		cursor: pointer;
		opacity: 0.3;
		-webkit-transition: all 1.2s;
	    transition: all 1.2s;
	}
	.selection-9 .pre-btn:hover , .selection-9 .next-btn:hover {
		opacity: 1;
		-webkit-transition: all 1.2s;
	    transition: all 1.2s;
	}
	.selection-9 .pre-btn {
		left: 5.36vw;
		top: 24.91vh;
	}
	.selection-9 .next-btn {
		right: 5.36vw;
		top: 24.91vh;
	}
	.selection-9 .pre-btn span {
		display: block;
	}
	.selection-9 .next-btn span {
		display: block;
	}
	.selection-9 .pre-btn i {
		display: block;
		width: 1.35vw;
		height: 1.2vw;
		margin: 1.39vh auto 0;
		background: url('../assets/42.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-9 .next-btn i {
		display: block;
		width: 1.35vw;
		height: 1.2vw;
		margin: 1.39vh auto 0;
		background: url('../assets/43.svg') center center no-repeat;
		background-size: 100% 100%;
	}

	.selection-9 .list_div {
		width: 14.69vw;
		margin: 0 auto;
		border: 1px solid #ECECEC;
		background: #FFFFFF;
	}
	.selection-9 .list_div img {
		display: block;
		width: 100%;
	}

	.selection-9 .list_div p {
		overflow: hidden;
		height: 3.85vw;
		text-align: center;
		color: #000000;
		line-height: 3.85vw;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Light';
	}

	#swiper {
		width: 100vw;
	}
	
	/*selection-10*/
	.selection-10 {
		background: url('../assets/101.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-10 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.selection-10 h2 {
		margin-bottom: 8.43vh;
		text-align: center;
		color: #FF9A20;
		font-family: PingFangSC-Semibold;
		font-size: 2.34vw;
	}
	.selection-10 img {
		width: 65.05vw;
		height: 33.75vw;
	}
	.selection-10 h2 strong {
		display: inline-block;
		margin: 0 1vw;
		color: #FFFFFF;
		line-height: 0.47vw;
		font-family: PingFangSC-Semibold;
		font-size: 3.91vw;
	}
	
	/*selection-11*/
	.selection-11 {
		background: url('../assets/105.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-11 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.selection-11 h2 {
		margin-bottom: 9.91vh;
		text-align: center;
		color: #FF9A20;
		font-family: PingFangSC-Semibold;
		font-size: 2.34vw;
	}
	.selection-11 h2 strong {
		color: #fff;
		line-height: 3.28vw;	
		font-family: PingFangSC-Semibold;
		font-size: 2.34vw;
	}
	
	.selection-11 .list_con {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.selection-11 .list_div {
		width: 15vw;
		margin: 0 0.31vw;
	}
	.selection-11 .list_div .list_bg {
		position: relative;
		width: 100%;
		height: 13.02vw;
	}
	.selection-11 .list_div .list_bg p {
		position: absolute;
		left: 0;
		bottom: 1.2vh;
		width: 100%;
		color: #FFFFFF;
		text-align: center;
		font-family: PingFangSC-Semibold;
		font-size: 1.3vw;
	}
	.selection-11 .list_div .list_bottom {
		width: 100%;
		height: 10.63vw;
		background: #fff;
	}
	.selection-11 .list_div .list_bottom p {
		padding-top: 2.78vh;
		color: #000000;
		text-align: center;	
		font-family: PingFangSC-Thin;
		font-size: 1.3vw;
	}
	
	
	.selection-11 .list_bg_01 {
		background: url('../assets/106.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-11 .list_bg_02 {
		background: url('../assets/107.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-11 .list_bg_03 {
		background: url('../assets/108.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-11 .list_bg_04 {
		background: url('../assets/109.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-11 .list_bg_05 {
		background: url('../assets/110.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-11 .list_div .list_bottom p {
		color: #000000;
		text-align: center;
		text-align: center;
		font-family: PingFangSC-Thin;
		font-size: 1.3vw;
	}

	/*selection-12*/
	.selection-12 {

	}
	.selection-12 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.selection-12 .con_ {
		position: relative;
		width: 63.39vw;
		height: 100vh;
		background: url('../assets/111.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-12 .tit {
		position: absolute;
		left: 6.09vw;
		top: 30.83vh;
		display: flex;
		justify-content: center;
		align-items: center;
		width: 17.71vw;
		height: 17.71vw;
		font-size: 2.34vw;
		background: url('../assets/Group135.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-12 .tit p {
		color: #FF9A20;
		text-align: center;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-12 .tit strong {
		color: #fff;
		font-family: 'PingFangSC-Semibold';
		font-size: 3.39vw;
	}

	.selection-12 .list-con {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 36.61vw;
		height: 100vh;
		color: #000000;
		line-height: 3.65vw;
		font-family: PingFangSC-Light;
		font-size: 1.56vw;
		background: #fff;
	} 

	/*selection-13*/
	.selection-13 {
		background: url('../assets/113.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-13 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.selection-13 .tit {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 17.71vw;
		height: 17.71vw;
		margin-right: 11.11vw;
		font-size: 2.34vw;
		background: url('../assets/Group135.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-13 .tit p {
		color: #FF9A20;
		text-align: center;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-13 .tit strong {
		color: #fff;
		font-family: 'PingFangSC-Semibold';
		font-size: 3.39vw;
	}
	.selection-13 img {
		width: 53.75vw;
	}

	/*selection-14*/
	.selection-14 {
		background: url('../assets/115.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-14 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.selection-14 .con_ {
		width: 76.04vw;
	}
	.selection-14 .tit {
		margin-bottom: 4.44vh;
		color: #FF9A20;
		text-align: center;
		font-family: PingFangSC-Semibold;
		font-size: 2.34vw;
	}
	.selection-14 .tit strong {
		color: #fff;
		font-family: PingFangSC-Semibold;
	}
	.selection-14 h4 {
		margin-bottom: 1.02vh;
		color: #FF9A20;	
		font-family: PingFangSC-Semibold;
		font-size: 1.56vw;
	}
	.selection-14 p {
		margin-bottom: 1.2vh;
		color: #FFFFFF;
		line-height: 2.08vw;	
		font-family: PingFangSC-Light;
		font-size: 0.94vw;
	}
	
	/*selection-15*/
	.selection-15 {

	}
	.selection-15 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.selection-15 .list_con {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 52.4vw;
		height: 100vh;
	}
	.selection-15 .list_con_ {
		height: 80vh;
	}
	.selection-15 .list_con img {
		display: block;
		width: 29.17vw;
		margin: 0 auto;
	}
	.selection-15 .list_con p {
		margin-bottom: 1.39vh;
		color: #000000;
		text-align: center;
		font-family: PingFangSC-Light;
		font-size: 1.3vw;
	}
	.selection-15 .list_con h2 {
		margin-bottom: 2.96vh;
		color: #000000;
		text-align: center;
		line-height: 4.17vw;
		font-family: PingFangSC-Regular;
		font-size: 2.86vw;
	}
	.selection-15 .list_con h2 strong {
		color: #FF9A20;
		font-size: 3.39vw;
		font-family: PingFangSC-Regular;
	}
	.selection-15 .list_con h4 {
		color: #000000;	
		text-align: center;
		font-family: PingFangSC-Light;
		font-size: 1.82vw;
	}
	
	.selection-15 .con_ {
		width: 47.6vw;
		height: 100vh;
		background: url('../assets/117.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-15 .con_ h2 {
		position: absolute;
		right: 5.83vw;
		top: 12.04vh;
		color: #FF9A20;
		font-family: PingFangSC-Semibold;
		font-size: 2.34vw;
	}
	.selection-15 .con_ h2 strong {
		color: #fff;
		font-family: PingFangSC-Semibold;
	}

	/*selection-16*/
	.selection-16 {
		background: url('../assets/118.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-16 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.selection-16 .con h2 {
		margin-bottom: 3.89vh;
		color: #FF9A20;
		font-family: PingFangSC-Semibold;
		font-size: 2.34vw;
	}
	.selection-16 .con h2 strong {
		color: #fff;
		font-family: PingFangSC-Semibold;
	}
	.selection-16 .left  {
		width: 36.15vw;
		margin-right: 6.15vw;
	}
	.selection-16 .list_div {

	}
	.selection-16 .list_div p {
		color: #FFFFFF;
		line-height: 2.34vw;	
		font-family: PingFangSC-Light;
		font-size: 1.04vw;
	}
	.selection-16 .list_div p strong {
		color: #FF9A20;
		line-height: 2.34vw;	
		font-family: PingFangSC-Semibold;
		font-size: 1.82vw;
	}
	.selection-16 .list_div h4 {
		color: #FF9A20;
		line-height: 2.34vw;
		font-family: PingFangSC-Semibold;
		font-size: 1.3vw;
	}
	.selection-16 .right {

	}
	.selection-16 .right h4 {
		color: #FF9A20;
		line-height: 1.88vw;	
		font-family: PingFangSC-Semibold;
		font-size: 1.3vw;
	}
	.selection-16 .right p {
		margin-bottom: 3.7vh;
		color: #fff;
		line-height: 1.88vw;	
		font-family: PingFangSC-Light;
		font-size: 1.04vw;
	}
	.selection-16 .right strong {
		color: #FF9A20;
		line-height: 1.88vw;	
		font-family: PingFangSC-Semibold;
		font-size: 1.82vw;
	}
	.selection-16 .right img {
		display: block;
		width: 37.76vw;
	}
	
	/*selection-17*/
	.selection-17 {
		background: url('../assets/120.jpg') center center no-repeat;
		background-size: cover;
	}
	.selection-17 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.selection-17 .con_ {
		
	}
	.selection-17 .tit {
		margin-bottom: 8.43vh;
		color: #FF9A20;
		text-align: center;
		font-family: 'PingFangSC-Semibold';
		font-size: 2.34vw;
	}
	.selection-17 .tit strong {
		color: #fff;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-17 .list_con {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.selection-17 .list_div {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 26.35vw;
		height: 33.91vw;
		margin: 0 0.63vw;
		border: 0.21vw solid #979797;	
	}
	.selection-17 .list_div_ {
		width: 90%;
	}
	.selection-17 .list_div h2 {
		margin-bottom: 3vh;
		color: #FFFFFF;
		text-align: center;
		line-height: 2.86vw;	
		font-family: PingFangSC-Regular;
		font-size: 2.08vw;
	}
	.selection-17 .list_div h3 {
		color: #fff;
		text-align: center;
		line-height: 2.3vw;
		font-size: 1.3vw;
		font-family: 'PingFangSC-Light';
	}
	.selection-17 .list_div h3 strong, .selection-17 .list_div p span {
		color: #FF9A20;
		font-size: 1.82vw;
		font-family: 'PingFangSC-Semibold';
	}
	.selection-17 .list_div h4 {
		color: #FF9A20;
		text-align: center;
		font-family: 'PingFangSC-Light';
		font-size: 1.04vw;
	}
	.selection-17 .list_div p {
		color: #fff;
		text-align: center;
		font-family: 'PingFangSC-Light';
		font-size: 0.83vw;
	}
	.selection-17 .list_div_con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 44vh;
	}
	
	/*selection-18*/
	.selection-18 {

	}
	.selection-18 .con {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 78.61vh;
		background: url('../assets/121.jpg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-18 .tit {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 17.71vw;
		height: 17.71vw;
		margin-right: 11.11vw;
		background: url('../assets/Group135.svg') center center no-repeat;
		background-size: 100% 100%;
	}
	.selection-18 .tit p {
		color: #FF9A20;
		text-align: center;
		font-family: 'PingFangSC-Semibold';
		font-size: 3.39vw;
	}
	.selection-18 .tit strong {
		color: #fff;
		font-family: 'PingFangSC-Semibold';
		font-size: 3.39vw;
	}
	.selection-18 .list-con {
		
	}
	.selection-18 .list-con li {
		display: flex;
		align-items: center;
		width: 52.4vw;
		height: 4.64vw;
		margin-bottom: 2.13vh;
		padding-left: 3.07vw;
		border: 0.05vw solid #979797;
		color: #fff;
		line-height: 2.86vw;
		font-family: PingFangSC-Light;
		font-size: 1.3vw;
		-webkit-transition: all 1.2s;
	    transition: all 1.2s;
	}
	.selection-18 .list-con li strong {
		color: #FF9A20;
		line-height: 2.86vw;	
		font-family: PingFangSC-Semibold;
		font-size: 1.3vw;
	}
	.selection-18 li:hover {
		color: #000;
		background: #FFFFFF;
		cursor: pointer;
		-webkit-transition: all 1.2s;
	    transition: all 1.2s;
	}
	
	
	@media screen and (max-width: 750px) {
		.mob {
			display: block;
		}
		.video1 {
		    max-width: 218%;
			width: 218%;
		}

		#tops {
			display: none;
			position: fixed;
			right: 6.13vw;
			bottom: 7.2vw;
			width: 10.13vw;
			height: 10.13vw;
			background: url('../assets/7.svg') center center no-repeat;
			background-size: 100% 100%;
			z-index: 99999999;
		}

		/*selection-1*/
		.selection-1 .con {
			background: rgba(0, 0, 0, 0.65);
		}
		.selection-1 .btn_weixin {
			width: 45.33vw;
			height: 10.67vw;
			margin: 0 auto;
			border-radius: 100px;
			text-align: center;
			line-height: 10.67vw;
			background: #ff973f;
			font-size: 5vw;
			font-family: 'PingFangSC-Regular';
		}

		.selection-1 .weixin-con {
			margin: 3.43vh auto 0;
			width: 50%;
			z-index: 2;
		}
		.selection-1 .weixin-con .codes {
			width: 38.05vw;
		}
		.selection-1 .h1 {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 88vw;
			height: 54.13vw;
			margin: 0 auto 4.11vh;
		}
		.selection-1 h1 {
			height: auto;
			margin: 0;
			line-height: 11.2vw;
			font-size: 7vw;
		}
		.selection-1 h1 strong {
			line-height: 11.2vw;
			font-size: 8vw;
		}
		.selection-1 h1 {
			margin-bottom: 4.07vh;
			color: #FFFFFF;
			text-align: center;
			line-height: 7.39vw;
			font-size: 6.67vw;
			font-family: 'PingFangSC-Regular';
		}
		.selection-1 h1 strong {
			display: inline-block;
			color: #FF973F;
			line-height: 10.53vw;
			font-size: 6.67vw;
			font-family: 'PingFangSC-Regular';
		}
		.selection-1 h3 {
			color: #BDBDBD;	
			font-family: 'PingFangSC-Light';
			font-size: 5.33vw;
		}
		.selection-1 p {
			margin-bottom: 0;
			line-height: 6.34vw; 
			font-size: 3.8vw;
		}
		.selection-1 p span {
			display: inline-block;
			width: 2vw;
		}
		
		.selection-1 .cont {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 66%;
			color: #FFFFFF;
			text-align: center;
			line-height: 2.34vw;
			font-size: 1.3vw;
		}
		.selection-1 .down {
			position: static;			
			display: block;
			height: 12vw;
			margin: 2vh auto 0;
		}

		.selection-1 .down svg {
			-webkit-animation: fall 1.2s infinite;
		    animation: fall 1.2s infinite;
		}
		
		/*selection-2*/
		.selection-2 {

		}
		.selection-2 .con {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100%;
		}
		.selection-2 .tit {
			margin-bottom: 6.45vh;
		}
		.selection-2 .tit h2 {
			text-align: center;
			color: #000000;
			font-size: 6.67vw;
			font-family: 'PingFangSC-Regular';
		}
		.selection-2 .tit h2 strong {
			color: #FF9A20;
			font-family: 'PingFangSC-Regular';
		}
		.selection-2 .list_div {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 71.47vw;
			height: 108vw;
			margin: 0 auto;
		}
		.selection-2 .list_div img {
			display: block;
			width: 13.33vw;
			margin: 0 auto 4.5vh;
		}
		.selection-2 .list_div .text1 {
			width: 100%;
			margin: 0 auto;
			color: #FFFFFF;
			text-align: center;
			line-height: 7.2vw;
			font-size: 4.27vw;
			font-family: 'PingFangSC-Regular';
		}
		.selection-2 .list_div strong {
			font-family: 'PingFangSC-Regular';
		}
		.selection-2 .list_div .text2 {
			width: 100%;
			margin: 0 auto;
			color: #FFFFFF;
			text-align: center;
			line-height: 7.2vw;
			color: #FFFFFF;
			font-size: 3.2vw;
			font-family: 'PingFangSC-Regular';
		}

		#swiper01 {
			width: 100vw;
			height: 125vw;
		}

		.selection-2 .col-bg1 {
		    background: url('../assets/005.jpg') center no-repeat padding-box;
		    background-size: cover;
		}
		.selection-2 .col-bg2 {
		    background: url('../assets/006.jpg') center no-repeat padding-box;
		    background-size: cover;
		}
		.selection-2 .col-bg3 {
		    background: url('../assets/007.jpg') center no-repeat padding-box;
		    background-size: cover;
		}
		.selection-2 .col-bg4 {
		    background: url('../assets/008.jpg') center no-repeat padding-box;
		    background-size: cover;
		}

		/*selection-3*/
		.selection-3 {
			height: 123.09vh;
			background: url('../assets/010.jpg') center center no-repeat;
			background-size: cover;
		}

		.selection-3 .letf-div {
			width: 75.47vw;
    		height: 66.4vw;
			margin: 0 auto;
			line-height: 9.6vw;
			font-size: 6.67vw;
			background: url('../assets/009.svg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-3 .right-div {
			margin: 4.17vh auto 0;
		}
		.selection-3 .right-div_ {
			display: flex;
			justify-content: center;
			padding: 1.5vh 0;
		}
		.selection-3 .list_div {
			width: 36.53vw;
			height: 53.6vw;
			margin: 0 2.53vw;
		}
		.selection-3 .letf-div h3 {
			margin-top: 12vw;
			text-align: left;
			font-size: 6.67vw;
		}
		.selection-3 .letf-div p {
			margin-top: 1.8vh;
			line-height: 4.2vw;
			font-size: 3.2vw;
		}
		.selection-3 .list_div h3 {
			font-size: 3.73vw;
		}

		.selection-3 .list_div p {
			line-height: 4.73vw;
			font-size: 2.67vw;
		}

		.selection-3 .iconfont {
			width: 10.67vw;
			height: 10.67vw;
			margin: 0 auto 1.35vh;
			font-size: 10.67vw;
		}

		/*selection-4*/
		.selection-4 {

		}
		.selection-4 .con_bg {
			position: absolute;
			right: 0;
			top: 0;
			width: 100vw;
			height: 55.77vh;
			background: url('../assets/011.jpg') center center no-repeat;
			background-size: cover;
		}	
		.selection-4 .list_div {
			position: absolute;
		    left: 0;
		    right: 0;
		    top: 50.13vw;
		    bottom: 0;
		    width: 96.8vw;
		    height: 117.8vw;
			background: url('../assets/012.png') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-4 .list_div_ {
			width: 74.47vw;
    		height: 80%;
		}

		.selection-4 .list_div h2 {
			margin-bottom: 1.8vh;
			font-size: 6.13vw;
		}
		.selection-4 .list_div h2 strong {
			font-size: 6.13vw;
		}

		.selection-4 .list_div p {
			margin-bottom: 2.55vh;
			color: #000000;
			line-height: 6.67vw;		
			font-size: 3.2vw;
		}

		.selection-4 .e-mail a {
			width: 8.67vw;
			height: 8.67vw;
			border: 0.27vw solid #000;
		}
		.selection-4 .e-mail-bg {
			position: absolute;
			left: -0.03vw;
			top: -0.01vw;
			margin: 0 auto;
			width: 2.65vw;
			height: 2.65vw;
		}
		.selection-4 .e-mail i {
			height: 3.2vw;
			font-size: 3.2vw;
		}
		
		/*selection-5*/
		.selection-5 {
			background: url('../assets/014.jpg') center center no-repeat;
			background-size: cover;
		}

		.selection-5 h2 {
			font-size: 6.67vw;
		}

		.selection-5 .list-con {
			height: auto;
		}

		.selection-5 .list-con img {
			width: 45.33vw;
			height: auto;
		}

		.poster-item {
			position: relative;
			width: 45.33vw;		
		}

		/*selection-6*/
		.selection-6 {
			height: 106vh;
			background: url('../assets/015.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-6 .con_ {
			width: 100%;
		}
		.selection-6 .tit {
			width: 80%;
			margin: 0 auto 34.93vh;
		}
		.selection-6 .tit h2 {
			margin-bottom: 2.85vh;
			text-indent: 0em;
			font-size: 6.67vw;
		}
		.selection-6 .tit p {
			width: 36.53vw;
			text-indent: 0em;
			font-size: 3.73vw;
		}
		.selection-6 .list-con {
			width: 100vw;
			justify-content: center;
		}

		.selection-6 .list_div {
			width: 41.87vw;
			height: 53.6vw;
			margin: 0 2.27vw;
			background: url('../assets/016.svg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-6 .list_div img {
			display: block;
			width: 11.73vw;
			margin: 0 auto 0.9vh;
		}
		.selection-6 .list_div h3 {
			margin-bottom: 2.7vh;
			color: #FF9A20;;
			font-size: 3.73vw;
		}
		
		.selection-6 .list_div p {
			color: #FFFFFF;
			text-align: center;
			line-height: 4.8vw;
			font-size: 3.2vw;
		}

		/*selection-7*/
		.selection-7 {
			background: url('../assets/018.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-7 .tit h2 {
			margin-bottom: 2.7vh;
			font-size: 6.67vw;
		}
		.selection-7 .tit p {			
			font-size: 3.73vw;
		}

		.selection-7 .list_div {

		}
		.selection-7 .list_div img {
			width: 41.07vw;
			margin-bottom: 4.2vh;
		}
		.selection-7 .list_div p {
			font-size: 5.33vw;
		}

		#swiper02 {
			width: 100vw;
			height: 50vh;
		}
		
		/*selection-8*/
		.selection-8 {
			background: url('../assets/019.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-8 .tit h2 {
			margin-bottom: 5.7vh;
			font-size: 6.67vw;
		}

		.selection-8 .list_div {
			width: 66.13vw;
			height: 100.27vw;
			margin: 0 auto;
		}

		.selection-8 .list_div p {
			margin-bottom: 5vw;
			font-size: 6vw;
		}

		#swiper03 {
			width: 100vw;
			height: 70vh;
		}

		/*selection-9*/
		.selection-9 {
			height: 72.11vh;
			background: #fff;
		}
		.selection-9 .con {
			height: 72.11vh;
		}
		.selection-9 .con_ {
			height: 82%;
		}
		.selection-9 .tit {
			margin-bottom: 7.5vh;
		}
		.selection-9 .tit h2 {
			font-size: 6.67vw;
		}

		.selection-9 .list_div {
			width: 50.4vw;
		}
		.selection-9 .list_div img {
			display: block;
			width: 100%;
		}

		.selection-9 .list_div p {
			height: 15.47vw;
			line-height: 15.47vw;
			font-size: 4.27vw;
		}

		.selection-9 .pre-btn, .selection-9 .next-btn {
			display: flex;
			justify-content: center;
			align-items: center;
			color: #000;
			font-size: 3.73vw;
			z-index: 999999;
			opacity: 1;
		}
		.selection-9 .pre-btn {
			left: 5.36vw;
			top: 106.13vw;
		}
		.selection-9 .next-btn {
			right: 5.36vw;
			top: 106.13vw;
		}
		.selection-9 .pre-btn span {
			display: block;
		}
		.selection-9 .next-btn span {
			display: block;
		}
		.selection-9 .pre-btn i {
			display: block;
			width: 4.8vw;
			height: 4.27vw;
			margin: 0 2.67vw 0 0;
			background: url('../assets/42.svg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-9 .next-btn i {
			display: block;
			width: 4.8vw;
			height: 4.27vw;
			margin: 0 0 0 2.67vw;
			background: url('../assets/43.svg') center center no-repeat;
			background-size: 100% 100%;
		}

		#swiper04 {
			width: 100vw;
			height: 60.38vw;
		}

		/*selection-10*/
		.selection-10 {
			height: 126.64vh;
			background: url('../assets/206.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-10 .con {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100%;
		}
		.selection-10 h2 {
			margin-bottom: 3.45vh;
			text-align: center;
			color: #FF9A20;
			font-family: PingFangSC-Semibold;
			font-size: 6.67vw;
		}
		.selection-10 img {
			width: 91.73vw;
			height: auto;
		}
		.selection-10 h2 strong {
			display: inline-block;
			margin: 0 1vw;
			color: #FFFFFF;
			line-height: 14.47vw;
			font-family: PingFangSC-Semibold;
			font-size: 12vw;
		}

		/*selection-11*/
		.selection-11 {
			background: url('../assets/213.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-11 h2 {
			margin-bottom: 5.55vh;
			font-size: 6.67vw;
		}
		.selection-11 h2 strong {
			color: #fff;
			font-size: 6.67vw;
			font-family: PingFangSC-Semibold;
		}
		
		.selection-11 .list_con {
			display: flex;
			justify-content: center;
			align-items: center;
		}
		.selection-11 .list_div {
			width: 65.33vw;
			margin: 0 auto;
		}
		.selection-11 .list_div .list_bg {
			position: relative;
			width: 100%;
			height: 57.07vw;
		}
		.selection-11 .list_div .list_bg p {
			position: absolute;
			left: 0;
			bottom: 1.2vh;
			width: 100%;
			color: #FFFFFF;
			text-align: center;
			font-family: PingFangSC-Semibold;
			font-size: 6.67vw;
		}
		.selection-11 .list_div .list_bottom {
			width: 100%;
			height: 46.4vw;
			background: #fff;
		}
		.selection-11 .list_div .list_bottom p {
			padding-top: 2.78vh;
			color: #000000;
			text-align: center;	
			font-family: PingFangSC-Thin;
			font-size: 5.33vw;
		}


		#swiper05 {
			width: 100vw;
			height: 75vh;
		}

		/*selection-12*/
		.selection-12 {
			background: url('../assets/214.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-12 .con_ {
			position: relative;
			width: 100vw;
			height: 100vh;
			background: transparent;
		}
		.selection-12 .tit {
			position: absolute;
			left: 2.93vw;
			top: 7.04vh;
			width: 45.33vw;
			height: 45.33vw;
			font-size: 2.34vw;
			background: url('../assets/Group135.svg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-12 .tit p {
			color: #FF9A20;
			text-align: center;
			font-size: 6vw;
			font-family: 'PingFangSC-Semibold';
		}
		.selection-12 .tit strong {
			color: #fff;
			font-family: 'PingFangSC-Semibold';
			font-size: 8.67vw;
		}

		.selection-12 .list-con {
			position: absolute;
			left: 0;
			top: 40vh;
			display: flex;
			justify-content: center;
			align-items: center;
			width: 54.61vw;
			height: 58vh;
			color: #000000;
			line-height: 8.65vw;
			font-family: PingFangSC-Light;
			font-size: 3.73vw;
			background: transparent;
		} 

		/*selection-13*/
		.selection-13 {
			height: 110vh;
			background: url('../assets/216.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-13 .con {
			height: 100%;
		}
		.selection-13 .tit {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 45.33vw;
			height: 45.33vw;
			margin-right: 0vw;
			margin-left: 37.33vw;
			margin-bottom: 2.7vh;
			font-size: 2.34vw;
			background: url('../assets/Group135.svg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-13 .tit p {
			color: #FF9A20;
			text-align: center;
			font-size: 6vw;
			font-family: 'PingFangSC-Semibold';
		}
		.selection-13 .tit strong {
			color: #fff;
			font-family: 'PingFangSC-Semibold';
			font-size: 8vw;
		}
		.selection-13 img {
			width: 84.27vw;
		}

		/*selection-14*/
		.selection-14 {
			height: 198.65vh;
			background: url('../assets/217.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-14 .con {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100%;
		}
		.selection-14 .con_ {
			width: 85.04vw;
		}
		.selection-14 .tit {
			margin-bottom: 7.05vh;
			color: #FF9A20;
			text-align: center;
			font-family: PingFangSC-Semibold;
			font-size: 6.67vw;
		}
		.selection-14 .tit strong {
			color: #fff;
			font-family: PingFangSC-Semibold;
		}
		.selection-14 h4 {
			margin-bottom: 1.8vh;
			color: #FF9A20;	
			text-align: center;
			font-family: PingFangSC-Semibold;
			font-size: 4.8vw;
		}
		.selection-14 p {
			margin-bottom: 4.2vh;
			color: #FFFFFF;
			text-align: left;
			line-height: 6.08vw;	
			font-family: PingFangSC-Light;
			font-size: 3.2vw;
		}

		/*selection-15*/
		.selection-15 {

		}
		.selection-15 .con {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100vh;
		}
		.selection-15 .list_con {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 52.4vw;
			height: auto;
		}
	
		.selection-15 .con_ {
			width: 100%;
			height: auto;
			background: transparent;
			background-size: 100% 100%;
		}
		.selection-15 .con_ h2 {
			position: static;
			margin-bottom: 5.4vh;
			color: #FF9A20;
			text-align: center;
			font-family: PingFangSC-Semibold;
			font-size: 6.67vw;
		}
		.selection-15 .con_ h2 strong {
			color: #000;
			font-family: PingFangSC-Semibold;
		}
		.selection-15 .list_con {
			width: 100%;
		}
		.selection-15 .list_con img {
			display: block;
			width: 84.8vw;
			margin: 0 auto;
		}
		.selection-15 .list_con p {
			margin-bottom: 1.39vh;
			color: #000000;
			text-align: center;
			font-family: PingFangSC-Light;
			font-size: 5.33vw;
		}
		.selection-15 .list_con h2 {
			margin-bottom: 2.96vh;
			color: #000000;
			text-align: center;
			line-height: 10.17vw;
			font-family: PingFangSC-Regular;
			font-size: 6.67vw;
		}
		.selection-15 .list_con h2 strong {
			color: #FF9A20;
			font-size: 9.33vw;
			font-family: PingFangSC-Semibold;
		}
		.selection-15 .list_con h4 {
			color: #000000;	
			text-align: center;
			font-family: PingFangSC-Light;
			font-size: 5.33vw;
		}

		/*selection-16*/
		.selection-16 {
			height: 161.92vh;
			background: url('../assets/219.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-16 .con {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100%;
		}
		.selection-16 .con h2 {
			margin-bottom: 5.55vh;
			color: #FF9A20;
			text-align: center;
			font-family: PingFangSC-Semibold;
			font-size: 6.67vw;
		}
		.selection-16 .con h2 strong {
			color: #fff;
			font-family: PingFangSC-Semibold;
		}
		.selection-16 .left  {
			width: 86.67vw;
			margin-right: 0;
			margin-bottom: 6.15vh;
		}
		.selection-16 .list_div {

		}
		.selection-16 .list_div p {
			color: #FFFFFF;
			line-height: 6.34vw;	
			font-family: PingFangSC-Light;
			font-size: 3.2vw;
		}
		.selection-16 .list_div p strong {
			color: #FF9A20;
			line-height: 8.34vw;	
			font-family: PingFangSC-Semibold;
			font-size: 5.33vw;
		}
		.selection-16 .list_div h4 {
			color: #FF9A20;
			line-height: 6.34vw;
			font-family: PingFangSC-Semibold;
			font-size: 3.2vw;
		}
		.selection-16 .list_div h4 p {
			display: inline;
		}
		.selection-16 .right {
			width: 86.67vw;
		}
		.selection-16 .right h4 {
			color: #FF9A20;
			line-height: 1.88vw;	
			font-family: PingFangSC-Semibold;
			font-size: 3.2vw;
		}
		.selection-16 .right p {
			margin-bottom: 3.7vh;
			color: #fff;
			line-height: 1.88vw;	
			font-family: PingFangSC-Light;
			font-size: 3.2vw;
		}
		.selection-16 .right strong {
			color: #FF9A20;
			line-height: 1.88vw;	
			font-family: PingFangSC-Semibold;
			font-size: 3.2vw;
		}
		.selection-16 .right img {
			display: block;
			width: 86.93vw;
		}

		/*selection-17*/
		.selection-17 {
			background: url('../assets/120.jpg') center center no-repeat;
			background-size: cover;
		}
		.selection-17 .con {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 100vh;
		}
		.selection-17 .con_ {
			
		}
		.selection-17 .tit {
			margin-bottom: 8.43vh;
			color: #FF9A20;
			text-align: center;
			font-family: 'PingFangSC-Semibold';
			font-size: 6.67vw;
		}
		.selection-17 .tit strong {
			color: #fff;
			font-family: 'PingFangSC-Semibold';
		}
		.selection-17 .list_con {
			display: flex;
			justify-content: center;
			align-items: center;
		}
		.selection-17 .list_div {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 83.2vw;
			height: 112.13vw;
			margin: 0 auto;
			border: none;
			background: url('../assets/222.png') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-17 .list_div_ {
			width: 90%;
		}
		.selection-17 .list_div h2 {
			margin-bottom: 5vh;
			color: #FFFFFF;
			text-align: center;
			line-height: 6.86vw;	
			font-family: PingFangSC-Regular;
			font-size: 6.08vw;
		}
		.selection-17 .list_div h3 {
			color: #fff;
			text-align: center;
			line-height: 7.3vw;
			font-size: 4.3vw;
			font-family: 'PingFangSC-Light';
		}
		.selection-17 .list_div h3 strong, .selection-17 .list_div p span {
			color: #FF9A20;
			font-size: 6.82vw;
			font-family: 'PingFangSC-Semibold';
		}
		.selection-17 .list_div h4 {
			color: #FF9A20;
			text-align: center;
			font-family: 'PingFangSC-Light';
			font-size: 3.04vw;
		}
		.selection-17 .list_div p {
			color: #fff;
			text-align: center;
			font-family: 'PingFangSC-Light';
			font-size: 2.83vw;
		}
		.selection-17 .list_div_con {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 44vh;
		}
		
		#swiper06 {
			width: 100vw;
			height: 75vh;
		}


		/*selection-18*/
		.selection-18 {
			height: auto;
		}
		.selection-18 .con {
			display: flex;
			justify-content: center;
			align-items: center;
			height: 123.39vh;
			background: url('../assets/223.jpg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-18 .tit {
			display: flex;
			justify-content: center;
			align-items: center;
			width: 45.33vw;
			height: 45.33vw;
			margin-right: 0;
			margin-left: 8vw;
			margin-bottom: 5.4vh;
			background: url('../assets/Group135.svg') center center no-repeat;
			background-size: 100% 100%;
		}
		.selection-18 .tit p {
			color: #FF9A20;
			text-align: center;
			font-family: 'PingFangSC-Semibold';
			font-size: 8vw;
		}
		.selection-18 .tit strong {
			color: #fff;
			font-family: 'PingFangSC-Semibold';
			font-size: 8vw;
		}
		.selection-18 .list-con {
			
		}
		.selection-18 .list-con li {
			display: block;
			width: 87.98vw;
			height: 10.39vw;
			margin-bottom: 2.13vh;
			padding: 3.47vw 3.07vw;
			border: 0.05vw solid #979797;
			color: #fff;
			line-height: 5.86vw;
			font-family: PingFangSC-Light;
			font-size: 3.73vw;
		}
		.selection-18 .list-con li strong {
			color: #FF9A20;
			line-height: 5.86vw;	
			font-family: PingFangSC-Semibold;
			font-size: 3.73vw;
		}


	}


	@media screen and (min-width: 751px) {
		.selection-4 .e-mail a:hover i {
			color: #fff;
			-webkit-transition: all .8s;
	    	transition: all .8s;
		}
		
		.selection-4 .e-mail a:hover {
			border: 0.1vw solid transparent;		
		}
		.selection-4 .e-mail a:hover .e-mail-bg {
			-webkit-transition: all .4s;
	    	transition: all .4s;
	    	-webkit-transform: scale(1);
		    transform: scale(1);
		}

		.selection-8 .list_div:hover {
			-webkit-transform: translateY(10px) scale(1.2);
		    transform: translateY(10px) scale(1.2);
			box-shadow: 0 12px 32px 0 rgba(0,0,0,0.34);
			-webkit-transition: all .8s;
	    	transition: all .8s;
		}
	}
</style>
