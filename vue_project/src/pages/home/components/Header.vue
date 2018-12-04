<template>
	<div class="header">
		<div class="header-left"><div class="iconfont back-icon">&#xe65d;</div></div>
		<div class="header-input"><span class="iconfont">&#xe61e;</span>输入景点/酒店/游玩主题</div>
		<div class="header-right">城市<span class="iconfont arrow-icon">&#xe65c;</span></div>
	</div>

</template>
<script>
export default {
		name: 'HomeHeader'
}
</script>
<style lang="stylus" scoped>

	.header
		display: flex 
		line-height:.86rem
		background:#00bcd4
		color:#fff
		.header-left
			float:left
			width:.86rem
			.back-icon
				text-align:center
				font-size:.4rem
		.header-right
			text-align:center
			float:right
			width:1.23rem
		.header-input
			flex:1
			height:.64rem
			line-height: .64rem
			padding-left:.2rem
			margin-top:.12rem
			margin-left:.2rem
			background:#fff
			border-radius:.1rem
			color:#ccc
			.arrow-icon
				margin-left:-.04rem
				font-size:.24rem
</style>