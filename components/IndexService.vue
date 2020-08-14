<template>
	<view class="">
		<view class="service">
			<view class="serviceItem">
				<image src="../static/image/icon1.png" mode=""></image>
				<text>魅族官网直供</text>
			</view>
			<view class="serviceItem">
				<image src="../static/image/icon2.png" mode=""></image>
				<text>满80免运费</text>
			</view>
			<view class="serviceItem">
				<image src="../static/image/icon3.png" mode=""></image>
				<text>7天无理由退货</text>
			</view>
		</view>
		<view class="shopNav">
			<view class="shopNavItem">
				<image src="../static/image/recommend1.png" mode=""></image>
				<text>魅族 16S Pro</text>
			</view>
			<view class="shopNavItem">
				<image src="../static/image/recommend2.png" mode=""></image>
				<text>魅族 16S Pro</text>
			</view>
			<view class="shopNavItem">
				<image src="../static/image/recommend3.jpg" mode=""></image>
				<text>魅族 16S Pro</text>
			</view>
			<view class="shopNavItem">
				<image src="../static/image/recommend4.jpg" mode=""></image>
				<text>魅族 16S Pro</text>
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style>
.service {
	display: flex;
	height: 70rpx;
	background: #F7F7F7;
	justify-content: center;
}
.serviceItem {
	font-size: 24rpx;
	color: #a3a3a3;
	display: flex;
	align-items: center;
	margin: 0 20rpx;
}
.serviceItem image {
	width: 35rpx;
	height: 35rpx;
	margin: 10rpx;
}
.shopNav {
	height: 225rpx;
	display: flex;
	justify-content: center;
	background: #fff;
}
.shopNavItem {
	margin: 10rpx;
}
.shopNavItem image {
	width: 100rpx;
	height: 100rpx;
	margin-top: 30rpx;
}
.shopNavItem text {
	display: block;
	font-size: 24rpx;
	color: #000000;
}
</style>
