<template>
	<div class="block-quote">
		<div>
			<span class="d-block">
				<slot></slot>
			</span>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.block-quote {
	border: none;
	border-left: 3px solid var(--primary-text-color);
	> div {
		padding: 6px 12px;
		span {
			font-weight: 600;
		}
	}
}
</style>