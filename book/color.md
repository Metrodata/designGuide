# 色彩
---

###界面色彩

<div class ="bg">
	<div class = "container">
		<div class="card standardBlue">
			<p>标准蓝</p>
			<div class="colorCardFooter">
				<p>#429AFF <br> RGB 208,74,100</p>
			</div>
		</div>
		<div class = "cardPara">
			<p class="cardParaTitle"><strong >标准蓝色</strong></p>
			<p>产品标准色，主产品蓝色色调以此为主。</p>
			<p> 个性化产品可能有不同主题色，保持一致性即可。</p>
		</div>
		<div class = "card"></div>
		<div class = "card"></div>
	</div>
	<div class = "container">
		<div class="card boxFrame">
			<p>border: 1px solid #429AFF;</p>
			<p>	color: #429AFF;</p>
		</div>
		<div class="cardPara">
			<p class="cardParaTitle"><strong >组件框</strong></p>
			<p>功能组件默认边框。</p>
		</div>
		<div class="card homePanel">
			<p>	border: 1px solid #429AFF;</p>
			<p>	color: rgba(255,255,255,0.8);</p>
			<p>	background: rgba(35,78,128,0.80);</p>
		</div>
		<div class="cardPara">
			<p class="cardParaTitle"><strong >首页面板</strong></p>
			<p>首页地图上半透明浮层，用于首页数据和表格展示。</p>
		</div>		
	</div>
	<div class = "container">
		<div class="card solidPanel">
			<p>border: 1px solid #429AFF;</p>
			<p>	color: #429AFF;</p>
			<p>	background: #1B243B;</p>
		</div>
		<div class="cardPara">
			<p class="cardParaTitle"><strong>菜单面板</strong></p>
			<p>下拉菜单，提示框（无边框）</p>
		</div>
		<div class="card mapPanel">
			<p>	border: none;</p>
			<p>	color: rgba(255,255,255,0.8); </p>
			<p>background: rgba(25,68,106, 0.8);</p>
		</div>
		<div class="cardPara ">
			<p class="cardParaTitle"><strong >地图面板</strong></p>
			<p>地图上半透明浮层，多用于数据可视化图例展示和调节。</p>
		</div>
	</div>
</div>   

<div class ="bg">
	<div class = "container">
		<div class="card boxFrame buttonFrame">
			<button class="buttonPrimary">启动查询</button>
			<button class="buttonLine">添加</button>
		</div>
		<div class="cardPara">
			<p class="cardParaTitle"><strong >按钮</strong></p>
			<p>产品按钮，分为主按钮和次按钮（幽灵按钮）</p>
		</div>
		<div class = "card"></div>
		<div class = "card"></div>
	</div>
</div>

```css
.buttonPrimary{
	background-color: #2E75B3;
	color: white;
	font-size: 14px;
	font-family: sans-serif;
	font-weight: 600;
	border: none;
	width: 84px;
	height: 28px;
	padding-top: 4px;
	transition: .2s;
	margin: 0 auto 24px auto;
	outline:none;
}

.buttonPrimary:hover{
	color: white;
	background-color: #429AFF;
	transition: .2s;
}

.buttonPrimary:active{
	color: white;
	background-color: #2E75B3;
}


.buttonLine{
	color: #429AFF;
	background-color: transparent;
	font-size: 14px;
	font-family: sans-serif;
	font-weight: 600;
	border: #429AFF 1px solid;
	width: 84px;
	height: 28px;
	padding-top: 4px;
	transition: .2s;
	margin: 0 auto 0 auto;
	outline:none;
}

.buttonLine:hover{
	color:white;
	background-color: #429AFF;
	transition: .2s;
}

.buttonLine:active{
	color: white;
	background-color: #2E75B3;
}
```


###可视化



<style>

*{
	box-sizing: border-box;
}

.bg{
	background-image: url("../img/bgBlur.png");
	width:100%;
	height: auto;
	padding: 1px;
	background-size: cover;
	background-position: center;
	margin-bottom: 30px; 
}

.container{
	margin: 60px auto;
	height: auto;
	width: 90%;
	display: flex;
	justify-content:space-between;
	/*border:1px red solid;*/
}

.card{
	width: 21%;
	height: 210px;
	padding: 20px 18px;
	position: relative;
	font-family: sans-serif;
	font-weight: 800;
	font-size: 13px;
	line-height: 18px;
	/*border: red 1px solid;*/
}
.colorCardFooter{
	opacity: 0.7;
	bottom: 15px;
	position: absolute;
}

.standardBlue{
	background-color: #429AFF;
	color: white;
}

.boxFrame{
	border: 1px solid #429AFF;
	color: #429AFF;
}

.solidPanel{
	background: #1B243B;
	border: 1px solid #429AFF;
	color: #429AFF;
}

.selectedArea{
	background: rgba(51,160,255,0.40);
	border: 4px solid #429AFF;
}

.cardPara{
	margin-left: -16px;
	color: white;
	width: 21%;
	font-family: sans-serif;
	font-size: 12px;
	font-weight: 600;
	line-height: 18px;
	color: rgba(255,255,255,0.9);
	padding-top: 20px;
	/*border: 1px red solid;*/
}

.cardParaTitle{
	font-size: 18px;
}


.mapPanel{
	border: none;
	color: rgba(255,255,255,0.8);
	background: rgba(35,78,128,0.8);
}

.homePanel{
	border: 1px solid #429AFF;
	background: rgba(32,43,69,0.9);
	color: rgba(255,255,255,0.8);
}

.buttonFrame{
	text-align:center;
	border: none;
	height:auto;
}

.buttonPrimary{
	display: block;
	background-color: #2E75B3;
	color: white;
	font-size: 14px;
	font-family: sans-serif;
	font-weight: 600;
	border: none;
	width: 84px;
	height: 28px;
	padding-top: 4px;
	transition: .2s;
	margin: 0 auto 24px auto;
	outline:none;
}

.buttonPrimary:hover{
	color: white;
	background-color: #429AFF;
	transition: .2s;
}

.buttonPrimary:active{
	color: white;
	background-color: #2E75B3;
}


.buttonLine{
	display: block;
	color: #429AFF;
	background-color: transparent;
	font-size: 14px;
	font-family: sans-serif;
	font-weight: 600;
	border: #429AFF 1px solid;
	width: 84px;
	height: 28px;
	padding-top: 4px;
	transition: .2s;
	margin: 0 auto 0 auto;
	outline:none;
}

.buttonLine:hover{
	color:white;
	background-color: #429AFF;
	transition: .2s;
}

.buttonLine:active{
	color: white;
	background-color: #2E75B3;
}
</style>