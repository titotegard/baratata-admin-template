<template>
	<nav class="navbar navbar-expand nav-light bg-light">
		<div class="container-fluid">
			<div class="navbar-brand"></div>
			<font-awesome-layers class="fa-2x avatar highlight">
				<font-awesome-icon :icon="['fas', 'user']" transform="shrink-7" />
				<font-awesome-icon :icon="['far', 'circle']" />
			</font-awesome-layers>
		</div>
	</nav>
</template>

<script>
export default {};
</script>

<style scoped>
.avatar:hover {
	cursor: pointer;
}
.avatar:hover :nth-child(2) {
	color: blue;
}
</style>
