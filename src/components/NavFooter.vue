<template>
	<div class="footer">
		<div class="footer-logo">
			<img src="/imgs/logo-footer.png" alt="">
			<p>小米商城</p>
		</div>
		<div class="footer-link">
			<a href="">樊智勇主页</a><span>|</span>
			<a href="">Vue全栈课程</a><span>|</span>
			<a href="">React全家桶课程</a><span>|</span>
			<a href="">微信支付专项课程</a><span>|</span>
			<a href="">樊智勇主页</a>
		</div>
		<div class="copyright">
			Copyright 2020
		</div>
	</div>
</template>
<script>
export default {
    name:"nav-footer"
}
</script>
<style lang="scss" scoped>
	@import './../assets/sass/base.scss';
	@import './../assets/sass/mixin.scss';
	@import './../assets/sass/config.scss';
	.footer{
		height: 234px;
		border-top: 4px solid $colorA;
		background-color: #333;
		color: $colorD;
		font-size: 16px;
		text-align: center;
		.footer-logo{
			margin-top: 46px;
			margin-bottom: 31px;
			img{
				width: 53px;
				height: 36px;
				margin-bottom: 13px;
			}
		}
		.footer-link{
			margin-bottom: 13px;
			a{
				color:$colorD;
				display: inline-block;
			}
			span{
					margin: 0 10px;
			}
		}
	}
</style>