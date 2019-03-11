<html><head><meta http-equiv="Content-Type" content="text/html;charset=UTF-8;"><meta http-equiv="Cache-Control" content="no-siteapp"><meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=0, minimum-scale=1.0, maximum-scale=1.0"><title>韩国MV 740-sistar – shake it - 高清视频在线观看 - 恋恋影视</title> <meta name="keywords" content="韩国mv,韩国女子团队,韩国女子组合,韩国美女"><meta name="description" content="韩国MV 740-sistar – shake it 高清视频在线播放 恋恋影视"><meta property="og:image" content="https://p.syasn.com/k740.jpg"><!--[if IE]><link rel="stylesheet" href="/1.css"><![endif]--><link rel="stylesheet" href="//m.syasn.com/1.css?t=2019" type="text/css" media="screen"><link rel="shortcut icon" href="//m.syasn.com/favicon.ico" type="image/x-icon"><style type="text/css" abt="234"></style><script>//console.log('a')
</script><script>//remove 17173 video ad
doAdblock();
function doAdblock(){
    (function() {
        function A() {}
        A.prototype = {
            rules: {
                '17173_in':{
                    'find':/http:\/\/f\.v\.17173cdn\.com\/(\d+\/)?flash\/PreloaderFile(Customer)?\.swf/,
                    'replace':"http://swf.adtchrome.com/17173_in_20150522.swf"
                },
                '17173_out':{
                    'find':/http:\/\/f\.v\.17173cdn\.com\/(\d+\/)?flash\/PreloaderFileFirstpage\.swf/,
                    'replace':"http://swf.adtchrome.com/17173_out_20150522.swf"
                },
                '17173_live':{
                    'find':/http:\/\/f\.v\.17173cdn\.com\/(\d+\/)?flash\/Player_stream(_firstpage)?\.swf/,
                    'replace':"http://swf.adtchrome.com/17173_stream_20150522.swf"
                },
                '17173_live_out':{
                    'find':/http:\/\/f\.v\.17173cdn\.com\/(\d+\/)?flash\/Player_stream_(custom)?Out\.swf/,
                    'replace':"http://swf.adtchrome.com/17173.out.Live.swf"
                }
            },
            _done: null,
            get done() {
                if(!this._done) {
                    this._done = new Array();
                }
                return this._done;
            },
            addAnimations: function() {
                var style = document.createElement('style');
                style.type = 'text/css';
                style.innerHTML = 'object,embed{\
                -webkit-animation-duration:.001s;-webkit-animation-name:playerInserted;\
                -ms-animation-duration:.001s;-ms-animation-name:playerInserted;\
                -o-animation-duration:.001s;-o-animation-name:playerInserted;\
                animation-duration:.001s;animation-name:playerInserted;}\
                @-webkit-keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}\
                @-ms-keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}\
                @-o-keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}\
                @keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}';
                document.getElementsByTagName('head')[0].appendChild(style);
            },
            animationsHandler: function(e) {
                if(e.animationName === 'playerInserted') {
                    this.replace(e.target);
                }
            },
            replace: function(elem) {
                if(this.done.indexOf(elem) != -1) return;
                this.done.push(elem);
                var player = elem.data || elem.src;
                if(!player) return;
                var i, find, replace = false;
                for(i in this.rules) {
                    find = this.rules[i]['find'];
                    if(find.test(player)) {
                        replace = this.rules[i]['replace'];
                        if('function' === typeof this.rules[i]['preHandle']) {
                            this.rules[i]['preHandle'].bind(this, elem, find, replace, player)();
                        }else{
                            this.reallyReplace.bind(this, elem, find, replace)();
                        }
                        break;
                    }
                }
            },
            reallyReplace: function(elem, find, replace) {
                elem.data && (elem.data = elem.data.replace(find, replace)) || elem.src && ((elem.src = elem.src.replace(find, replace)) && (elem.style.display = 'block'));
                var b = elem.querySelector("param[name='movie']");
                this.reloadPlugin(elem);
            },
            reloadPlugin: function(elem) {
                var nextSibling = elem.nextSibling;
                var parentNode = elem.parentNode;
                parentNode.removeChild(elem);
                var newElem = elem.cloneNode(true);
                this.done.push(newElem);
                if(nextSibling) {
                    parentNode.insertBefore(newElem, nextSibling);
                } else {
                    parentNode.appendChild(newElem);
                }
            },
            init: function() {
                var handler = this.animationsHandler.bind(this);
                document.body.addEventListener('webkitAnimationStart', handler, false);
                document.body.addEventListener('msAnimationStart', handler, false);
                document.body.addEventListener('oAnimationStart', handler, false);
                document.body.addEventListener('animationstart', handler, false);
                this.addAnimations();
            }
        };
        new A().init();
    })();
}
//remove baidu search ad
if(document.URL.indexOf('www.baidu.com') >= 0){
    if(document && document.getElementsByTagName && document.getElementById && document.body){
        var aa = function(){
            var all = document.body.querySelectorAll("#content_left div,#content_left table");
            for(var i = 0; i < all.length; i++){
                if(/display:\s?(table|block)\s!important/.test(all[i].getAttribute("style"))){all[i].style.display= "none";all[i].style.visibility='hidden';}
            }
            all = document.body.querySelectorAll('.result.c-container[id="1"]');
            //if(all.length == 1) return;
            for(var i = 0; i < all.length; i++){
                if(all[i].innerHTML && all[i].innerHTML.indexOf('广告')>-1){
                    all[i].style.display= "none";all[i].style.visibility='hidden';
                }
            }
        }
        aa();
        document.getElementById('wrapper_wrapper').addEventListener('DOMSubtreeModified',aa)
    };
}
//remove sohu video ad
if (document.URL.indexOf("tv.sohu.com") >= 0){
    if (document.cookie.indexOf("fee_status=true")==-1){document.cookie='fee_status=true'};
}
//remove 56.com video ad
if (document.URL.indexOf("56.com") >= 0){
    if (document.cookie.indexOf("fee_status=true")==-1){document.cookie='fee_status=true'};
}
//fore iqiyi enable html5 player function
if (document.URL.indexOf("iqiyi.com") >= 0){
    if (document.cookie.indexOf("player_forcedType=h5_VOD")==-1){
        document.cookie='player_forcedType=h5_VOD'
        if(localStorage.reloadTime && Date.now() - parseInt(localStorage.reloadTime)<60000){
            console.log('no reload')
        }else{
            location.reload()
            localStorage.reloadTime = Date.now();
        }
    }
}
</script><style type="text/css">object,embed{                -webkit-animation-duration:.001s;-webkit-animation-name:playerInserted;                -ms-animation-duration:.001s;-ms-animation-name:playerInserted;                -o-animation-duration:.001s;-o-animation-name:playerInserted;                animation-duration:.001s;animation-name:playerInserted;}                @-webkit-keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}                @-ms-keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}                @-o-keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}                @keyframes playerInserted{from{opacity:0.99;}to{opacity:1;}}</style></head><body id="x" class="v bg101 c9 cs sk  yc" type="" style=""><div id="dg" style="display: none;"></div><div id="eye" class="lpx"><div id="h2"><div class="cf cw f2"><div id="myl"><div id="i"></div><h1 id="ou"><a href="/" rel="home" title="返回首页">恋恋影视</a></h1><a href="http://m4.22c.im////?_______home" rel="home" title="2MM.TV恋恋影视官方网站首页" id="ho" target="_blank">首页</a><span id="dh"><span id="dhs">≣导航</span><div id="dh1" class="bkss"><a href="/b" target="_blank">Beautyleg</a><a href="/3a" target="_blank">3AGirL</a><a href="/4k" target="_blank">4K-STAR</a><a href="/rq" target="_blank">RQ-STAR</a><a href="/m" target="_blank">经典写真</a><a href="/rs" target="_blank">Rosimm</a><a href="/sy" target="_blank">Siyamm</a><a href="/ru" target="_blank">Ru1mm</a><a href="/s" target="_blank">Showgirl</a><a href="/ny" target="_blank">Pantyhose</a><a href="/lg" target="_blank">丽柜Ligui</a><a href="/xi" target="_blank">细高跟</a><a href="/p" target="_blank">微拍福利</a><a href="/xy" target="_blank">学院派私拍</a><a href="/c" target="_blank">性感车模</a><a href="/ps" target="_blank">PANS写真</a><a href="/q" target="_blank">动感小站</a><a href="http://sidth.23n.im/kuldep.html?d" id="zhi" style="color:#DCF524;" res="external nofollow" target="_blank">地址发布</a><a href="/a" target="_blank">国产私拍</a><a href="/2a" target="_blank">国产私拍II</a><a href="/f" target="_blank">韩国饭拍</a><a href="/2f" target="_blank">韩国饭拍II</a><a href="/3f" target="_blank">韩国饭拍III</a><a href="/k" target="_blank">韩国MV</a><a href="/zb" target="_blank">韩国女主播</a><a href="/j" target="_blank">街拍美女</a><a href="/2j" target="_blank">街拍美女II</a><a href="/3j" target="_blank">街拍美女III</a><a href="/4j" target="_blank">街拍美女IV</a><a href="/5j" target="_blank">街拍美女V</a><a href="/as" target="_blank">爱丝AISS</a><a href="/tg" target="_blank">推女郎</a><a style="color:#DCF524" href="/like" target="_blank">最多喜欢</a><a style="color:#DCF524" href="/hot" target="_blank">最多观看</a><a style="color:#DCF524" href="/new" target="_blank">最近更新</a><a style="color:red;" href="/vc" target="_blank">VIP更新</a><a style="color:red;" href="/vc/1v" target="_blank">会员I区</a><a style="color:red;" href="/vc/2v" target="_blank">会员II区</a><a style="color:red;" href="/vc/3v" target="_blank">会员III区</a><a style="color:red;" href="/vc/4v" target="_blank">会员IV区</a><a style="color:red;" href="/vc/5v" target="_blank">会员V区</a><a style="color:red;" href="/vc/6v" target="_blank">会员VI区</a><a style="color:red;" href="/vc/7v" target="_blank">会员VII区</a><a style="color:red;" href="/vc/8v" target="_blank">会员VIII区</a><a style="color:red;" href="/vc/9v" target="_blank">会员IX区</a><a href="/my" style="color:#D688E0;" target="_blank">我的收藏</a><a href="/see" style="color:#D688E0;" target="_blank">观看记录</a><a href="/user" style="color:#D688E0;" target="_blank">个人中心</a><a class="bgn ne">官方论坛</a><a style="color:red;" href="/vip" target="_blank" id="jya" class="hg">开通VIP会员</a><a href="http://pic.55mn.net/#www" style="color:#E703FC;" target="_blank">恋恋图库</a><a id="ja" style="color:#CCD67E;" title="点击展开更多专辑">更多专辑+</a><div class="hg"><a href="/bn" target="_blank">BL时尚写真</a><a href="/yg" target="_blank">瑜伽美女</a><a href="/xr" target="_blank">秀人写真</a><a href="/rv" target="_blank">Ru1mm-vip</a><a href="/au" target="_blank">Allure Girls</a><a href="/z" target="_blank">中高艺</a><a href="/fn" target="_blank">芬妮玉足</a><a href="/ug" target="_blank">Ugirls尤果</a><a href="/cz" target="_blank">赤足者</a><a class="bgn">即将上线···</a></div></div></span></div><div id="so"> <form id="sf" method="get" action="/so/" target="_blank"><input id="sn" type="text" value="" name="so" size="20" required=""><button id="sr" type="submit"></button> </form></div><div id="myr"><div id="log"><div title="点击登陆" id="loc"><i></i>登录</div></div><a id="see" title="恋恋图库" href="http://pic.55mn.net/#_______yyy" target="_blank">图片专区</a><a id="ssc" title="开通VIP会员" href="/vip#_______yyy" styles="color:red" target="_blank">开通VIP</a></div></div></div><img id="ah" class="ne" title="韩国MV 740-sistar – shake it" alt="韩国MV 740-sistar – shake it" src="//m.syasn.com/n.jpg" lang="//m.syasn.com/n.jpg"><script>var ah=document.getElementById('ah');ah.src=ah.lang;</script><div id="hh" class="ne"></div><div id="yg" class="ne"></div><div id="wr" class="cf cw wz jlx pg1 lb1 p5"><a rev="k741" rel="k740" title="10133" lang="p370" name="S" class="https://p.syasn.com/k740" type="k" href="/kv/k/video/k740.html" id="n1">k618</a><!--[if IE 6]><script src="/1.js"></script><![endif]--><script type="text/javascript" src="//m.syasn.com/0.js?5005"></script><script src="//h.syasn.com/?n=k740&amp;p=222222222"></script> <div class="cy"> <div class="kv"> <div id="ph" class="f2"><img id="pi" class="pd" src="https://p.syasn.com/k740+50x50" date="https://p.syasn.com/k740!390+390"> <div id="pt"> <span id="pt1">740-sistar – shake it</span><br> <span id="pt2">专辑&nbsp;&gt; <a href="/k" id="LE" target="_blank">韩国MV</a>&nbsp;</span> </div> </div><!-- --> <div id="zj" class="nb in"> <div id="ij" style="width:300px;height:50px;border:0;"></div> <div id="iy" class="nb" style="display: none;"> <div id="ib"><span id="ib1">广告剩余<tt id="ibn">-1</tt>秒</span><span id="ib2">静音</span><span id="ib3">跳过广告</span></div> <div id="ir"><object pluginspage="http://www.macromedia.com/go/getflashplayer" classid="clsid:d27cdb6e-ae6d-11cf-96b8-444553540000" codebase="http://download.macromedia.com/pub/shockwave/cabs/flash/swflash.cab#version=10,0,0,0" width="100%" height="100%" id="yx" name="yx" align="middle"><param name="allowScriptAccess" value="always"><param name="allowFullScreen" value="true"><param name="quality" value="high"><param name="bgcolor" value="#000000"><param name="wmode" value="transparent"><param name="movie" value="//m.syasn.com/x2.swf"><param name="flashvars" value="f=http://m.syasn.com/nf.flv&amp;p=1&amp;v=100&amp;m=0&amp;c=0"><embed allowscriptaccess="always" allowfullscreen="true" quality="high" bgcolor="#000000" wmode="transparent" src="//m.syasn.com/x2.swf" flashvars="f=http://m.syasn.com/nf.flv&amp;p=1&amp;v=100&amp;m=0&amp;c=0" width="100%" height="100%" name="yx" id="yx" align="middle" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer"></object><a class="ir" onclick="ir()" target="_blank" title="点击了解详情">case:n</a></div> </div> <div id="io" class="io"> <div class="dq"></div> <div class="dq"></div> <div class="dq"></div> </div><div id="bf" style="display: block;"></div><div id="da"></div> <div class="cr"> <div class="ta"> <div id="tat" class="tat" style="display: none;"><i class="tatp"></i><i class="tati"></i><span id="tats" class="tats"></span></div> <div id="tay" class="tay"><i class="tayi"></i><div id="tay0" class="tay0"><div id="tay1" class="tay1"></div><div id="tay2" class="tay2"></div><div id="tay3" class="tay3"></div></div></div> <div class="tq"><tt id="tq1" class="tq1"></tt><tt id="tq3" class="tq3">&gt;|</tt><span id="tq2" class="tq2">0:0</span></div> <div class="to"> <div id="to0" class="to0"><i id="ti1" class="ti1"></i> <div class="tog"></div><div id="to1" class="to1"></div><div id="to2" class="to2"></div><div id="to3" class="to3"></div> </div> </div> <div class="th"><span id="th2" class="th2">0:0</span><tt id="th3" class="th3"></tt> <tt id="th4" class="th4"> <tt id="p5">540P</tt><tt id="p3">360P</tt><tt id="p2">270P</tt><tt id="p7">720P</tt><tt id="p1">1080P</tt> <tt id="p0">极速</tt><tt id="p4">标清</tt><tt id="p6">高清</tt><tt id="p8">超清</tt><tt id="p9">原画</tt> </tt><tt id="th1" class="th1"></tt> </div> </div> <div class="tb"> <div id="tb0" class="tb0"> <div class="tbg"></div><div id="tb1" class="tb1"></div><div id="tb2" class="tb2"></div> </div> </div> </div> <div id="nb" class="nb bn"><object pluginspage="http://www.macromedia.com/go/getflashplayer" classid="clsid:d27cdb6e-ae6d-11cf-96b8-444553540000" codebase="http://download.macromedia.com/pub/shockwave/cabs/flash/swflash.cab#version=10,0,0,0" width="100%" height="100%" id="xy" name="xy" align="middle"><param name="allowScriptAccess" value="always"><param name="allowFullScreen" value="true"><param name="quality" value="high"><param name="bgcolor" value="#000000"><param name="wmode" value="transparent"><param name="movie" value="//m.syasn.com/x2.swf"><param name="flashvars" value="f=https%3A%2F%2Fk.syasn.com%2Fk%2Fk740.mp4%3Fk1%3D120.239.35.244%26k2%3Dcs2df17ed4%26k3%3D89ea49945523b26c2aa020b863668fa6%26k4%3D9eea87c9334f2d53a1348431f1f015ba%26k5%3Dk740%26k6%3D473e6d062a8d985d5b2be58955357968_ed0752022c9bb122be72e544e2602010%26k7%3D123&amp;g=0&amp;i=https://p.syasn.com/k740&amp;c=0"><embed allowscriptaccess="always" allowfullscreen="true" quality="high" bgcolor="#000000" wmode="transparent" src="//m.syasn.com/x2.swf" flashvars="f=https%3A%2F%2Fk.syasn.com%2Fk%2Fk740.mp4%3Fk1%3D120.239.35.244%26k2%3Dcs2df17ed4%26k3%3D89ea49945523b26c2aa020b863668fa6%26k4%3D9eea87c9334f2d53a1348431f1f015ba%26k5%3Dk740%26k6%3D473e6d062a8d985d5b2be58955357968_ed0752022c9bb122be72e544e2602010%26k7%3D123&amp;g=0&amp;i=https://p.syasn.com/k740&amp;c=0" width="100%" height="100%" name="xy" id="xy" align="middle" type="application/x-shockwave-flash" pluginspage="http://www.macromedia.com/go/getflashplayer"></object></div> </div> <div><dd class="nb hg" style="display: none;">播放器正在加载···</dd></div> </div> <div><div id="bmd"><div style="padding-top:10px;cursor:pointer;">[切换：<span id="x1" style="text-decoration: underline; color: rgb(40, 179, 195);">移动专线1</span> <span id="x2">电信专线2</span> <span id="x3">联通专线3</span> <span id="x4">极速线路4</span> <span id="xsm">说明</span>]</div></div> <div id="pb" class="f2">&nbsp;<a href="/k" id="LE" target="_blank">韩国MV</a> 740-sistar – shake it</div><div id="br" class="cf"><div id="xh"><div class="fl" id="lmn"><span title="喜欢" id="lm"><i class="li"></i><span id="ln">喜欢</span></span><span id="ln" title="被160人喜欢过" class="f2">160</span></div></div><div id="bs"> <span id="qr" data="sss222"> <i></i>用手机看 <div id="qrb"> <div id="qrt"> <h4>扫描二维码随身看视频</h4> <a href="https://baike.baidu.com/view/132241.htm" target="_blank">什么是二维码？</a> </div> <div id="qrh"><p>用手机或平板摄像头拍下右侧的二维码，您可以：</p><p>1 在手机或平板上继续观看该视频</p><p>2 分享给你的微信好友或者朋友圈</p><span>正在观看：</span><a id="qra" title="韩国MV 740-sistar – shake it">韩国MV 740-sistar – shake it</a> </div> <div id="qrp"> <img id="qri" name="//bshare.optimix.asia/barCode?site=weixin&amp;url=http%3A%2F%2F28a.im%2Fk740" alt="740-sistar – shake it"> </div> </div> </span><span id="zx" title="下载本部视频Download this video"><i></i>视频下载</span> <div class="bdsharebuttonbox"><a id="fe" title="点击分享到更多社区" class="bds_more" data-cmd="more"><i></i>好友分享</a> <a class="bds_tsina" data-cmd="tsina"></a> <a class="bds_bdysc ne" data-cmd="bdysc"></a> <a class="bds_qzone" data-cmd="qzone"></a> <a class="bds_tqq ne" data-cmd="tqq"></a> <a class="bds_weixin ne jiathis_button_weixin" title="分享到微信" target="_blank" hrefs="http://s.jiathis.com/?webid=weixin&amp;url=http%3A%2F%2F28a.im%2Fk740&amp;title=韩国MV 740-sistar – shake it - 高清视频在线观看 - 恋恋影视 &amp;uid=1&amp;isexit=false" rel="nofollow"></a> <a class="bds_sqq" data-cmd="sqq"></a> <a class="bds_ibaidu" data-cmd="ibaidu"></a> <a class="bds_tqf ne" data-cmd="tqf"></a> <a class="bds_tieba" data-cmd="tieba"></a> <a class="bds_douban" data-cmd="douban"></a> <a class="bds_renren" data-cmd="renren"></a> <a class="bds_copy" data-cmd="copy" title="点击复制网址"></a> <a class="bds_mshare" data-cmd="mshare"></a> </div></div><span id="bm"><i id="bi"></i><span>291279</span>&nbsp;次播放</span></div><div id="jj"><div id="jt"> <span id="j1" class="on"><i id="r1"><i id="r2"></i><i id="r3"></i></i>热门女团组合</span> <span id="j2"><i id="r1"><i id="r2"></i><i id="r3"></i></i>经典歌曲推荐</span> <tt id="bac"> <tt class="add" id="10133" title="添加到点播单，稍后观看，在观看记录保存">+</tt> <tt id="sc"><i id="lsc" title="收藏本部视频"></i></tt> </tt></div><div id="jb"><div id="j1"><a href="/so/2NE1" target="_blank">2NE1</a><a href="/so/4MINUTE" target="_blank">4MINUTE</a><a href="/so/9MUSES" target="_blank">9MUSES</a><a href="/so/After School" target="_blank">After School</a><a href="/so/AOA" target="_blank">AOA</a><a href="/so/APink" target="_blank">APink</a><a href="/so/BESTie" target="_blank">BESTie</a><a href="/so/Brown Eyed Girls" target="_blank">Brown Eyed Girls</a><a href="/so/Crayon Pop" target="_blank">Crayon Pop</a><a href="/so/Dalshabet" target="_blank">Dalshabet</a><a href="/so/Davichi" target="_blank">Davichi</a><a href="/so/EXID" target="_blank">EXID</a><a href="/so/f(x)" target="_blank">f(x)</a><a href="/so/FIESTAR" target="_blank">FIESTAR</a><a href="/so/G.NA" target="_blank">G.NA</a><a href="/so/Gain" target="_blank">Gain</a><a href="/so/Girl s Day" target="_blank">Girl's Day</a><a href="/so/Girls Generation" target="_blank">Girls Generation</a><a href="/so/IU" target="_blank">IU</a><a href="/so/KARA" target="_blank">KARA</a><a href="/so/Orange Caramel" target="_blank">Orange Caramel</a><a href="/so/Rainbow" target="_blank">Rainbow</a><a href="/so/Secret" target="_blank">Secret</a><a href="/so/2NE1" target="_blank">2NE1</a><a href="/so/SISTAR" target="_blank">SISTAR</a><a href="/so/SPICA" target="_blank">SPICA</a><a href="/so/Stellar" target="_blank">Stellar</a><a href="/so/Tahiti" target="_blank">Tahiti</a><a href="/so/T-ARA" target="_blank">T-ARA</a><a href="/so/The Seeya" target="_blank">The Seeya</a><a href="/so/Wonder Girls" target="_blank">Wonder Girls</a><a href="/so/홍진영" target="_blank">홍진영/洪真英</a></div><div id="j2"><a href="/so/活着" target="_blank">活着[Cheer Up]</a><a href="/so/爱情的电池" target="_blank">爱情的电池</a><a href="/so/不羁的男人" target="_blank">不羁的男人</a><a href="/k135" target="_blank">Dancing Queen</a><a href="/k139" target="_blank">Lonely Christmas</a><a href="/k141" target="_blank">Bar Bar Bar</a><a href="/k708" target="_blank">FM</a><a href="/k142" target="_blank">Uh-ee</a><a href="/k505" target="_blank">Marionette</a><a href="/k730" target="_blank">Run Devil Run</a><a href="/k702" target="_blank">动摇</a><a href="/k78" target="_blank">短裙</a><a href="/k245" target="_blank">Mr.Mr.</a><a href="/k747" target="_blank">Number Nine</a><a href="/k735" target="_blank">i’m ill</a><a href="/k320" target="_blank">Paparazzi 简美妍</a><a href="/k248" target="_blank">PAPARAZZI 少女时代</a><a href="/k677" target="_blank">bbang bbang</a><a href="/k728" target="_blank">oh 少女时代</a><a href="/k732" target="_blank">the boys</a><a href="/k116" target="_blank">No way</a><a href="/k38" target="_blank">Ready Go</a><a href="/so/Genie" target="_blank">Genie</a><a href="/k535" target="_blank">Lovey Dovey</a><a href="/k537" target="_blank">Roly Poly</a><a href="/k539" target="_blank">Sexy Love</a><a href="/so/heart attack" target="_blank">heart attack</a><a href="/k529" target="_blank">DAY BY DAY</a><a href="/k240" target="_blank">Gee 少女时代</a><a href="/k562" target="_blank">Trouble Maker</a><a href="/k415" target="_blank">Funny Hunny</a><a href="/k464" target="_blank">SHY BOY</a><a href="/k447" target="_blank">TO ME</a><a href="/k475" target="_blank">Alone</a><a href="/k150" target="_blank">Big Baby Baby</a><a href="/so/Ah Yeah" target="_blank">Ah Yeah</a><a href="/k244" target="_blank">MR. TAXI</a><a href="/k367" target="_blank">All Right</a><a href="/k444" target="_blank">RAINBOW A</a></div></div></div> </div> <p>&nbsp;</p><div id="xm" class="xm"></div> <!-- rst --> <div id="xc" class="cf"><span id="xct">猜你喜欢</span><br> <div class="hm"><div class="xh"><div class="xs f2"><span>&nbsp;vipc2&nbsp;</span></div> <div id="si"><span>&nbsp;25&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <a id="ha" href="/2v49" title="vipc2 欧美写真 第49集" class="r81"><p>欧美写真 第49集</p><img id="ca" class="i" alt="欧美写真 第49集" src="//m.syasn.com/c.jpg" name="https://p.syasn.com/2v49.165/210"></a> </div></div> <div class="hm"><div class="xh"><div class="xs f2"><span>&nbsp;韩国饭拍III&nbsp;</span></div> <div id="si"><span>&nbsp;223&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <a id="ha" href="/3f145" title="韩国饭拍III 145-150511 LAYSHA – Turn Up The Music" class="r50"><p>145-150511 LAYSHA – Turn Up The Music</p><img id="ca" class="i" alt="145-150511 LAYSHA – Turn Up The Music" src="//m.syasn.com/c.jpg" name="https://p.syasn.com/3f145.165/210"></a> </div></div> <div class="hm"><div class="xh"><div class="xs f2"><span>&nbsp;vipc9&nbsp;</span></div> <div id="si"><span>&nbsp;434&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <a id="ha" href="/9v90" title="vipc9 台湾写真 TPlmage090 Baby.G" class="r87"><p>台湾写真 TPlmage090 Baby.G</p><img id="ca" class="i" alt="台湾写真 TPlmage090 Baby.G" src="//m.syasn.com/c.jpg" name="https://p.syasn.com/9v90.165/210"></a> </div></div> <div class="hm"><div class="xh"><div class="xs f2"><span>&nbsp;国产私拍&nbsp;</span></div> <div id="si"><span>&nbsp;8919&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <a id="ha" href="/a18" title="国产私拍 silkbaby丝宝VIP之红妆浅笑" class="r51"><p>silkbaby丝宝VIP之红妆浅笑</p><img id="ca" class="i" alt="silkbaby丝宝VIP之红妆浅笑" src="//m.syasn.com/c.jpg" name="https://p.syasn.com/a18.165/210"></a> </div></div> <div class="hm"><div class="xh"><div class="xs f2"><span>&nbsp;韩国女主播&nbsp;</span></div> <div id="si"><span>&nbsp;648&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <a id="ha" href="/zb164" title="韩国女主播 164-朴佳琳" class="r33"><p>164-朴佳琳</p><img id="ca" class="i" alt="164-朴佳琳" src="//m.syasn.com/c.jpg" name="https://p.syasn.com/zb164.165/210"></a> </div></div> <div class="hm"><div class="xh"><div class="xs f2"><span>&nbsp;siyamm&nbsp;</span></div> <div id="si"><span>&nbsp;1145&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <a id="ha" href="/sy15" title="siyamm 丝雅写真 第15集" class="r28"><p>丝雅写真 第15集</p><img id="ca" class="i" alt="丝雅写真 第15集" src="//m.syasn.com/c.jpg" name="https://p.syasn.com/sy15.165/210"></a> </div></div> <div class="hm"><div class="xh"><div class="xs f2"><span>&nbsp;vipc1&nbsp;</span></div> <div id="si"><span>&nbsp;156&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <a id="ha" href="/1v40" title="vipc1 日韩写真 第40集" class="r88"><p>日韩写真 第40集</p><img id="ca" class="i" alt="日韩写真 第40集" src="//m.syasn.com/c.jpg" name="https://p.syasn.com/1v40.165/210"></a> </div></div> <div class="hm"><div class="xh"><div class="xs f2"><span>&nbsp;PANS写真&nbsp;</span></div> <div id="si"><span>&nbsp;686&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <a id="ha" href="/ps600" title="PANS写真 第600集 冰冰" class="r5"><p>第600集 冰冰</p><img id="ca" class="i" alt="第600集 冰冰" src="//m.syasn.com/c.jpg" name="https://p.syasn.com/ps600.165/210"></a> </div></div> </div><!-- red --> <div id="b1"></div><script type="text/javascript" src="//m.syasn.com/2.js"></script> <div id="mr"></div> <div id="CYan">　</div> <div id="SOHUCS"></div><div id="uyan_frame"></div> <div id="nr"></div> </div> <style>#sb,#il{margin-bottom:0px;display:none;}</style><div id="se" class="ks"><div id="il" style=""></div><div id="sb"><div id="sbr"></div></div> <div id="s1" class="s1 f2"> <li> <span class="add" id="8885" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;48&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/k231" title="韩国MV 231_Girl’s Day(걸스데이) – FEMALE PRESIDENT(여자대통령)">231_Girl’s Day(걸스데이) – FEMALE PRESIDENT(여자대통령)</a></div><div id="sp2">频道：<a href="/k" id="LE" target="_blank">韩国MV</a></div><div id="sp3"><i id="bi"></i>&nbsp;67396&nbsp;次播放</div></div> <a id="sa" href="/k231" title="韩国MV 231_Girl’s Day(걸스데이) – FEMALE PRESIDENT(여자대통령)" target="_blank" class="r1"><img id="ka" alt="韩国MV 231_Girl’s Day(걸스데이) – FEMALE PRESIDENT(여자대통령)" src="https://p.syasn.com/k231!145,85" name="https://p.syasn.com/k231!145,85" class="r80" style="display: inline;"></a> </li> <li> <span class="add" id="10081" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;98&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/k688" title="韩国MV 688-wanna.b – attention">688-wanna.b – attention</a></div><div id="sp2">频道：<a href="/k" id="LE" target="_blank">韩国MV</a></div><div id="sp3"><i id="bi"></i>&nbsp;172284&nbsp;次播放</div></div> <a id="sa" href="/k688" title="韩国MV 688-wanna.b – attention" target="_blank" class="r38"><img id="ka" alt="韩国MV 688-wanna.b – attention" src="https://p.syasn.com/k688!145,85" name="https://p.syasn.com/k688!145,85" class="r5" style="display: inline;"></a> </li> <li> <span class="add" id="9141" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;5&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/k480" title="韩国MV 480_SKARF(스카프) – Oh! Dance">480_SKARF(스카프) – Oh! Dance</a></div><div id="sp2">频道：<a href="/k" id="LE" target="_blank">韩国MV</a></div><div id="sp3"><i id="bi"></i>&nbsp;9752&nbsp;次播放</div></div> <a id="sa" href="/k480" title="韩国MV 480_SKARF(스카프) – Oh! Dance" target="_blank" class="r73"><img id="ka" alt="韩国MV 480_SKARF(스카프) – Oh! Dance" src="https://p.syasn.com/k480!145,85" name="https://p.syasn.com/k480!145,85" class="r13" style="display: inline;"></a> </li> <li> <span class="add" id="10068" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;10&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/k675" title="韩国MV 675-pink funniade – sos">675-pink funniade – sos</a></div><div id="sp2">频道：<a href="/k" id="LE" target="_blank">韩国MV</a></div><div id="sp3"><i id="bi"></i>&nbsp;17852&nbsp;次播放</div></div> <a id="sa" href="/k675" title="韩国MV 675-pink funniade – sos" target="_blank" class="r27"><img id="ka" alt="韩国MV 675-pink funniade – sos" src="https://p.syasn.com/k675!145,85" name="https://p.syasn.com/k675!145,85" class="r73" style="display: inline;"></a> </li> <li> <span class="add" id="9212" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;36&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/k551" title="韩国MV 551_The Seeya(더 씨야) – Be with you(내 맘은 죽어가요) (Dance Ver.) (feat. SPEED)">551_The Seeya(더 씨야) – Be with you(내 맘은 죽어가요) (Dance Ver.) (feat. SPEED)</a></div><div id="sp2">频道：<a href="/k" id="LE" target="_blank">韩国MV</a></div><div id="sp3"><i id="bi"></i>&nbsp;45792&nbsp;次播放</div></div> <a id="sa" href="/k551" title="韩国MV 551_The Seeya(더 씨야) – Be with you(내 맘은 죽어가요) (Dance Ver.) (feat. SPEED)" target="_blank" class="r2"><img id="ka" alt="韩国MV 551_The Seeya(더 씨야) – Be with you(내 맘은 죽어가요) (Dance Ver.) (feat. SPEED)" src="https://p.syasn.com/k551!145,85" name="https://p.syasn.com/k551!145,85" class="r89" style="display: inline;"></a> </li> <li> <span class="add" id="10064" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;12&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/k671" title="韩国MV 671-nc.a – vanilla shake">671-nc.a – vanilla shake</a></div><div id="sp2">频道：<a href="/k" id="LE" target="_blank">韩国MV</a></div><div id="sp3"><i id="bi"></i>&nbsp;24447&nbsp;次播放</div></div> <a id="sa" href="/k671" title="韩国MV 671-nc.a – vanilla shake" target="_blank" class="r9"><img id="ka" alt="韩国MV 671-nc.a – vanilla shake" src="https://p.syasn.com/k671!145,85" name="https://p.syasn.com/k671!145,85" class="r29" style="display: inline;"></a> </li> <li> <span class="add" id="8905" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;26&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/k251" title="韩国MV 251_Girls’ Generation 少女时代 – Run Devil Run (런데빌런)">251_Girls’ Generation 少女时代 – Run Devil Run (런데빌런)</a></div><div id="sp2">频道：<a href="/k" id="LE" target="_blank">韩国MV</a></div><div id="sp3"><i id="bi"></i>&nbsp;42767&nbsp;次播放</div></div> <a id="sa" href="/k251" title="韩国MV 251_Girls’ Generation 少女时代 – Run Devil Run (런데빌런)" target="_blank" class="r52"><img id="ka" alt="韩国MV 251_Girls’ Generation 少女时代 – Run Devil Run (런데빌런)" src="https://p.syasn.com/k251!145,85" name="https://p.syasn.com/k251!145,85" class="r75" style="display: inline;"></a> </li> <li> <span class="add" id="8783" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;7&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/k132" title="韩国MV 132_ChoColat (쇼콜라) – Syndrome (신드롬)">132_ChoColat (쇼콜라) – Syndrome (신드롬)</a></div><div id="sp2">频道：<a href="/k" id="LE" target="_blank">韩国MV</a></div><div id="sp3"><i id="bi"></i>&nbsp;13192&nbsp;次播放</div></div> <a id="sa" href="/k132" title="韩国MV 132_ChoColat (쇼콜라) – Syndrome (신드롬)" target="_blank" class="r69"><img id="ka" alt="韩国MV 132_ChoColat (쇼콜라) – Syndrome (신드롬)" src="https://p.syasn.com/k132!145,85" name="https://p.syasn.com/k132!145,85" class="r16" style="display: inline;"></a> </li> <li> <span class="add" id="13948" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;1676&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/b727" title="Beautyleg 第七百二十七集 727Tina">第七百二十七集 727Tina</a></div><div id="sp2">频道：<a href="/b" id="LE" target="_blank">Beautyleg</a></div><div id="sp3"><i id="bi"></i>&nbsp;2997307&nbsp;次播放</div></div> <a id="sa" href="/b727" title="Beautyleg 第七百二十七集 727Tina" target="_blank" class="r37"><img id="ka" alt="Beautyleg 第七百二十七集 727Tina" src="https://p.syasn.com/b727!145,85" name="https://p.syasn.com/b727!145,85" class="r12" style="display: inline;"></a> </li> <li> <span class="add" id="14994" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;1832&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/m537" title="经典写真 YouWu尤物馆 木木hanna VN.009 2018.04.04">YouWu尤物馆 木木hanna VN.009 2018.04.04</a></div><div id="sp2">频道：<a href="/m" id="LE" target="_blank">经典写真</a></div><div id="sp3"><i id="bi"></i>&nbsp;3280825&nbsp;次播放</div></div> <a id="sa" href="/m537" title="经典写真 YouWu尤物馆 木木hanna VN.009 2018.04.04" target="_blank" class="r61"><img id="ka" alt="经典写真 YouWu尤物馆 木木hanna VN.009 2018.04.04" src="https://p.syasn.com/m537!145,85" name="https://p.syasn.com/m537!145,85" class="r4" style="display: inline;"></a> </li> <li> <span class="add" id="4422" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;162&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/f49" title="韩国饭拍 49-140927 Dal★shabet – Mr.BangBang 달샤벳">49-140927 Dal★shabet – Mr.BangBang 달샤벳</a></div><div id="sp2">频道：<a href="/f" id="LE" target="_blank">韩国饭拍</a></div><div id="sp3"><i id="bi"></i>&nbsp;282795&nbsp;次播放</div></div> <a id="sa" href="/f49" title="韩国饭拍 49-140927 Dal★shabet – Mr.BangBang 달샤벳" target="_blank" class="r24"><img id="ka" alt="韩国饭拍 49-140927 Dal★shabet – Mr.BangBang 달샤벳" src="https://p.syasn.com/f49!145,85" name="https://p.syasn.com/f49!145,85" class="r45" style="display: inline;"></a> </li> <li> <span class="add" id="13456" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;21719&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/ps602" title="PANS写真 第602集 木木">第602集 木木</a></div><div id="sp2">频道：<a href="/ps" id="LE" target="_blank">PANS写真</a></div><div id="sp3"><i id="bi"></i>&nbsp;36948829&nbsp;次播放</div></div> <a id="sa" href="/ps602" title="PANS写真 第602集 木木" target="_blank" class="r90"><img id="ka" alt="PANS写真 第602集 木木" src="https://p.syasn.com/ps602!145,85" name="https://p.syasn.com/ps602!145,85" class="r72" style="display: inline;"></a> </li> <li> <span class="add" id="2077" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;4269&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/ru35" title="ru1mm 第35集 如壹写真">第35集 如壹写真</a></div><div id="sp2">频道：<a href="/ru" id="LE" target="_blank">ru1mm</a></div><div id="sp3"><i id="bi"></i>&nbsp;7288201&nbsp;次播放</div></div> <a id="sa" href="/ru35" title="ru1mm 第35集 如壹写真" target="_blank" class="r53"><img id="ka" alt="ru1mm 第35集 如壹写真" src="https://p.syasn.com/ru35!145,85" name="https://p.syasn.com/ru35!145,85" class="r81" style="display: inline;"></a> </li> <li> <span class="add" id="14544" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;2942&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/rs224" title="Rosimm 第224集 rosi写真">第224集 rosi写真</a></div><div id="sp2">频道：<a href="/rs" id="LE" target="_blank">Rosimm</a></div><div id="sp3"><i id="bi"></i>&nbsp;5089669&nbsp;次播放</div></div> <a id="sa" href="/rs224" title="Rosimm 第224集 rosi写真" target="_blank" class="r51"><img id="ka" alt="Rosimm 第224集 rosi写真" src="https://p.syasn.com/rs224!145,85" name="https://p.syasn.com/rs224!145,85" class="r40" style="display: inline;"></a> </li> <li> <span class="add" id="11966" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;521&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/9v134" title="vipc9 台湾写真 TPlmage134 Lucy.A">台湾写真 TPlmage134 Lucy.A</a></div><div id="sp2">频道：<a href="/vc/9v" id="LE" target="_blank">vipc9</a></div><div id="sp3"><i id="bi"></i>&nbsp;945931&nbsp;次播放</div></div> <a id="sa" href="/9v134" title="vipc9 台湾写真 TPlmage134 Lucy.A" target="_blank" class="r62"><img id="ka" alt="vipc9 台湾写真 TPlmage134 Lucy.A" src="https://p.syasn.com/9v134!145,85" name="https://p.syasn.com/9v134!145,85" class="r9" style="display: inline;"></a> </li> <li> <span class="add" id="12886" title="添加到点播单，稍后观看，在观看记录保存">+</span> <div id="si"> <span>&nbsp;226&nbsp;<span class="sm">人喜欢&nbsp;</span></span></div> <div id="sp"><div id="sp1"><a href="/cz23" title="赤足者 23-金色尖细高跟、直筒裤极薄肉丝MM终极5部大特写2">23-金色尖细高跟、直筒裤极薄肉丝MM终极5部大特写2</a></div><div id="sp2">频道：<a href="/cz" id="LE" target="_blank">赤足者</a></div><div id="sp3"><i id="bi"></i>&nbsp;418959&nbsp;次播放</div></div> <a id="sa" href="/cz23" title="赤足者 23-金色尖细高跟、直筒裤极薄肉丝MM终极5部大特写2" target="_blank" class="r39"><img id="ka" alt="赤足者 23-金色尖细高跟、直筒裤极薄肉丝MM终极5部大特写2" src="https://p.syasn.com/cz23!145,85" name="https://p.syasn.com/cz23!145,85" class="r29" style="display: inline;"></a> </li> </div> </div><script type="text/javascript" src="//m.syasn.com/1.js?t=55"></script><div id="fb">
<div id="bgbox">
<div id="bgtop">
<h3>恋恋影视，轻松换肤</h3>
<span id="xbg">×</span>
</div>
<div id="bglist" class="bglist">
<span class="g101 on"><p>Don't use bg skin</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww4.sinaimg.cn/large/b330dc26gw1egqmklb0h9j203s02kwe9.jpg"></span>
<span class="g102"><p>忆童年</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww4.sinaimg.cn/large/b330dc26gw1egqmklnzqsj203h01ya9w.jpg"></span>
<span class="g103"><p>梅</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww4.sinaimg.cn/large/b330dc26gw1egnj23h44fg203h01yt8l.gif"></span>
<span class="g104"><p>耍酷的蜘蛛</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww1.sinaimg.cn/large/b330dc26gw1egqmkmvnskj203h01ya9w.jpg"></span>
<span class="g105"><p>灰姑娘城堡</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww4.sinaimg.cn/large/b330dc26gw1egq17mocknj203h01y744.jpg"></span>
<span class="g106"><p>最终幻想</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww3.sinaimg.cn/large/b330dc26gw1egqmknrqglj203h01y3yc.jpg"></span>
<span class="g107"><p>漫步云端</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww1.sinaimg.cn/large/b330dc26gw1egq17sd3zuj203h01yglf.jpg"></span>
<span class="g108"><p>怀春的少女</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww4.sinaimg.cn/large/b330dc26gw1egqmkoo8cej203h01yjr7.jpg"></span>
<span class="g109"><p>劳斯莱斯蓝鸟</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww3.sinaimg.cn/large/005yE9HSgw1eplcy90vi6j303h01ya9v.jpg"></span>
<span class="g110"><p>红酒女郎</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww4.sinaimg.cn/large/b330dc26gw1egqmkpybwgj203h01y0sk.jpg"></span>
<span class="g111"><p>我们都是坏孩子</p><i></i><img id="bka" src="//m.syasn.com/n.jpg" name="//ww2.sinaimg.cn/large/b330dc26gw1egqmkqe2cdj203h01yjr8.jpg"></span>
<div id="upb"><i></i>
<input id="upi" type="file" name="upi">
<div class="dup">点击上传<br>或<br>直接拖曳图片进来</div>
<div class="cup">双击上传</div>
<img id="pre" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==" name="pre">
<textarea id="tex" value=""></textarea>
</div>
</div>
</div>
<div id="xz">
<div id="xzt">视频下载(DownLoad this video)</div><div id="xzx">×</div>
<div id="xzl">
<div id="dn" class="btn" title="百度网盘下载">　百度网盘　</div><br>
<div id="fn" class="btn" title="百度网盘下载">　百度网盘　</div>
<tt id="xzz">　不能下载的请点击此处查看！</tt>
</div>
<div id="xzr">
<div>&nbsp;扫码下载至手机：<span class="smt">
<span class="sms">　　非会员扫码前，请先点击喜欢按钮。<br>　　开通会员可以用手机看,一键下载等特权。<i class="smi"></i></span>
</span></div>
<tt></tt>
<img id="xzi">
</div>
<div id="xzb">
　　不能自动弹出下载文件的用户请更换浏览器(推荐360浏览器)！非会员仅限单或双线程下载，加入会员即可多线程高速无限制任意下载。<br>
　　【会员也支持右键一键快捷下载视频！！！】
</div>
</div>

