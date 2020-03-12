<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	
	/* 官方的css库 */
	@import './common/uni.css';
	
	/* iconfont图标库 */
	@import './common/iconfont.css';
	@import './common/animate.css' ;
</style>
