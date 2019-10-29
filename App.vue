<script>
	// APP.vue文件
	export default {
		onLaunch: function() {//
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
	/*浏览器初始化的默认样式*/
	@import "static/css/initialize.css";

	/*每个页面公共css */
	* {
		font-size: 16px;
	}

	/*解决图片因为高度而不能铺满的问题*/
	uni-page-body {
		height: 100%;
	}

	page {
		height: 100%;
	}
</style>
