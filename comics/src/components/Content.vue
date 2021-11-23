<template>
  <section class="content">
  </section>
</template>

<script>
export default {
    name: 'Content'
}
</script>

<style scoped lang="scss">
    section{
        display: flex;
        align-items: center;
        background: #1c1c1c;
        height: 200px;
        &:after{
            content: '--> Content goes here <--';
            color: #fff;
            font-size: 30px;
            width: 90%;
            margin: 0 auto;
        }
    }
</style>