<template>
	<el-form label-width="80px">
		<el-form-item label="decision节点名称">
			<el-input v-model="name"></el-input>
		</el-form-item>
		<el-form-item label="显示名称">
			<el-input v-model="name"></el-input>
		</el-form-item>
		<el-form-item label="描述">
			<el-input v-model="name"></el-input>
		</el-form-item>
	</el-form>
</template>

<script>
export default {
    name: 'decisionConfig',
    data() {
        return {
            name: ''
        }
    },
    methods: {

    }
}
</script>

<style>

</style>