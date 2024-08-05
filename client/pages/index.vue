<template>
    <el-container>
        <el-aside>
            <el-card style="max-width: 480px">
                <p v-for="o in 4" :key="o" class="text item">{{ 'List item ' + o }}</p>
            </el-card>
        </el-aside>
        <el-main>main</el-main>
    </el-container>
</template>

