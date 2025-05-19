<script setup lang="ts">
// 你可以根据实际情况引入图片
</script>

<template>
  <div class="donation-container">
    <div class="donation-header">
      <div>
        <!--        <b>最新网站存活</b>（勿在公开平台分享）：<a href="https://chat18.aichatos10.com/" target="_blank">https://chat18.aichatos10.com/</a> -->
        <b>最新网站存活</b>（勿在公开平台分享）：<a href="" target="_blank" />
      </div>
      <div class="donation-warning">
        二维码是自愿捐赠！请确保网站您能使用，并且用了很久觉得好再捐赠！网站完全免费，纯算不补贴，站长也会自费运营网站！网站成本平均一人一月大概3元，只要每月捐三元 网站就能活下去
      </div>
      <div class="donation-ps">
        PS: 所有捐赠将用于维护免费站点
      </div>
      <div class="donation-api">
        此处为公告：openai已不再赠送api免费5美元额度，但本站将持续提供，站长自费运营，请低调使用，勿在公开渠道传播，站长目前切换了api渠道，网站将持续运行！
      </div>
    </div>
    <div class="donation-qrcodes">
      <div class="qrcode-item">
        <div class="qrcode-title alipay">
          推荐使用支付宝
        </div>
        <img src="@/assets/alipay_qr.png" alt="支付宝二维码" class="qrcode-img">
      </div>
      <div class="qrcode-item">
        <div class="qrcode-title wechat">
          推荐使用微信支付
        </div>
        <img src="@/assets/wechat_qr.png" alt="微信二维码" class="qrcode-img">
      </div>
    </div>
  </div>
</template>

<style scoped>
.donation-container {
  max-width: 600px;
  margin: 40px auto;
  padding: 24px;
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 2px 8px #0001;
  text-align: center;
}
.donation-header {
  margin-bottom: 32px;
  font-size: 15px;
  color: #222;
}
.donation-warning {
  color: #d0021b;
  margin: 8px 0;
  font-weight: bold;
}
.donation-ps {
  color: #888;
  margin-bottom: 8px;
}
.donation-api {
  color: #e67e22;
  margin-bottom: 16px;
}
.donation-qrcodes {
  display: flex;
  justify-content: center;
  gap: 32px;
}
.qrcode-item {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.qrcode-title {
  font-weight: bold;
  margin-bottom: 8px;
  font-size: 16px;
}
.qrcode-title.alipay {
  color: #1677ff;
}
.qrcode-title.wechat {
  color: #1aad19;
}
.qrcode-img {
  width: 180px;
  height: 180px;
  border: 1px solid #eee;
  border-radius: 8px;
  background: #fafafa;
}
@media (max-width: 600px) {
  .donation-qrcodes {
    flex-direction: column;
    gap: 20px;
  }
}
</style>
