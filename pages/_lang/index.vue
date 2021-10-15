<template>
  <div class="wrap">
    <div class="banner">
      <div class="top">
        <img src="~assets/img/newimg/mintology-logo@2x.png" alt="">
        <div class="linkBox">
          <div class="link">
            <a href="https://mintology.gitbook.io/faq/" target="_blank" v-if="isShow2" @mouseover="isShow2=!isShow2">FAQ</a>
            <a href="https://mintology.gitbook.io/faq/" target="_blank" v-if="!isShow2" @mouseleave="isShow2=!isShow2">FAQ</a>
            
          </div>
          <div class="link">
            <a href="https://forms.gle/ru4fic9yHJKT8d358" target="_blank" v-if="isShow1" @mouseover="isShow1=!isShow1">Listing Request</a>
            <img src="~assets/img/newimg/icon_arrow-right-up@2x.png" alt="" v-if="isShow1" @mouseover="isShow1=!isShow1">
            <a href="https://forms.gle/ru4fic9yHJKT8d358" target="_blank" v-if="!isShow1" @mouseleave="isShow1=!isShow1">Listing Request</a>
            <img src="~assets/img/newimg/hover.png" alt="" v-if="!isShow1" @mouseleave="isShow1=!isShow1">
            
          </div>
        </div>
        <div class="menu-icon" @click="toggle">
          <img v-if="!isShow" src="~/assets/img/newimg/menu-line@2x.png"/>
          <img v-else src="~/assets/img/newimg/close-fill@2x.png"/>
        </div>
        <div class="menu-list" v-if="isShow">
          <div class="link">
            <a href="https://mintology.gitbook.io/faq/" target="_blank" v-if="isShow2" @mouseover="isShow2=!isShow2">FAQ</a>
            <!-- <img src="~assets/img/newimg/icon_arrow-right-up@2x.png" alt="" v-if="isShow2" @mouseover="isShow2=!isShow2"> -->
            <a href="https://mintology.gitbook.io/faq/" target="_blank" v-if="!isShow2" @mouseleave="isShow2=!isShow2">FAQ</a>
            <!-- <img src="~assets/img/newimg/hover.png" alt="" v-if="!isShow2" @mouseleave="isShow2=!isShow2"> -->
            
          </div>
          <div class="link">
            <a href="https://forms.gle/ru4fic9yHJKT8d358" target="_blank" v-if="isShow1" @mouseover="isShow1=!isShow1">Listing Request</a>
            <img src="~assets/img/newimg/icon_arrow-right-up@2x.png" alt="" v-if="isShow1" @mouseover="isShow1=!isShow1">
            <a href="https://forms.gle/ru4fic9yHJKT8d358" target="_blank" v-if="!isShow1" @mouseleave="isShow1=!isShow1">Listing Request</a>
            <img src="~assets/img/newimg/hover.png" alt="" v-if="!isShow1" @mouseleave="isShow1=!isShow1">
            
          </div>
        </div>
      </div>
      <div class="center">
        <div class="left">
          <img src="~assets/img/newimg/text@2x.png" alt="">
            <div class="btndiv">
              <div class="btn">
                <a href="https://app.mintology.studio" target="_blank">Launch APP
                <img src="~assets/img/newimg/icon_right@2x.png" alt=""></a>
              </div>
              <!-- <div class="btn" id="appbtn" @mouseenter="enter()" @mouseleave="leave()" @click="enter()">Join Community </div>
              <img src="~assets/img/newimg/icon_right@2x.png" alt="" @mouseenter="enter()" @mouseleave="leave()" @click="enter()"> -->
              <!-- <div class="btn-soon" v-if="isShow2">Coming Soon</div> -->
            </div>
          <!-- </a> -->
        </div>
        <div class="right">
          <img src="~assets/img/newimg/jpg_head@2x.png" alt="">
          <!-- <img src="~assets/img/newimg/web-img.png" alt=""> -->
        </div>
      </div>
      <div class="footer">
      <div class="center">
        <div class="top">
          <div class="link">
            <a href="https://twitter.com/mintologystudio?s=11" target="_blank"><img src="~assets/img/newimg/icon_twitter@2x.png" alt="" ></a>
            <a href="https://discord.gg/4UgKKXXY2K" target="_blank"><img src="~assets/img/newimg/discord.png" alt=""></a>
          </div>
          <span>Email: hello@mintology.studio</span>
        </div>
        <div class="add">
          <a href="https://finance.yahoo.com/news/introducing-worlds-first-curated-nft-093400542.html" target="_blank"><img src="~assets/img/newimg/add1.png" alt="" ></a>
          <a href="https://seekingalpha.com/pr/18469030-introducing-worlds-first-curated-nft-launchpad" target="_blank"><img src="~assets/img/newimg/add2.png" alt=""></a>
          <a href="https://www.marketwatch.com/press-release/introducing-the-worlds-first-curated-nft-launchpad-2021-09-13" target="_blank"><img src="~assets/img/newimg/add3.png" alt=""></a>
          <a href="https://www.benzinga.com/pressreleases/21/09/n22903166/introducing-the-worlds-first-curated-nft-launchpad" target="_blank"><img src="~assets/img/newimg/add4.png" alt=""></a>
          <a href="https://beincrypto.com/introducing-the-worlds-first-curated-nft-launchpad/" target="_blank"><img src="~assets/img/newimg/add5.png" alt=""></a>
        </div>
        <div class="add-h5">
          <div class="item">
            <a href="https://finance.yahoo.com/news/introducing-worlds-first-curated-nft-093400542.html" target="_blank"><img src="~assets/img/newimg/add1.png" alt="" ></a>
          <a href="https://seekingalpha.com/pr/18469030-introducing-worlds-first-curated-nft-launchpad"  target="_blank"><img src="~assets/img/newimg/add2.png" alt=""></a>
          </div>
          <div class="item">
            <a href="https://www.marketwatch.com/press-release/introducing-the-worlds-first-curated-nft-launchpad-2021-09-13" target="_blank"><img src="~assets/img/newimg/add3.png" alt=""></a>
          <a href="https://www.benzinga.com/pressreleases/21/09/n22903166/introducing-the-worlds-first-curated-nft-launchpad" target="_blank"><img src="~assets/img/newimg/add4.png" alt=""></a>
          </div>
          <div class="item">
            <a href="https://beincrypto.com/introducing-the-worlds-first-curated-nft-launchpad/" target="_blank"><img src="~assets/img/newimg/add5.png" alt=""></a>
            <a href="javaScript:;" target="_blank"></a>
          </div>
        </div>
      </div>
    </div>
    </div>
    
  </div>
