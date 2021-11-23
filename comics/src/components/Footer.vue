<template>
  <footer>
        <div class="content-footer">
            <div class="btn">
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="social">
                <h3>FOLLOW US</h3>
                <img src="../assets/img/footer-facebook.png" alt="facebook">
                <img src="../assets/img/footer-twitter.png" alt="twitter">
                <img src="../assets/img/footer-youtube.png" alt="youtube">
                <img src="../assets/img/footer-pinterest.png" alt="pinterest">
                <img src="../assets/img/footer-periscope.png" alt="periscope">
            </div>
        </div>
  </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style scoped lang="scss">
    footer{
        height: 150px;
        background-color: #303030;
        display: flex;
        align-items: center;

        .content-footer{
            display: flex;
            justify-content: space-between;
            width: 90%;
            margin: 0 auto;

            button{
                background: none;
                outline: none;
                padding: 10px;
                color: #fff;
                font-weight: 700;
                font-size: 18px;
                border: 2px solid #0282f9;
            }
        }
        .social{
            display: flex;

            img{
                margin: 0 10px;
                width: 100%;
            }

            h3{
                display: flex;
                align-items: center;
                color: #0282f9;
            }
        }
    }
</style>