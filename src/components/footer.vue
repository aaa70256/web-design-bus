<template>
	<div class="footer">
		<p>Copyright © 2018 交通局版權所有</p>
		<ul class="list">
			<li><a href="">關於我們</a></li>
			<li><a href="">路線資訊</a></li>
			<li><a href="">聯絡我們</a></li>
			<li><a href="">網站導覽</a></li>
			<li><a href="">FAQs</a></li>
		</ul>
	</div>
</template>
<style scoped>
.footer {
	background-color: #e0dada;
	height: 100px;
	display: flex;
	justify-content: space-between;
}
.footer p {
	margin: 40px;
	color: chocolate;
	font-weight: bold;
}
.list {
	float: left;
	margin: 40px;
}
.list li {
	float: left;
	margin-left: 20px;
}
.list li a {
	text-decoration: none;
	color: cadetblue;
	font-weight: bold;
	display: block;
}
</style>
