<template>
	<b-navbar toggleable="lg" class="px-4 rw-navbar index-spacing">
		<nuxt-link to="/" target="_self" class="navbar-brand">
			<logo class="nv-logo" />
		</nuxt-link>

		<b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

		<b-collapse id="nav-collapse" is-nav>
			<b-navbar-nav class="ml-auto">
				<br />
				<li class="nav-item">
					<a href="#" target="_self" class="nav-link"> About Us </a>
				</li>
				<li class="nav-item">
					<nuxt-link to="/portfolio" target="_self" class="nav-link">
						Portfolio
					</nuxt-link>
				</li>
				<li class="nav-item">
					<nuxt-link to="/contact" target="_self" class="nav-link">
						Contact Us
					</nuxt-link>
				</li>
				<li class="nav-item">
					<a
						href="https://academic.rowareng.com"
						class="p-0 nav-link"
					>
						<button class="btn btn--primary text-uppercase">
							<span>Academic</span>
						</button>
					</a>
				</li>
			</b-navbar-nav>
		</b-collapse>
	</b-navbar>
</template>

<script>
export default {
	computed: {
		homeSpacing() {
			return this.$route.name == "index";
		},
	},
};
</script>

<style lang="scss" scoped>
.nav-link {
	color: var(--neutral-text-color) !important;
	font-weight: 400;
	padding-right: 32px !important;
	font-size: 17px;
}
.nuxt-link-exact-active,
.nuxt-link-active {
	font-weight: 500;
	color: var(--primary-text-color) !important;
}
.navbar {
	padding: 30px 35px !important;
	background-color: transparent;
	position: relative;
	z-index: 9999;
}
</style>