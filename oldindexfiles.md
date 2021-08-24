<html>
  <head>
	  <head>
  <title>Seth's Developer Portal</title>
  <link rel="icon" href="images/pfp.jpg">
  <link rel="shortcut icon" type="image/jpg" href="/image/pfp.jpg"/>
</head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="ogauthor" content="Hyperz#0001">
    <meta name="ogsite" content="https://sethhalsey.me">
	<meta name="ogdiscord" content="https://sethhalsey.me/discord">
	<meta name="ognavbarcreator" content="https://jakehamblin.com/">
    <meta name="description" content="Main development website for Seth Halsey. AKA SethTheKings,">
    <meta name="keywords" content="Seth, Halsey, Dev, Developer, Portal, Github, OpenSource, Free, HTML">
    <style>
	    .body {
  margin: 0;
	font-family: 'Montserrat', sans-serif;
	background-color: #172970;
}

.navbar {
	display: flex;
	width: 80%;
	padding: 2vh 10%;
	align-items: center;
	justify-content: center;
	position: relative;
	z-index: 5;
	transition: all .5s ease;
}

.navbar.scrolled {
	padding: 1vh 10%;
	background-color: #0c151c;
}

.navbar.dropdownshown {
	padding: 2vh 10%;
	background-color: transparent;
}

.navbar .left {
	width: 25%;
}

.navbar .left img {
	height: 7.5vh;
	width: auto;
	opacity: 1;
	transition: visibility .25s ease, opacity .25s ease;
}

.navbar.dropdownshown .left img {
	visibility: hidden;
	opacity: 0;
}

.navbar .right {
	width: 75%;
	text-align: right;
}

.navbar .right a {
	font-size: 2.2vh;
	color: #fff;
	text-decoration: none;
	font-weight: 500;
	margin-left: 2%;
	position: relative;
}

.navbar .right a.dropdownbtn {
	display: none;
	font-size: 3vh;
}

.navbar .right .links a:after {
	position: absolute;
	content: "";
	top: 100%;
	left: 0;
	width: 0%;
	height: .25vh;
	background-color: #fff;
	margin-top: .5vh;
	transition: width .3s ease;
}

.navbar .right .links a:hover:after, .navbar .right .links a.active:after {
	width: 100%;
}

.body .title1 {
	color: white;
	font-size: 34px;
	font-weight: bold;
}

.body .img1 {
	width: 285px;
	height: 165px;
	margin-top: 55px;
	margin-left: 105px;
	margin-right: auto;
	border: 2px solid white;
	border-radius: 8px;
	overflow: hidden;
	transition: opacity .2s;
}

.body .img1:hover {
	opacity: 0.7;
}

.body .img2 {
	width: 285px;
	height: 160px;
	margin-top: 55px;
	margin-left: 175px;
	margin-right: auto;
	border: 2px solid white;
	border-radius: 8px;
	overflow: hidden;
	transition: opacity .2s;
}

.body .img2:hover {
	opacity: 0.7;
}

.body .img3 {
	width: 285px;
	height: 160px;
	margin-top: 55px;
	margin-left: 175px;
	margin-right: auto;
	border: 2px solid white;
	border-radius: 8px;
	overflow: hidden;
	transition: opacity .2s;
}

.body .img3:hover {
	opacity: 0.7;
}

.body .img4 {
	width: 285px;
	height: 160px;
	margin-top: 55px;
	margin-left: 175px;
	margin-right: auto;
	border: 2px solid white;
	border-radius: 8px;
	overflow: hidden;
	transition: opacity .2s;
}

.body .img4:hover {
	opacity: 0.7;
}

.body .img5 {
	width: 285px;
	height: 160px;
	margin-top: 55px;
	margin-left: 105px;
	margin-right: auto;
	border: 2px solid white;
	border-radius: 8px;
	overflow: hidden;
	transition: opacity .2s;
}

.body .img5:hover {
	opacity: 0.7;
}

