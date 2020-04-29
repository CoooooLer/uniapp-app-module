<template>
	<view class="content animated fadeInLeft">
		 <navigator url="/pages/test/test" hover-class="navigator-hover">
			<button type="default">跳转到新页面</button>
		</navigator>
		
		
	</view>
</template>

<script>
	export default {
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

<style lang="stylus" scoped>
	page
		background-color #1CBBB4
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		height 50upx
	}

	
</style>
