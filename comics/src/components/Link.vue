<template>
  <section>
      <div class="link-page">
            <div class="content-link">
                <div class="text-content">
                    <h3>DC COMICS</h3>
                    <a href="#">Characters</a>
                    <a href="#">Comics</a>
                    <a href="#">Movies</a>
                    <a href="#">Tv</a>
                    <a href="#">Games</a>
                    <a href="#">Videos</a>
                    <a href="#">News</a>
                    <h3>SHOP</h3>
                    <a>Shop DC</a>
                    <a>Shop DC Collectibles</a>
                </div>
                <div class="text-content">
                    <h3>DC</h3>
                    <a href="#">Terms Of Use</a>
                    <a href="#">Privacy policy (New)</a>
                    <a href="#">Ad Choices</a>
                    <a href="#">Advertising</a>
                    <a href="#">Talent Workshops</a>
                    <a href="#">CPSC Certificates</a>
                    <a href="#">Ratings</a>
                    <a href="#">Shop Help</a>
                    <a href="#">Contact Us</a>
                </div>
                <div class="text-content">
                    <h3>SITES</h3>
                    <a href="#">DC</a>
                    <a href="#">MAD Magazine</a>
                    <a href="#">DC kids</a>
                    <a href="#">DC Universe</a>
                    <a href="#">DC Power Visa</a>
                </div>
          </div>
          <img src="../assets/img/dc-logo-bg.png" alt="">
      </div>
  </section>
</template>

<script>
export default {
    name: 'Link'
}
</script>

<style scoped lang="scss">
    section{
        height: 100%;
        background-image: url(../assets/img/footer-bg.jpg);
        padding: 15px 0;
        background-position: center;
        background-size: cover;
        position: relative;
        overflow: hidden;

        .link-page{
            display: flex;
            justify-content: space-between;
            width: 90%;
            margin: 0 auto;

            img{
                position: absolute;
                height: 640px;
                bottom: -67px;
                right: 350px;
            }
        }

        .content-link{
            display: flex;
            width: 30%;
            height: 100%;
        }

        .text-content{
            display: flex;
            flex-direction: column;
            padding: 20px 0;
            padding-right: 25px;

            h3{
                color: #fff;
                padding: 10px 0;
            }

            a{
                color: #908f8f;
                padding: 10px 0;
                text-decoration: none;
            }
        }
    }
</style>