<template>
    <section id="sliderType">
        <h2 class="ir_so">슬라이드 영역</h2>
        <div class="slider__inner">
            <div class="slider">
                <div class="slider__img">
                <div class="desc">
                    <span>DEVELOPER</span>
                    <h3>NEW FRONTEND</h3>
                    <p>
                    당신이 만들어갈 새로운 이야기
                    <br> 당신도 할 수 있습니다.
                    </p>
                    <div class="btn">
                    <a href="/" class="white">
                        자세히 보기
                    </a>
                    <a href="/" class="black">
                        사이트 보기
                    </a>
                    </div>
                </div>
                </div>
                <div class="slider__arrow">
                <a href="/" class="left">
                    <span class="ir_pm">이전이미지</span>
                </a>
                <a href="/" class="right">
                    <span class="ir_pm">다음이미지</span>
                </a>
                </div>
                <div class="slider__dot">
                <a href="/" class="dot active">
                    <span class="ir_pm">1</span>
                </a>
                <a href="/" class="dot">
                    <span class="ir_pm">2</span>
                </a>
                <a href="/" class="dot">
                    <span class="ir_pm">3</span>
                </a>
                <a href="/" class="dot">
                    <span class="ir_pm">4</span>
                </a>
                <a href="/" class="play">
                    <span class="ir_pm">자동플레이</span>
                </a>
                <a href="/" class="stop">
                    <span class="ir_pm">정지</span>
                </a>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped>
.slider {
    position: relative;
} 
.slider__img {
    background-image: url(../assets/img/slider_bg01.jpg);
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    /* height: 500px; */
}
.slider__img .desc {
    width: 1160px;
    margin: 0 auto;
    padding: 100px 20px;
    color: #fff;
}
.slider__img .desc span {
    font-size: 16px;
    background: #fff;
    color: #000;
    padding: 2px 15px 0px;
    border-radius: 30px;
}
.slider__img .desc h3 {
    font-size: 110px;
    font-weight: 300;
    margin-left: -8px;
    margin-bottom: 10px;
}
.slider__img .desc p {
    font-size: 20px;
    font-weight: 300;
    line-height: 1.4;
    margin-bottom: 130px;
}
.slider__img .desc .btn a {
    font-size: 16px;
    padding: 11px 50px;
    display: inline-block;
}
.slider__img .desc .btn .white {
    background: #fff;
    color: #000;
}
.slider__img .desc .btn .black {
    background: #000;
    color: #fff;
}
.slider__arrow a {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 27px;
    height: 39px;
    background: url(../assets/img/slider_icon.png);
}
.slider__arrow .left{
    left: 10px;
    background-position: 0 -50px;
}
.slider__arrow .right {
    right: 10px;
    background-position: -23px -50px;
}
.slider__dot {
    position: absolute;
    left: 50%;
    bottom: 25px;
    transform: translateX(-50%);
}
.slider__dot a {
    width: 14px;
    height: 14px;
    background: url(../assets/img/slider_icon.png);
    display: inline-block;
    margin: 2px;
}
.slider__dot .dot {
    background-position: -70px -50px;
}
.slider__dot .dot.active {
    background-position: -50px -50px;
}
.slider__dot .play {
    background-position: -88px -50px;
}
.slider__dot .stop {
    background-position: -110px -50px;
}
</style>