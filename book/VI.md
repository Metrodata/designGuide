# 脉策数据VI规范
---
###公司

#####公司全称 Logo:
<div class="box longbox">
	<img class="longLogo" src="../img/fullLogo.png">
</div>  

#####公司简称 Logo:
<div class="container">
	<div class="box shortbox greenInverse">
		<img class="shortLogo" src="../img/shortWhite.png">
	</div>  
	<div class="box shortbox redInverse">
		<img class="shortLogo" src="../img/cityGroupWhite.png">
	</div>  
</div> 

<div class="container">
	<div class="box shortbox">
		<img class="shortLogo" src="../img/shortLogo.png">
	</div>  
	<div class="box shortbox">
		<img class="shortLogo" src="../img/cityDataGroup.png">
	</div>  
</div>


######公司 Logo 色彩：
<div class="container">
	<div class="colorCard greenInverse">
		<p>绿色</p>
		<div class="colorCardFooter">
			<p>#307A74 <br> RGB 48,122,116</p>
		</div>
	</div>
	<div class="colorCard redInverse">
		<p>红色</p>
		<div class="colorCardFooter">
			<p>#D93526 <br> RGB 217,53,38</p>
		</div>
	</div>
	<div class="colorCard"></div>
	<div class="colorCard"></div>
	<div class="colorCard"></div>
</div>	

###产品

#####产品Datamap Logo:
<div class="box longbox blueInverse">
	<img class="longLogo" src="../img/dataMap.png">
</div>  

<div class="box longbox">
	<img class="longLogo" src="../img/dataMapBlue.png">
</div>

#####产品Datamap Logo (加汉字):
<div class="container">
	<div class="box shortbox blueInverse">
		<img class="shortLogo" src="../img/dataMapHZ.png">
	</div>  
	<div class="box shortbox">
		<img class="shortLogo" src="../img/dataMapHZBlue.png">
	</div>  
</div>

#####产品首页:



<style>
*{
	box-sizing: border-box;
	border-radius: 2px;
}
.box{
	border: 1px solid #E6E6E6;
	text-align: center;
	padding:40px;
	width: 100%;
}
.container{
	padding: 6px 0;
	display: flex;
	text-align:justify;
	justify-content:space-between;
	width: 100%;
	position: relative;
}

.shortbox{
	margin: 2.5px;
	width: 49%;
}
.longbox{
	margin: 0 0 10px 0;
}

.greenInverse{
	background-color:#307A74;
}
.redInverse{
	background-color:#D93526;
}
.blueInverse{
	background-color:#3E96D2;
}


.shortLogo{
	border: none;
	width: 200px;
}
.longLogo{
	border: none;
	width: auto;
	height:56px;
}

.colorCard{
	font-family: sans-serif;
	font-weight: 800;
	font-size: 14px;
	color: white;
	justify-content:space-between;
	width: 19%;
	height: 200px;
	padding: 20px 18px;
}

.colorCardFooter{
	opacity: 0.7;
	bottom: 15px;
	position: absolute;
}

</style>