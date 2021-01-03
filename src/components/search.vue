<template>
	<view class="content">
		<view class="content-search">
            搜索
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
.content{
    padding: 10rpx 0;
  position: fixed;/*悬停搜索框的关键样式*/
  top: 0px;
  left: 0;
  width: 100%;
  z-index: 999;
  background-color: #e21918;
}
.content-search{
     display: flex;
  align-items: center;
  justify-content: center;
  width: 700rpx;
  height: 80rpx;
  color: #ccc;
  border-radius: 5rpx;
  background-color: #fff;
}
</style>
