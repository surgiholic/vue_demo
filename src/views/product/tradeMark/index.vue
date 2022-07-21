<template>
  <div>
    <!-- 按钮 -->
    <el-button
      type="primary"
      icon="el-icon-plus"
      style="margin: 10px 0px"
    >添加</el-button>
    <!-- table -->
    <el-table style="width: 100%" border>
      <el-table-column prop="prop" label="序号" width="80" align="center" />
      <el-table-column prop="prop" label="品牌名称" width="width" />
      <el-table-column prop="prop" label="品牌logo" width="width" />
      <el-table-column prop="prop" label="操作" width="width" />
    </el-table>
    <!-- 分页器 -->
    <el-pagination
      style="margin-top: 20px; textalign: center"
      :current-page="6"
      :page-size="20"
      :page-sizes="[5, 10, 20]"
      :pager-count="11"
      layout="prev, pager, next, jumper, ->, total, sizes"
      :total="1000"
    />
  </div>
</template>

<script>
export default {
  name: 'TradeMark'
}
</script>

<style scoped></style>
