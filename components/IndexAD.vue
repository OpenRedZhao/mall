<template>
	<view class="">
		<view class="indexAD">
			<view class="indexADleft">
				<image src="../static/image/ad1.jpg" mode=""></image>
			</view>
			<view class="indexADright">
				<view class="indexADrightItem">
					<image src="../static/image/ad2.jpg" mode=""></image>
				</view>
				<view class="indexADrightItem">
					<image src="../static/image/ad3.png" mode=""></image>
				</view>
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style>
	.indexAD {
		display: flex;
		border-top: 20rpx solid #f4f4f4;
	}
	.indexADleft, .indexADright {
		width: 50%;
	}
	.indexADleft {
		height: 520rpx;
	}
	.indexADleft image {
		width: 100%;
		height: 520rpx;
	}
	.indexADrightItem {
		height: 260rpx;
	}
	.indexADrightItem image {
		width: 100%;
		height: 260rpx;
	}
</style>
