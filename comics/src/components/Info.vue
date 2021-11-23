<template>
  <section>
      <div class="info">
            <div class="imgbox">
                <img src="../assets/img/buy-comics-digital-comics.png"    alt="">
                <p>DIGITAL COMICS</p>
            </div>
            <div class="imgbox">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <p>DL MERCHANDISE</p>
            </div>
            <div class="imgbox">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <p>SUBSCRIPTION</p>
            </div>
            <div class="imgbox">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </div>
            <div class="imgbox">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p>
            </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Info'
}
</script>

<style scoped lang="scss">
    section{
        height: 220px;
        background-color: #0282f9;
        display: flex;
        align-items: center;

        .info{
            display: flex;
            align-items: center;
            justify-content: space-around;
            width: 90%;
            margin: 0 auto;

            .imgbox{
                display: flex;
                align-items: center;
            }

            p{
                padding: 10px;
                color: #fff;
            }

            img{
                width: 60px;
            }
        }
    }
</style>