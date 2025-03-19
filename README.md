## Hi there 👋
<span class="container">
    <span class="box">
        <p>
        I'm Hughie, a developer from China. I'm interested in web development, machine learning and computer vision. I'm also a fan of guitar and music.
        </p>
    </span>
    <span class="eraser">
        <span class="text">
            I'm Hughie, a developer from China. I'm interested in web development, machine learning and computer vision. I'm also a fan of guitar and music.
        </span>
    </span>
</span>
<hr>

## Language I use
<img src="https://api.githubtrends.io/user/svg/hughie21/langs?time_range=one_year&theme=classic"/>

## My Projects
- [NovelMaker](https://github.com/hughie21/NovelMaker) - An epub edittor.
- [Customs Crawler](https://github.com/hughie21/customs-crawler) - A customs crawler.

## My practice
[![IceEnd's GitHub stats](https://github-immortality.vercel.app/api?username=hughie21)]

<style>
    .container{
        font-size: 20px;
        color: white;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans';
    }
    .text{
        --p: 30%;
        color: transparent;
        background: linear-gradient(to right, transparent var(--p), black calc(var(--p) + 5px));
        animation: erase 5s forwards linear;
    }
    .box{
        width: 500px;
        height: 500px;
        margin: 80px auto;
        position: relative;
        line-height: 2;
    }
    .eraser{
        position: absolute;
        inset: 0;
    }
    @property --p{
        syntax: '<percentage>';
        initial-value: 0%;
        inherits: false;
    }
    @keyframes erase{
        0%{
            --p: 0%;
        }
        100%{
            --p: 100%;
        }
    }
</style>
