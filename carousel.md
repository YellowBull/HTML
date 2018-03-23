# 使用bootstrap实现轮播图功能
```HTML
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <link type="text/css" rel="stylesheet" href="../public/css/bootstrap.min.css"/>
    <script type="text/javascript" src="../public/js/jquery-3.2.1.min.js"></script>
    <script type="text/javascript" src="../public/bootstrap/js/bootstrap.min.js"></script>
    <title>公告详情</title>
</head>
<style>
    .carousel {
        max-height: 500px;
        background-color: #000;
        margin-bottom: 40px;
    }
    .carousel .item {
        max-height: 500px;
        background-color: #000;
    }
    .carousel img{
        max-width: 100%;
        height: auto;
    }
    .carousel-caption p{
        margin-bottom: 20px;
        font-size: 20px;
        line-height: 1.8;
    }
</style>
<body>
<!--轮播广告-->
<div id="carousel-example-generic" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
        <li data-target="#carousel-example-generic" data-slide-to="0" class="active"></li>
        <li data-target="#carousel-example-generic" data-slide-to="1"></li>
        <li data-target="#carousel-example-generic" data-slide-to="2"></li>
        <li data-target="#carousel-example-generic" data-slide-to="3"></li>
    </ol>

    <!-- Wrapper for slides -->
    <div class="carousel-inner" role="listbox">
        <div class="item active">
            <img src="../img/banner.jpg">
        </div>
        <div class="item ">
            <img src="../img/banner2.jpg">
        </div>
        <div class="item ">
            <img src="../img/banner3.jpg">
        </div>
        <div class="item">
            <img src="../img/banner4.jpg">
            <!--<div class="carousel-caption">
                <h1>Opera</h1>
                <p>Opera浏览器，是一款挪威Opera Software ASA公司制作的支持多页面标签式浏览的网络浏览器。</p>
                <p><a class="btn btn-lg btn-primary" href="http://www.opera.com/zh-cn" target="_blank"
                      role="button">点我下载</a></p>
            </div>-->
        </div>
    </div>
    <!-- Controls -->
    <a class="left carousel-control" href="#carousel-example-generic" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#carousel-example-generic" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
    </a>
</div>

</body>
</html>
```