<div id="pse">
<div class="cf">
<div id="psz">播放器设置</div><div id="psx">×</div>
</div>
<div id="pq">
画质：<span id="pq2">270p</span><span id="pq3">360p</span><span id="pq5">540p</span><span id="pq7">720p</span><span id="pq1">1080p</span>
</div>
<div id="psc">
<div id="ju">
位置：<span class="jl">居左</span><span class="jc">居中</span><span class="jr">居右</span>
</div>
<div id="pg">
皮肤：<span class="pg3">黑色</span><span class="pg2">紫色</span><span class="pg5">蓝色</span><span class="pg4">红色</span><span class="pg1">灰色</span>
</div>
<div id="lb">
播完：<span class="lb1">停止</span><span class="lb2">重播</span><span class="lb3">剧集连播</span><span class="lb4">随机连播</span>
</div>
<div id="qt">
其他：<span id="ht" class="ht" title="标题居下">标题居下</span><span id="oj" class="oj" title="开启视频镜像">镜像模式</span>
<span id="lp" class="bp" title="切换至大型播放器">大型播放器</span><br>
<span id="kz" class="kz" title="开启智能显示控制栏">智能显示控制栏</span><span id="zd" class="zd" title="开启自动播放视频">自动播放视频</span>
<span id="cyl" class="cyl" title="关闭控制栏预览图">关闭预览图</span>
</div>
</div>
</div>

