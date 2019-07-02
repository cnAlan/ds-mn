<template>
  <b-container class="theme-container video-container">
    <b-row>
      <b-col class="box"  @click="$bvModal.show('bv-modal-example')">
        <img src="/images/a.jpeg" alt="videoA">
        <div class="play-icon">
          <img src="/images/play.png" alt="icon">
        </div>
        <p>视频教学A</p>
      </b-col>
      <b-col class="box"  @click="$bvModal.show('bv-modal-example')">
        <img src="/images/a.jpeg" alt="videoA">
        <div class="play-icon">
          <img src="/images/play.png" alt="icon">
        </div>
        <p>视频教学B</p>
      </b-col>
    </b-row>
    <b-row class="mt-3">
      <b-col class="box"  @click="$bvModal.show('bv-modal-example')">
        <img src="/images/a.jpeg" alt="videoA">
        <div class="play-icon">
          <img src="/images/play.png" alt="icon">
        </div>
        <p>视频教学C</p>
      </b-col>
      <b-col class="box"  @click="$bvModal.show('bv-modal-example')">
        <img src="/images/a.jpeg" alt="videoA">
        <div class="play-icon">
          <img src="/images/play.png" alt="icon">
        </div>
        <p>视频教学D</p>
      </b-col>
    </b-row>
    <b-modal id="bv-modal-example" hide-footer>
      <template slot="modal-title">
        视频播放
      </template>
      <div class="d-block text-center">
        <video src="http://www.w3school.com.cn/i/movie.ogg" controls></video>
      </div>
      <b-button class="mt-3" block @click="$bvModal.hide('bv-modal-example')">关闭</b-button>
    </b-modal>
  </b-container>
</template>
<script>
export default {
  mounted() {
    this.$store.commit('setNavigate', 'video');
  }
}
</script>
<style scoped>
img {
  width: 100%;
}
.play-icon {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  padding-left: 15px;
  padding-right: 15px;
  background: rgba(255, 255, 255, .4);
  text-align: center;
}
.play-icon img {
  width: 25%;
  margin-top: 20%;
}
.box {
  position: relative;
}
.video-container {
  display: block;
}
</style>

