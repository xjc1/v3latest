<template>
  <div class="TailwindCpm">
    <div
      class="flex items-center p-6 max-w-sm mx-auto bg-white rounded-xl shadow-lg space-x-6 pt-6"
    >
      <!-- 头像区域 -->
      <div class="shrink-0">
        <img
          class="h-24 w-24 object-cover rounded-full"
          src="https://tailwind.nodejs.cn/_next/static/media/erin-lindford.90b9d461.jpg"
          alt="Erin Lindford"
        />
      </div>

      <!-- 内容区域 -->
      <div>
        <div class="text-xl font-bold text-black">Erin Lindford</div>
        <p class="text-gray-500 font-medium text-base">Product Engineer</p>

        <!-- 按钮 -->
        <button
          class="mt-4 px-6 py-1 text-purple-600 font-semibold rounded-full border border-purple-200 hover:bg-purple-50 transition duration-200 ease-in-out focus:outline-none focus:ring-2 focus:ring-purple-600 focus:ring-offset-2"
        >
          Message
        </button>
      </div>
    </div>
    <div class="p-6 w-[500px]">
      <article>
        <img class="float-right ml-6 aspect-16/9 w-2/5 rounded-lg object-cover outline -outline-offset-1 outline-black/10" src="./music.png" />
        <p>
          Maybe we can live without libraries, people like
          you and me. Maybe. Sure, we're too old to change
          the world, but what about that kid, sitting down, opening a book, right now, in a
          branch at the local library and finding drawings of pee-pees and wee-wees on the Cat in
          the Hat and the Five Chinese Brothers? Doesn't HE deserve better? Look. If you think this
          is about overdue fines and missing books, you'd better think again. This is about that
          kid's right to read a book without getting his mind warped! Or: maybe that turns you on,
          Seinfeld; maybe that's how y'get your kicks. You and your good-time buddies.
        </p>
      </article>
    </div>
  </div>
</template>

<script setup lang="ts">
// 导入语句
import { ref, reactive } from 'vue'
</script>

<style scoped lang="scss">
.TailwindCpm {
  // 组件样式
  min-height: 100vh;
  background: #efeff0;
}
</style>
