<template>
  <scroll-view class="index" :scroll-y="true" :refresher-enabled="a">
    <view class="inner"></view>
    <view class="inner"></view>
    <view class="inner"></view>
  </scroll-view>
</template>

<script lang="ts" setup>
import { ref } from 'vue'
import './index.scss'

const a = ref(false)
</script>