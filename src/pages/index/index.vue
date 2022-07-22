<template>
  <view class="flex p-2.5">
    <view class="p-2.5 w-1/2">
      <text>1</text>
    </view>
    <view class="p-2.5 w-1/2" v-for="item in list" :key="item">
      <image src="../../cover.jpg" />
    </view>
    <!-- <view class="p-2.5 w-1/2">
      <image src="../../cover.jpg" />
    </view>
    <view class="p-2.5 w-1/2">
      <image src="../../cover.jpg" />
    </view> -->
  </view>
</template>

<script setup>
import { ref } from "vue";

const list = ref([1, 2, 3]);
</script>
