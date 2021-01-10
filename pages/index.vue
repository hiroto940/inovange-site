<template>
  <div>
    <div class="mx-auto" style="width: 200px;">
      <canvas class="my-4 w-100" id="myChartc" width="900" height="400"></canvas>
    </div>
    <div>
      <Logo/>
      <canvas class="my-4 w-100" id="myChartb" width="900" height="50"></canvas>
     <center>
       <a href="https://5fd0a3954d85ffe9dc6c6956--relaxed-snyder-bc4367.netlify.app/inovange-site-origin/" class="btn-circle-border-simple">about</a>
      <a href="https://5fd0a3954d85ffe9dc6c6956--relaxed-snyder-bc4367.netlify.app/inovange-site-member/" class="btn-circle-border-simple">members</a>
      <a href="https://5fd0a3954d85ffe9dc6c6956--relaxed-snyder-bc4367.netlify.app/inovange-site-portforio/" class="btn-circle-border-simple">works</a>
     </center>
    </div>
  </div>
</template>
<script>
import Logo from '@/components/Logo'

export default {
  components: { Logo }
}
</script>
<style>
.btn-circle-border-simple {
  display: inline-block;
  text-decoration: none;
  color: #8B0000;
  width: 150px;
  height: 150px;
  line-height: 150px;
  border-radius: 50%;
  border: solid 2px #8B0000;
  text-align: center;
  overflow: hidden;
  font-weight: bolder;
  transition: .4s;
  margin: 10px;
  font-family: "HoloLens MDL2 Assets";
  opacity: 0.7;
}

.btn-circle-border-simple:hover {
  background: #8B0000;
  text-shadow:
    0 0 10px rgba(255,255,255, 1),
    0 0 50px rgba(255, 255, 255, .8),
    0 0 75px rgba(255, 255, 255, .6),
    0 0 76px rgba(255, 255, 255, .4),
    0 0 77px rgba(255, 255, 255, .5),
    0 0 78px rgba(255, 255, 255, .4),
    0 0 79px rgba(255, 255, 255, .3),
    0 0 80px rgba(255, 255, 255, .2),
    0 0 85px rgba(255, 255, 255, .1);

}

</style>
