<template>
  <div class="home">
    <nav class="sider-nav">
      <ul>
        <li>          
          <p>4008-931-898</p>
          <i class="icon-5"></i>
        </li>
        <li>
          <p>yacht58@163.com</p> 
          <i class="icon-6"></i>
        </li>
        <li class="nav-li-top">
          <p>Top</p>
          <i class="icon-7"></i>
        </li>
      </ul>
    </nav> 
    <app-header class="header_mob"></app-header>
    <div id="swiperCon" class="swiper-container">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
              <div class="selection selection-1">
                <app-header class="header_pc"></app-header>
                <video autoplay="" class="video1" loop="" src="../assets/video1.mp4"></video>
                <div class="video1_mob"></div>
                <div class="roll"></div>
                <div class="cont">
                  <h2 class="text1">启航黄金之旅，</h2>
                  <h2 class="text1">尊享快意人生！</h2>
                  <p>专业的俱乐部运营<br/>
                    细微入至的管家式服务<br/>
                    让您在享受游艇服务的同时，收获尊贵与财富
                  </p>
                  <button class="down-btn">
                    <i class="icon-Group-47"></i>
                  </button>
                  <div class="qr-code">
                    <img src="../assets/8.png" alt="">
                    <p>进入携艇商城<br/>了解更多游艇资讯</p>
                    <p class="scroll-down">Scroll Down</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="selection selection-2">
                <div class="discr-con">
                  <h2 class="tit icon-3">中国游艇会品牌运营领航者</h2>
                  <p class="discr"><strong>提供多元化的游艇服务项目：</strong>游艇租赁观光、高端商务接待、海岛游，海钓，游艇婚礼，游艇派对等。</p>
                </div>
                <div class="section-row">
                  <div class="section-col col-bg1">
                    <div class="card-bg">
                    </div>
                    <div class="card-content">
                      <img alt="" class="card-img" src="../assets/11.svg">
                      <p class="title">简易预定步骤</p>
                      <p class="text1">说明清晰，预定步骤简易及多元化船只选择。</p>
                    </div>
                  </div>
                  <div class="section-col col-bg2">
                    <div class="card-bg" style="border-color: #fff;">
                    </div>
                    <div class="card-content">
                      <img alt="" class="card-img" src="../assets/12.svg">
                      <p class="title">多种优惠<br/>透明收费架构</p>
                      <p class="text1">所有收费及船只详情清楚表明，还有定期推出独家限时优惠。</p>
                    </div>
                  </div>
                  <div class="section-col col-bg3">
                    <div class="card-bg">
                    </div>
                    <div class="card-content">
                      <img alt="" class="card-img" src="../assets/13.svg">
                      <p class="title">最新及多元化的<br/>船只选择</p>
                      <p class="text1">不同类别的租船服务：游艇、活动船、帆船、快艇等。</p>
                    </div>
                  </div>
                  <div class="section-col col-bg4">
                    <div class="card-bg" style="border-color: #fff;">
                    </div>
                    <div class="card-content">
                      <img alt="" class="card-img" src="../assets/14.svg">
                      <p class="title">专属客服为您<br/>解答预定问题</p>
                      <p class="text1">官方服务热线：400-931-898</p>
                    </div>
                  </div>
                  <div class="section-col col-bg5">
                    <div class="card-bg">
                    </div>
                    <div class="card-content">
                      <img alt="" class="card-img" src="../assets/15.svg">
                      <p class="title">一条龙服务</p>
                      <p class="text1">提供租船、餐饮、个人化套餐如：DJ、鸡尾酒、婚礼、商务会议等。</p>
                    </div>
                  </div>
                </div>
                <!-- <div id="swiperList" class="swiper-container">
                  <div class="swiper-wrapper">
                    <div class="swiper-slide">
                      <div class="card-content col-bg1">
                        <img alt="" class="card-img" src="../assets/11.svg">
                        <p class="title">简易预定步骤</p>
                        <p class="text1">说明清晰，预定步骤简易及多元化船只选择</p>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="card-content col-bg2">
                        <img alt="" class="card-img" src="../assets/12.svg">
                        <p class="title">最新及多元化的<br/>船只选择</p>
                        <p class="text1">不同类别的租船服务：游艇、活动船、帆船、快艇等。</p>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="card-content col-bg3">
                        <img alt="" class="card-img" src="../assets/13.svg">
                        <p class="title">最新及多元化的<br/>船只选择</p>
                        <p class="text1">不同类别的租船服务：游艇、活动船、帆船、快艇等。</p>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="card-content col-bg4">
                        <img alt="" class="card-img" src="../assets/14.svg">
                        <p class="title">专属客服为您<br/>解答预定问题</p>
                        <p class="text1">官方服务热线：400-931-898</p>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="card-content col-bg5">
                        <img alt="" class="card-img" src="../assets/15.svg">
                        <p class="title">一条龙服务</p>
                        <p class="text1">提供租船、餐饮、个人化套餐如：DJ、鸡尾酒、婚礼、商务会议等。</p>
                      </div>
                    </div>
                  </div>
                  <div class="swiper-pagination"></div>
                </div> -->
              </div>
            </div>
            <div class="swiper-slide">
              <div class="selection selection-3">
                <h3 class="tit icon-3">产品模式</h3>
                <p class="discr">游艇种类</p>
                <div class="cont">
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/21.jpg">
                      </div>
                      <p class="title">豪华游艇</p>
                      <div class="list-bg"></div>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/22.jpg">
                      </div>
                      <p class="title">西式游艇</p>
                      <div class="list-bg"></div>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/23.jpg">
                      </div>
                      <p class="title">游艇</p>
                      <div class="list-bg"></div>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/24.jpg">
                      </div>
                      <p class="title">帆船</p>
                      <div class="list-bg"></div>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/25.jpg">
                      </div>
                      <p class="title">大型活动船</p>
                      <div class="list-bg"></div>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/26.jpg">
                      </div>
                      <p class="title">快艇</p>
                      <div class="list-bg"></div>
                    </div>
                  </div>
                </div>
                <!-- <div id="swiperList02" class="swiper-container">
                  <div class="swiper-wrapper">
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/21.jpg">
                        </div>
                        <p class="title">豪华游艇</p>
                        <div class="list-bg"></div>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/22.jpg">
                        </div>
                        <p class="title">西式游艇</p>
                        <div class="list-bg"></div>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/23.jpg">
                        </div>
                        <p class="title">游艇</p>
                        <div class="list-bg"></div>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/24.jpg">
                        </div>
                        <p class="title">帆船</p>
                        <div class="list-bg"></div>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/25.jpg">
                        </div>
                        <p class="title">大型活动船</p>
                        <div class="list-bg"></div>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/26.jpg">
                        </div>
                        <p class="title">快艇</p>
                        <div class="list-bg"></div>
                      </div>
                    </div>
                  </div>
                  <div class="swiper-pagination"></div>
                </div> -->
              </div>
            </div>
            <div class="swiper-slide">
              <div class="selection selection-4">
                <h3 class="tit icon-3">市场需求</h3>
                <p class="discr">热门品牌</p>
                <div class="cont">
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/27.jpg">
                      </div>
                      <p class="title">阿兹慕/Azimut</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/28.jpg">
                      </div>
                      <p class="title">法拉帝/Ferretti</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/29.jpg">
                      </div>
                      <p class="title">圣斯克/Sunseeker</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/30.jpg">
                      </div>
                      <p class="title">丽娃/Riva</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/31.jpg">
                      </div>
                      <p class="title">公主游艇／Princess</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/32.jpg">
                      </div>
                      <p class="title">博纳多/Beneteau</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/33.jpg">
                      </div>
                      <p class="title">卡兰奇/Cranchi</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/34.jpg">
                      </div>
                      <p class="title">拉尔森/Larson</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/35.jpg">
                      </div>
                      <p class="title">Blohm+Voss</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/36.jpg">
                      </div>
                      <p class="title">Marquis</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="selection selection-5">
                <video autoplay="" class="video2" loop="" src="../assets/video2.mp4"></video>
                <img class="video2_mob" src="../assets/video2.gif" alt="">
                <h3 class="tit icon-3">应用场景</h3>
                <p class="discr">多元化的游艇服务项目</p>
                <div class="cont">
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/38.jpg">
                      </div>
                      <p class="title">游艇租赁观光</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/39.jpg">
                      </div>
                      <p class="title">高端商务接待</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/40.jpg">
                      </div>
                      <p class="title">海岛游</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/41.jpg">
                      </div>
                      <p class="title">海钓</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/42.jpg">
                      </div>
                      <p class="title">游艇婚礼</p>
                    </div>
                  </div>
                  <div class="list-div">
                    <div class="cont-div">
                      <div class="cont-img-bg">
                        <img class="cont-img" src="../assets/43.jpg">
                      </div>
                      <p class="title">游艇派对</p>
                    </div>
                  </div>
                </div>
                <!-- <div id="swiperList03" class="swiper-container">
                  <div class="swiper-wrapper">
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/38.jpg">
                        </div>
                        <p class="title">游艇租赁观光</p>
                        </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/39.jpg">
                        </div>
                        <p class="title">高端商务接待</p>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/40.jpg">
                        </div>
                        <p class="title">海岛游</p>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/41.jpg">
                        </div>
                        <p class="title">海钓</p>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/42.jpg">
                        </div>
                        <p class="title">游艇婚礼</p>
                      </div>
                    </div>
                    <div class="swiper-slide">
                      <div class="cont-div">
                        <div class="cont-img-bg">
                          <img class="cont-img" src="../assets/43.jpg">
                        </div>
                        <p class="title">游艇派对</p>
                      </div>
                    </div>
                  </div>
                  <div class="swiper-pagination"></div>
                </div> -->
              </div>
            </div>
            <div class="swiper-slide">
              <div class="selection selection-6">
                <div class="selection-6-con">
                  <h3 class="tit icon-3">公司简介</h3>
                  <p class="discr">厦门携艇网络科技有限公司</p>
                  <div class="con">
                    <p>立足厦门，放眼全国。<br />
                      携艇在中国游艇市场获得跨越发展的同时，已于2012年迈向全国，逐步构建辐射全国的服务网络。
                    </p>
                    <p>携艇秉承“永续、稳健、规范”的经营理念，携艇目前已开发了全国多个沿海城市的游艇高端消费市场。未来，携艇将通过“点线面”的联盟化发展策略，分阶段、分区域地拓展全国版图，真正成为中国游艇行业联盟服务提供商。</p>
                    <p>公司服务于崇尚自然，乐于共享、富有实力的高端客户，倡导领先的管理理念，采用创新的以携艇网络平台、携艇VIP会所联盟、会员人脉网为平台的三网合一的经营模式，为客户提供最尊贵、最体贴、最优惠的服务。</p>
                    <p>
                      目前，携艇会在全国主要游艇港拥有多家合作会所，可以在全国范围内为VIP客户提供多元化的游艇服务项目：游艇租赁观光、高端商务接待、海岛游，海钓，游艇婚礼，游艇派对等。</p>
                    <img class="discr-img" src="../assets/40.png" alt="">
                  </div>
                </div>
                <app-footer></app-footer>  
              </div>
            </div>
        </div>
    </div>
    <div class="home_mob">
      <div class="selection selection-1">
        <div class="video1_mob"></div>
        <div class="roll"></div>
        <div class="cont">
          <h2 class="text1">启航黄金之旅，</h2>
          <h2 class="text1">尊享快意人生！</h2>
          <p>专业的俱乐部运营<br/>
            细微入至的管家式服务<br/>
            让您在享受游艇服务的同时，收获尊贵与财富
          </p>
          <button class="down-btn" @click="downSlider">
            <i class="icon-Group-47"></i>
          </button>
          <div class="qr-code">
            <img src="../assets/8.png" alt="">
            <p>进入携艇商城<br/>了解更多游艇资讯</p>
          </div>
        </div>
      </div>
      <div class="selection selection-2">
        <div class="discr-con">
          <h2 class="tit icon-3">中国游艇会品牌运营领航者</h2>
          <p class="discr"><strong>提供多元化的游艇服务项目：</strong>游艇租赁观光、高端商务接待、海岛游，海钓，游艇婚礼，游艇派对等。</p>
        </div>
        <div id="swiperList" class="swiper-container">
          <div class="swiper-wrapper">
            <div class="swiper-slide">
              <div class="card-content col-bg1">
                <img alt="" class="card-img" src="../assets/11.svg">
                <p class="title">简易预定步骤</p>
                <p class="text1">说明清晰，预定步骤简易及多元化船只选择</p>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="card-content col-bg2">
                <img alt="" class="card-img" src="../assets/12.svg">
                <p class="title">最新及多元化的<br/>船只选择</p>
                <p class="text1">不同类别的租船服务：游艇、活动船、帆船、快艇等。</p>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="card-content col-bg3">
                <img alt="" class="card-img" src="../assets/13.svg">
                <p class="title">最新及多元化的<br/>船只选择</p>
                <p class="text1">不同类别的租船服务：游艇、活动船、帆船、快艇等。</p>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="card-content col-bg4">
                <img alt="" class="card-img" src="../assets/14.svg">
                <p class="title">专属客服为您<br/>解答预定问题</p>
                <p class="text1">官方服务热线：400-931-898</p>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="card-content col-bg5">
                <img alt="" class="card-img" src="../assets/15.svg">
                <p class="title">一条龙服务</p>
                <p class="text1">提供租船、餐饮、个人化套餐如：DJ、鸡尾酒、婚礼、商务会议等。</p>
              </div>
            </div>
          </div>
          <div class="swiper-pagination"></div>
        </div>
      </div>
      <div class="selection selection-3">
        <h3 class="tit icon-3">产品模式</h3>
        <p class="discr">游艇种类</p>
        <div id="swiperList02" class="swiper-container">
          <div class="swiper-wrapper">
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/21.jpg">
                </div>
                <p class="title">豪华游艇</p>
                <div class="list-bg"></div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/22.jpg">
                </div>
                <p class="title">西式游艇</p>
                <div class="list-bg"></div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/23.jpg">
                </div>
                <p class="title">游艇</p>
                <div class="list-bg"></div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/24.jpg">
                </div>
                <p class="title">帆船</p>
                <div class="list-bg"></div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/25.jpg">
                </div>
                <p class="title">大型活动船</p>
                <div class="list-bg"></div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/26.jpg">
                </div>
                <p class="title">快艇</p>
                <div class="list-bg"></div>
              </div>
            </div>
          </div>
          <div class="swiper-pagination"></div>
        </div>
      </div>
      <div class="selection selection-4">
        <h3 class="tit icon-3">市场需求</h3>
        <p class="discr">热门品牌</p>
        <div class="cont">
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/27.jpg">
              </div>
              <p class="title">阿兹慕/Azimut</p>
            </div>
          </div>
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/28.jpg">
              </div>
              <p class="title">法拉帝/Ferretti</p>
            </div>
          </div>
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/29.jpg">
              </div>
              <p class="title">圣斯克/Sunseeker</p>
            </div>
          </div>
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/30.jpg">
              </div>
              <p class="title">丽娃/Riva</p>
            </div>
          </div>
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/31.jpg">
              </div>
              <p class="title">公主游艇／Princess</p>
            </div>
          </div>
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/32.jpg">
              </div>
              <p class="title">博纳多/Beneteau</p>
            </div>
          </div>
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/33.jpg">
              </div>
              <p class="title">卡兰奇/Cranchi</p>
            </div>
          </div>
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/34.jpg">
              </div>
              <p class="title">拉尔森/Larson</p>
            </div>
          </div>
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/35.jpg">
              </div>
              <p class="title">Blohm+Voss</p>
            </div>
          </div>
          <div class="list-div">
            <div class="cont-div">
              <div class="cont-img-bg">
                <img class="cont-img" src="../assets/36.jpg">
              </div>
              <p class="title">Marquis</p>
            </div>
          </div>
        </div>
      </div>
      <div class="selection selection-5">
        <img class="video2_mob" src="../assets/video2.gif" alt="">
        <h3 class="tit icon-3">应用场景</h3>
        <p class="discr">多元化的游艇服务项目</p>
        <div id="swiperList03" class="swiper-container">
          <div class="swiper-wrapper">
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/38.jpg">
                </div>
                <p class="title">游艇租赁观光</p>
                </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/39.jpg">
                </div>
                <p class="title">高端商务接待</p>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/40.jpg">
                </div>
                <p class="title">海岛游</p>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/41.jpg">
                </div>
                <p class="title">海钓</p>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/42.jpg">
                </div>
                <p class="title">游艇婚礼</p>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="cont-div">
                <div class="cont-img-bg">
                  <img class="cont-img" src="../assets/43.jpg">
                </div>
                <p class="title">游艇派对</p>
              </div>
            </div>
          </div>
          <div class="swiper-pagination"></div>
        </div>
      </div>
      <div class="selection selection-6">
        <div class="selection-6-con">
          <h3 class="tit icon-3">公司简介</h3>
          <p class="discr">厦门携艇网络科技有限公司</p>
          <div class="con">
            <p>立足厦门，放眼全国。<br />
              携艇在中国游艇市场获得跨越发展的同时，已于2012年迈向全国，逐步构建辐射全国的服务网络。
            </p>
            <p>携艇秉承“永续、稳健、规范”的经营理念，携艇目前已开发了全国多个沿海城市的游艇高端消费市场。未来，携艇将通过“点线面”的联盟化发展策略，分阶段、分区域地拓展全国版图，真正成为中国游艇行业联盟服务提供商。</p>
            <p>公司服务于崇尚自然，乐于共享、富有实力的高端客户，倡导领先的管理理念，采用创新的以携艇网络平台、携艇VIP会所联盟、会员人脉网为平台的三网合一的经营模式，为客户提供最尊贵、最体贴、最优惠的服务。</p>
            <p>
              目前，携艇会在全国主要游艇港拥有多家合作会所，可以在全国范围内为VIP客户提供多元化的游艇服务项目：游艇租赁观光、高端商务接待、海岛游，海钓，游艇婚礼，游艇派对等。</p>
            <img class="discr-img" src="../assets/40.png" alt="">
          </div>
        </div>
        <app-footer></app-footer>  
      </div>
    </div>
  </div>
