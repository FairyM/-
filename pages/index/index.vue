<template>
	<view class="month">
		<view class="tx-list">
			<view class="thismonth">本月</view>
			<view class="tx-item">
				<view class="qian">
					<view class="theday">昨天</view>
					<view class="thetime">09:00</view>
				</view>
				<view class="zfb">转至支付宝账户</view>
				<view class="hou">
					<view class="money">230.00元</view>
					<view class="state" style="color: #ff8e16;">提现中</view>
				</view>
			</view>
			<view class="xian"></view>
			<view class="tx-item">
				<view class="qian">
					<view class="theday">昨天</view>
					<view class="thetime">09:00</view>
				</view>
				<view class="wx">转至微信账户</view>
				<view class="hou">
					<view class="money">230.00元</view>
					<view class="state">已到账</view>
				</view>
			</view>
			<view class="xian"></view>
			<view class="tx-item">
				<view class="qian">
					<view class="theday">昨天</view>
					<view class="thetime">09:00</view>
				</view>
				<view class="wx">转至微信账户</view>
				<view class="hou">
					<view class="money">230.00元</view>
					<view class="state">已到账</view>
				</view>
			</view>
			<view class="xian"></view>
			<view class="tx-item">
				<view class="qian">
					<view class="theday">昨天</view>
					<view class="thetime">09:00</view>
				</view>
				<view class="zfb">转至支付宝账户</view>
				<view class="hou">
					<view class="money">230.00元</view>
					<view class="state">已到账</view>
				</view>
			</view>
			<view class="xian"></view>
		</view>
		<view class="thismonth">六月</view>
		<view class="tx-list">
			<view class="tx-item">
				<view class="qian">
					<view class="theday">昨天</view>
					<view class="thetime">09:00</view>
				</view>
				<view class="zfb">转至支付宝账户</view>
				<view class="hou">
					<view class="money">230.00元</view>
					<view class="state">已到账</view>
				</view>
			</view>
			<view class="xian"></view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.thismonth {
		width: 400px;
		height: 28px;
		color: #666666;
		background-color: #d6d6e2;
		padding-left: 25rpx;
		opacity: 0.2;
	}
	.theday {
		width: 100px;
		height: 32px;
		font-family: PingFang-SC-Medium;
		font-size: 17px;
		font-weight: normal;
		font-stretch: normal;
		line-height: 36px;
		letter-spacing: 0px;
		color: #666666;
		margin-left: 38rpx;
	}
	.thetime {
		width: 68px;
		height: 21px;
		font-family: PingFang-SC-Medium;
		font-size: 13px;
		font-weight: normal;
		font-stretch: normal;
		line-height: 36px;
		letter-spacing: 0px;
		color: #999999;
		margin-left: 36rpx;
	}
	.zfb {
		width: 350rpx;
		height: 32rpx;
		display: flex;
		align-content: center;
		font-family: PingFang-SC-Medium;
		font-size: 34rpx;
		font-weight: normal;
		font-stretch: normal;
		line-height: 36px;
		letter-spacing: 0px;
		color: #666666;
	}
	.wx {
		width: 350rpx;
		height: 32rpx;
		font-family: PingFang-SC-Medium;
		font-size: 34rpx;
		font-weight: normal;
		font-stretch: normal;
		line-height: 36px;
		letter-spacing: 0px;
		color: #666666;
	}
	.money {
		width: 100px;
		height: 30px;
		text-align: right;
		padding-right: 2px;
		font-family: PingFang-SC-Medium;
		font-size: 17px;
		font-weight: normal;
		font-stretch: normal;
		line-height: 36px;
		letter-spacing: 0px;
		color: #666666;
	}
	.state {
		text-align: right;
		padding-right: 2px;
		font-family: PingFang-SC-Medium;
		font-size: 15px;
		font-weight: normal;
		font-stretch: normal;
		line-height: 36px;
		color: #999999;
	}
	.qian{
		display: flex;
		flex-direction: column;
	}
	.hou{
		margin-right: 10rpx;
		display: flex;
		flex-direction: column;
	}
	.tx-item{
		display: flex;
		flex-direction: row;
	}
	.xian {
		width: 630px;
		height: 1px;
		background-color: #eeeeee;
	}
</style>