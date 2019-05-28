<template>
  <section class="features">
  <h2>Features</h2>
  <div class="time"><span></span><span></span></div>
  <div class="rowtime">
    <div class="features_item"><img src="../../assets/img/item1.png" alt="" />
      <p>Born Identity: Bringing Burton Hardgoods to Life</p>
    </div>
    <div class="features_item"><img src="../../assets/img/item2.png" alt="" />
      <p>Jeremy Jones: On That Street Grind</p>
    </div>
    <div class="features_item"><img src="../../assets/img/item3.png" alt="" />
      <p>Burton’s Tokyo Rail Days Recap</p>
    </div>
    <div class="features_item"><img src="../../assets/img/item4.png" alt="" />
      <p>Burton’s Tokyo Rail Days Preview</p>
    </div>
  </div>
</section>
</template>
<style lang="sass" scoped>
  .features
    width: 100%
    display: flex
    flex-direction: column
    align-items: center
    padding: 120px 15px
    @media (max-width:770px)
        padding: 20px 90px
    h2
        text-transform: uppercase
        font-size: 48px
        @media (max-width:640px)
            font-size: 28px
    .time
        position relative
        padding: 35px 0
        margin-bottom: 100px
        display: flex
        justify-content: center
        @media (max-width:770px)
            margin: 0
        span
            position: absolute
            content: ''
            background: #000000
            padding: 2px 20px
            display: inline-block
            transform: rotateZ(-45deg)
            &:nth-child(2)
                transform: rotateZ(45deg)
    .rowtime
        display: flex
        justify-content: space-between
        align-items: flex-start
        flex-wrap: wrap
        width: 100%
        max-width: 960px
        @media (max-width:640px)
            justify-content: center
        .features_item
            max-width: 220px
            justify-content: center
            display: flex
            flex-direction: column
            text-align: center
            align-items: center
            @media (max-width:770px)
                margin: 10px 0
            p
                text-align: left
                line-height: 2rem
                padding: 20px 0 0
                font-size: 16px
</style>

