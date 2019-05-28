<template>
  <div>
    <div class="spacer"></div>
    <section class="section2">
        <div class="container">
            <div class="row">
                <div class="col-md-7 security-logos">
                    <img src="../../assets/images/bitgo.png" alt="BitGo">
                    <img src="../../assets/images/norton.png" alt="Norton">
                    <img src="../../assets/images/secure-trading.png" alt="Secure Trading">
                    <img src="../../assets/images/mcafee.png" alt="McAffee">
                </div>
                <div class="col-md-5 text-center">
                    <div class="bitcoin bid">
                        <sup>BID</sup>
                        <h2><span data-init="visitor-currency-symbol">$</span>326.56</h2> <sup><i class="fa fa-caret-up"></i></sup>
                    </div>
                    <div class="bitcoin ask">
                        <sup>ASK</sup>
                        <h2><span data-init="visitor-currency-symbol">$</span>329.52</h2> <sup><i class="fa fa-caret-up"></i></sup>
                    </div>
                </div>
            </div>
        </div>
    </section>
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
.section2 {
  background: #ffffff;
  padding-top: 10px;
  padding-bottom: 10px;
  border: 1px #e7ebf3 solid;
}

.security-logos img {
  margin: 5px 15px;
}

.security-logos {
  text-align: center;
}

.bitcoin {
  padding: 10px 10px 0 10px;
  text-align: center;
  display: inline-block;
}

.bitcoin h2 {
  display: inline-block;
  padding: 0;
  margin: 0;
  font-weight: 900;
}

.bitcoin sup {
  font-size: 13px;
  padding: 0 5px;
}

.bitcoin.bid {
  color: #f66600;
}

.bitcoin.bid h2 {
  color: #00c500;
}

.bitcoin.ask {
  color: #9f91b4;
}

.bitcoin.ask h2 {
  color: #9f91b4;
}

</style>
