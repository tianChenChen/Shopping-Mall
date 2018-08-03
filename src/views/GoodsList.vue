<template>
  <div>
    <breadcrumb slot="bread"></breadcrumb>
    <div class="main">
      <div class="main_left">
        <ul>
          <p>分类</p>
          <li>产品1</li>
          <li>产品2</li>
        </ul>
      </div>
      <div class="main_rig">
        <ul>
          <li>
            <div class="main_rig_pro">
              <div class="img">
                <img src="@/assets/img/product-01.jpg"/>
              </div>
              <div class="main_rig_title">
                <h6>desingse chair</h6>
                <p>$799</p>
                <a href="javascript:;">discover</a>
                <a href="javascript:;">ADD TO CART</a>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
import 'assets/css/base.css'
import 'assets/css/goodlist.css'
import Breadcrumb from 'components/breadcrumb.vue'

export default {
  components: {
    Breadcrumb
  }
}
</script>

<style lang="css" scoped>
/* @import 'assets/css/base.css';
@import 'assets/css/goodlist.css'; */
</style>


