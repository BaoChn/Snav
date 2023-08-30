<template>
  <n-tabs class="all-box" size="large" justify-content="space-evenly" animated >
    <n-tab-pane class="no-padding" name="link" tab="捷径">
      <ShortCut />
    </n-tab-pane>
    <n-tab-pane name="note" tab="便签">
      <iframe src="//memo.chancel.me/" height="450vh" width="100%" frameborder="0" style="border-radius:.5em;"></iframe>
      <p style="text-align: center;">测试功能，不代表最终效果</p>
    </n-tab-pane>
    <n-tab-pane name="more" tab="待办">
      <iframe src="//gaohaoyang.github.io/ToDo-WebApp/" height="450vh" width="100%" frameborder="0" style="border-radius:.5em;"></iframe>
      <p style="text-align: center;">测试功能，不代表最终效果</p>
    </n-tab-pane>
  </n-tabs>
</template>

<script setup>
import { NTabs, NTabPane } from "naive-ui";
import ShortCut from "@/components/AllFunc/Box/ShortCut.vue";
</script>