<div class="lof" id="lof"><form>
		<span class="loy">用户名/邮箱/Username/Email</span><span class="lox" id="lox">×</span>
		<input type="text" name="username" class="lou" id="lou">
		<span>密码/Password</span>
		<input type="password" name="password" class="lou" id="lop">
	    <label><input name="rememberme" type="checkbox" value="forever"> 记住登录 Remember Me</label><a href="/find" class="wj" target="_blank">[忘记密码?]</a>
		<div><span class="lob" id="lob">登录Log In</span>
		<a class="loa" onclick="q2();">没有账号？点击注册&gt;&gt;</a></div>
</form></div>

<div class="lof" id="ref"><form>
		<span class="loy">用户名\Username</span><span class="lox" id="rex">×</span>
		<input type="text" name="username" class="lou" id="re1">
		<span>邮箱\Email</span>
		<input type="text" name="email" class="lou" id="re2">
		<span>密码\Password</span>
		<input type="password" name="password" class="lou" id="re3">
		<span>确认密码\Confirm Password</span>
		<input type="password" name="password" class="lou" id="re4">
		<span><a id="yao" href="/vip" target="_blank">邀请码\Invitation code[点击获取]</a></span>
		<input type="text" name="inv" class="lou" id="re5">
		<div><span class="lob" id="reb">注册Register</span>
		<a class="loa" onclick="q1();">已有账号？点击登陆&gt;&gt;</a></div>
