<template>
    <div style="padding: 30px">
        <el-button @click="visible = true">Button</el-button>
        <el-dialog :visible.sync="visible" title="Hello world">
            <p>処理されました。</p>
        </el-dialog>
    </div>
</template>

<script>
export default {
    data: function () {
        return { visible: false };
    },
};
</script>