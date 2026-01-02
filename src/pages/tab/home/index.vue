<template>
  <view class="flex flex-col items-center justify-center">
    <image
      class="mb-50rpx mt-200rpx h-200rpx w-200rpx"
      src="@/static/images/logo.png"
      width="200rpx"
      height="200rpx"
    />
    <view class="px-30rpx text-center">
      <view class="font-size-36rpx color-gray-700">
        uniapp 团队协作开发实践模板(Vue3)
      </view>
      <view class="mt-20rpx color-gray-500">
        使用 uniapp+vite+vue3+typescript+uview-plus+unocss 搭建的适合团队协作的快速开发模版
      </view>
    </view>
  </view>
</template>

<script setup lang="ts">
import { useUserStore } from '@/store';

const userStore = useUserStore();
console.log('userStore.user_name', userStore.user_name);
</script>
