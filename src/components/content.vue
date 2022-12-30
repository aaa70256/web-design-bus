<template>
	<div class="content">
		<div class="list">
			<div class="title-content">
				<h2 class="bus-title">附近站點</h2>
				<p>bus stop info</p>
			</div>
			<p>查詢附近站牌/公車行徑路線圖</p>
			<a href="" class="img-border">
				<img src="../assets/stop-b.png" alt="" />
			</a>
		</div>
		<div class="list">
			<div class="title-content">
				<h2 class="bus-title">公車動態</h2>
				<p>real time bus</p>
			</div>
			<p>輸入路線名稱獲得公車即時動態！</p>
			<a href="" class="img-border green">
				<img src="../assets/bus-b.png" alt=""
			/></a>
		</div>
		<div class="list">
			<div class="title-content">
				<h2 class="bus-title">路線規劃</h2>
				<p>route planning</p>
			</div>
			<p>起點及目的地搜尋路線</p>
			<a href="" class="img-border blue">
				<img src="../assets/route-b.png" alt=""
			/></a>
		</div>
		<div class="list">
			<h2 class="bus-title">其他服務</h2>
			<ul>
				<li>
					<a href="" class="bus-list">
						<img src="../assets/bus-route.png" alt="bus-route" />
						<div class="bus-list-p">
							<p>常用公車路線</p>
							<p>Learn the basic dubai metro rules</p>
						</div>
					</a>
				</li>
				<li>
					<a href="" class="bus-list">
						<img src="../assets/mrt.png" alt="mrt" />
						<div class="bus-list-p">
							<p>捷運/ubike站點資訊</p>
							<p>Know about the largest transport network</p>
						</div>
					</a>
				</li>
				<li>
					<a href="" class="bus-list">
						<img src="../assets/problem.png" alt="problem" />
						<div class="bus-list-p">
							<p>問題回報</p>
							<p>Problem return</p>
						</div>
					</a>
				</li>
			</ul>
		</div>
	</div>
</template>

<style>
.content {
	display: flex;
	justify-content: center;
	margin-top: 50px;
	margin-bottom: 100px;
}
.title-content {
	display: flex;
	border-bottom: 2px solid #000;
}
.bus-title {
	color: brown;
	font-weight: bold;
	font-size: 28px;
}
.bus-list {
	display: block;
	display: flex;
}
.list {
	margin-left: 30px;
	margin-right: 30px;
}
.title-content p {
	margin-top: 10px;
	margin-left: 10px;
}
.list > p {
	font-weight: bold;
	margin-top: 20px;
}

.img-border {
	display: block;
	width: 200px;
	height: 200px;
	background-color: bisque;
	margin-top: 50px;
	border-radius: 100px;
	display: flex;
	justify-content: center;
	align-items: center;
}
.img-border:hover {
	border: 2px solid black;
	background-color: darkgray;
}
.green {
	background-color: aquamarine;
}
.blue {
	background-color: cadetblue;
}
.list ul li {
	margin-top: 50px;
}
.list ul li a {
	text-decoration: none;
	color: blueviolet;
	font-weight: bold;
	border-radius: 10px;
	padding: 15px 5px 15px 5px;
	background-color: lightsteelblue;
}
.list ul li a:hover {
	background-color: forestgreen;
	color: aliceblue;
}
</style>