</form></div>



<div id="eb">
<div id="ebt"><div id="ebp">提示信息</div><div id="ebx">×</div></div>
<div id="ebc"></div>
<div id="ebb">确定</div>
</div>

<div id="am" style="display: none; left: 96px; top: 40px;">
<a id="mys" href="/" target="_blank">恋恋影视</a>
<tt></tt>
<span id="mfs" class="cg">复制视频地址</span>
<span id="mft" class="cg">复制当前时间视频地址</span>
<span id="mfa" class="cg">复制flash地址</span>
<span id="mfh" class="cg">复制当前时间flash地址</span>
<span id="mfi" class="cg">复制嵌入代码(站外分享免广告,支持移动端)</span>
<span id="mfe">分享本页</span>
<a id="mfn" target="_blank">返回原网页继续观看</a>
<tt></tt>
<span class="gr kr6">min-480p@20150111</span>
<span class="gr kr9">max-540-720-1080p@20150112</span>
<span class="gr krn">not play page@20150111</span>
<tt></tt>
<span id="msc" class="cg">收藏本集视频</span>
<span id="mdl" class="cg">下载本集视频</span>
<tt></tt>
<a id="mmy" href="/my" target="_blank">我的收藏</a>
<a id="mse" href="/see" target="_blank">观看记录</a>
<a id="msr" href="/user" target="_blank">个人中心</a>
<tt></tt>
<span id="mde" class="cg">关灯</span>
<span id="mps" class="cg">播放器设置</span>
<a id="mhe" href="/help" target="_blank">在线帮助和反馈</a>
</div>
<a id="up" href="返回顶部" rel="nofollow" class="r30" style="display: none;"></a>
<div class="xf"></div>
</div>

