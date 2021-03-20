<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <style type="text/css">
        .q{
            width: 100%;
            height: 50px;
            background-color: cadetblue;
        }
        .w{
            width: 290px;
            height: 633px;
            border: 1px solid rgb(0,0,0);
            background-color: rgb(252, 243, 243);
        }
        .r{
            width: 910px;
            height: 3000px;
            position: absolute;
            left: 302px;
            top: 58px;
            background-color: rgb(255, 255, 255);
            border: 1px solid rgb(0,0,0);
        }
        .e{
            width: 300px;
            height: 2200px;
            border: 1px solid rgb(0,0,0);
            position: absolute;
            left: 1217px;
            top: 58px;
            background-color: rgb(252, 243, 243);
        }
        .t{
            width: 55px;
            height: 56px;
            background-color: rgb(46,246,246);
            position: absolute;
            left: 355px;
            top: 1px;
            animation: move 1s;
            animation-duration: 10s;
        }
        .y{
            width: 800px;
            height: 400px;
            position: absolute;
            left: 30px;
        }
        @keyframes move{
            0%{
                transform: translateX(0);
            }
            100%{
                transform: translateX(500px);
            }
        }           
         #pt{
                width: 290px;
                height: 430px;
                overflow: hidden;
                position: absolute;
                left: 0px;
                top: 0px;
                border-radius: 5px 5px 5px 5px;
            }
            #tp{
                width: 1200px;
                animation: switch 4s ease-out infinite;
            }
            #tp>img{
                float:left;
                width: 290px;
                height: 430px;
            }
            @keyframes switch{
                35%, 60% {
				margin-left: -290px;
			}
            70%, 100% {
				margin-left: -0px;
			}
            }
        .q>a:hover{
            color: sandybrown;
        }
        .java{
            display: inline-block;
        }
        .tupian{
            width: 190px;
            height: 100px;
            position: absolute; 
            top: 10px;
            left: 5px; 
            border-radius: 5px 5px 5px 5px;
            overflow:hidden;
        }
        .tupian img{
            cursor:pointer;
            transition:all 0.5s;
        }
        .tupian img:hover{
            transform:scale(1.3)
        }
        .tupianto{
            width: 190px;
            height: 100px;
            position: absolute;
            top: 10px;
            left: 5px;
            border-radius: 5px 5px 5px 5px;
            overflow: hidden;
        }
        .tupianto img{
            cursor:pointer;
            transition: all 0.5s;
        }
        .tupianto img:hover{
            transform: scale(1.3);
        }
        .diyi li:hover{
            color: salmon;
        }
        .dito li:hover{
            color: salmon;
        }
        .y h3:hover{
            color: salmon;
        }
        .jishushequ li:hover{
            color: salmon;
        }
        .yqlj a:hover{
            color: skyblue;
        }
        .bg1 {
            position: absolute;
            width: 890px;
            height: 600px;
            top: 200px;
            background: url(images/bg1.png) no-repeat;
            animation: move_bg 50s linear infinite;
        }
        .bg2 {
            top: 600px;
            width: 890px;
            height: 600px;
            background: url(images/bg2.png) no-repeat;
            animation: move_bg 80s linear infinite;
        }
        .bear {
            position: absolute;
            top: 400px;
            width: 200px;
            height: 100px;
            background: url(images/bear.png) no-repeat;
            animation: bear 1s steps(8) infinite, move 1s forwards;
            z-index: 1;
        }
        @keyframes bear {
            0% {
                background-position: 0 0;
            }

            100% {
                background-position: -1600px 0;
            }
        }
        @keyframes move {
            0% {
                left: 0;
            }

            100% {
                left: 50%;
                /* margin-left: -100px; */
                transform: translateX(-50%);
            }
        }
        @keyframes move_bg {
            0% {
                background-position: 0 0;
            }

            100% {
                background-position: 100% 0;
            }
        }
        </style>
        </head>
        <body>
            <div class="q">
                <h3 style="position: absolute; top: 3px; left: 30px;"><a  href="#" style="text-decoration: none; color: azure;">首页</a></h3>
                <h3 style="position: absolute; top: 3px; left: 100px;"><a href="#">推荐</a></h3>
                <h3 style="position: absolute; top: 3px; left: 170px;"><a href="#">下载</a></h3>
                <h3 style="position: absolute; top: 3px; left: 240px;"><a href="#">贴吧</a></h3>
                <h3 style="position: absolute; top: 3px; left: 310px;"><a href="#"  >问答</a></h3>
                <h3 style="position: absolute; top: 3px; left: 380px;"><a href="#">代码</a></h3>
                <h3 style="position: absolute; top: 3px; left: 450px;"><a href="#">程序员学院</a></h3>
                </div>
                <div class="w">
                    </div>
                    <div class="e">
                        <div style="width:100px; height:100px; border-radius:50%; overflow:hidden; position: absolute; left: 90px; top: 20px; border: 1px solid rgb(0,0,0);"align="center">
                            <img src="img/头像.jpg" alt="正方形的原始图片" width="100" height="110">
                            </div>
                            <p style="position: absolute; left: 90px; top: 120px;"><b>qq_45984604006</b></p>
                            <div style="width: 290px; height: 430px;position: absolute;top: 680px;">
                                <p style="font-size: 20px;"><b>遇见offer</b></p>
                                <div style="width: 270px;height: 200px;border: 1px solid rgb(0, 0, 0);position: absolute; left: 10px;">
                                    <img src="img/22.jpg" width="270" height="200">
                                </div>
                                <div style="width: 270px; height: 130px;border: 1px solid rgb(0, 0, 0);position: absolute;top: 265px;left: 10px;border-radius:0px 0px 5px 5px">
                                    <div style="position: absolute;left: 1px;">
                                    <ul>
                                        <li><a href="#" style="text-decoration: none;color: cornflowerblue;">微软专场</a></li>
                                        <li><a href="#" style="text-decoration: none;color: cornflowerblue;">引才入想</a></li>
                                        <li><a href="#" style="text-decoration: none;color: cornflowerblue;">腾讯招聘专场</a></li>
                                        <li><a href="#" style="text-decoration: none;color: cornflowerblue;">payply专场</a></li>
                                    </ul>
                                    </div>
                                    <ul style="position: absolute;left: 110px;list-style: none;">
                                        <li>研发团队岗位介</li>
                                        <li> 拿一线工资</li>
                                        <li> 在鹅厂遇见未来</li>
                                        <li>五年市值翻五倍！</li>
                                    </ul>
                                </div>
                            </div>
                            <div style="width: 290px;height: 430px;position: absolute;top: 200px;left: 4px;">
                                <div id="pt">
                                    <div id="tp">
                                        <a href="https://marketing.csdn.net/p/93d63cef8eeaa62d67fa243c92334bb7"><img src="img/24.png" style="width: 290px;height: 430px;"></a>
                                        <a href="https://edu.csdn.net/huiyiCourse/series_detail/175" ><img src="img/25.png" style="width: 290px;height: 430px;border-radius: 5px 5px 5px 5px;"></a>
                                        </div>
                                    </div>
                                </div>
                                <div style="width: 270px;height: 400px;position: absolute;top: 1080px;left: 10px;">
                                    <img src="img/29.png" width="270" height="400" style="border-radius: 5px;">
                                    </div>              
                        </div>
                        <div class="r">
                            <div class="t"></div>
                            <img src="img/1.png" width="44px" height="44px" style="vertical-align:middle;" align="left">
                            <p align="left" style="font-size: 18px;"><b>热门话题</b></p>
                            <h4 style="position: absolute; left: 85px;"><a href="#" style="text-decoration: none;color: aliceblue;">百度29岁程序员修改数据被捕</a></h4>
                            <p style="position: absolute; left: 85px;top: 95px; font-size: 15px;color: azure;"><a href="#" style="color: aliceblue;">特斯拉回应上海工厂摄像头被入侵：<br>已停止联网 | 极客日报</a></p>
                            <p style="position: absolute; left: 236px; top: 136px;"><a style="color: azure; text-decoration: none;"  href="#">查看更多></a></p>
                            <h4 style="position: absolute; left: 355px;"><a style="color: aliceblue;text-decoration: none;"href="#">产品经理与程序员</a></h4>
                            <p style="position: absolute; left: 355px;top: 95px; font-size: 15px;color: azure;"><a href="#" style="color: aliceblue;">细数产品经理“八大罪状”|漫画</a></p>
                            <p style="position: absolute; left: 485px; top: 136px;"><a style="color: azure; text-decoration: none;"  href="#">查看更多></a></p>
                            <h4 style="position: absolute; left: 592px;"><a href="#" style="color: aliceblue; text-decoration: none;">复旦新专利，衣服可当显示器用</a></h4>
                            <p style="position: absolute; left: 592px;top: 95px; font-size: 15px;color: azure;"><a href="#" style="color: aliceblue;">王兴：对“中国智造”文字游戏不感兴<br>趣|即可日报</a></p>
                            <p style="position: absolute; left: 744px; top: 136px;"><a style="color: azure; text-decoration: none;"  href="#">查看更多></a></p>
                            <div align="center">
                            <img data-v-62bd07a5="" src="https://img-home.csdnimg.cn/images/20210311095048.jpg" width="250"  height="128" style="border-radius:5px 5px 5px 5px">
                            <img data-v-62bd07a5="" src="https://img-home.csdnimg.cn/images/20210311032929.jpg" width="250" height="128" style="border-radius: 5px 5px 5px 5px;">
                            <img data-v-62bd07a5="" src="https://img-home.csdnimg.cn/images/20210305051007.jpg" width="250" height="128" style="border-radius: 5px 5px 5px 5px;">
                            </div>
                            <img src="img/精选头条.png" width="44" height="44">
                            <p align="left" style="font-size: 18px; position: absolute; left: 50px; top: 185px;"><b>精选头条</b></p>
                            <div class="y">
                                <img src="img/3.jpg" width="400" style="position: absolute; top: 8px; border-radius: 5px 5px 5px 5px;">
                                <h3><a href="#" style="text-decoration: none; color: rgb(255, 0, 0);">10 万 Rust 游戏玩家的数据永久丢失，一场大<br>火，让云计算巨头的数据中心化为灰烬</a></h3>   
                                <div style="width:40px; height:40px; border-radius:50%; overflow:hidden;  border: 1px solid rgb(0,0,0);"align="center">
                                    <img src="img/7.png" alt="正方形的原始图片" width="40" height="40">
                                    </div>
                                    <h3><a href="#" style="text-decoration: none; color: rgb(0, 0, 0); position: absolute; top: 175px;">10 万 Rust 游戏玩家的数据永久丢失，一场大<br>火，让云计算巨头的数据中心化为灰烬</a></h3>
                                    <p style="position: absolute;left: 50px;top: 238px;">CSDN咨询</p>
                                    <h3 style="position: absolute; left: 500px; top: 2px;" class="bei">被"钱"困住的开发者们!</h3>
                                    <div style="position: absolute;left: 500px; top: 50px; width:30px; height:30px; border-radius:50%; overflow:hidden;  border: 1px solid rgb(0,0,0);"align="center">
                                        <img src="img/7.png" alt="正方形的原始图片" width="30" height="30">
                                        </div>
                                        <p style="position: absolute;left: 535px; top: 50px;">CSDN咨询</p>
                                    <img src="img/4.jpg" width="90"  height="90" align="center" style="position: absolute; left: 408px; top: 8px; border-radius: 5px 5px 5px 5px;">
                                    <h3 style="position: absolute; left: 500px; top: 104px;" class="di">第一个吃flutter2.0的,踩了这些坑</h3>
                                    <div style="position: absolute; left: 500px; top: 150px; width:40px; height:40px; border-radius:50%; overflow:hidden;  border: 1px solid rgb(0,0,0);"align="center">
                                        <img src="img/8.png" alt="正方形的原始图片" width="40" height="40">
                                        </div>
                                        <p style="position: absolute;left: 545px;top: 165px;">恋猫de小盾</p>
                                    <img src="img/5.jpg" width="90"  height="90" align="center" style="position: absolute; left: 408px; top: 106px; border-radius: 5px 5px 5px 5px;">
                                    <div style="position:absolute;left:500px;top: 265px; height:40px; border-radius:50%; overflow:hidden;  border: 1px solid rgb(0,0,0);"align="center">
                                        <img src="img/头像.jpg" alt="正方形的原始图片" width="40" height="40">
                                        </div>
                                        <p></p>
                                    <h3 style="position: absolute; left: 500px; top: 202px;" class="zhuhe">祝贺个人博客网开发进度已达百分之三十</h3>
                                    <img src="img/6.jpg" width="90"  height="90" align="center" style="position: absolute; left: 408px; top:204px; border-radius: 5px 5px 5px 5;">
                                </div>
                                    <img src="img/9.png" style="width: 910px; height: 80px; border: 1px solid rgb(0,0,0);position: absolute;top: 550px; left: 0px;">
                                    <div style="width: 910px; height: 450px;position: absolute;top: 633px;">
                                        <img src="img/10.png" width="44" height="44" class="imga" style="position: absolute; top: 5px;">
                                        <h4 class="java" style="position: absolute; left: 53px;">java</h4>
                                        <div style="width: 420px; height: 120px; background-color: rgb(255, 255, 255); position: absolute;top: 50px; left: 10px; border-radius: 5px 5px 5px 5px; box-shadow:1px 1px 5px 5px #888888">
                                            <div class="tupian">
                                                <img src="img/11.jpg" width="190" height="100">
                                                </div>
                                            <h3 style="position: absolute; left: 200px; top: 0px;">JDK9对String字符串的新一....</h3>
                                            <p style="position: absolute; left: 200px; top: 50px; color: rgb(153,153,153);">JDK9对String字符串的新一轮优化，不可不知</p>
                                            </div>
                                            <div style="width: 420px; height: 120px; background-color: rgb(255,255,255); position: absolute;top: 50px; left: 480px; box-shadow: 1px 1px 5px 5px #888888;
                                            border: px solid black; border-radius: 5px 5px 5px 5px;">
                                            <div class="tupianto">
                                                <img src="img/12.jpg" width="190" height="100">
                                                </div>
                                                <h3 style="position: absolute; left: 200px;">java基础学习总结147....</h3>
                                                <p style="position: absolute; left: 200px; top: 35px; color:rgb(153,153,153)">Java基础学习总结（174）——Java 开发者应该会的流程图绘制技巧</p>
                                                </div>
                                                <div style="width: 420px; height: 220px; border: 1px solid rgb(0,0,0); position: absolute;top: 190px; left: 10px; border-radius: 5px 5px 5px 5px;" class="diyi">
                                                    <ul>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li><b>lock的优势与特征</b></li></a>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 50px;"><b>Dubbo 版 Swagger 来啦！</b></li></a>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 80px;"><b>一文带你搞懂从动态代理实现到Spring AOP</b></li></a>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 115px;"><b>实现网页长截图的常见思路总结</b></li></a>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 150px;"><b>Java 类加载器 ClassLoader 详解与双亲委托模型</b></li></a>
                                                        </ul>
                                                </div>
                                                <div style="width: 420px; height: 220px; border:1px solid rgb(0,0,0); position: absolute;top: 190px; left: 480px;" class="dito">
                                                    <ul>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li><b>lock的优势与特征</b></li></a>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 50px;"><b>JDK&nbsp;的optional</b></li></a>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 80px;"><b>sparing boot2.x基础教程:使用flyway管理数据库版本</b></li></a>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 115px;"><b>spring boot文件上传功能 实现与简单示例</b></li></a>
                                                        <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 150px;"><b>疑难杂症之灾一切 网络中断，怎么 破?</b></li></a>
                                                        </ul>
                                        </div>
                            </div>
                            <img src="img/13.png" style="position: absolute; top: 1050px; width: 44px; height: 44px; left: 1px;">
                            <div style="width: 910px; height: 450px;position: absolute;top: 1050px;">
                                <div style="width: 420px; height: 120px; background-color: rgb(255, 255, 255); position: absolute;top: 50px; left: 10px; border-radius: 5px 5px 5px 5px; box-shadow:1px 1px 5px 5px #888888">
                                    <div class="tupian">
                                        <img src="img/14.jpg" width="190" height="100">
                                        </div>
                                    <h3 style="position: absolute; left: 200px; top: 0px;"><a href="#" style="color: rgb(0,0,0); text-decoration: none;">教父：花半分钟就看透事物....</h3>
                                    <p style="position: absolute; left: 200px; top: 50px; color: rgb(153,153,153);">教父：花半分钟就看透事物，和花一辈子都看不清本质的人，注定是截然不同的命运...</p>
                                    </div>
                                    <div style="width: 420px; height: 120px; background-color: rgb(255,255,255); position: absolute;top: 50px; left: 480px; box-shadow: 1px 1px 5px 5px #888888;
                                    border: px solid black; border-radius: 5px 5px 5px 5px;">
                                    <div class="tupianto">
                                        <img src="img/15.jpg" width="190" height="100">
                                        </div>
                                        <h3 style="position: absolute; left: 200px;"><a href="#" style="color: rgb(0,0,0); text-decoration: none;">写给人生的九封信，愿你的....</h3>
                                        <p style="position: absolute; left: 200px; top: 48px; color:rgb(153,153,153)">写给人生的九封信，愿你的人生淡定从容，繁华似锦！！！</p>
                                        </div>
                                        <div style="width: 420px; height: 220px; border: 1px solid rgb(0,0,0); position: absolute;top: 190px; left: 10px; border-radius: 5px 5px 5px 5px;" class="diyi">
                                            <ul>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li><b>活该你是工程师（自序）</b></li></a>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 50px;"><b>人人都有认知障</b></li></a>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 80px;"><b>做一个很出色的程序员</b></li></a>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 115px;"><b>做一个很出色的程序员</b></li></a>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 150px;"><b>沉迷游戏自学编程，创建游戏帝国，却黯然退场的“鬼才...</b></li></a>
                                                </ul>
                                        </div>
                                        <div style="width: 420px; height: 220px; border:1px solid rgb(0,0,0); position: absolute;top: 190px; left: 480px;" class="dito">
                                            <ul>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li><b>技术经理成长复盘-核心骨干主动离职的影响</b></li></a>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 50px;"><b>春节之后，我有了这些感悟</b></li></a>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 80px;"><b>技术经理成长复盘-聊聊核心骨干</b></li></a>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 115px;"><b>博客之星心灵感悟</b></li></a>
                                                <a href="" style="color: rgb(0,0,0); text-decoration: none;"><li style="position: absolute; top: 150px;"><b>十三个世界著名的定律</b></li></a>
                                                </ul>
                                </div>
                    </div>
                    <div style="width: 910px; height: 120px; position: absolute; top: 1500px; border:1px solid rgb(211, 211, 211);background-color: rgb(246,246,246);">
                        <div style="position: absolute; left: 10px;top: 20px;">
                        <img src="img/15.png" style="width:44px; height:44px; ">  
                        <img src="img/16.png" style="width:44px; height:44px; ">  
                        <img src="img/17.png" style="width:44px; height:44px; ">  
                        </div>
                            <h3 style="position: absolute; left: 10px;top: 55px;">首页</h3>
                            <h3 style="position: absolute; left: 60px; top: 55px;">动态</h3>
                            <h3 style="position: absolute; top: 55px; left: 110px;">排行</h3>
                            <p style="float:left;margin-top: 30px;width: 1px;height: 40px; background: rgb(0, 0, 0);position: absolute;left: 180px;"></p>
                                <h4 style="position: absolute; top:1px; left: 200px;">python</h4>
                                <h4 style="position:absolute;top:45px; left:200px">游戏开发</h4>
                                <h4 style="position:absolute;top:45px; left:300px">运维</h4>
                                <h4 style="position:absolute;top:1px; left: 300px">java</h4>
                                <h4 style="position:absolute;top:45px; left:380px">程序人生</h4>
                                <h4 style="position:absolute;top:1px; left:380px">信息安全</h4>
                                <h4 style="position:absolute;top:1px; left:480px">研发管理</h4>
                                <h4 style="position:absolute;top:45px; left:480px">移动开发</h4>
                                <h4 style="position:absolute;top:45px; left:580px">数据库</h4>
                                <h4 style="position:absolute;top:1px; left:580px">物联网</h4>
                                <h4 style="position:absolute;top:1px; left:680px">前端</h4>
                                <h4 style="position:absolute;top:45px; left:680px">其他</h4>
                                <div style="position: absolute; left: 730px; top: 5px; width: 160px; height: 80px;border: 1px solid rgb(0, 0, 0)">
                                    <img src="img/18.png" style="width: 30px;height: 30px;position: absolute;top: 13px;">
                                    <h4 style="position: absolute;left: 32px;top: 0px;">直播</h4>
                                    <img src="img/19.png" style="position: absolute;top: 13px;left: 85px;width: 30px;height: 30px;">
                                    <h4 style="position: absolute;left: 115px;top: 0px;">专栏</h4>
                                    <img src="img/20.png" style="position: absolute; top: 50px;width: 30px;height: 30px;">
                                    <h4 style="position: absolute;top: 35px;left: 32px;">活动</h4>
                                    <img src="img/21.png" style="position: absolute;top: 50px;left: 85px;width: 30px;height: 30px;">
                                    <h4 style="position: absolute; left: 115px;top: 35px;">学习</h4>
                                </div>
                            </div>
                            <img src="img/25.png" width="44" height="44" style="position: absolute;top: 1630px;left: 10px;">
                            <h4 style="position: absolute;top:1625px;left: 54px;">技术社区</h4>
                            <div style="width: 890px;height: 600px;position: absolute;top:1680px;left: 10px;">
                                <div style="width: 420px;height: 250px;border: 1px solid rgb(0,0,0);" class="jishushequ">
                                    <ul>
                                        <a href="#" style="color:rgb(129, 127, 127);text-decoration: none;"><li>【直播预告】20年码龄的技术VC大咖详解数据编码</li></a>
                                        <li style="position: absolute;top: 50px;"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">【回看】成为软件工程师，这些技术就够了！</a></li>
                                        <li style="position: absolute;top: 85px;"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">每周训练5小时，自信从容进大厂</a></li>
                                        <li style="position:absolute;top:120px"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">Java 最常见的 200+ 面试题：面试必备</a></li>
                                        </ul>
                                        <div style="width: 400px;height: 70px;border: 1px solid rgb(0,0,0);position: absolute;left: 10px;top: 170px;border-radius: 5px 5px 5px 5px;">
                                            <img src="img/7.png" width="35" height="35" style="position: absolute;top: 15px;">
                                            <h5 style="position: absolute;left: 40px;top: 5px;"><a href="#" style="color: rgb(0,0,0);text-decoration: none;">高校俱乐部</a></h5>
                                            <img src="img/26.png" style="position: absolute;left: 130px;top: 23px;" width="18" height="18">
                                            <h5 style="position: absolute;left: 151px; top: 4px;">1154</h5>
                                            <img src="img/27.png" style="position: absolute;left: 206px;top: 23px;" width="18" height="18">
                                            <h5 style="position: absolute;left: 226px; top: 4px;">1154</h5>
                                            <div style="width: 80px; height: 30px;border: 1px solid rgb(0,0,0);position: absolute;top: 20px; left: 288px;border-radius: 20px;">
                                                <p style="position: absolute;left: 8px;top: -8px;"><a href="#" style="color: rgb(0,0,0);text-decoration: none;">进入社区</a></p>
                                                </div>
                                            </div>
                                </div>
                                <div style="width: 420px;height: 250px;border:1px solid rgb(0,0,0);position: absolute;left: 460px;top: 0px;">
                                    <ul>
                                        <li><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">98*上天的源码要不要：GitHub 热点速览 v.21.08</li>
                                        <li style="position: absolute;top: 50px;"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">开篇词：为什么学习可视化，应该怎么学</a></li>
                                        <li style="position: absolute;top: 85px;"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">聚合云监测背景介绍</a></li>
                                        <li style="position:absolute;top:120px"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">企业级数据服务API工具</a></li>
                                        </ul>
                                        <div style="width: 400px;height: 70px;border: 1px solid rgb(0,0,0);position: absolute;left: 10px;top: 170px;border-radius: 5px 5px 5px 5px;">
                                            <img src="img/7.png" width="35" height="35" style="position: absolute;top: 15px;">
                                            <h5 style="position: absolute;left: 40px;top: 5px;"><a href="#" style="color: rgb(0,0,0);text-decoration: none;">高校俱乐部</a></h5>
                                            <img src="img/26.png" style="position: absolute;left: 130px;top: 23px;" width="18" height="18">
                                            <h5 style="position: absolute;left: 151px; top: 4px;">1154</h5>
                                            <img src="img/27.png" style="position: absolute;left: 206px;top: 23px;" width="18" height="18">
                                            <h5 style="position: absolute;left: 226px; top: 4px;">1154</h5>
                                            <div style="width: 80px; height: 30px;border: 1px solid rgb(0,0,0);position: absolute;top: 20px; left: 288px;border-radius: 20px;">
                                                <p style="position: absolute;left: 8px;top: -8px;"><a href="#" style="color: rgb(0,0,0);text-decoration: none;">进入社区</a></p>
                                                </div>
                                            </div>
                                </div>
                                <div style="width: 420px; height: 250px;border: 1px solid rgb(0,0,0);position: absolute;top: 260px;">
                                    <ul>
                                    <li><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">98*上天的源码要不要：GitHub 热点速览 v.21.08</li>
                                        <li style="position: absolute;top: 50px;"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">开篇词：为什么学习可视化，应该怎么学</a></li>
                                        <li style="position: absolute;top: 85px;"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">聚合云监测背景介绍</a></li>
                                        <li style="position:absolute;top:120px"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">企业级数据服务API工具</a></li>
                                        </ul>
                                        <div style="width: 400px;height: 70px;border: 1px solid rgb(0,0,0);position: absolute;left: 10px;top: 170px;border-radius: 5px 5px 5px 5px;">
                                            <img src="img/7.png" width="35" height="35" style="position: absolute;top: 15px;">
                                            <h5 style="position: absolute;left: 40px;top: 5px;"><a href="#" style="color: rgb(0,0,0);text-decoration: none;">高校俱乐部</a></h5>
                                            <img src="img/26.png" style="position: absolute;left: 130px;top: 23px;" width="18" height="18">
                                            <h5 style="position: absolute;left: 151px; top: 4px;">1154</h5>
                                            <img src="img/27.png" style="position: absolute;left: 206px;top: 23px;" width="18" height="18">
                                            <h5 style="position: absolute;left: 226px; top: 4px;">1154</h5>
                                            <div style="width: 80px; height: 30px;border: 1px solid rgb(0,0,0);position: absolute;top: 20px; left: 288px;border-radius: 20px;">
                                                <p style="position: absolute;left: 8px;top: -8px;"><a href="#" style="color: rgb(0,0,0);text-decoration: none;">进入社区</a></p>
                                                </div>
                                            </div>
                                </div>
                                <div style="width: 420px; height: 250px; border: 1px solid rgb(0,0,0); position: absolute;top: 260px;left: 460px;">
                                    <ul>
                                    <li><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">98*上天的源码要不要：GitHub 热点速览 v.21.08</li>
                                        <li style="position: absolute;top: 50px;"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">开篇词：为什么学习可视化，应该怎么学</a></li>
                                        <li style="position: absolute;top: 85px;"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">聚合云监测背景介绍</a></li>
                                        <li style="position:absolute;top:120px"><a href="#" style="color:rgb(129, 127, 127);text-decoration: none;">企业级数据服务API工具</a></li>
                                        </ul>
                                        <div style="width: 400px;height: 70px;border: 1px solid rgb(0,0,0);position: absolute;left: 10px;top: 170px;border-radius: 5px 5px 5px 5px;">
                                            <img src="img/7.png" width="35" height="35" style="position: absolute;top: 15px;">
                                            <h5 style="position: absolute;left: 40px;top: 5px;"><a href="#" style="color: rgb(0,0,0);text-decoration: none;">高校俱乐部</a></h5>
                                            <img src="img/26.png" style="position: absolute;left: 130px;top: 23px;" width="18" height="18">
                                            <h5 style="position: absolute;left: 151px; top: 4px;">1154</h5>
                                            <img src="img/27.png" style="position: absolute;left: 206px;top: 23px;" width="18" height="18">
                                            <h5 style="position: absolute;left: 226px; top: 4px;">1154</h5>
                                            <div style="width: 80px; height: 30px;border: 1px solid rgb(0,0,0);position: absolute;top: 20px; left: 288px;border-radius: 20px;">
                                                <p style="position: absolute;left: 8px;top: -8px;"><a href="#" style="color: rgb(0,0,0);text-decoration: none;">进入社区</a></p>
                                                </div>
                                            </div>
                                    </div>
                            </div>
                            <img src="img/1615972401951.jpg" style="width: 910px; height: 80px; border: 1px solid rgb(0,0,0);position: absolute;top: 2200px; left: 0px;">
                            <div style="position: absolute;top:2300px;width: 890px;height: 150px;border: 1px solid rgb(0,0,0);left: 10px;" class="yqlj">
                                <img src="img/30.png" width="44" height="44">
                                <h3 style="position: absolute;left: 45px;top: -5px;">友情链接</h3>
                                <div style="width: 150px;height: 50px;border: 1px solid rgb(153,153,153); position: absolute;left: 10px; border-radius: 5px;">
                                    <p style="font-size: 25px; position: absolute;top: -13px;left: 25px; color: rgb(153,153,153);"><a href="#" style="color: rgb(153,153,153);text-decoration: none;">视觉中国</a></p>
                                </div>
                                <div style="width: 150px;height: 50px;border: 1px solid rgb(153,153,153); position: absolute;left: 200px; border-radius: 5px;">
                                    <p style="font-size: 25px; position: absolute;top: -13px;left: 25px; color: rgb(153,153,153);"><a href="#" style="color: rgb(153,153,153);text-decoration: none;">BOSS直聘</a></p>
                                </div>
                                <div style="width: 130px;height: 50px;border: 1px solid rgb(153,153,153); position: absolute;left: 400px; border-radius: 5px;">
                                    <p style="font-size: 25px; position: absolute;top: -13px;left: 25px; color: rgb(153,153,153);"><a href="#" style="color: rgb(153,153,153);text-decoration: none;">看准网</a></p>
                                </div>
                                <div style="width: 100px;height: 50px;border: 1px solid rgb(153,153,153); position: absolute;left: 600px; border-radius: 5px;">
                                    <p style="font-size: 25px; position: absolute;top: -13px;left: 25px; color: rgb(153,153,153);"><a href="#" style="color: rgb(153,153,153);text-decoration: none;">Veer</a></p>
                                </div>
                                </div> 
                                <div style="width: 890px;height: 550px;position: absolute;top: 2440px;left: 10px;"> 
                                    <div class="bear"></div>
                                    <div class="bg1"></div>
                                    <div class="bg2"></div>
                                    </div>     
                        </div>
                        <div style="width:1509px;height: 236px;border: 1px solid rgb(0, 0, 0);position: absolute;top:3061px;background-color: rgb(126, 136, 156);">
                            </div>
            </body>
    </html>
