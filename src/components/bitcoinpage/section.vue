<template>
  <section class="section1" id="top" tabindex="-1">
    <header>
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-sm-4 logo">
                    <a href="/" title="BitCoin Formula"><img src="../../assets/images/logo.svg" alt="Bitcoin Formula" class="img-responsive inline-block"></a>
                </div>
                <div class="col-md-6 col-sm-8 hidden-xs">

                    <div class="row">
                        <div class="col-sm-6">
                            <div class="flag-wrapper">
                                <div class="text text-uppercase text-right">
                                    Exclusive for<br><strong>Residents</strong>            </div>
                                <div class="flag">
                                    <img src="../../assets/images/flags/china.png" alt="Flag">
                                </div>
                            </div>
                        </div>
                        <div class="col-sm-6">
                            <div id="ui-names">
                                <div class="media notification-top">
                                    <div class="media-left">
                                        <img class="img-circle" src="../../assets/images/20.jpg" alt="" width="57" height="57">
                                    </div>
                                    <div class="media-body">
                                        <p>
                                            <span>Станіслав Д. </span>
                                            <span>just made</span>
                                        </p>
                                        <div class="h3">
                                            <span>$218</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <strong>
        <div class="container">
            <div class="row">
                <div class="col-sm-12 headline">
                    <h1 data-i18n="Bitcoin Is Making People Rich">Bitcoin Is Making People Rich</h1>
                    <h2 data-i18n="And You Can Become The Next Millionaire">And You Can Become The Next Millionaire…</h2>
                    <h4><span data-i18n="See what famous people like">See what famous people like</span> <strong>Bill
                        Gates</strong> <span data-i18n="and">and</span> <strong>Richard Branson</strong> <span data-i18n="have to say">have to say</span></h4>
                </div>
            </div>
            <div class="gap40-mobile"></div>
            <div class="row">
                <div class="col-md-8 col-sm-7">
                    <div class="video-container algo-video-container">
                        <video id="bitcoin-video" controls="" autoplay="" preload="" controlslist="nodownload">
                            <source src="../../assets/video/bitcoin.mp4" type="video/mp4"  poster="../../images/videothumbnail.jpg">
                            </video>
                    </div>
                </div>
                <div class="col-md-4 col-sm-5">
                    <div class="formwrap-outer">
                        <div class="formwrap">
                            <div class="form-header">
                                <span data-i18n="Start Changing">Start Changing</span> <span class="text-green" data-i18n="Your Life Today">Your Life TODAY</span>
                            </div>
                            <div class="form-body">
                                <form method="post" id="regForm" data-fr-reg="" style="margin:0!important;">
                                    <div data-subject="wrapper" id="form-wrapper" class="">
                                        <div id="slide1" class="1">
                                            <div class="progbar">
                                                <ul>
                                                    <li class="active">1</li>
                                                    <li>2</li>
                                                </ul>
                                            </div>
                                            <div class="form-group">
                                                <input class="form-control" name="firstName" placeholder="First name" type="text" required="required" data-validation="length" data-validation-length="3-30"/>
                                            </div>
                                            <div class="form-group">
                                                <input class="form-control" name="lastName" placeholder="Last name" type="text" required="required" data-validation="length" data-validation-length="3-30"/>
                                            </div>
                                            <div class="form-group">
                                                <input class="form-control" name="email" type="email" required="required" data-validation="email" placeholder="E-mail"/>
                                            </div>
                                            <div class="form-group">
                                                <button type="button" class="next-button" data-order="1">NEXT &gt;</button>
                                            </div>
                                        </div>
                                        <div id="slide2" class="2 hidden">
                                            <div class="progbar">
                                                <ul>
                                                    <li class="completed">✓</li>
                                                    <li class="active">2</li>
                                                </ul>
                                            </div>
                                            <div class="form-group">
                                                <input name="leadPhone" type="text" data-validation="mobile" required="required" class="form-control">
                                            </div>
                                            <div class="form-group">
                                                <select  name="leadCountryId" class="form-control"></select>
                                            </div>
                                            <div class="form-group">
                                                <button type="submit" class="next-submit">REGISTER NOW</button>
                                            </div>
                                        </div>
                                    </div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </strong>
