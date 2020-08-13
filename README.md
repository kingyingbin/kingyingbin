<!--### Hi there 👋-->

<!--
**kingyingbin/kingyingbin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=kingyingbin)](https://github.com/anuraghazra/github-readme-stats)



<div id="blog-news">
    <div class="wrap">
    <!--部署内外层图片-->
    <div class="cube">
        <!--前面图片 -->
        <div class="out_front">
            <img src="https://i.loli.net/2019/07/31/5d4168d61625e88903.jpg" class="pic">
        </div>
        <!--后面图片 -->
        <div class="out_back">
            <img src="https://i.loli.net/2019/07/31/5d41787b77f8c42157.jpg" class="pic">
        </div>
        <!--左面图片 -->
        <div class="out_left">
            <img src="https://i.loli.net/2019/07/31/5d41787b4c26120803.jpg" class="pic">
        </div>
        <!--右面图片 -->
        <div class="out_right">
            <img src="https://i.loli.net/2019/12/09/mApU4v7rz6IyoVq.jpg" class="pic">
        </div>
        <!--上面图片 -->
        <div class="out_top">
            <img src="https://i.loli.net/2019/07/31/5d41787b8838579898.jpg" class="pic">
        </div>
         <!--下面图片 -->
        <div class="out_bottom">
            <img src="https://i.loli.net/2019/07/31/5d4177a5c03b276317.jpg" class="pic">
        </div>

 <!--小正方体 -->
    <span class="in_front">
            <img src="https://i.loli.net/2019/07/31/5d4177a5b220c91577.jpg" class="in_pic">
        </span>
    <span class="in_back">
             <img src="https://i.loli.net/2019/07/31/5d41787b58abb52587.jpeg" class="in_pic">
        </span>
    <span class="in_left">
            <img src="https://i.loli.net/2019/07/31/5d41787b5ebdf38746.jpg" class="in_pic">
        </span>
    <span class="in_right">
            <img src="https://i.loli.net/2019/07/31/5d41787b6ac7a98179.jpeg" class="in_pic">
        </span>
    <span class="in_top">
            <img src="https://i.loli.net/2019/07/31/5d4177a57bcfd95180.jpg" class="in_pic">
        </span>
    <span class="in_bottom">
            <img src="https://i.loli.net/2019/07/31/5d41787ba3a5644599.jpg" class="in_pic">
        </span>
 
</div>
<style>
    /*最外层容器样式*/
    .wrap {
        width: 60px;
        height: 60px;
        margin: 90px;
        position: relative;
    }
 
    /*得到立方体效果*/
    .cube {
        width: 50px;
        height: 50px;
        margin: 0 auto;
        transform-style: preserve-3d;
        /*设置动画播放样式:动画对象 播放速度 时间 播放次数*/
        animation: rotate linear 15s infinite;
    }
 
    /*动画旋转的方式*/
    /*得到动画效果*/
    @-moz-keyframes rotate {                     /*firefox*/
        from {
            transform: rotateX(0deg) rotateY(0deg);
        }
        to {
            transform: rotateX(720deg) rotateY(360deg);
        }
    }
    @-webkit-keyframes rotate {                /*sofari chrome*/
        from {
            transform: rotateX(0deg) rotateY(0deg);
        }
        to {
            transform: rotateX(720deg) rotateY(360deg);
        }
    }
    @-o-keyframes rotate {                    /*opera*/
        from {
            transform: rotateX(0deg) rotateY(0deg);
        }
        to {
            transform: rotateX(720deg) rotateY(360deg);
        }
    }
    /*每张图片的样式*/
    .cube div {
        position: absolute;
        width: 120px;
        height: 120px;
        opacity: 1.5;
        /*过渡效果*/
        transition: all .5s;
    }
 
    /*定义所有图片样式*/
    .pic {
        width: 120px;
        height: 120px;
    }
 
    .cube .out_front {
        transform: rotateY(0deg) translateZ(60px);
    }
 
    .cube .out_back {
        transform: rotateY(180deg) translateZ(60px);
    }
 
    .cube .out_left {
        transform: rotateY(-90deg) translateZ(60px);
    }
 
    .cube .out_right {
        transform: rotateY(90deg) translateZ(60px);
    }
 
    .cube .out_top {
        transform: rotateX(90deg) translateZ(60px);
    }
 
    .cube .out_bottom {
        transform: rotateX(-90deg) translateZ(60px);
    }
 
    /*定义小正方体样式*/
    .cube span {
        display: block;
        width: 80px;
        height: 80px;
        position: absolute;
        top: 20px;
        left: 20px;
    }
 
    .cube .in_pic {
        width: 80px;
        height: 80px;
    }
 
    .cube .in_front {
        transform: rotateY(0deg) translateZ(40px);
    }
 
    .cube .in_back {
        transform: rotateY(180deg) translateZ(40px);
    }
 
    .cube .in_left {
        transform: rotateY(-90deg) translateZ(40px);
    }
 
    .cube .in_right {
        transform: rotateY(90deg) translateZ(40px);
    }
 
    .cube .in_top {
        transform: rotateX(90deg) translateZ(40px);
    }
 
    .cube .in_bottom {
        transform: rotateX(-90deg) translateZ(40px);
    }
 
    /*鼠标移入后样式*/
    .cube:hover .out_front {
        transform: rotateY(0deg) translateZ(90px);
    }
 
    .cube:hover .out_back {
        transform: rotateY(180deg) translateZ(90px);
    }
 
    .cube:hover .out_left {
        transform: rotateY(-90deg) translateZ(90px);
    }
 
    .cube:hover .out_right {
        transform: rotateY(90deg) translateZ(90px);
    }
 
    .cube:hover .out_top {
        transform: rotateX(90deg) translateZ(90px);
    }
 
    .cube:hover .out_bottom {
        transform: rotateX(-90deg) translateZ(90px);
    }
</style>
