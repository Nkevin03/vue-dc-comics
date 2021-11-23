<template>
  <header>
      <img src="../assets/img/dc-logo.png" alt="dc-logo">
      <ul>
          <li><a href="#">CHARACTERS</a></li>
          <li><a href="#">COMICS</a></li>
          <li><a href="#">MOVIES</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">GAMES</a></li>
          <li><a href="#">COLLECTIBLES</a></li>
          <li><a href="#">VIDEOS</a></li>
          <li><a href="#">FANS</a></li>
          <li><a href="#">SHOP</a></li>
      </ul>
  </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped lang="scss">
    header{
        display: flex;
        align-items: center;
        width: 90%;
        height: 100px;
        padding: 10px;
        margin: 0 auto;
        justify-content: space-between;
    }
    img{
        width: 80px;
    }
    ul{
        display: flex;
        li{
            display: flex;
            list-style: none;
            padding: 10px;
            height: 100px;
            &:hover{
                border-bottom: 3px solid #0282f9;
            }
        }

        a{
            display: flex;
            align-items: center;
            text-decoration: none;
            font-weight: 700;
            font-size: 15px;
            color: #464646;
            &:hover{
                color: #0282f9;
            }
        }
    }
</style>