</section>
</template>
<script>
export default {
  
}
</script>
<style>
@import url('https://fonts.googleapis.com/css?family=Oswald:200,300,400,500,600,700&display=swap');
.logo img {
  height: 5vh;
  font-family: 'Oswald', sans-serif;
}
/* Overrides */
.nospace {
  padding-left: 0;
  padding-right: 0;
}

.nomargin {
  margin-left: -15px;
  margin-right: -15px;
}

.clr {
  clear: left;
}

.ninja {
  display: none;
}

.uppercase {
  text-transform: uppercase;
}

.cursor {
  cursor: pointer;
}

.text-right {
  text-align: right;
}

.text-center {
  text-align: center;
}
.text-center img {
  height: 5vh;
}

.text-upper {
  text-transform: uppercase;
}

.fs16 {
  font-size: 16px;
}

.fs13 {
  font-size: 13px;
}

.text-bold {
  font-weight: bold;
}

.text-red {
  color: #e93347;
}

.text-white {
  color: #ffffff;
}

.text-bluelight {
  color: #b8f3fc;
}

.text-orange {
  color: #ff9000;
}

.text-blue {
  color: #4c6fd6;
}

.text-pink {
  color: #b50256;
}

.text-green {
  color: #08d908;
}

.inline-block {
  display: inline-block;
}

.padding-tb-10 {
  padding-top: 10px;
  padding-bottom: 10px;
}

.padding-tb-20 {
  padding-top: 20px;
  padding-bottom: 20px;
}

.padding-tb-40 {
  padding-top: 40px;
  padding-bottom: 40px;
}

.padding-tb-50 {
  padding-top: 50px;
  padding-bottom: 50px;
}

.padding-tb-60 {
  padding-top: 50px;
  padding-bottom: 60px;
}

.padding-tb-80 {
  padding-top: 80px;
  padding-bottom: 80px;
}

.padding-tbl-20 {
  padding: 20px 0 20px 20px;
}

.padding-tbr-20 {
  padding: 20px 20px 20px 0;
}

.gap20 {
  height: 20px;
}

.gap40 {
  height: 40px;
}

.gap40-mobile {
  height: 40px;
}
.spacer {
  height: 10px;
  background: #f7f8fa;
}

.spacer2 {
  height: 10px;
  background: #e7e7e7;
  border-top: 1px #e1e1e1 solid;
  border-bottom: 1px #e1e1e1 solid;
}

.embed-container {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
  max-width: 100%;
  border: 1px #7c3ed8 solid;
}

.embed-container iframe, .embed-container object, .embed-container embed {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.row.vdivide [class*='col-']:after {
  background: #e0e0e0;
  width: 1px;
  content: "";
  display: block;
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  min-height: 70px;
}

.row.vdivide [class*='col-']:first-child:before {
  background: #e0e0e0;
  width: 1px;
  content: "";
  display: block;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  min-height: 70px;
}

/* Sections */
.section1 {
  background: url(../../assets/images/section1bg.jpg) top center no-repeat;
  padding-top: 10px;
  padding-bottom: 30px;
  background-size: cover;
}

.section1 header {
  background: #ffffff;
  padding-top: 20px;
  padding-bottom: 20px;
  margin-bottom: 40px;
}

header .media h5 {
  text-transform: uppercase;
  font-weight: 300;
  font-family: 'Lato', sans-serif;
  padding: 0;
  margin: 5px 0;
}

header .media h5 strong {
  font-weight: 900;
}

header .media p, header .media .h3 {
  padding: 0;
  margin: 0;
}

header .notification-top {
  background: #392b6f;
  border-radius: 50px;
  border: 4px #e3e3e3 solid;
  width: auto;
  padding: 5px;
  display: flex;
}

header .notification-top p {
  color: #ffffff;
  font-size: 12px;
  margin-top: 5px;
}

header .notification-top .h3 {
  color: #08d908;
  font-size: 28px;
  font-weight: 900;
}

header .notification-top .media-body {
  text-align: center;
}
.headline {
  text-align: center;
  color: #ffffff;
  text-shadow: 0px 8px 4px rgba(0, 0, 0, 0.1);
}
#bitcoin-video {
  width: 100%;
}
.headline h1 {
  font-size: 54px;
  font-weight: 900;
  padding: 0;
  margin: 0 0 10px 0;
}

.headline h2 {
  font-size: 40px;
  font-weight: 400;
  padding: 0;
  margin: 0 0 10px 0;
}

