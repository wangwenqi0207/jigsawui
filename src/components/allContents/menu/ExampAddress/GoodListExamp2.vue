<template>
  <div>
    <div>
    <div class="orderCollectBox">
      <img src="../../../../../static/img/cards01.jpg" alt="">
      <div class="orderCollectBoxR">
        <h1>xxxxx外卖xxxxxx<img src="../../../../../static/img/cards01.jpg" alt=""></h1>
        <h2>
          <p>
            <i class="iconfont">&#xe622;</i>
            <i class="iconfont">&#xe622;</i>
            <i class="iconfont">&#xe622;</i>
            <i class="iconfont">&#xe622;</i>
            <i class="iconfont">&#xe622;</i>
          </p>
          人均：￥xx
        </h2>
        <h3>科技xxx路&nbsp;&nbsp;立xxxx技</h3>
      </div>
    </div>
  </div>
    <div>
      <div class="orderCollectBox">
        <img src="../../../../../static/img/cards01.jpg" alt="">
        <div class="orderCollectBoxR">
          <h1>xxxxx外卖xxxxxx<img src="../../../../../static/img/cards01.jpg" alt=""></h1>
          <h2>
            <p>
              <i class="iconfont">&#xe622;</i>
              <i class="iconfont">&#xe622;</i>
              <i class="iconfont">&#xe622;</i>
              <i class="iconfont">&#xe622;</i>
              <i class="iconfont">&#xe622;</i>
            </p>
            人均：￥xx
          </h2>
          <h3>科技xxx路&nbsp;&nbsp;立xxxx技</h3>
        </div>
      </div>
    </div>
    <div>
      <div class="orderCollectBox">
        <img src="../../../../../static/img/cards01.jpg" alt="">
        <div class="orderCollectBoxR">
          <h1>xxxxx外卖xxxxxx<img src="../../../../../static/img/cards01.jpg" alt=""></h1>
          <h2>
            <p>
              <i class="iconfont">&#xe622;</i>
              <i class="iconfont">&#xe622;</i>
              <i class="iconfont">&#xe622;</i>
              <i class="iconfont">&#xe622;</i>
              <i class="iconfont">&#xe622;</i>
            </p>
            人均：￥xx
          </h2>
          <h3>科技xxx路&nbsp;&nbsp;立xxxx技</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: "GoodListExamp2"
    }
</script>

<style scoped>
  .orderCollectBox{
    width: 40%;
    display: flex;
    border-top: .2rem solid #f7f7f7;
    padding: 1.4rem 0;
    background: #ffffff;
  }
  .orderCollectBox img{
    width:7.7rem;
    height: 5.8rem;
    margin: auto 0;
    margin-right: 1rem;
  }
  .orderCollectBoxR{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
  }
  .orderCollectBoxR h1{
    font-size:1.5rem ;
    font-weight:100 ;
    display: flex;
    align-items: center;
  }
  .orderCollectBoxR h1 img{
    width: 1.5rem;
    height: 1.5rem;
    margin-left:1rem;
  }
  .orderCollectBoxR h2{
    font-size:1.2rem ;
    font-weight:100 ;
    display: flex;
    align-items: center;
  }
  .orderCollectBoxR h2 p{
    font-size:1rem ;
    color: #ffc94f;
    margin-right: .5rem;
  }
  .orderCollectBoxR h3{
    font-size:1.2rem ;
    font-weight:100 ;
  }
</style>