.body .img6 {
	width: 285px;
	height: 160px;
	margin-top: 55px;
	margin-left: 175px;
	margin-right: auto;
	border: 2px solid white;
	border-radius: 8px;
	overflow: hidden;
	transition: opacity .2s;
}

.body .img6:hover {
	opacity: 0.7;
}

.body .img7 {
	width: 285px;
	height: 160px;
	margin-top: 55px;
	margin-left: 175px;
	margin-right: auto;
	border: 2px solid white;
	border-radius: 8px;
	overflow: hidden;
	transition: opacity .2s;
}

.body .img7:hover {
	opacity: 0.7;
}

.body .img8 {
	width: 285px;
	height: 160px;
	margin-top: 55px;
	margin-left: 175px;
	margin-right: auto;
	border: 2px solid white;
	border-radius: 8px;
	overflow: hidden;
	transition: opacity .2s;
}

.body .img8:hover {
	opacity: 0.7;
}

.body .footer {
	background-color: #131313;
	height: 75px;
	margin-top: 200px;
}

.body .footer .footertext {
	color: white;
	font-size: 20px;
	padding-top: 25px
}

    </style>
  </head>
  <body class="body">
  <section class="navbar">
		<div class="left">
			<a href="https://sethhalsey.me/"><img src="/images/pfp.jpg"></a>
		</div>
		<div class="right">
			<div class="links">
				<a href="http://sethhalsey.me" class="active">Home</a>
				<a href="http://sethhalsey.me/discord">Discord</a>
				<a href="http://sethhalsey.me/mods" target="_blank">Mods</a>
				<a href="http://sethhalsey.me/store">Store</a>
				<a href="http://scp-forms.wikidot.com" target="_blank">Forms</a>
				<a href="https://docs.sethhalsey.me" target="_blank">Docs</a>
				<a href="http://sethhalsey.me/2b2tmap">2b2t Map</a>
			</div>
			<a class="dropdownbtn" onclick="dropdown()"><i class="fas fa-bars"></i></a>
		</div>
	</section>
	<p class="title1" align=center>[ Seth's Developer Portal ]</p>
	<a href="http://sethhalsey.me/2b2t">
	<img class="img1" src="http://sethhalsey.me/images/Capture.PNG" ></img>
	</a>
	<div class="footer">
		<p class="footertext" align=center>Copyright 2021 Seth Halsey Development, Website Design By Hyperz</p>
	</div>
  </body>

<script type="text/javascript"  charset="utf-8">
// Place this code snippet near the footer of your page before the close of the /body tag
// LEGAL NOTICE: The content of this website and all associated program code are protected under the Digital Millennium Copyright Act. Intentionally circumventing this code may constitute a violation of the DMCA.
                            
eval(function(p,a,c,k,e,d){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--){d[e(c)]=k[c]||e(c)}k=[function(e){return d[e]}];e=function(){return'\\w+'};c=1};while(c--){if(k[c]){p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c])}}return p}(';k O=\'\',28=\'23\';1I(k i=0;i<12;i++)O+=28.X(B.J(B.K()*28.F));k 2t=8,2y=2E,2h=4r,34=4q,2g=D(t){k o=!1,i=D(){z(q.1j){q.2K(\'2Q\',e);E.2K(\'1T\',e)}R{q.2M(\'2S\',e);E.2M(\'26\',e)}},e=D(){z(!o&&(q.1j||4p.2v===\'1T\'||q.2N===\'2P\')){o=!0;i();t()}};z(q.2N===\'2P\'){t()}R z(q.1j){q.1j(\'2Q\',e);E.1j(\'1T\',e)}R{q.2T(\'2S\',e);E.2T(\'26\',e);k n=!1;35{n=E.4n==4m&&q.1Y}32(a){};z(n&&n.2Y){(D r(){z(o)G;35{n.2Y(\'14\')}32(e){G 4l(r,50)};o=!0;i();t()})()}}};E[\'\'+O+\'\']=(D(){k t={t$:\'23+/=\',4k:D(e){k r=\'\',d,n,o,c,s,l,i,a=0;e=t.e$(e);1f(a<e.F){d=e.16(a++);n=e.16(a++);o=e.16(a++);c=d>>2;s=(d&3)<<4|n>>4;l=(n&15)<<2|o>>6;i=o&63;z(37(n)){l=i=64}R z(37(o)){i=64};r=r+U.t$.X(c)+U.t$.X(s)+U.t$.X(l)+U.t$.X(i)};G r},13:D(e){k n=\'\',d,l,c,s,a,i,r,o=0;e=e.1p(/[^A-4j-4i-9\\+\\/\\=]/g,\'\');1f(o<e.F){s=U.t$.1N(e.X(o++));a=U.t$.1N(e.X(o++));i=U.t$.1N(e.X(o++));r=U.t$.1N(e.X(o++));d=s<<2|a>>4;l=(a&15)<<4|i>>2;c=(i&3)<<6|r;n=n+S.T(d);z(i!=64){n=n+S.T(l)};z(r!=64){n=n+S.T(c)}};n=t.n$(n);G n},e$:D(t){t=t.1p(/;/g,\';\');k n=\'\';1I(k o=0;o<t.F;o++){k e=t.16(o);z(e<1v){n+=S.T(e)}R z(e>2E&&e<4h){n+=S.T(e>>6|4g);n+=S.T(e&63|1v)}R{n+=S.T(e>>12|2p);n+=S.T(e>>6&63|1v);n+=S.T(e&63|1v)}};G n},n$:D(t){k o=\'\',e=0,n=4f=1r=0;1f(e<t.F){n=t.16(e);z(n<1v){o+=S.T(n);e++}R z(n>4e&&n<2p){1r=t.16(e+1);o+=S.T((n&31)<<6|1r&63);e+=2}R{1r=t.16(e+1);2k=t.16(e+2);o+=S.T((n&15)<<12|(1r&63)<<6|2k&63);e+=3}};G o}};k r=[\'4c==\',\'3X\',\'4b=\',\'4a\',\'49\',\'48=\',\'47=\',\'46=\',\'45\',\'44\',\'43=\',\'42=\',\'41\',\'40\',\'3Z=\',\'3Y\',\'4s=\',\'4d=\',\'4t=\',\'4L=\',\'4N=\',\'4O=\',\'4P==\',\'4Q==\',\'4R==\',\'4S==\',\'4M=\',\'4T\',\'4V\',\'4W\',\'4X\',\'4Y\',\'4Z\',\'51==\',\'4U=\',\'4K=\',\'3V=\',\'4J==\',\'4I=\',\'4H\',\'4G=\',\'4F=\',\'4E==\',\'4D=\',\'4C==\',\'4B==\',\'4A=\',\'4z=\',\'4y\',\'4x==\',\'4w==\',\'4u\',\'3W==\',\'3U=\'],f=B.J(B.K()*r.F),Y=t.13(r[f]),w=Y,M=1,v=\'#3o\',a=\'#3n\',W=\'#3m\',g=\'#3l\',Q=\'\',b=\'3k!\',y=\'3i 3h 3g 3f\\\'3b 3c 39 2x 2w. 3a\\\'s 3d.  3p 3j\\\'t?\',p=\'3r 3G 3T-3S, 3R 3Q\\\'t 3P 3O U 3N 3M.\',s=\'I 3L, I 3K 3J 3I 2x 2w.  3q 3H 3F!\',o=0,h=0,n=\'3s.3E\',l=0,Z=e()+\'.2d\';D u(t){z(t)t=t.1R(t.F-15);k o=q.2R(\'2U\');1I(k n=o.F;n--;){k e=S(o[n].1F);z(e)e=e.1R(e.F-15);z(e===t)G!0};G!1};D m(t){z(t)t=t.1R(t.F-15);k e=q.3D;x=0;1f(x<e.F){1m=e[x].1O;z(1m)1m=1m.1R(1m.F-15);z(1m===t)G!0;x++};G!1};D e(t){k n=\'\',o=\'23\';t=t||30;1I(k e=0;e<t;e++)n+=o.X(B.J(B.K()*o.F));G n};D i(o){k i=[\'3B\',\'3A==\',\'3z\',\'3y\',\'2H\',\'3x==\',\'3w=\',\'3v==\',\'3u=\',\'3t==\',\'52==\',\'4v==\',\'54\',\'5k\',\'6B\',\'2H\'],a=[\'38=\',\'6s==\',\'6D==\',\'6v==\',\'6r=\',\'6e\',\'6o=\',\'67=\',\'38=\',\'6d\',\'6g==\',\'6h\',\'53==\',\'6n==\',\'62==\',\'6q=\'];x=0;1H=[];1f(x<o){c=i[B.J(B.K()*i.F)];d=a[B.J(B.K()*a.F)];c=t.13(c);d=t.13(d);k r=B.J(B.K()*2)+1;z(r==1){n=\'//\'+c+\'/\'+d}R{n=\'//\'+c+\'/\'+e(B.J(B.K()*20)+4)+\'.2d\'};1H[x]=24 1U();1H[x].1W=D(){k t=1;1f(t<7){t++}};1H[x].1F=n;x++}};D C(t){};G{2G:D(t,a){z(6l q.N==\'6k\'){G};k o=\'0.1\',a=w,e=q.1b(\'1q\');e.1g=a;e.j.1h=\'1P\';e.j.14=\'-1l\';e.j.V=\'-1l\';e.j.1x=\'29\';e.j.11=\'6j\';k d=q.N.2z,r=B.J(d.F/2);z(r>15){k n=q.1b(\'2b\');n.j.1h=\'1P\';n.j.1x=\'1A\';n.j.11=\'1A\';n.j.V=\'-1l\';n.j.14=\'-1l\';q.N.6i(n,q.N.2z[r]);n.1d(e);k i=q.1b(\'1q\');i.1g=\'2A\';i.j.1h=\'1P\';i.j.14=\'-1l\';i.j.V=\'-1l\';q.N.1d(i)}R{e.1g=\'2A\';q.N.1d(e)};l=6f(D(){z(e){t((e.1X==0),o);t((e.1Z==0),o);t((e.1K==\'2m\'),o);t((e.1S==\'2j\'),o);t((e.1E==0),o)}R{t(!0,o)}},27)},1L:D(e,c){z((e)&&(o==0)){o=1;E[\'\'+O+\'\'].1B();E[\'\'+O+\'\'].1L=D(){G}}R{k p=t.13(\'61\'),h=q.6c(p);z((h)&&(o==0)){z((2y%3)==0){k l=\'6b=\';l=t.13(l);z(u(l)){z(h.1J.1p(/\\s/g,\'\').F==0){o=1;E[\'\'+O+\'\'].1B()}}}};k f=!1;z(o==0){z((2h%3)==0){z(!E[\'\'+O+\'\'].2V){k d=[\'6a==\',\'69==\',\'68=\',\'66=\',\'6p=\'],m=d.F,a=d[B.J(B.K()*m)],r=a;1f(a==r){r=d[B.J(B.K()*m)]};a=t.13(a);r=t.13(r);i(B.J(B.K()*2)+1);k n=24 1U(),s=24 1U();n.1W=D(){i(B.J(B.K()*2)+1);s.1F=r;i(B.J(B.K()*2)+1)};s.1W=D(){o=1;i(B.J(B.K()*3)+1);E[\'\'+O+\'\'].1B()};n.1F=a;z((34%3)==0){n.26=D(){z((n.11<8)&&(n.11>0)){E[\'\'+O+\'\'].1B()}}};i(B.J(B.K()*3)+1);E[\'\'+O+\'\'].2V=!0};E[\'\'+O+\'\'].1L=D(){G}}}}},1B:D(){z(h==1){k L=2o.6t(\'2r\');z(L>0){G!0}R{2o.6w(\'2r\',(B.K()+1)*27)}};k u=\'6x==\';u=t.13(u);z(!m(u)){k c=q.1b(\'5Z\');c.21(\'5w\',\'5X\');c.21(\'2v\',\'1i/5t\');c.21(\'1O\',u);q.2R(\'5s\')[0].1d(c)};5r(l);q.N.1J=\'\';q.N.j.17+=\'P:1A !19\';q.N.j.17+=\'1s:1A !19\';k Z=q.1Y.1Z||E.2X||q.N.1Z,f=E.5q||q.N.1X||q.1Y.1X,r=q.1b(\'1q\'),M=e();r.1g=M;r.j.1h=\'2B\';r.j.14=\'0\';r.j.V=\'0\';r.j.11=Z+\'1u\';r.j.1x=f+\'1u\';r.j.2u=v;r.j.1V=\'5p\';q.N.1d(r);k d=\'<a 1O="5o://5n.5m" j="H-1c:10.5l;H-1k:1n-1o;1a:5Y;">5j 5h 55 5g-5f 2U</a>\';d=d.1p(\'5e\',e());d=d.1p(\'5d\',e());k i=q.1b(\'1q\');i.1J=d;i.j.1h=\'1P\';i.j.1y=\'1D\';i.j.14=\'1D\';i.j.11=\'5c\';i.j.1x=\'5b\';i.j.1V=\'2D\';i.j.1E=\'.6\';i.j.2n=\'2s\';i.1j(\'59\',D(){n=n.58(\'\').57().56(\'\');E.36.1O=\'//\'+n});q.1Q(M).1d(i);k o=q.1b(\'1q\'),C=e();o.1g=C;o.j.1h=\'2B\';o.j.V=f/7+\'1u\';o.j.5i=Z-5v+\'1u\';o.j.5K=f/3.5+\'1u\';o.j.2u=\'#5W\';o.j.1V=\'2D\';o.j.17+=\'H-1k: "5V 5U", 1t, 1w, 1n-1o !19\';o.j.17+=\'5T-1x: 5S !19\';o.j.17+=\'H-1c: 5R !19\';o.j.17+=\'1i-1z: 1C !19\';o.j.17+=\'1s: 5Q !19\';o.j.1K+=\'2J\';o.j.33=\'1D\';o.j.5P=\'1D\';o.j.5N=\'2q\';q.N.1d(o);o.j.5M=\'1A 5J 5x -5I 5H(0,0,0,0.3)\';o.j.1S=\'2e\';k x=30,w=22,Y=18,Q=18;z((E.2X<2W)||(5G.11<2W)){o.j.2Z=\'50%\';o.j.17+=\'H-1c: 5E !19\';o.j.33=\'5D;\';i.j.2Z=\'65%\';k x=22,w=18,Y=12,Q=12};o.1J=\'<2O j="1a:#5C;H-1c:\'+x+\'1G;1a:\'+a+\';H-1k:1t, 1w, 1n-1o;H-1M:5B;P-V:1e;P-1y:1e;1i-1z:1C;">\'+b+\'</2O><2L j="H-1c:\'+w+\'1G;H-1M:5A;H-1k:1t, 1w, 1n-1o;1a:\'+a+\';P-V:1e;P-1y:1e;1i-1z:1C;">\'+y+\'</2L><5z j=" 1K: 2J;P-V: 0.2I;P-1y: 0.2I;P-14: 2a;P-2l: 2a; 2F:5y 6m #3e; 11: 25%;1i-1z:1C;"><p j="H-1k:1t, 1w, 1n-1o;H-1M:2C;H-1c:\'+Y+\'1G;1a:\'+a+\';1i-1z:1C;">\'+p+\'</p><p j="P-V:5F;"><2b 5L="U.j.1E=.9;" 5O="U.j.1E=1;"  1g="\'+e()+\'" j="2n:2s;H-1c:\'+Q+\'1G;H-1k:1t, 1w, 1n-1o; H-1M:2C;2F-5u:2q;1s:1e;5a-1a:\'+W+\';1a:\'+g+\';1s-14:29;1s-2l:29;11:60%;P:2a;P-V:1e;P-1y:1e;" 6C="E.36.6u();">\'+s+\'</2b></p>\'}}})();E.2f=D(t,e){k n=6y.6z,o=E.6A,r=n(),i,a=D(){n()-r<e?i||o(a):t()};o(a);G{3C:D(){i=1}}};k 2i;z(q.N){q.N.j.1S=\'2e\'};2g(D(){z(q.1Q(\'2c\')){q.1Q(\'2c\').j.1S=\'2m\';q.1Q(\'2c\').j.1K=\'2j\'};2i=E.2f(D(){E[\'\'+O+\'\'].2G(E[\'\'+O+\'\'].1L,E[\'\'+O+\'\'].4o)},2t*27)});',62,412,'|||||||||||||||||||style|var||||||document|||||||||if||Math||function|window|length|return|font||floor|random|||body|aWkugpgqQxis|margin||else|String|fromCharCode|this|top||charAt||||width||decode|left||charCodeAt|cssText||important|color|createElement|size|appendChild|10px|while|id|position|text|addEventListener|family|5000px|thisurl|sans|serif|replace|DIV|c2|padding|Helvetica|px|128|geneva|height|bottom|align|0px|jtOuNUKUlA|center|30px|opacity|src|pt|spimg|for|innerHTML|display|VQOetxbMfu|weight|indexOf|href|absolute|getElementById|substr|visibility|load|Image|zIndex|onerror|clientHeight|documentElement|clientWidth||setAttribute||ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789|new||onload|1000|uJajTZrGyN|60px|auto|div|babasbmsgx|jpg|visible|zrVoKFRXZo|oYHdcaAeNG|wMAzmxIHCq|vTcAXjueHx|none|c3|right|hidden|cursor|sessionStorage|224|15px|babn|pointer|EpOsJCntwy|backgroundColor|type|blocker|ad|fcJbrtHirG|childNodes|banner_ad|fixed|300|10000|127|border|VVvDYyEzCr|cGFydG5lcmFkcy55c20ueWFob28uY29t|5em|block|removeEventListener|h1|detachEvent|readyState|h3|complete|DOMContentLoaded|getElementsByTagName|onreadystatechange|attachEvent|script|ranAlready|640|innerWidth|doScroll|zoom|||catch|marginLeft|eylAbkYGJB|try|location|isNaN|ZmF2aWNvbi5pY28|an|That|re|using|okay|CCC|you|like|looks|It|doesn|Welcome|FFFFFF|c70000|000000|ffffff|Who|Let|But|moc|cHJvbW90ZS5wYWlyLmNvbQ|Y2FzLmNsaWNrYWJpbGl0eS5jb20|YWR2ZXJ0aXNpbmcuYW9sLmNvbQ|YWdvZGEubmV0L2Jhbm5lcnM|YS5saXZlc3BvcnRtZWRpYS5ldQ|YWQuZm94bmV0d29ya3MuY29t|anVpY3lhZHMuY29t|YWQubWFpbC5ydQ|YWRuLmViYXkuY29t|clear|styleSheets|kcolbdakcolb|in|without|me|my|disabled|have|understand|awesome|site|making|keep|can|we|income|advertising|c3BvbnNvcmVkX2xpbms|QWRDb250YWluZXI|b3V0YnJhaW4tcGFpZA|YWRCYW5uZXJXcmFw|QWRBcmVh|QWQ3Mjh4OTA|QWQzMDB4MjUw|QWQzMDB4MTQ1|YWQtY29udGFpbmVyLTI|YWQtY29udGFpbmVyLTE|YWQtY29udGFpbmVy|YWQtZm9vdGVy|YWQtbGI|YWQtbGFiZWw|YWQtaW5uZXI|YWQtaW1n|YWQtaGVhZGVy|YWQtZnJhbWU|YWQtbGVmdA|QWRGcmFtZTI|191|c1|192|2048|z0|Za|encode|setTimeout|null|frameElement|UOedgUhycR|event|160|142|QWRGcmFtZTE|QWRGcmFtZTM|Z29vZ2xlX2Fk|YWRzLnp5bmdhLmNvbQ|YWRzZW5zZQ|cG9wdXBhZA|YWRzbG90|YmFubmVyaWQ|YWRzZXJ2ZXI|YWRfY2hhbm5lbA|IGFkX2JveA|YmFubmVyYWQ|YWRBZA|YWRiYW5uZXI|YWRCYW5uZXI|YmFubmVyX2Fk|YWRUZWFzZXI|Z2xpbmtzd3JhcHBlcg|QWRCb3gxNjA|QWRGcmFtZTQ|RGl2QWQ|QWRMYXllcjE|QWRMYXllcjI|QWRzX2dvb2dsZV8wMQ|QWRzX2dvb2dsZV8wMg|QWRzX2dvb2dsZV8wMw|QWRzX2dvb2dsZV8wNA|RGl2QWQx|QWREaXY|RGl2QWQy|RGl2QWQz|RGl2QWRB|RGl2QWRC|RGl2QWRD||QWRJbWFnZQ|YWRzLnlhaG9vLmNvbQ|YmFubmVyX2FkLmdpZg|YWRzYXR0LmFiY25ld3Muc3RhcndhdmUuY29t|own|join|reverse|split|click|background|40px|160px|FILLVECTID2|FILLVECTID1|adblock|anti|your|minWidth|Create|YWRzYXR0LmVzcG4uc3RhcndhdmUuY29t|5pt|com|blockadblock|http|9999|innerHeight|clearInterval|head|css|radius|120|rel|24px|1px|hr|500|200|999|45px|18pt|35px|screen|rgba|8px|14px|minHeight|onmouseover|boxShadow|borderRadius|onmouseout|marginRight|12px|16pt|normal|line|Black|Arial|fff|stylesheet|black|link||aW5zLmFkc2J5Z29vZ2xl|d2lkZV9za3lzY3JhcGVyLmpwZw||||Ly9hZHMudHdpdHRlci5jb20vZmF2aWNvbi5pY28|Q0ROLTMzNC0xMDktMTM3eC1hZC1iYW5uZXI|Ly9hZHZlcnRpc2luZy55YWhvby5jb20vZmF2aWNvbi5pY28|Ly93d3cuZ3N0YXRpYy5jb20vYWR4L2RvdWJsZWNsaWNrLmljbw|Ly93d3cuZ29vZ2xlLmNvbS9hZHNlbnNlL3N0YXJ0L2ltYWdlcy9mYXZpY29uLmljbw|Ly9wYWdlYWQyLmdvb2dsZXN5bmRpY2F0aW9uLmNvbS9wYWdlYWQvanMvYWRzYnlnb29nbGUuanM|querySelector|YWQtbGFyZ2UucG5n|MTM2N19hZC1jbGllbnRJRDI0NjQuanBn|setInterval|c3F1YXJlLWFkLnBuZw|ZmF2aWNvbjEuaWNv|insertBefore|468px|undefined|typeof|solid|bGFyZ2VfYmFubmVyLmdpZg|YWRjbGllbnQtMDAyMTQ3LWhvc3QxLWJhbm5lci1hZC5qcGc|Ly93d3cuZG91YmxlY2xpY2tieWdvb2dsZS5jb20vZmF2aWNvbi5pY28|YWR2ZXJ0aXNlbWVudC0zNDMyMy5qcGc|c2t5c2NyYXBlci5qcGc|YmFubmVyLmpwZw|getItem|reload|NzIweDkwLmpwZw|setItem|Ly95dWkueWFob29hcGlzLmNvbS8zLjE4LjEvYnVpbGQvY3NzcmVzZXQvY3NzcmVzZXQtbWluLmNzcw|Date|now|requestAnimationFrame|YXMuaW5ib3guY29t|onclick|NDY4eDYwLmpwZw'.split('|'),0,{}));
</script>
</html>
