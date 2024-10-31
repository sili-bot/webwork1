<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>我的简易网页布局</title>
		<style type="text/css">
			body{
				background-color: dimgray;
				margin: 0px;
				padding: 0px;
			}
			ul{
					list-style-type:none;
			 		margin:0px auto;
			    	padding:0px;
			    	display:flex;
					justify-content:center;
					background-color:black;
			}
			li{
				 	width:15%;
			    	line-height:50px;
			    	text-align:center;
			    	background-size:100% 100%;
					color: aliceblue;
			}
			.txt1{
				color: gold;
				font-size: 30px;
				font-family: 华文行楷;
				border-right: 1px solid lightgoldenrodyellow;
			}
			.img1{
				width: 75%;
				height: 85%;
				display: flex;
				position: absolute;
				left: 12.5%;
			}
			.page1{
				height: 150px;
				width: 40px;
				display: flex;
				position: absolute;
				left: 12.5%;
				top: 290px;
				align-items: center;
				justify-content: center;
				font-size: 20px;
				background-color: rgba(255,255,255,0.0);
				border-radius: 25px;
				color: grey;
			}
			.page2{
				height: 150px;
				width: 40px;
				display: flex;
				position: absolute;
				right: 12.5%;
				top: 290px;
				align-items: center;
				justify-content: center;
				font-size: 20px;
				background-color: rgba(255,255,255,0.0);
				border-radius: 25px;
				color: grey;
			}
			.choose1{
				height: 90px;
				width: 37.5%;
				display: flex;
				position: absolute;
				top: 89%;
				left: 12.5%;
				align-items: center;
				justify-content: center;
				font-size: 45px;
				color: dimgray;
				background-color: black;
				font-family: 华文楷体;
				border-color: beige;
			}
			.choose2{
				height: 90px;
				width: 37.5%;
				display: flex;
				position: absolute;
				top: 89%;
				right: 12.5%;
				align-items: center;
				justify-content: center;
				font-size: 45px;
				color: dimgray;
				background-color: black;
				font-family: 华文楷体;
				border-color: beige;
			}
			.hide1{
				text-decoration: none;
				color: dimgray;
			}
		</style>
	</head>
	<body>
		<ul>
			<li id="first" class="txt1">言er</li>
			<li>首页</li>
		    <li>魂类游戏</li>
			<li>类魂游戏</li>
			<li>其他</li>
		</ul>
		<img src="12138.png" class="img1"/>
		<button type="button" class="page1" onclick="">◁</button>
		<button type="button" class="page2">▷</button>
		<button type="button" class="choose1">继续了解</button>
		<button type="button" class="choose2" onclick="location.href='https://ys.mihoyo.com'"><a href="https://ys.mihoyo.com/" class="hide1">不感兴趣</a></button>
	</body>
</html>
