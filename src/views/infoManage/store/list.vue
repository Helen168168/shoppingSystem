<template>
    <div>
        <el-table
            :data="tableData"
            border
            style="width: 100%">
            <el-table-column type='index'
                            label="序号"
                            width="180">
            </el-table-column>
            <el-table-column prop="usernme"
                            label="用户名"
                            width="180"> </el-table-column>
            <el-table-column prop="createDate"
                            label="创建日期"></el-table-column>
            <el-table-column prop="location"
                            label="创建定位"> </el-table-column>
        </el-table>
    </div>
</template>

<script>
/**
 * 店家列表
 */
export default {
    data() {
        return {
            table: []
        }
    }
}
</script>