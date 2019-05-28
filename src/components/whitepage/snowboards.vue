<template>
  <section class="snowboards">
  <h2>snowboards</h2>
  <p>Aliquam erat volutpat. Curabitur ut consequat arcu eget laoreet est</p>
  <div class="time"><span></span><span></span></div>
  <div class="button_wrap">
    <div id="next"><img src="../../assets/img/next.svg" alt="" /></div>
    <div id="prev"><img src="../../assets/img/prev.svg" alt="" /></div>
  </div>
  <div class="row">
    <div class="wrap">
      <div class="snowboards_item"><img src="../../assets/img/board1.png" alt="" /></div>
      <div class="snowboards_item active"><img src="../../assets/img/board2.png" alt="" /></div>
      <div class="snowboards_item"><img src="../../assets/img/board3.png" alt="" /></div>
    </div>
  </div>
  <h3>Snowboard extreme Series</h3>
</section>
</template>
<style lang="sass" scoped>
    
.snowboards
    width: 100%
    text-align: center
    padding: 150px 0 200px
    position: relative
    @media (max-width:770px)
        padding: 15px 0
    h2
        text-transform: uppercase
        font-size: 48px
        font-weight: 300
        margin: 0
        padding-bottom: 40px
        @media (max-width:640px)
            font-size: 28px
            padding:  30px 0 0 
    p
        font-size: 14px
        text-transform: uppercase
        @media (max-width:640px)
            font-size: 14px
            padding: 20px 50px
    h3
        font-size: 24px
        text-transform: uppercase
        font-weight: 300
        padding: 50px 0
        @media (max-width:640px)
            font-size: 24px
            padding: 40px 70px 0
    .time
        position relative
        padding: 30px 0
        display: flex
        justify-content: center
        margin-top: 20px
        margin-bottom: 120px
        @media (max-width:770px)
            margin: 20px 0
        @media (max-width:640px)
            display: none
        span
            position: absolute
            content: ''
            background: #000000
            padding: 2px 20px
            display: inline-block
            transform: rotateZ(-45deg)
            &:nth-child(2)
                transform: rotateZ(45deg)
    .button_wrap
        position: relative
        max-width: 1400px
        margin: 0 auto
        z-index: 10
        #next
            position: absolute
            right: 10px
            font-size: 180px
            cursor: pointer
            padding-top: 100px
            z-index: 10
            img
                @media (max-width 640px)
                    height: 100px
        #prev
            position: absolute
            left: 10px
            font-size: 180px
            cursor: pointer
            padding-top: 100px
            z-index: 10
            img
                @media (max-width 640px)
                    height: 100px
    .row
        position: relative
        max-width: 960px
        height: 410px
        margin: 0 auto
        display: flex
        justify-content: center
        align-items: center
        color: #b7b7b7
        overflow: hidden
        .wrap
            position: relative
            left: 0
            display: flex
            align-items: center
            transition: 0.5s
            .snowboards_item
                padding: 0 100px
                opacity: 0.5
                transition: 1s all
                box-sizing: content-box
                @media (max-width:770px)
                    padding: 0 50px
            .active
                opacity: 1
</style>

