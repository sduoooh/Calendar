<script setup>
// import  CalendarCell from "./CalendarCell.vue"
import { ref } from "vue"
import { MyData } from "./export"
</script>
<template>
    <!-- <el-popover placement="right" width="80px" trigger="click">
        <template #reference>
            <el-button style="width: 16px">纵览</el-button>
        </template>
        <div class="width: 80px;">
            <CalendarCell v-for="day in days">{{ day }}</CalendarCell>
            <p>{{MyData}}</p>
        </div>
    </el-popover> -->

    <div class="test">
        <p v-for="i in MyData">{{i}}</p>
    </div>
</template> 

<style>
.test {
    background-color: black;
    color: white;
    width: 900px;
}
</style>


