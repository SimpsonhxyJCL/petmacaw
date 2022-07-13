<template>
	<view class="">
		<swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000" circular="true">
			<swiper-item>
				<view class="swiper-item"><image :src="swiperList[0]" mode=""></image></view>
			</swiper-item>
			<swiper-item>
				<view class="swiper-item"><image :src="swiperList[1]" mode=""></image></view>
			</swiper-item>
		</swiper>
	</view>
</template>

<script>
	export default{
		data(){
			return{
				swiperList:["../../static/image/cat1.jpg","../../static/image/cat2.jpg"]
			}
		},
		methods:{
			
		},
		computed:{
			
		}
	}
</script>

<style>
	.swiper-item{
		/* margin-left:50rpx; */
	}
</style>
