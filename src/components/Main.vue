<template>
  <div class="main">
    <div class="hk-hero uk-margin-bottom">
      Navigation
    </div>
    <div class="uk-container uk-container-center">
      <div class="uk-grid uk-grid-collapse uk-margin-bottom">
        <div class="uk-width-1-5 hk-panel-line">
          <div class="hk-item uk-margin-top">
            <a href="#">
              <div class="item-img"><i class="uk-icon-building"></i></div>
              <div class="item-txt">
                <h4>시설</h4>
                <p>시설 조달청계약요청 현황</p>
              </div>
            </a>
          </div>
        </div>
        <div class="uk-width-1-5 hk-panel-line">
          <div class="hk-item uk-margin-top">
            <a href="">
              <div class="item-img"><i class="uk-icon-cog"></i></div>
              <div class="item-txt">
                <h4>용역</h4>
                <p>용역 조달청계약요청 현황</p>
              </div>
            </a>
          </div>
        </div>
        <div class="uk-width-1-5 hk-panel-line">
          <div class="hk-item uk-margin-top">
            <a href="#">
              <div class="item-img"><i class="uk-icon-inbox"></i></div>
              <div class="item-txt">
                <h4>물품</h4>
                <p>물품 조달청계약요청 현황</p>
              </div>
            </a>
          </div>
        </div>
        <div class="uk-width-1-5 hk-panel-line">
          <div class="hk-item uk-margin-top">
            <a href="#">
              <div class="item-img"><i class="uk-icon-location-arrow"></i></div>
              <div class="item-txt">
                <h4>규격</h4>
                <p>규격 조달청계약요청 현황</p>
              </div>
            </a>
          </div>
        </div>
        <div class="uk-width-1-5">
          <div class="hk-item uk-margin-top">
            <a href="#">
              <div class="item-img"><i class="uk-icon-pie-chart"></i></div>
              <div class="item-txt">
                <h4>발주계획현황</h4>
                <p>발주계획 목록</p>
              </div>
            </a>
          </div>
        </div>
      </div>
      <div class="community uk-margin-bottom">
        <div class="hk-main-head">
          <h1>커뮤니티 및 지원센터</h1>
        </div>

      </div>
    </div>
  </div>
</template>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
// *------------
// * Color Settings
// *------------
$text-default:#4a4a4a;
$text-default-darken:darken($text-default, 10%);
$text-gray:#9b9b9b;
$head-line:#e5e5e5;

.main {
  // .uk-grid-divider > * {padding-right: 0px;}
}
.hk-panel-line {border-right: 1px solid #ddd;height:90px;}

.hk-item {
  padding: 0 20px;
  line-height: 56px;
  a {line-height: 56px;height: 56px;color:$text-default;}
  :hover{color: $text-default-darken;}
  .item-img {
    float: left;
    margin-right: 20px;
    font-size:56px;
    width:56px;height:56px;
  }
  .item-txt{
    h4 {margin:8px 0 7px 0;line-height: 16px;}
    p{font-size:12px;line-height: 14px;margin-top: 10px;color:$text-gray}
  }
}

.hk-main-head {
  position: relative;
  border-bottom: 1px solid $head-line;margin-bottom: 70px;height:20px;
  h1 {position: absolute;font-size: 30px;width:320px;left:50%;background: white;text-align: center;margin-left: -160px;}
}
</style>
