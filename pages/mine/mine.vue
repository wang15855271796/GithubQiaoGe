<template>
	<scroll-view >
		<view class="container">
			<view class="container_top">
				<!-- 设置和消息 -->
				<view class="container_head">
					<navigator><text class="iconfont icon-shezhi"></text></navigator>
					<navigator><text class="iconfont icon-icon--"></text></navigator>
				</view>
				
				<!-- 头像信息 -->
				<view class="uni-flex header">
					<image src="../../static/logo.png" style="width: 121rpx; height: 121rpx;"></image>
					<text>Hello,18757104843</text>
					<text class="member">翘歌会员</text>
				</view>
				
				<!-- 卡片信息 -->
				<view class="card_info">
					<view class="card_info_title">
						<text style="margin-top: 30rpx; font-weight: 700; font-size: 37rpx; margin-left: 30rpx;">翘歌·	<text style=" font-weight: 400;font-size: 30rpx;">会员中心</text></text>
						<text style="font-size: 22rpx; margin-right: 36rpx; margin-top: 41rpx;">更多权益 ></text>
					</view>
					
					<view class="card_info_content">
						<text>买食材，当然选翘歌！</text>
					</view>
				</view>
				
	
			</view>
			
			<view class="container_bottom">
				<!-- 余额 -->
				<view class="content_top">
					<text>余额100</text>
					<text>优惠券100</text>
				</view>
			</view>
		</view>
	</scroll-view> 

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

<style lang="scss">
	@import "../../common/icon.css";
	.container {
		width: 100%;
		display: flex;
		flex-direction: column;
		background-color: #f8f8f8;
		.container_top {
			
			display: flex;
			flex-direction: column;
			background: linear-gradient(-79deg, #D253B1 0%, #FB6F4A 100%);
			height: 500rpx;
			position: relative; 
			
			.container_head {
				display: flex;
				width: 90%;
				margin: 10rpx auto;
				align-items: space-between;
				justify-content: space-between;
				
				text {
					color: #FFFFFF;
				}
			}
			
			.header {
				width: 90%;
				display: flex;
				align-items: center;
				height: 90rpx;
				text-align: center;
				margin-left: 60rpx;
				margin-top: 38rpx;

				text {
					margin-left: 33rpx;
					font-size: 38rpx;
					font-weight: 700;
					color: #FFFFFF;
				}
				
				.member {
					font-size: 20rpx;
					font-weight: 400;
					padding: 8rpx;
					border-radius: 35rpx;
					background-color: rgba(0, 0, 0, 0.3);
				}
			}
			
			.card_info {
				width: 80%;
				display: flex;
				flex-direction: column;
				border-radius: 30rpx 30rpx 0 0;
				height: 220rpx;
				margin: auto;
				position: absolute;
				bottom: 0;
				left: 0;
				margin-left: 10%;
				background-color: #414041;
				
				text {
					color: #FFD4AB;
				}
				.card_info_title {
					display: flex;
					justify-content: space-between;
				}
				
				.card_info_content {
					display: flex;
					font-weight: 700;
					font-size: 37rpx;
					margin-top: 45rpx;
					margin-left: 30rpx;
				}
				
			}
		}
		
		.container_bottom{
			display: flex;
			width: 100%;
			flex-direction: column;
			background-color: #ffffff;
			.content_top {
				width: 100%;
				display: flex;
				align-items: center;
				justify-content: space-around;
				height: 120rpx;
				color: #333333;
				
			}
		}
	}
</style>
