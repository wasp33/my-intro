<template>
  <div aria-label="A complete example of page header">
    <el-page-header>
      <template #content>
        <div class="flex items-center">
          <el-avatar
            class="mr-3"
            :size="50"
            src="https://cube.elemecdn.com/0/88/03b0d39583f48206768a7534e55bcpng.png"
          />
          <span class="text-large font-600 mr-3"> Title </span>
        </div>
      </template>
      <template #extra>
        <div class="flex items-center">
          <el-button class="ml-2" plain>Aug-13-2025</el-button>
        </div>
      </template>

      <el-descriptions :column="3" size="small" class="mt-4">
        <el-descriptions-item label="Username"> kooriookami </el-descriptions-item>
        <el-descriptions-item label="Telephone"> 18100000000 </el-descriptions-item>
        <el-descriptions-item label="Place">Suzhou</el-descriptions-item>
        <el-descriptions-item label="Remarks">
          <el-tag size="small">School</el-tag>
        </el-descriptions-item>
        <el-descriptions-item label="Address">
          No.1188, Wuzhong Avenue, Wuzhong District, Suzhou, Jiangsu Province
        </el-descriptions-item>
      </el-descriptions>
      <p class="mozila-headline-700 mt-4 text-large">
        Element Plus team uses <b>weekly</b> release strategy under normal circumstance, but
        critical bug fixes would require hotfix so the actual release number <b>could be</b> more
        than 1 per week.
      </p>
    </el-page-header>
  </div>
</template>

<script setup lang="js"></script>
<style>
.mozilla-headline-<uniquifier > {
  font-family: 'Mozilla Headline', sans-serif;
  font-optical-sizing: auto;
  font-weight: <weight>;
  font-style: normal;
  font-variation-settings: 'wdth' 100;
}
</style>