.headline h4 {
  font-size: 22px;
  font-weight: 300;
  padding: 0;
  margin: 0 0 20px 0;
}

.headline h4 strong {
  color: #32e732;
}

/*FORM*/
.formwrap-outer {
  background: rgba(0, 0, 0, 0.4);
  border: 1px #7d73a4 solid;
  padding: 10px;
}

.formwrap {
  background: #ffffff;
}

.form-header {
  background: #1c163b;
  padding: 20px 20px 35px 20px;
  color: #ffffff;
  font-size: 40px;
  text-transform: uppercase;
  font-family: 'Oswald', sans-serif;
  line-height: 40px;
  text-align: center;
  font-weight: 500;
  border-bottom: 4px #08d908  solid;
}

.form-body {
  padding: 20px 20px;
  padding-bottom:5px;
  position: relative;
  margin-top: -45px;
}

.form-body .form-control {
  border-radius: 0;
  background: #e7e7e7;
  font-weight: 300;
  height: 40px;
}

.form-body button {
  font-family: 'Oswald', sans-serif;
  font-size: 24px;
  color: #ffffff;
  text-shadow: 0.5px 0.866px 0px rgba(1, 198, 0, 0.35);
  border-radius: 4px;
  text-transform: uppercase;
  padding: 8px 25px;
  width: 100%;
  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#0be00b+0,01c601+100 */
  background: #0be00b;
  /* Old browsers */
  /* FF3.6-15 */
  /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to bottom, #0be00b 0%, #01c601 100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#0be00b', endColorstr='#01c601',GradientType=0 );
  /* IE6-9 */
}
.form-body button:focus, .form-body button:hover {
  color: #ffffff;
  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#01c601+0,0be00b+100 */
  background: #01c601;
  /* Old browsers */
  /* FF3.6-15 */
  /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to bottom, #01c601 0%, #0be00b 100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#01c601', endColorstr='#0be00b',GradientType=0 );
  /* IE6-9 */
}

.progbar {
  padding: 0 0 30px 0;
}

.progbar ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
  display: block;
  text-align: center;
}

.progbar ul li {
  display: inline-block;
  padding: 7px;
  width: 45px;
  height: 45px;
  margin: 0 20px;
  text-align: center;
  font-family: 'Oswald', sans-serif;
  font-size: 20px;
  border-radius: 50%;
  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#e4e4e4+0,c6c7c6+100 */
  background: #e4e4e4;
  /* Old browsers */
  /* FF3.6-15 */
  /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to bottom, #e4e4e4 0%, #c6c7c6 100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#e4e4e4', endColorstr='#c6c7c6',GradientType=0 );
  /* IE6-9 */
  border: 1px #cdcdcd solid;
  color: #6d6d6d;
  text-shadow: 0.5px 0.866px 0px rgba(255, 255, 255, 0.35);
}

.progbar ul li.active {
  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#5c4b9c+0,403276+100 */
  background: #5c4b9c;
  /* Old browsers */
  /* FF3.6-15 */
  /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to bottom, #5c4b9c 0%, #403276 100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#5c4b9c', endColorstr='#403276',GradientType=0 );
  /* IE6-9 */
  color: #ffffff;
  border-color: #5e4c9e;
  text-shadow: 0.5px 0.866px 0px rgba(0, 0, 0, 0.35);
}

.progbar ul li.completed {
  /* Permalink - use to edit and share this gradient: http://colorzilla.com/gradient-editor/#08d908+0,01ba01+100 */
  background: #08d908;
  /* Old browsers */
  /* FF3.6-15 */
  /* Chrome10-25,Safari5.1-6 */
  background: linear-gradient(to bottom, #08d908 0%, #01ba01 100%);
  /* W3C, IE10+, FF16+, Chrome26+, Opera12+, Safari7+ */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#08d908', endColorstr='#01ba01',GradientType=0 );
  /* IE6-9 */
  color: #ffffff;
  border-color: #08d908;
  text-shadow: 0.5px 0.866px 0px rgba(0, 0, 0, 0.35);
}
.flag-wrapper {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding-top: 12px;
    padding-bottom: 12px;
}

.flag-wrapper .flag {
    margin-left: 15px;
}

.flag-wrapper .flag img {
    max-height: 50px;
}

</style>

