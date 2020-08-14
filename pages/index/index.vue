<template>
	<view class="content">
		<MyHeader></MyHeader>
		<IndexSwiper></IndexSwiper>
		<IndexService></IndexService>
		<IndexAD></IndexAD>
	</view>
</template>

<script>
	import MyHeader from "../../components/MyHeader.vue"
	import IndexSwiper from "../../components/IndexSwiper.vue"
	import IndexService from "../../components/IndexService.vue"
	import IndexAD from "../../components/IndexAD.vue"
	export default {
		components: {
			MyHeader, //首页顶部导航组件
			IndexSwiper, //首页轮播图组件
			IndexService, //首页服务组件
			IndexAD	//首页广告组件
		},
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	/* 首页背景颜色 */
	page {
		background: #f4f4f4;
	}
	
	
</style>