</template>
<script>
import { setCookie, getCookie } from "~/assets/js/cookie";
export default {
  data() {
    return {
      iosItem: "",
      androidItem: "",
      isShow: false,
      isShow1: true,
      isShow2: true,
      isShow3: false,
      isShow4: false,
      showActive:1,
      localeList: [
        {
          label: "English",
          key: "en",
        },
        {
          label: "简体中文",
          key: "zh",
        }
      ],
      localObj: {
        en: {
          key: "English",
        },
        zh: {
          key: "简体中文",
        },
      },
      // locale: "简体中文",
    };
  },
  computed: {
    locale() {
      return this.$store.state.locale;
    }
  },
  mounted() {

  },
  methods: {
    toggle() {
      this.isShow = !this.isShow;
    },
    enter(){
        this.isShow2 = true;
      },
      leave(){
        this.isShow2 = false;
      },
    mouseOver() {
      this.openList();
    },
    mouseLeave() {
      this.hideList();
    },
    openList() {
      this.isShow = true;
    },
    hideList() {
      this.isShow = false;
    },
    switchLanguage(lang,index) {
      this.showActive = index;
      setCookie("lang", lang);
      // console.log('this.$route####', this.$route);
      this.$store.dispatch("setLanguage", lang);
      this.$i18n.locale = lang;
    },
  },
};
</script>
<style lang="scss" scoped>
.wrap {
  width: 100%;
  // min-height: 100vh;
  height: 100%;
  position: relative;
  .center{
    width: 1200px;
    margin: 0 auto;
  }
  .banner{
    min-width:1280px;
    background: url('~assets/img/newimg/banner-bg1.png') 50% no-repeat;
    background-size:cover;
    min-height:100vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    .top{
      width: 1200px;
      margin: 0px auto;
      padding-top: 10px;
      display: flex;
      justify-content: space-between;
      position: relative;
      img{
        width: 181.5px;
        height: 30px;
      }
      .menu-icon {
        display: none;
      }
      .menu-list{
        display: none;
      }
      .linkBox{
        display: flex;
      }
      .link{
        display: flex;
        justify-content: space-around;
        align-items: center;
        margin-left: 30px;
        a{
          font-size: 18px;
          font-weight: 400;
          color: #000000;
          margin-top: 10px;
          &:hover{
            color: rgb(67, 228, 208);
          }
        }
        img{
          height: 20px;
          width: 20px;
          margin-top: 10px;
        }
      }
    }
    .center{
      height: 600px;
      position: relative;
      .left{
        position: absolute;
        top: 140px;
        left:50px;
        img{
          width: 400px;
          height: 250px;
        }
        .btndiv{
          width: 220px;
          position: relative;
          margin-top: 40px;
          .btn{
            a{
              color: #fff;
            }
            width: 220px;
            height: 55px;
            line-height: 55px;
            padding-left: 35px;
            text-align: left;
            background: #000;
            color: #fff;
            font-size: 20px;
            font-weight: 700;
            cursor: pointer;
          }
          // &:hover{
          //   .btn-soon{
          //     display: block;
          //   }
          // }
          .btn-soon{
            width: 160px;
            height: 50px;
            line-height: 55px;
            text-align: center;
            color: #000;
            font-weight: 600;
            background: url('~assets/img/newimg/soon.png');
            background-size: 100% 100%;
            position: absolute;
            top: 60px;
            left: 110px;
            // display: none;
          }
          img{
            width: 24px;
            height: 24px;
            position: absolute;
            top: 0;
            right:30px;
            bottom: 0;
            margin: auto;
          }
        }
      }
      .right{
        position: absolute;
        top: 100px;
        right: -0px;
        img{
          &:nth-child(1){
            display: none;
          }
        }
      }
    }
    .footer{
      min-width:1200px;
      // height: 90px;
      margin-bottom: 50px;
      // background: #2F2F2F;
      .center{
        height: unset;
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
      }
      .top{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        .link{
          width:90px;
          display: flex;
          justify-content: space-between;
          img{
            width: 38px;
            height: 38px;
            opacity: 0.8;
            &:hover{
              opacity: 1;
            }
          }
        }
        span{
          font-size: 16px;
          font-weight: 400;
          color: #000000;
          line-height: 22px;
          margin-top: 10px;
        }
      }
      .add{
        display: flex;
        justify-content: flex-end;
        align-items: center;
        a{
          &:nth-child(1){
            img{
              width: 82px;
              height: 30px;
            }
          }
            &:nth-child(2){
              margin: 0 25px;
              img{
                width: 115px;
                height: 20px;
              }
            }
            &:nth-child(3){
              img{
                width:110px;
                height:15px;
              }
            }
            &:nth-child(4){
              margin-left: 25px;
              img{
                width: 110px;
                height: 13px;
              }
            }
            &:nth-child(5){
              margin-left: 25px;
              img{
                width: 100px;
                height: 26px;
              }
            }
          }
        }
        .add-h5{
          display: none;
        }
      }
    }
  }
 
