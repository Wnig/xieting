<template>
	<footer class="clearfix">
    <div class="footer_pc">
      <div class="left">
        <h3>厦门携艇网络科技有限公司</h3>
        <p class="addr"><span>地址：厦门市思明区观音山商务运营中心9号楼21层</span><span class="span_last">联系电话：0592-5911328</span></p>
        <p class="addr"><span>负责人微信：johncai8888</span><span>传真：0592-5912328</span><span class="span_last">邮箱：yacht58@163.com</span></p>
      </div>
      <i class="bor"></i>
      <div class="right">
        <h4>游艇预订及会员服务热线：</h4>
        <p class="hot"><i class="icon-41"></i>4008-931-898 </p>
      </div>
    </div>
    <div class="footer_mob">
      <h3>厦门携艇网络科技有限公司</h3>
      <p class="addr"><span>地址：厦门市思明区观音山商务运营中心9号楼21层</span><span class="span_last">联系电话：0592-5911328</span><span>负责人微信：johncai8888</span></p>
      <p class="addr"><span>传真：0592-5912328</span><span class="span_last">邮箱：yacht58@163.com</span></p>
      <h4>游艇预订及会员服务热线：</h4>
      <p class="hot"><i class="icon-41"></i>4008-931-898 </p>
    </div>
  </footer>
</template>

<script>
import '../font/style.css'

export default {
  name: 'app-footer',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
  /*底部*/
  footer {
    width: 75%;
    margin: 0 auto;
    padding: 6.67vh 0;
    background-color: #16151b;
  }
  footer h3 {
    margin-bottom: 1.2vh;
    color: #A9A9A9;
    text-align: left;
    font-size: 1.56vw;
  }
  footer p {
    color: #9E9898;
    line-height: 1.61vw; 
    font-size: 1.04vw;
  }
  footer .left {
    float: left;
    padding-right: 4.43vw;
  }
  footer .right {
    float: left;
    padding-left: 4.43vw;
  }
  footer .addr span {
    display: inline-block;
    margin-right: 2vw;
  } 
  footer .addr .span_last {
    margin-right: 0;
  }
  footer .right h4 {
    color: #999999;
    text-align: left;
    line-height: 1.93vw;
    font-size: 1.3vw;
  }
  footer .right p {
    margin-top: 3.04vh;
    color: #999999;
    line-height: 1.93vw;
    font-size: 2.34vw;
    font-weight: 600;
  }
  footer .right p i {
    margin-right: 0.78vw;
    font-size: 2.19vw;
  }
  footer .bor {
    float: left;
    width: 0.08vw;
    height: 9.91vh;
    background-color: #4A4A4A;
  }
  .footer_mob {
      display: none;
  }
  @media screen and (max-width: 750px) {
    footer {
      width: 100%;
      padding: 5.67vh 0;
      background-color: #16151b;
    }
    footer .addr .span_last {
      margin-right: 2vw;
    }
    .footer_pc {
      display: none;
    }
    .footer_mob {
      display: block;
      text-align: center;
    }
    footer h4 {
      display: none;
      color: #999999;
      line-height: 4.93vw;
      font-size: 2.3vw;
      text-align: center;
    }
    footer h3 {
      text-align: center;
      font-size: 4.56vw;
    }
    footer p {
      line-height: 5.61vw;
      font-size: 3.04vw;
    }
    footer .hot {
      display: none;
      margin-top: 1.04vh;
      line-height: 2.93vw;
      font-size: 4.34vw;
    }
    footer p i {
        margin-right: 0.78vw;
        font-size: 4.19vw;
    }
  }
</style>