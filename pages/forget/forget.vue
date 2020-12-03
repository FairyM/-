<template>
	<view class="message">
		<view class="input-group">
			<view class="input-row">
				<image class="icon-phone" src="../../static/icon-phone@2x.png"></image>
				<input class="m-input" type="text" maxlength='11' placeholder="请输入手机号"></input>
			</view>
		</view>
		<view class="xian"></view>
		<view class="input-group">
			<view class="input-row">
				<image class="icon-yzm" src="../../static/icon-yzm@2x.png"></image>
				<input class="m-input" type="text" maxlength='6' placeholder=" 请输入验证码"></input>
				<button class="bton2" plain="true" type="warn">获取验证码</button>
			</view>
		</view>
		<view class="xian"></view>
		<view class="input-group">
			<view class="input-row">
				<image class="icon-suo" src="../../static/icon-suo@2x.png"></image>
				<input class="m-input" type="text" placeholder=" 新密码" password="true"></input>
			</view>
		</view>
		<view class="xian"></view>
		<view class="input-group">
			<view class="input-row">
				<image class="suo-2" src="../../static/icon-suo@2x.png"></image>
				<input class="m-input" type="text" placeholder=" 确认密码" password="true"></input>
			</view>
		</view>
		<view class="xian"></view>
		<view class="btn-row">
			<button class="bton" open-type="openSetting">
				<image src="../../static/圆角矩形4@2x.png"></image>
				<view class="sure" style="color: #FFFFFF;">确定</view>
			</button>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
			}
		},
		onLoad() {
	
		},
		methods: {
	
		}
	}
</script>

<style>
	.container {
		padding: 20rpx;
		font-size: 14rpx;
		line-height: 24rpx;
	}
	.icon-phone {
		width: 27rpx;
		height: 41rpx;
	}
	.icon-yzm {
		width: 28rpx;
		height: 24rpx;
	}
	.icon-suo {
		width: 28rpx;
		height: 38rpx;
	}
	.suo-2 {
		width: 28rpx;
		height: 38rpx;
	}
	.bton{
		width: 570rpx;
		height: 88rpx;
		border-radius: 44rpx;
		background-color: #eb9229;
		display: flex;
		margin-top: 150rpx;
		border: 0;
	}
	.bton2 {
		width: 200rpx;
		height: 70rpx;
		border: solid 1rpx #eb9229;
		border-radius:25rpx;
		font-family: PingFang-SC-Regular;
		font-size: 28rpx;
		font-weight: normal;
		font-stretch: normal;
		letter-spacing: 0rpx;
	}
	.input-row{
		display: flex;
		flex-direction: row;
		margin-left: 60rpx;
		margin-top: 98rpx;
	}
	.m-input {
		width: 165rpx;
		height: 26rpx;
		font-family: PingFangSC-Regular;
		font-size: 28rpx;
		font-weight: normal;
		font-stretch: normal;
		letter-spacing: 0rpx;
		color: #cccccc;
	}
	.xian {
		width: 630rpx;
		height: 1rpx;
		background-color: #eeeeee;
		margin-left: 60rpx;
		margin-right: 60rpx;
	}
	.sure {
		position: absolute;
		width: 300rpx;
		height: 34rpx;
		font-family: PingFangSC-Regular;
		font-size: 45rpx;
		font-weight: normal;
		font-stretch: normal;
		letter-spacing: 0rpx;
		color: #ffffff;
		margin-left: 100rpx;
	}
</style>