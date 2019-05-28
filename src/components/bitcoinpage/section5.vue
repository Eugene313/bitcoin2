<template>
    <section class="section5">
        <div class="transwhite">
            <div class="container">
                <div class="row">
                    <div class="col-sm-2"></div>
                    <div class="col-sm-10">
                        <h1 data-i18n="Hear From Our Members Who Rely On Our Software To Fund Their Luxury Lifestyles">
                            Hear From Our Members Who Rely On Our Software To Fund Their Luxury Lifestyles</h1>
                    </div>
                </div>
            </div>
        </div>
        <ul>
            <li><span class="sr-only">Testimonial Image</span></li>
            <li><span class="sr-only">Testimonial Image</span></li>
            <li><span class="sr-only">Testimonial Image</span></li>
            <li><span class="sr-only">Testimonial Image</span></li>
            <li><span class="sr-only">Testimonial Image</span></li>
        </ul>
    </section>
</template>
<style>
.section5 {
  position: relative;
  height: 200px;
}

.section5 ul {
  padding: 0;
  margin: 0;
  display: block;
}

.section5 li {
  padding: 0;
  margin: 0;
  display: inline-block;
  width: 20%;
  height: 200px;
  float: left;
}

.section5 li:nth-child(1) {
  background: url(../../assets/images/testimonial1.jpg) top center no-repeat;
  background-size: cover;
}

.section5 li:nth-child(2) {
  background: url(../../assets/images/testimonial2.jpg) top center no-repeat;
  background-size: cover;
}

.section5 li:nth-child(3) {
  background: url(../../assets/images/testimonial3.jpg) top center no-repeat;
  background-size: cover;
}

.section5 li:nth-child(4) {
  background: url(../../assets/images/testimonial4.jpg) top center no-repeat;
  background-size: cover;
}

.section5 li:nth-child(5) {
  background: url(../../assets/images/testimonial5.jpg) top center no-repeat;
  background-size: cover;
}

.transwhite {
  background: rgba(255, 255, 255, 0.5);
  text-align: center;
  padding-top: 15px;
  padding-bottom: 15px;
  position: absolute;
  width: 100%;
  bottom: 0;
  z-index: 2;
  border: 1px #ffffff solid;
}

.transwhite h1 {
  padding: 0;
  margin: 0;
  color: #261e52;
  font-weight: 900;
  text-shadow: 1px 1.732px 4px rgba(0, 0, 0, 0.1);
}
</style>
