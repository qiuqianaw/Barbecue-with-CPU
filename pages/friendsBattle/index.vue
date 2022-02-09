<template>
	<view class="content">
		<image class="image-top" mode="widthFix" src="../../static/friendsBattle/img_friends_battle_top_battle.png"></image>
		<view class="person-info">
			<view class="person-left">
				<image class="avatar" src="../../static/logo.png"></image>
				<text style="font-weight: bold;">X X X</text>
				<text>积分值：999</text>
				<text>斗胜率：99%</text>
			</view>
			<view style="flex: 1;"></view>
			<view class="person-left">
				<image class="avatar" src="../../static/logo.png"></image>
				<text style="font-weight: bold;">X X X</text>
				<text>积分值：999</text>
				<text>斗胜率：99%</text>
			</view>
		</view>
		<!-- 等待好友应战... -->
		<view class="btn-gray">邀 请 好 友 对 战</view>
		
		<!-- <view class="mask">
			<view class="pop-box">
				<image class="pop-top" mode="widthFix" src="../../static/friendsBattle/img_friends_battle_poptop.png"></image>
				<text>是否确定退出？</text>
				<text>退出后房间失效，好友无法应战</text>
				<view class="btn-bottom">
					<view class="btn-left">退出</view>
					<view class="btn-right">取消</view>
				</view>
			</view>
		</view> -->
	</view>
</template>

<script>
</script>

<style scoped>
	.content {
		width: 100%;
		height: 100%;
		background-image: url(../../static/friendsBattle/img_friends_battle_bg.png);
		background-size: 100% 100%;
		background-position: center bottom;
		display: flex;
		flex-direction: column;
		align-items: center;
	}
	.image-top {
		width: 350rpx;
		margin-top: 60rpx;
	}
	.person-info {
		width: 100%;
		color: white;
		display: flex;
		padding: 80rpx;
		margin-top: 50rpx;
	}
	.person-left {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
	.person-left text {
		margin: 15rpx 0rpx;
	}
	.avatar {
		border-radius: 50%;
		width: 120rpx;
		height: 120rpx;
	}
	.btn-gray {
		width: calc(100% - 250rpx);
		height: 80rpx;
		border-radius: 80rpx;
		color: white;
		line-height: 80rpx;
		text-align: center;
		background-color: #6E6E96;
		font-size: 31rpx;
		margin-top: 50rpx;
	}
	.mask {
		height: 100%;
		width: 100%;
		position: absolute;
		background-color: rgba(0,0,0,.5);
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.pop-box {
		width: 80%;
		height: 400rpx;
		background-color: white;
		border-radius: 30rpx;
		display: flex;
		flex-direction: column;
		padding: 10rpx 20rpx;
	}
	.pop-top {
		align-self: center;
		width: 100rpx;
		margin-top: 40rpx;
		margin-bottom: 50rpx;
	}
	.pop-box text {
		color: #868686;
		font-size: 30rpx;
		line-height: 50rpx;
	}
	.btn-bottom {
		display: flex;
		justify-content: center;
	}
	.btn-bottom view {
		width: 120rpx;
		height: 55rpx;
		color: white;
		line-height: 55rpx;
		border-radius: 10rpx;
		text-align: center;
		background-color: #FF9C37;
		margin-right: 10rpx;
		margin-top: 40rpx;
	}
	.btn-right {
		background-color: #E5E5E5 !important;
		color: #909090 !important;
		margin-left: 10rpx;
	}
</style>
