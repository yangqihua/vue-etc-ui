<template>
  <div class="block">
    <etc-cell-group>
        <etc-cell-item>
            <span slot="left">支付方式</span>
            <span slot="right">微信</span>
        </etc-cell-item>
        <etc-cell-item arrow>
            <span slot="left">项目资料</span>
        </etc-cell-item>
        <etc-cell-item>
            <span slot="left">卡号：</span>
            <input slot="right" type="number" placeholder="请输入粤通卡卡号" />
        </etc-cell-item>
    </etc-cell-group>
    <etc-cell-group>
        <etc-cell-item>
            <etc-icon slot="icon" name="phone"></etc-icon>
            <input slot="right" type="number" placeholder="请输入手机号码" />
        </etc-cell-item>
        <etc-cell-item>
            <etc-icon slot="icon" name="codev"></etc-icon>
            <input slot="left" type="number" placeholder="输入验证码" />
            <div slot="right" style="width: 6rem;">
              <etc-button type="primary" slot="right" size="medium">发送验证码</etc-button>
            </div>
        </etc-cell-item>
        <etc-cell-item arrow type="a" href="tel:13719477521">
            <etc-icon slot="icon" name="tel"></etc-icon>
            <span slot="left">我的电话</span>
            <span slot="right">13719477521</span>
        </etc-cell-item>
        <etc-cell-item arrow type="link" href="#">
            <etc-icon slot="icon" name="location"></etc-icon>
            <span slot="left">我的地址</span>
            <span slot="right">修改地址</span>
        </etc-cell-item>
        <etc-cell-item arrow type="a">
            <img slot="icon" class="icon" src="../assets/logo.png" />
            <span slot="left">我的图标</span>
            <span slot="right">可自定义图标</span>
        </etc-cell-item>
    </etc-cell-group>
  </div>
</template>
<script>
export default {
  methods: {
    test() {
      alert("666")
    }
  }
}

</script>
<style lang="scss">


</style>
