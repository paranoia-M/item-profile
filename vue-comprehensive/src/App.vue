<template>
  <div id="app">
    <div id="nav">
      <vue-particles
        color="#FFF"
        :particleOpacity="0.8"
        :particlesNumber="120"
        shapeType="star"
        :particleSize="8"
        linesColor="#FFF"
        :linesWidth="2"
        :lineLinked="false"
        :lineOpacity="0.6"
        :linesDistance="40"
        :moveSpeed="1"
        :hoverEffect="true"
        hoverMode="grab"
        :clickEffect="false"
        clickMode="push"
        class="lizi"
      />
    </div>
    <router-view />
    </div>
    
  </div>
</template>
<script>
export default {
  components: {},
}
</script>
<style lang="scss" scoped>
  body{
    width: 100%;
    
  }
  .lizi{
    position:fixed;
    top:0;
    width:100%;
     background: #f8c4c4;
     z-index: -1000;
  }
</style>
