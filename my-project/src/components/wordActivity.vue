<template>
  <div class="container">
      <ul class="activity-list" id="example-1" >
        <!-- <li v-for="item in items" >
            <img :src="item.src">
            <span> {{item.message}} </span>
        </li> -->
        <li>dddd</li>
      </ul>
    </div>
</template>

<script>
export default {
  name: 'wordActivity',
  data () {
    return {
      items: [
        { src: 'http://upload.youzu.com/youzu/2018/0427/100817272.jpg', message: '标题最多15个字标题最多15个字' },
        { src: 'http://upload.youzu.com/youzu/2018/0427/100817272.jpg', message: '标题最多15个字标题最多15个字' },
        { src: 'http://upload.youzu.com/youzu/2018/0427/100817272.jpg', message: '标题最多15个字标题最多15个字' }
      ]
    }
  }
}
</script>
<style>
  .container {
    width: 7.5rem;
    margin: 0 auto;
  }
  .activity-list li{
    background: url(src/assets/activityBg.png) no-repeat;
    width: 5.83rem;
    height: 3.94rem;
    margin:0 auto;
  }
  .activity-list li img{
    width:5.5rem;
    height:2.7rem;
    display: block;
    margin:0 auto;
  }
  .activity-list li span{
    font-size:0.24rem;
    color:#921E07;
    font-weight:700;
    height:0.92rem;
    line-height:0.92rem;
    text-align: center;
  }
</style>

