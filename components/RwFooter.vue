<template>
	<footer>
		<b-container>
			<div class="main-footer">
				<b-row>
					<b-col cols="12" class="mb-4" md="3">
						<div>
							<!-- <img src="" alt="" /> -->
							<logo class="ft-logo" />
						</div>
					</b-col>
					<b-col cols="12" class="mb-4" md="3">
						<div>
							<div class="ft-header-title">
								<span>About</span>
							</div>
							<div>
								<ul>
									<li>
										<nuxt-link to="/contact">
											<span>Contact</span>
										</nuxt-link>
									</li>
									<li>
										<a href="">
											<span>Products</span>
										</a>
									</li>
								</ul>
							</div>
						</div>
					</b-col>
					<b-col cols="12" class="mb-4" md="3">
						<div>
							<div class="ft-header-title">
								<span>Social</span>
							</div>
							<div>
								<ul>
									<li>
										<a href="">
											<span class="mr-2">
												<fa
													:icon="[
														'fab',
														'facebook-f',
													]"
												/>
											</span>
											<span>Facebook</span>
										</a>
									</li>
									<li>
										<a href="">
											<span class="mr-2">
												<fa
													:icon="['fab', 'twitter']"
												/>
											</span>
											<span>Twitter</span>
										</a>
									</li>
									<li>
										<a href="">
											<span class="mr-2">
												<fa
													:icon="['fab', 'linkedin']"
												/>
											</span>
											<span>LinkedIn</span>
										</a>
									</li>
									<li>
										<a href="">
											<span class="mr-2">
												<fa
													:icon="['fab', 'instagram']"
												/>
											</span>
											<span>Instagram</span>
										</a>
									</li>
								</ul>
							</div>
						</div>
					</b-col>
					<b-col cols="12" class="mb-4" md="3">
						<div>
							<div class="ft-header-title">
								<span>Contact</span>
							</div>
							<div>
								<ul>
									<li>
										<a href="">
											<span>+234 816 566 1377</span>
										</a>
									</li>
									<li>
										<a href="">
											<span>info@rowareng.com</span>
										</a>
									</li>
								</ul>
							</div>
						</div>
					</b-col>
				</b-row>
			</div>
			<div class="copyright"></div>
		</b-container>
	</footer>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
footer {
	background-color: var(--grey-color);
	padding: 48px 12px;
	position: relative;
	z-index: 10;
	.ft-header-title {
		font-weight: 600;
		margin-bottom: 16px;
		font-size: 18px;
	}
	.ft-logo {
		width: 45px;
		height: 45px;
	}
	ul {
		li {
			margin-bottom: 5px;
			font-size: 16px;
			color: var(--grey-text-color-2);
		}
	}
}
</style>