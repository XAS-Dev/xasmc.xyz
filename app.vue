<template>
  <!-- 没错, 这是个服务器主页 -->
  <div class="bg h-dvh w-dvw overflow-hidden bg-black bg-opacity-80 flex items-center justify-center flex-col">
    <span class="text-zinc-400 text-4xl">XAS Minecraft Server</span>
    <span class="text-5xl mt-20">🫵😡</span>
    <span class="text-zinc-400 text-2xl">给我玩 Minecraft </span>
    <span
      class="text-zinc-400 mt-20 border-2 ml-2 mr-2 p-1 border-zinc-600 inline-block w-40 text-center rounded-full hover:bg-slate-600 transition-colors duration-500 transform-gpu"><a
        href="https://qm.qq.com/q/3hQeLmSyNW">加入服务器QQ群</a></span>
    <span class="text-zinc-700 text-xs mt-1">无法跳转? 加群513213647</span>
    <span class="footer fixed bottom-4 text-lg text-zinc-400 font-thin text-center"><a href="https://beian.miit.gov.cn/"
        target="_blank">陕ICP备2023002983号-2</a></span>
  </div>
</template>

<script lang="ts" setup>
useHead({
  title: "XAS Minecraft 服务器",
  meta: [
    { name: "description", content: `欢迎来到 XAS Minecraft 服务器` },
    {
      hid: "keywords",
      name: "keywords",
      content: "minecraft,mc,server,服务器,主页,XAS",
    },
  ],
});
</script>
