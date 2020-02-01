<template>
    <section class="box-wrapper">
        <div class="container">
            <div class="row">
                <ul>
                    <li>
                        <span class="icon"><img alt="Vue icon" src="../assets/images/zendguard.png"></span>
                        <p>PHP Send Guard Loader</p>
                    </li>
                    <li>
                        <span class="icon"><img alt="Vue icon" src="../assets/images/composer.png"></span>
                        <p>PHP Composer</p>
                    </li>
                    <li>
                        <span class="icon"><img alt="Vue icon" src="../assets/images/ioncube.png"></span>
                        <p>PHP IonCube Loader</p>
                    </li>
                </ul>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name: 'PHP'
}
</script>

<style lang="scss">
.box-wrapper {
    ul {
        text-align: center;
        width: 100%;
        li {
            display: inline-block;
            padding: 0 70px;
            .icon {
                height: 200px;
                display: flex;
                align-items: center;
                justify-content: center;
                img {
                    width: 200px;
                }
            }
            &:nth-of-type(2){
                 .icon{
                    img {
                        width: 130px;
                    }
                 }
            }
        }
    }
}

</style>