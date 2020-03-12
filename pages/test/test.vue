<template>
	<view class="content">
		<view class="box animated " hover-class="box-hover bounceIn">
			按压动画测试
		</view>
		
		<view class="box2">
			<text>文本</text>
			<view>1</view>
			<view>2</view>
			<view>3</view>
			<view>4</view>
			
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="stylus">
	.content
		display flex
		justify-content center
		flex-direction column
		.box
			background #1CBBB4
			width 200upx
			height 200upx
		.box-hover
			background #ff6900
			
		.box2
			width 300upx
			height 300upx
			margin 20upx
			padding 10upx
			// view:nth-of-type(1)
			// 	background orange
			// view:nth-of-type(2)
			// 	background green
			// view:nth-of-type(3)
			// 	background pink
			view:nth-of-type(2n-1)
				background red
			view:nth-of-type(2n)
				background blue
</style>
