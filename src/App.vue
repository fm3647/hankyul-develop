<template>
  <header class="header">
      <div class="hk-toptool">
        <div class="uk-container uk-container-center">
          <nav class="uk-navbar">
              <ul class="uk-navbar-nav">
                <li><a href="#">로그인</a></li>
                <li><a href="#">회원가입</a></li>
              </ul>
              <div class="uk-navbar-flip">
                  <ul class="uk-navbar-nav">
                      <li><a href="">커뮤니티</a></li>
                      <li><a href="">고객센터</a></li>
                  </ul>
              </div>
          </nav>
        </div>
      </div>
      <div class="uk-navbar hk-navbar">
        <div class="uk-container uk-container-center">
          <a href="#" class="uk-navbar-brand logo"><img src="./assets/img/logo-w.svg" alt="logo"></a>
          <ul class="uk-navbar-nav">
            <li><a href="#">시설입찰</a></li>
            <li><a href="#">용역입찰</a></li>
            <li><a href="#">물품입찰</a></li>
            <li><a href="#">맞춤공고</a></li>
            <li><a href="#">내 서류함</a></li>
          </ul>
        </div>
      </div>
  </header>
  <Main></Main>
  <div class="hk-block-footer">
    <div class="uk-container uk-container-center">
      <div class="uk-grid">
        <div class="uk-width-1-4">
          <ul class="uk-nav">
            <li class="uk-nav-header">기본정보</li>
            <li><a href="#">회사소개</a></li>
            <li><a href="#">커뮤니티</a></li>
            <li><a href="#">고객센터</a></li>
          </ul>
        </div>
        <div class="uk-width-1-4">
          <ul class="uk-nav">
            <li class="uk-nav-header">입찰정보</li>
            <li><a href="#">시설입찰</a></li>
            <li><a href="#">용역입찰</a></li>
            <li><a href="#">물품입찰</a></li>
            <li><a href="#">맞춤정보</a></li>
            <li><a href="#">내 서류함</a></li>
          </ul>
        </div>
        <div class="uk-width-1-4">
          <ul class="uk-nav">
            <li class="uk-nav-header">기타</li>
            <li><a href="#">이용약관</a></li>
            <li><a href="#">개인정보취급방침</a></li>
            <li><a href="#">이메일무단수집거부</a></li>
          </ul>
        </div>
        <div class="uk-width-1-4">
          <div class="hk-block-contact">
            <h5>고객지원센터</h5>
            <p class="tel">02-2038-8178</p>
            <p class="fax">Fax : 02-2038-8179</p>
            <p class="txt">평일 : 오전 09:00 ~ 18:00<br/>토, 일, 공휴일은 쉽니다.</p>
          </div>
        </div>
        <div class="uk-width-1-1">
          <hr class="uk-grid-divider">
          <p class="link">
            <b>전자입찰</b>   나라장터(G2B)   국방종합전자조달   대한주택공사   KT(한국통신)   인천국제공항   한국마사회   한국도로공사   한국가스공사   한국전력공사   한국수력원자력(주)   한국전자통신연구원   한국수자원공사   포스코   한국철도공사   한국철도시설공단   한국석유공사 ,
            <b>건설협회</b>   건설교통부   대한건설협회   대한설비건설협회   대한전문건설협회   건설공제조합   전문건설공제조합   대한건축사협회   한국건설기술인협회   한국전기공사협회   한국정보통신공사협회   한국소방안전협회
          </p>
        </div>
      </div>
    </div>
  </div>
  <footer class="hk-footer">
    <div class="uk-container uk-container-center">
      <div class="f-logo">
        <img src="./assets/img/logo.svg" alt="" />
      </div>
      <div class="copyright">
        서울특별시 금천구 서부샛길 606 A동 2102-2호(가산동,대성디폴리스지식산업센터) | 대표전화 : 02-2038-8178 | 대표자 : 김충래<br/>
        사업자명 : 한결 ITS | 사업자번호 : 119-21-19832 | 통신판매신고 : 2013-서울금천-0026호 | webmaster@bidhk.co.kr<br/>
        <span>Copyright ⓒ 2013 <b>한결 ITS</b>. All Rights Reserved</span>
      </div>
    </div>
  </footer>
