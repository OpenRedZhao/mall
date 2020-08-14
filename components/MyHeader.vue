<template>
	<view class="myheader">
		<view class="status"></view>
		<view class="header">
			<!-- 顶部导航 -->
			<view class="navbar">
				<view class="search">
					<image src="../static/image/search.png" mode=""></image>
				</view>
				<view class="logo">
					<image src="../static/image/logo.png" mode=""></image>
				</view>
				<view class="cart">
					<image src="../static/image/trolley.png" mode=""></image>
				</view>
			</view>
			<!-- 顶部菜单 -->
			<view class="menuTab">
				<view class="menuTabItem menuActive">
					推荐
				</view>
				<view class="menuTabItem">
					手机
				</view>
				<view class="menuTabItem">
					声学
				</view>
				<view class="menuTabItem">
					配件
				</view>
				<view class="menuTabItem">
					生活
				</view>
			</view>
		</view>
		<!-- 占位元素 -->
		<view class="menuTabEmtyp"></view>
	</view>
</template>

<script>
</script>

<style>
	/* 顶部app状态栏 */
	.status {
	      height: var(--status-bar-height);
	      width: 100%;
		  position: fixed;
		  top: 0rpx;
		  background: #000000;
		  z-index: 9;
	  }
	/* 顶部菜单 */
	.header {
		height: 180rpx;
		width: 100%;
		position: fixed;
		background: #fff;
		z-index: 9;
		top: var(--status-bar-height);
	}
	
	.navbar {
		height: 110rpx;
		display: flex;
		margin: 0 20rpx;
		align-items: center; /* 垂直居中 */
		justify-content: space-between; /* 两边对齐 */
	}
	.navbar .search image, .navbar .cart image {
		width: 30rpx;
		height: 30rpx;
	}
	.navbar .logo image {
		width: 140rpx;
		height: 30rpx;
	}
	.menuTab {
		height: 70rpx;
		display: flex;
		margin: 0 20rpx;
		justify-content: space-between;
	}
	.menuTab .menuTabItem {
		font-size: 28rpx;
		width: 60rpx;
		height: 55rpx;
		line-height: 55rpx;
	}
	.menuTab .menuTabItem.menuActive {	/* 选中激活 这里没有空格*/
		color: #0bbbef;
		border-bottom: 1px solid #0bbbef;
	}
	.menuTabEmtyp {
		height: 180rpx;
	}
</style>
