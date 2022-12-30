<template>
	<div class="Header">
		<div class="header">
			<div class="logo">
				<img src="@/assets/logo (1).png" alt="logo" />
				<div class="font">
					<p class="title">公車動態資訊</p>
					<p class="engtitle">real-time bus arrival info system</p>
				</div>
			</div>
			<div class="bell">
				<img src="@/assets/bells.png" alt="bell" />
			</div>
		</div>
		<div class="banner"></div>
	</div>
</template>

<style scoped>
.header {
	margin-left: 50px;
	margin-right: 50px;
	padding: 30px;
	display: flex;
	justify-content: space-between;
	align-items: center;
	flex-wrap: wrap;
}
.logo {
	border-left: 10px solid #000;
	display: flex;
	align-items: center;
}
.logo img {
	margin-left: 50px;
}
.font {
	margin-left: 20px;
}
.title {
	color: brown;
	font-weight: bold;
	font-size: 20px;
}
.engtitle {
	color: brown;
	font-weight: bold;
	font-size: 10px;
}
.banner {
	margin-left: 80px;
	background-image: url("../assets/banner.png");
	background-size: cover;
	width: 1120px;
	height: 195px;
}
</style>
