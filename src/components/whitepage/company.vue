<template>
  <section class="company">
  <div class="row">
    <h2>The Mountains </h2>
    <h2>Snowboarding ®</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec tincidunt auctor facilisis. Nam massa dui, imperdiet et mi ut, sagittis viverra odio. Duis et lectus eu enim gravida vulputate nec eget nisi. Nunc ultrices velit blandit, dapibus lacus in, feugiat erat. Donec non porttitor augue, sit amet lacinia purus. Nulla fringilla quam est, luctus dapibus odio suscipit ut. Vivamus et lectus a nunc fringilla volutpat. Morbi sed congue sem.</p><br /><br />
    <p>Aliquam erat volutpat. Curabitur ut consequat arcu, eget laoreet est. Vivamus semper nibh sit amet libero hendrerit luctus. Fusce non bibendum lorem. Fusce laoreet risus eget tortor lobortis egestas. Etiam tempus quam sed felis viverra scelerisque. Integer fringilla libero risus, vel euismod turpis auctor ac. Proin elementum aliquet libero a dapibus. Mauris et tempor dolor.</p>
  </div>
</section>
</template>
<style lang="sass" scoped>
.company
    background: url(../../assets/img/bgsnow.jpg) no-repeat
    background-size: cover
    background-position: top
    width: 100%
    color: #ffffff
    padding: 250px 15px
    @media (max-width: 770px)
        background-size: cover
        background-position: right bottom
        padding: 120px 15px
    @media (max-width:640px)
        background: none
        max-height: 450px
        color: #000000
        padding: 15px 
    .row
        max-width: 960px
        height: 100%
        margin: 0 auto
        display: flex
        flex-direction: column
        justify-content: center
        padding: 15px 0
        h2
            font-size: 48px
            margin: 0
            text-transform: uppercase
            &:nth-child(2)
                margin-bottom: 50px
                @media (max-width:640px)
                    margin: 0
            @media (max-width:640px)
                font-size: 28px
                text-align: center
        p
            max-width: 600px
            font-size: 15px
            line-height: 30px
            @media (max-width:770px)
                max-width: 350px
            &:nth-child(6)
                @media(max-width: 770px)
                    display: none
            @media (max-width:640px)
                padding: 10px 0

</style>

