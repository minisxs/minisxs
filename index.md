
<!DOCTYPE html>
<html>
<head><meta http-equiv="Content-Type" content="text/html; charset=gb18030">
<link rel="shortcut icon"  type="image/x-icon"   href="-favicon.ico"/>
<LINK href="favicon.ico" type="image/x-icon" rel="icon" />
<title>剑灵软萌萌活动助手--官网网站</title>
<meta name="description" content="剑灵软萌萌活动助手可以帮您快速领取游戏礼包、刷帮豆、签到等各种功能,本软件快速、安全、高效是您的不二选择" />
<meta name="keywords" content="软萌萌活动助手,剑灵小助手,剑灵活动助手,剑灵助手官网,剑灵活动一键，剑灵,帮豆,剑灵礼包助手,刷帮豆软件,剑灵一键领取奖励,逆战,剑灵礼包" />
<link rel="stylesheet" href="css/header.css">
<link rel="stylesheet" href="css/style.css">
</head>
<body>
<div class="header">
    <div class="head">
        <div class="logo_box">
            <h1 class="hide_txt png"><a href="/" title="软萌萌">剑灵软萌萌活动助手</a></h1>
            <a href="**" class="btn_download">立即**</a>
        </div>
        <div class="nav_box" id="h_nav">
            <a href="#">主页</a>
            <a href="http://t.cn/EMtqdDp" target="_blank" >前往购买</a>
            <span class="ic_line"></span>
        </div>
    </div>
</div>
<div class="wrap" id="wrap">
    <div class="wrapper">
        <div class="main_sec">
            <ul class="page_list" id="page_list">
                <li class="page page1 show">
                    <div class="p_wrap">
                        <div class="content">
                            <div class="value_box">
                                <h2 class="hide_txt png">剑灵软萌萌活动助手——快速、安全、高效</h2>
								  <div class="btn_box clearfix"> <a href="http://t.cn/EMtqdDp" target="_blank" class="btn_download" title="前往购买">前往购买</a> </div>
								   <div class="msg_box">
								   <p>购买成功后会出现VIP版下载方式购买后可以使用全部功能哦</p>
								   <p>软萌萌活动助手能够帮您一键领取活动奖励、帮豆一键获取兑换解放双手</p>
								   <p>正常情况下帮豆每天可以领取兑奖两张100W经验符助你洪门星级快速提升</p>
								   <!--p>FZSM</p-->
								   </div>
                            </div>
                            <div class="ic_box">
                                <i class="ic_1 png"></i>
                                <i class="ic_2 png"></i>
                                <i class="ic_3 png"><i class="ic_31 png"></i></i>
                            </div>
                        </div>
                    </div>
                </li>
            <div class="control_box" id="control_box">
                <a href="javascript:;" class="btn_change on"><i class="png"></i></a>
                <a href="javascript:;" class="btn_change"><i class="png"></i></a>
                <a href="javascript:;" class="btn_change"><i class="png"></i></a>
                <a href="javascript:;" class="btn_change"><i class="png"></i></a>
            </div>
        </div>
    </div>
    </div>
    <div class="sys_footer">
    <div class="foot">
        <p class="links">
        <p></p>
    </div>
</div>
<script src="js/jquery.js"></script>
<script src="js/pageScoller.js"></script>
<script>
(function(){


    var $hNav=$("#h_nav"),
        $hLinks=$hNav.find("a"),
        $hLine=$hNav.find(".ic_line");
    var lens=function(){
            var l1=[],l2=[];
            for(var i=0;i<$hLinks.length;i++){
                l1.push($hLinks.eq(i).outerWidth());
                l2.push($hLinks.eq(i).width());
            }
            return {left:l1,width:l2};
        }();
    var getLeft=function(idx){
        var s=0;
        for(var i=0;i<idx;i++){
            s+=lens.left[i];
        }
        return s;
    };
    $hNav.on("mouseenter",function(){
        $hLine.show();
    })
    $hNav.on("mouseleave",function(){
        $hLine.hide();
    })
    $hLinks.on("mouseenter",function(){
        var idx=$hLinks.index(this);
        $hLine.css({left:getLeft(idx)+15,width:lens.width[idx]});
    })

</script>
<script src="https://s4.cnzz.com/z_stat.php?id=1261889513&web_id=1261889513" language="JavaScript"></script>
</body>
</html>

