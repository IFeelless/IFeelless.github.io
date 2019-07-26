<template>
	<div>
	<h1>home</h1>
	<button @click="goToMeun" class="btn btn-success">Let's order!</button>
	</div>
</template>

<script>
	export default{
		methods: {
			goToMeun() {
				//挑战到上次浏览的页面
				// this.$router.go(-1)
				//跳转到指定地址
				// this.$router.replace('/menu')
				//跳转到指定路由的名字下
				// this.$router.replace({name:'menuLink'})
				//通过push进行跳转
				this.$router.push({name:'menuLink'})
			}
		},
	}
</script>

<style>
</style>
