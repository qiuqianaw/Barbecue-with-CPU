<template>
	<view class="content">
		<text class="problem-text">为什么用“连理枝”比喻恩爱的夫妻？有什么典故？</text>
		<view class="choose-text">
			<text>A.&nbsp;&nbsp;XXXXXXXXX</text>
			<text>B.&nbsp;&nbsp;XXXXXXXXX</text>
			<text>C.&nbsp;&nbsp;XXXXXXXXX</text>
			<text>D.&nbsp;&nbsp;XXXXXXXXX</text>
		</view>
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

<style>
	.content {
		width: 100%;
		height: 100%;
		background-color: #ffffff;
		display: flex;
		flex-direction: column;
		justify-content: center;
		padding: 0rpx 60rpx;
	}
	text {
		font-size: 36rpx;
	}
	.problem-text {
		/* height: 350rpx; */
		margin-bottom: 250rpx;
	}
	.choose-text {
		margin-left: 10rpx;
		margin-bottom: 80rpx;
	}
	.choose-text text {
		display: block;
		margin-bottom: 70rpx;
	}
</style>