</template>

<script>
import Main from './components/Main'
export default {
  components: {
    Main
  }
}
</script>

<style lang="scss">
// *------------
// * Color Settings
// *------------
$color-blue:#339EE2 !default;
$color-blue-darken:darken($color-blue, 5%);//#1f93dc
$color-blue-darken-plus:darken($color-blue-darken, 5%);//#1c84c6
$color-white:white;
$color-gray:darken($color-white, 46.8%);
$color-gray-darken:darken($color-white, 80%);
$color-block:darken($color-white, 4%);
$color-footer:darken($color-white, 2.8%);
$text-default:#5b5b5b;
$text-gray:#9b9b9b;

// *------------
// * Default Style Start
// *------------
a,
.uk-tab > li > a {color:$color-gray-darken;}

a:hover,
.uk-tab > li:hover > a {
  color:$color-blue;
}

.uk-tab-left > li.uk-active > a,
.uk-tab-right > li.uk-active > a {
  border-color: transparent;
  background: transparent;
  color:$color-blue;
}

.uk-tab-left > li.uk-active > a {

}
.uk-tab-left > li:nth-child(n+2) > a,
.uk-tab-right > li:nth-child(n+2) > a {
  margin-top: 0;
}
.uk-tab {
  li {
    a:hover,a:focus,.uk-open > a{
      color:$color-blue;
      background: transparent;
      border-color: transparent;
    }
  }
  :hover,:focus,.uk-open,.uk-active {border-right:1px solid $color-blue;}
}

// * Header
.uk-container {min-width:1200px !important;}
.header {
  .hk-toptool {
    background: $color-blue-darken;
    color:$color-white;
    height:28px;line-height: 28px;
    .uk-navbar {background-color: $color-blue-darken;}
    .uk-navbar-nav {
      li {
        a {font-size: 12px;color:$color-white;line-height: 28px;height:28px; cursor: pointer;}
      }
      :hover,:focus,:active {background: $color-blue-darken-plus;}
    }
  }
  .hk-navbar{
    background: $color-blue;
    line-height: 62px;height:62px;
    .uk-navbar-nav {
      li {
        a {font-size: 16px;color:$color-white;line-height: 62px;height:62px;cursor: pointer;}
      }
      :hover,:focus,:active{background: $color-blue-darken;}
    }
  }
  .logo {
    width:148px;
    margin-right: 20px;
  }
}
.hero {height: 382px;background: url(./assets/img/main-intro.jpg) no-repeat;}

// * Footer Block
.hk-block-footer{
  background: $color-block;
  padding:60px 0 30px 0;
  .uk-nav {
    .uk-nav-header{color:$color-gray-darken;font-size:18px;font-weight: normal;padding-bottom: 20px;}
    a {
      color:$color-gray;font-size:14px;
    }
    a:hover {color:$color-blue;}
  }
  .hk-block-contact {
    h5 {font-size: 18px;}
    .tel {font-size:22px;color:$color-blue;margin-bottom: 0;}
    .fax {margin-top: 0;}
    .txt {color:$color-gray;font-size:14px;}
  }
  .link {
    font-size: 12px;color:$text-gray;
    b {color:$color-gray-darken;}
  }
}

// * Footer
.hk-footer {
  padding: 30px 0;
  background: $color-footer;
  .f-logo {
    margin-right: 20px;
    float: left;
    img {width:149px;}
  }
  .copyright{
    float: left;
    font-size: 12px;
    color:$text-gray;
    span {
      font-size: 9px;
      b {color:$text-default;}
    }
  }
}
</style>