</template>

<script>
import '../font/style.css'
import Header from './Header'
import Footer from './Footer'
let storage = window.sessionStorage;

export default {
  name: 'Home',
  data () {
    return {
      show: false
    }
  },
  created() {

  },
  mounted() {
    let swiperCon = new Swiper('#swiperCon', {
      direction: 'vertical',
      slidesPerView: 1,
      spaceBetween: 300,
      mousewheelControl: true,
      paginationClickable: true,
      nextButton:'#swiperCon .down-btn, #swiperCon .scroll-down'
    });
    document.querySelector('.nav-li-top').onclick = function() {
      swiperCon.slideTo(0, 1000, false);
    };

    let swiperList = new Swiper('#swiperList, #swiperList02, #swiperList03', {
      slidesPerView: 1,
      spaceBetween: 300,
      mousewheelControl: true,
      paginationClickable: true,
      pagination:'.swiper-pagination',  
    });
  },
  methods: {
    downSlider() {
      let downHeight = document.documentElement.clientHeight;
      window.scrollTo(0, downHeight);
    }
  },
  components: {
    'app-header': Header,
    'app-footer': Footer,
  }
}
</script>

<style scoped>
  .home_mob {
    display: none;
  }

  /*视频播放*/
  .video1, .video2, .video1_mob, .video2_mob {
    position: relative;
    z-index: -1;
    width: 100%;
    height: 100%;
    -o-object-fit: fill;
    object-fit: fill;
  }
  .video1_mob, .video2_mob {
    display: none;
  }

  /*波浪背景*/
  .roll {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 16.85vh;
    background: url('../assets/9.png') center center no-repeat;
    background-size: 100% 100%;
    z-index: 11;
  }
  
  /*selection-1*/
  .selection-1 {
    position: relative;
    background-color: rgba(0, 0, 0, 0.7);
  }
  .selection-1 .cont {
    position: absolute;
    top: 18.43vh;
    left: 0;
    width: 89.32vw;
    height: 81.67vh;
    margin: 0 5.35vw;
    padding-top: 10vh;
    padding-left: 6.35vw;
    background: url('../assets/10.png') center center no-repeat;
    background-size: cover;
  }
  .selection-1 .cont .text1 {
    font-size: 3.39vw;
    color: #FFFFFF;
    font-weight: 700;
  }
  .selection-1 .cont p {
    margin-top: 5.28vh;
    color: #FFFFFF;
    line-height: 2.55vw;
    font-size: 1.3vw;
  }
  /*二维码*/
  .selection-1 .qr-code {
    position: absolute;
    right: 8.28vw;
    bottom: 3.89vh;
    z-index: 15;
  }
  .selection-1 .qr-code img {
    display: block;
    width: 9.52vw;
    margin: 0 auto;
  }
  .selection-1 .qr-code p {
    margin-top: 1.57vh;
    color: #FFFFFF;
    text-align: center;
    line-height: 1.46vw;
    font-size: 1.04vw;
  }
  .selection-1 .qr-code .scroll-down {
    margin-top: 15.3vh;
    color: #FFFFFF;
    font-size: 1.3vw;
    z-index: 20;
    cursor: pointer;
  }
  
  /*selection-2*/
  .selection-2 {
    overflow: hidden;
    width: 100%;
    height: 100%;
    color: #fff;
    text-align: center;
    position: relative;  
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
    background: url('../assets/16.jpg') center no-repeat padding-box;
    background-size: cover;
  }
  .selection-2 .section-row .col-bg2 {
    background: url('../assets/17.jpg') center no-repeat padding-box;
    background-size: cover;
  }
  .selection-2 .section-row .col-bg3 {
    background: url('../assets/18.jpg') center no-repeat padding-box;
    background-size: cover;
  }
  .selection-2 .section-row .col-bg4 {
    background: url('../assets/19.jpg') center no-repeat padding-box;
    background-size: cover;
  }
  .selection-2 .section-row .col-bg5 {
    background: url('../assets/20.jpg') center no-repeat padding-box;
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
    top: -88vw;
    left: -94vw;
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
    top: 14.2vw;
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
    width: 4vw;
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
    font-size: 1vw;
    line-height: 1.6vw;
    margin: auto;
    padding-top: 2.41vh;
    width: 100%;
    text-align: center;
    color: #fff;
    opacity: 0;
    -webkit-transition: all .6s;
    transition: all .6s;
  }
  .selection-2 .section-row .section-col:hover .text1 {
    opacity: 1;
    -webkit-transition: all .6s;
    transition: all .6s;
  }

  
  /*selection-3*/
  .selection-3 {
    position: relative;
    background: #46B5D8;
  }
  .selection-3 .tit {
    padding-top: 11.39vh;
  }
  .selection-3 .tit:after {
    color: #fff;
  }
  .selection-3 .cont {
    width: 80%;
    margin: 0 auto;
    padding-top: 3.33vw;
    text-align: center;
  }
  .selection-3 .cont .list-div { 
    display: inline-block;
    position: relative;   
  }
  .selection-3 .cont .list-div .cont-div {
    position: relative;
    z-index: 15;
  }
  .selection-3 .cont .list-div .cont-img {
    display: block;
    width: 24.11vw; 
    -webkit-transition: all 1s;
    transition: all 1s;
  }
  .selection-3 .cont .list-div .title {
      position: absolute;
      top: 45%;
      left: 0;
      width: 100%;
      color: #fff;
      font-size: 1.3vw;
      z-index: 100;
          
  }
  .selection-3 .cont .list-div .list-bg {
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.65);
    z-index: 15;
  }
  .selection-3 .cont .list-div:hover .list-bg {
    opacity: 0;
  }
  .selection-3 .cont .list-div:hover .title {
    opacity: 0;
  }
  .selection-3 .cont .list-div .cont-img-bg {
    width: 24.11vw;
    padding: 0;
    overflow: hidden;
    cursor: pointer;
    position: relative;
  }
  .selection-3 .cont .list-div:hover .cont-img {
    -webkit-transform: scale(1.5);
    transform: scale(1.5);
  }

  /*selection-4*/
  .selection-4 {
    position: relative;
    background: url('../assets/37.jpg') center center no-repeat;
    background-size: cover;
  }
  .selection-4 .cont {
    width: 73vw;
    margin: 8.25vw auto;
    text-align: center;
  }
  .selection-4 .cont .list-div { 
    display: inline-block;    
    margin: 0 1.9vw 5vh 1.9vw;
  }
  .selection-4 .cont .list-div .cont-div {
    position: relative;
    cursor: pointer;
    z-index: 15;
  }
  .selection-4 .cont .list-div .cont-img {
    height: 100%;
    margin: 0 auto 0;
    background: none;
  }
  .selection-4 .cont .list-div .cont-img-bg {
    width: 9.9vw;
    height:3.7vw;
    margin: 0 auto;
    border-radius: 50%;
    -webkit-transition: all 0.8s;
    transition: all 0.4s;
  }
  .selection-4 .cont .list-div:hover .cont-img-bg {
    box-shadow: 5px 0px 30px 0px rgba(0, 0, 0, 0.8);
    -webkit-transform: scale(1.2) translateY(-5px);
    transform: scale(1.2) translateY(-5px);
    -webkit-transition: all 0.8s;
    transition: all 0.4s;
  }
  .selection-4 .cont .list-div .cont-img {
    width: 100%;
  }
  .selection-4 .cont .list-div .title {  
    white-space: nowrap;
    text-overflow: ellipsis; 
    overflow: hidden;
    width: 10vw;  
    height: 2.5vw;
    color: #FFFFFF;
    line-height: 2.5vw;
    font-size: 1.04vw;
    -webkit-transition: all 0.8s;
    transition: all 0.4s;
  }
  .selection-4 .cont .list-div:hover .title {
    -webkit-transform: scale(1.2);
    transform: scale(1.2);
    -webkit-transition: all 0.8s;
    transition: all 0.4s;
  }
  .selection-4 .tit {
    padding-top: 17.04vh;
  }  
  
  /*selection-5*/
  .selection-5 {
    position: relative;
    background-color: rgba(22, 21, 25, 0.75);
  }
  .selection-5 .tit {
    position: absolute;
    top: 13.7vh;
    left: 0;
    padding-top: 0;
  }
  .selection-5 .discr {
    position: absolute;
    top: 25.26vh;
    left: 0;
    padding-top: 0;
  }
  .selection-5 .cont {
    position: absolute;
    top: 42.96vh;
    left: 0;
    padding: 0 10.13vw;
    text-align: center;
  }
  .selection-5 .cont .list-div { 
    display: inline-block;    
    margin: 0 0.26vw;
    transition: all 0.4s;
  }
  .selection-5 .cont .list-div:hover {
    box-shadow: 5px 0px 5px 0px rgba(0, 0, 0, 0.3);
    -webkit-transform: scale(1.05) translateY(-5px);
    transform: scale(1.05) translateY(-5px);
    -webkit-transition: all 0.8s;
    transition: all 0.4s;
  }
  .selection-5 .cont .list-div .cont-div {
    position: relative;
    background: #161519;
    z-index: 15;
  }
  .selection-5 .cont .list-div .cont-img {
    height: 100%;
    margin: 0 auto 0;
    background: none;
  }
  .selection-5 .cont .list-div .cont-img-bg {
    width: 11.82vw;
    border-radius: 50%;
  }
  .selection-5 .cont .list-div .cont-img {
    width: 100%;
  }
  .selection-5 .cont .list-div .title {    
    margin: 0;
    color: #FFFFFF;
    line-height: 2.88vw;
    font-size: 1.3vw;
  }
  
  /*selection-6*/
  .selection-6 {
    background-color: #16151b;
  }
  .selection-6-con {
    border-bottom: 0.1vh solid rgba(88, 202, 237, 0.5);
    background: url('../assets/44.jpg') top no-repeat;
    background-size: 240% 100%;
  }
  .selection-6 .con {
    width: 60%;
    margin: 2.78vh auto 10.59vh;
  }
  .selection-6 .con p {
    text-align: center;
    color: #BBBBBB;
    line-height: 1.79vw;
    font-size: 1.04vw;
  }
  .selection-6 .tit {
    padding-top: 11.91vh;
  }
  .selection-6 .discr-img {
    display: block;
    width: 33.18vw;
    margin: 2.59vh auto 0;
  }
  #swiperList, #swiperList02, #swiperList03  {
    display: none;
  }
  
  @media screen and (max-width: 750px) {
    #swiperCon {
      display: none;
    }
    .home_mob {
      display: block;
      width: 100vw;
    }
    .video1_mob, .video2_mob {
      display: block;
    }
    .video1, .video2 {
      display: none;
    }
    .video1_mob {
      width: 100%;
      height: 100%;
      background: url('../assets/video1.gif') center center no-repeat;
      background-size: 240% auto;
    }
    .down-btn {
      left: 6.35vw;
      bottom: 15vh;
      width: 9.4vw;
      height: 9.4vw;
    }
    .down-btn i {
      font-size: 4.35vw;
    }
    .selection-1 {
      height: 100vh;
    }
    .selection-1 .cont .text1 {
      font-size: 7.39vw;
    }
    .selection-1 .cont p {
      line-height: 6.55vw;
      font-size: 3.6vw;
    }
    .selection-1 .qr-code {
        bottom: 4.89vh;
    }
    .selection-1 .qr-code p {
      line-height: 4.55vw;
      font-size: 3vw;
    }
    .selection-1 .qr-code img {
        width: 32.52vw;
    }
    .selection-1 .qr-code .scroll-down {
        display: none;
    }
    .sider-nav {
      display: none;
    }
    .roll {
      background: url(../assets/09.png) center center no-repeat;
      background-size: 100% 100%;
    }
    .selection-2 {
      height: 100vh;
      background-color: #F5F7F7;
    }
    .selection-2 .discr-con {
      width: 68%;
      margin: 0 auto;
      padding: 0;
      padding-top: 11vh;
      background-color: #F5F7F7;
    }
    .selection-2 .discr-con .tit {
      padding-top: 7.04vh;
      font-size: 4.82vw;
    }
    .selection-2 .discr-con .discr {
      padding-top: 5.48vh;
      padding-bottom: 2.65vh;
      font-size: 3.3vw;
    }
    .selection-2 .discr-con:after {
      display: none;
    }
    .selection-2 .section-row {
      display: none;
    }
    #swiperList {
      display: block;
      height: 60vh;
    }
    .card-content {
      width: 68%;
      height: 88%;
      margin: 0 auto;
      padding: 6vh 8vw 14vh 8vw;
      -webkit-box-shadow: 2px 20px 20px rgba(0, 0, 0, .2);
      box-shadow: 2px 20px 20px rgba(0, 0, 0, .2);
    }
    .selection-2 .col-bg1 {
      background: url('../assets/16.jpg') center no-repeat padding-box;
      background-size: cover;
    }
    .selection-2 .col-bg2 {
      background: url('../assets/17.jpg') center no-repeat padding-box;
      background-size: cover;
    }
    .selection-2 .col-bg3 {
      background: url('../assets/18.jpg') center no-repeat padding-box;
      background-size: cover;
    }
    .selection-2 .col-bg4 {
      background: url('../assets/19.jpg') center no-repeat padding-box;
      background-size: cover;
    }
    .selection-2 .col-bg5 {
      background: url('../assets/20.jpg') center no-repeat padding-box;
      background-size: cover;
    }

    .selection-2 .card-content .card-img {
      width: 15vw;
      margin-top: 4vh;
    }
    .selection-2 .card-content .title {
        padding-top: 5.09vh;
        color: #46b5d8;
        font-size: 4.3vw;
        font-weight: 600;
    }
    .selection-2 .card-content .text1 {
        text-align: justify;
        font-size: 3vw;
        line-height: 5.6vw;
        margin: auto;
        padding-top: 2.41vh;
        width: 100%;
        text-align: center;
        color: #fff;
    }
    .selection-3 {
      height: 100vh;
    }
    .selection-3 .cont {
      display: none;
    }
    .selection-3 .tit {
      /*padding-top: 22.2vh;*/
      padding-top: 14.39vh;
    }
    .selection-4 {
      height: 100vh;
    }
    .selection-4 .tit {
        /*padding-top: 24.04vh;*/
        padding-top: 12.04vh;
    }
    #swiperList02 {
      display: block;
      height: 61.8vh;
    }
    .selection-3 .cont-div {
      position: relative;
      width: 68%;
      margin: 0 auto 0;
      -webkit-box-shadow: 2px 20px 20px rgba(0, 0, 0, .2);
      box-shadow: 2px 20px 20px rgba(0, 0, 0, .2);
    }
    .selection-3 .discr {
      padding-bottom: 2.65vh;
    } 
    .selection-3 .cont-img-bg {
      width: 100%;
      height: 52.8vh;
      margin: 0 auto;
      padding: 0;
      overflow: hidden;
      cursor: pointer;
      position: relative;
    }
    .selection-3 .cont-img {
      display: block;
      width: 100%;
      height: 100%;
      -webkit-transition: all 1s;
      transition: all 1s;
    }
    .selection-3 .title {
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 8.88vw;
      color: #fff;
      text-align: center;
      line-height: 8.88vw;
      font-size: 3.3vw;
      z-index: 100;
    }
    .selection-3 .list-bg {
      position: absolute;
      left: 0;
      bottom:0;
      width: 100%;
      height: 8.88vw;
      background-color: rgba(0, 0, 0, 0.65);
      z-index: 15;
    }

    .selection-4 .cont {
      width: 78vw;
      margin: 3.25vh auto 0;
      text-align: center;
    }
    .selection-4 .cont .list-div .cont-img-bg {
      width: 26.9vw;
      height: 9.7vw;
    }
    .selection-4 .cont .list-div {
      display: inline-block;
      margin: 0 4.9vw 3vh 4.9vw;
    }
    .selection-4 .cont .list-div .title {
      width: 26.9vw;
      height: 5.5vw;
      color: #BBBBBB;
      line-height: 5.5vw;
      font-size: 2.8vw;
    }
    .selection-5 .cont {
      display: none;
    }
    #swiperList03 {
      display: block;
      position: absolute;
      top: 34.96vh;
      left: 0;
      height: 59vh;
      padding: 0 10.13vw;
      text-align: center;
    }
    .selection-5 {
      height: 100vh;
    }
    .selection-5 .tit {
      top: 16.7vh;
    }
    .selection-5 .discr {
      position: absolute;
      top: 26.26vh;      
      left: 0;
      padding-top: 0;
    }
    .selection-5 .cont-div {
      position: relative;
      width: 85%;
      height: 89.5%;
      margin: 0 auto;
      background: #161519;
      z-index: 15;
    }
    .selection-5 .cont-img {
      display: block;
      width: 100%;
      height: 100%;
      margin: 0 auto 0;
      background: none;
    }
    .selection-5 .cont-img-bg {
        width: 100%;
        height: 88%;
        border-radius: 50%;
    }
    .selection-5 .title {
      margin: 0;
      color: #FFFFFF;
      line-height: 8.88vw;
      font-size: 3.3vw;
    }
    
    .selection-6 .con {
      width: 80%;
    }

    .selection-6 .con p {
      line-height: 6vw;
      font-size: 3.4vw;
    }
    .selection-6 .discr-img {
      display: block;
      width: 80.18vw;
      margin: 2.59vh auto 0;
    }

  }
  @media screen and (min-width: 751px) {
    .home {
      width: 100vw;
      height: 100vh;
    }
  }
  
</style>