</div></div>

<div id="ff">
<div id="fx" class="xf">
 <div class="fx">
	Copyright © 2015 <a href="/" rel="home">恋恋影视</a> All rights reserved &nbsp;&nbsp;<a href="/vip" target="_blank"> 加入vip </a>|<a href="/note" target="_blank"> 免责声明 </a>|<a href="/ad" target="_blank"> 广告服务 </a>|<a href="/link" target="_blank"> 友情链接 </a>|<a href="/contact" target="_blank"> 联系我们 </a>|<a href="/help" target="_blank"> 留言板&nbsp;</a>
	<br>
	<a href="/so?_______res" target="_blank">热搜：</a><a href="/so/ROSI写真" target="_blank">ROSI写真 </a><a href="/so/TuiGirl" target="_blank">TuiGirl </a>
	<a href="/so/妖精" target="_blank">妖精 </a><a href="/so/winnie" target="_blank">Winnie </a><a href="/so/筱崎爱" target="_blank">筱崎爱 </a>
	<a href="/so/车展" target="_blank">车展 </a><a href="/so/beautyleg" target="_blank">beautyleg </a><a href="/so/饭拍" target="_blank">饭拍 </a>
	<a href="/so/rq-star" target="_blank">rq-star </a><a href="/so/丽柜" target="_blank">丽柜 </a><a href="/so/AISS" target="_blank">AISS </a>
	<a href="/so/秀人" target="_blank">秀人 </a><a href="/so/rosimm" target="_blank">rosimm </a><a href="/so/小雪" target="_blank">小雪 </a>
	<a href="/so/3AGirL" target="_blank">3AGirL </a><a href="/so/vicni" target="_blank">Vicni </a><a href="/so/雨涵" target="_blank">雨涵 </a>
	<a href="/so/chinajoy" target="_blank">chinajoy </a><a href="/so/韩国女主播" target="_blank">韩国女主播 </a><a href="/so/pans写真" target="_blank">PANS </a>
	<a href="/so/丝雅" target="_blank">丝雅 </a><a href="/so/ru1mm" target="_blank">ru1mm </a><a href="/so/推女郎" target="_blank">推女郎 </a>
	<a href="/so/AAA女郎" target="_blank">AAA女郎 </a><a href="/so/小玲" target="_blank">小玲 </a><a href="/so/杉原杏璃" target="_blank">杉原杏璃 </a>
	<a href="/so/Ligui" target="_blank">Ligui </a><a href="/so/爱丝" target="_blank">爱丝 </a><a href="/so/siyamm" target="_blank">siyamm </a>
	<a href="/so/朴妮唛" target="_blank">朴妮唛 </a><a href="/so/4k-star" target="_blank">4k-star </a><a href="/so/学院派" target="_blank">学院派 </a>
	<iframe id="dl" class="ne"></iframe>
 </div>
</div>
</div>
<div title="网站设置" id="gs"></div>
<div id="xt" class="ne"><div id="xtx">×</div></div><style>
.hm2{text-align:center!important;float:none!important;padding-top:10px!important;}
.cn .hm{width:16%!important;}.co .hm{width:15%!important;}
.hm,.hm2,.hm1,#i2,.my .hm{text-align:center!important;}.co{background-color:#8A484F!important;}
</style>
</body></html>
