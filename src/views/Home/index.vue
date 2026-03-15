<script setup lang="ts">
import GridPatternDashed from '@/components/grid-pattern/grid-pattern-dashed.vue'

defineOptions({
  name: 'Demo',
})

</script>

<template>
  <GridPatternDashed />
  <div class="demo-content px-[12px]">
    <img
      class="block w-[120px] mx-auto mb-[30px] pt-[40px]"
      alt="Vue logo"
      src="~@/assets/logo_melomini.png"
    >
    <div
      class="text-[14px] py-[12px] px-[20px] rounded-[12px] bg-[var(--color-block-background)] mt-[14px]"
    >
      <div>
        <a
          class="flex items-center"
          href="https://github.com/yulimchen/vue3-h5-template"
          target="_blank"
        >
          <svg-icon class="text-[20px] mr-[8px]" name="github" />
          <h3 class="font-bold text-[18px] my-[4px]">Vue3-h5-template</h3>
          <svg-icon class="text-[12px] ml-[5px]" name="link" />
        </a>
      </div>
      <p class="leading-[24px] my-[6px]">
        基于 Vue3 全家桶、TypeScript、Vite 构建工具，开箱即用的 H5
        移动端项目基础模板
      </p>
    </div>

    <div
      class="mt-[16px] pb-[24px] grid grid-cols-2 gap-[12px] text-[14px] text-center"
    >
      
    </div>
  </div>
</template>
