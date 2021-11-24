<template>
  <section>
        <div class="content">
            <div class="current">
                <h3>CURRENT SERIES</h3>
            </div>
            <ul>
                <li v-for="(product, i) in products" :key="`${i}`">
                    <img :src="product.thumb">
                    <a href="#"> {{product.series}} </a>
                </li>
                <div class="btn">
                <button>LOAD MORE</button>
            </div>
            </ul>
        </div>
  </section>
</template>

<script>
export default {
    name: 'Content',
    data(){
        return { 
            products: [
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX',
                    series: 'Action Comics',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01',
                    series: 'American Vampire 1976',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01',
                    series: 'American Vampire 1976',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb',
                    series: 'Aquaman',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76',
                    series: 'Batgirl',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
                    series: 'Batman',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8',
                    series: 'Batman/Superman',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk',
                    series: 'Batman/Superman Annual',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8',
                    series: 'Batman: The Joker War Zone',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY',
                    series: 'Batman: Three Jokers',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX',
                    series: 'Batman: White Knight Presents: Harley Quinn',
                },
                {
                    thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq',
                    series: 'Catwoman',
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
    section{
        background: #1c1c1c;

        .content{
            position: relative;
            width: 90%;
            margin: 0 auto;

            .current{
                position: absolute;
                display: flex;
                align-items: center;
                color: #fff;
                top: -20px;
                height: 50px;
                padding: 20px;
                background: #0282f9;
            }
        }

        ul{
            list-style: none;
            display: flex;
            flex-wrap: wrap;
            padding: 70px 0;

            li{
                display: flex;
                flex-direction: column;
                width: calc(100% / 6);
                padding: 20px 0;

                img{
                    width: 150px;
                    height: 150px;
                }

                a{
                    color: #fff;
                    text-decoration: none;
                    padding: 10px 0;
                    width: 155px;
                }
            }
        }

        .btn{
            display: flex;
            justify-content: center;
            width: 100%;

            button{
            background: #0282f9;
            color: #fff;
            border: none;
            padding: 10px 30px;
            }
        }
    }
</style>