<template>
    <el-container>
        <el-header>
                <div class="mb-4">
                    <el-button :type="''" link >Декомпозиция</el-button>
                    <el-button :type="''" link >Канбан</el-button>
                </div>
                <div>
                    <el-avatar :icon="UserFilled" />
                </div>
        </el-header>
    <slot></slot>
</el-container>
</template>

<script setup lang="ts">
import {UserFilled} from "@element-plus/icons-vue";
</script>

<style scoped lang="scss">

</style>