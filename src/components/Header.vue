<template>
    <div class="header-wrapper">
        <div class="top-header">
            <div class="container">
                <div class="row">
                    <div class="left">
                        <span class="icon"><img alt="Vue icon" src="../assets/images/price.png"></span>
                        <p>gratis ebook 9 cara cerdas menggunakan domain [ x ]</p>
                    </div>
                    <div class="right ml-auto">
                        <ul>
                            <li>
                                <span class="icon"><img alt="Vue icon" src="../assets/images/phone.png"></span>
                                <p>0274-5305505</p>
                            </li>
                            <li>
                                <span class="icon"><img alt="Vue icon" src="../assets/images/chat.png"></span>
                                <p>live chat</p>
                            </li>
                            <li>
                                <span class="icon"><img alt="Vue icon" src="../assets/images/user.svg"></span>
                                <p>member area</p>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="navbar-menu">
            <div class="container">
                <div class="row">
                    <nav class="navbar navbar-expand-lg ">
                        <a class="navbar-brand" href="#"> <img alt="Vue logo" src="../assets/images/niagahoster-logo.png"></a>
                        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                            <span class="navbar-toggler-icon"></span>
                        </button>

                        <div class="collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="navbar-nav ml-auto">
                                <li class="nav-item active">
                                    <a class="nav-link" href="#">Hosting <span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Domain <span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Server <span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Website <span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Afiliasi <span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Promo <span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Pembayaran <span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Review <span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Kontak <span class="sr-only">(current)</span></a>
                                </li>
                                <li class="nav-item">
                                    <a class="nav-link" href="#">Blog <span class="sr-only">(current)</span></a>
                                </li>
                            </ul>
                        </div>
                    </nav>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss">
    .top-header{
        border-bottom: 1px solid #F4F4F4;
        padding-bottom: 15px;
        .right {
            ul {
                display: flex;
                position: relative;
                top: 15px;
                li {
                    display: flex;
                    padding-left: 20px;
                    align-items: center;
                    .icon {
                        padding-right: 10px;
                        img {
                            width: 20px;
                        }
                    }
                    p{
                        margin-bottom: 0;
                        text-transform: capitalize;
                        font-size: 14px;
                    }
                }
            }
        }
        .left{
            display: flex;
            align-items: center;
            .icon {
                background: #0090EF;
                text-align: center;
                margin-right: 15px;
                position: relative;
                width: 30px;
                height: 40px;
                padding: 2px 0 0;
                img {
                    width: 18px;
                }
                &:after {
                    content: '';
                    width: 0;
                    height: 0;
                    border-left: 14px solid transparent;
                    border-right: 14px solid transparent;
                    border-bottom: 10px solid #fff;
                    position: absolute;
                    left: 0;
                    right: 0;
                    margin: 0 auto;
                    bottom: 0;
                }
            }
            p {
                margin: 0;
                text-transform: capitalize;
                font-size: 14px;
            }
        }
    }
    .navbar-menu {
        padding: 10px 0;
        border-bottom: 1px solid #f4f4f4;
        .navbar{
            width: 100%;
            padding: 0;
            .navbar-brand{
                img{
                    width: 300px;
                }
            }
        }
    }

</style>