@keyframes bounce-down {
        25% {
             transform: translateY(-4px);
        }
        50%, 100% {
             transform: translateY(0);
        }
        75% {
             transform: translateY(4px);
        }
}
@keyframes bounce-opcity {
        25% {
             opacity: 0.5;
        }
        // 40%{
        //      opacity: 0.3;
        // }
        50%{
             opacity: 0;
        }
        75% {
             opacity: 0.5;
        }
        // 75% {
        //      opacity: 0.9;
        // }
        100% {
             opacity: 1.0;
        }
}
@media screen and (max-width: 750px) {
.wrap {
    width: 100%;
    min-height: 120vh;
    background: #FFF;
  .center {
    width: 100%;
    padding: 0px 20px;
    margin: 0 auto;
  }
  .banner {
    min-width: unset;
    background-size: 100% 100%;
    background-image: url("../../assets/img/newimg/h5-bg.png");
    background-position: center;
    height: unset;
    .top{
      width: 100%;
      padding: 20px 20px 0;
      img{
        width: 130px;
        height: 24px;
      }
      .menu-icon {
        display: block;
        img {
          width: 24px;
        }
      }
      .menu-list {
        display: block;
        position: fixed;
        left: 0px;
        top: 60px;
        right: 0px;
        bottom: 0px;
        height: 130px;
        background: #fff;
        z-index: 99;
        // padding: 20px;
        .link{
          // display: unset;
          margin-left: 10px;
          justify-content: center;
          margin-top: 20px;
          a{
            font-size: 14px;
            font-weight: 400;
            color: #000000;
            line-height: 14px;
            font-family: "Montserrat";
          }
          img{
            width: 15px;
            height: 15px;
          }
        }
      }
      .linkBox{
        display: none;
      }
    }
    .center{
      padding: 0 20px;
      position: relative;
      .left{
        width: 100%;
        margin-top: 0px;
        position: unset;
        margin-top: 80px;
        img{
          width: 100%;
          height: 100%;
        }
        .btndiv{
          width: 170px;
          .btn{
            width: 170px;
            height: 40px;
            line-height: 40px;
            font-size: 18px;
            padding-left: 15px;
            font-family: "Montserrat";
          }
          .btn-soon{
            width: 140px;
            height: 35px;
            line-height:38px;
            top: 45px;
            left: 110px;
            font-family: "Montserrat";
            z-index: 99;
          }
          img{
            position: absolute;
            right: 12px;
          }
        }
      }
      .right{
        position: absolute;
        top: 460px;
        right:0px;
        left: 0px;
        margin: auto;
        img{
          width:310px;
          height: 240px;
          margin:  0 auto;
          z-index: -1;
          &:nth-child(1){
            display: block;
          }
          &:nth-child(2){
            display: none;
          }
        }
      }
    }
    .footer{
      min-width: 100%;
      margin-top: 90px;
      padding-bottom: 0;
      margin-bottom: 40px;
      .center{
        display: flex;
        flex-direction: column-reverse;
        justify-content: center;
        align-items: center;
      }
      .top{
        width: 100%;
        .link{
          width: 70px;
          margin: 0 auto;
          margin-bottom: 10px;
          img{
            width: 30px;
            height: 30px;
          }
        }
        span{
          text-align: center;
          margin: 0 auto;
          font-family: "Montserrat";
        }
      }
      .add{
        display: none;
      }
      .add-h5{
        display: block;
        margin-top: 50px;
        .item{
          display: flex;
          align-items: center;
          justify-content: space-around;
          a{
          &:nth-child(1){
            img{
              width: 110px;
              height: 42px;
            }
          }
            &:nth-child(2){
              margin-left: 30px;
              img{
                width: 140px;
                height: 30px;
              }
            }
            
          }
          &:nth-child(2){
            margin-top: 30px;
            a{
              &:nth-child(1){
              img{
                width:140px;
                height:20px;
              }
            }
            &:nth-child(2){
              img{
                width: 140px;
                height: 22px;
              }
            }
            }
          }
          &:nth-child(3){
            margin-top: 30px;
            a{
              &:nth-child(1){
              img{
                width:140px;
                height:37px;
              }
            }
            &:nth-child(2){
                width: 130px;
                height: 22px;
            }
            }
          }
        }
        }
      }
    }
  
  
}
}
</style>