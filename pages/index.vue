<template>
	<div class="home">
		<section class="main-section">
			<b-container>
				<b-row>
					<b-col md="8" cols="12">
						<div>
							<div class="landing-text">
								<span>
									Software solution
									<br />
									without border
								</span>
							</div>
							<div class="landing-sub-text mt-3">
								<span>
									Roware is a technology company focused on
									building
									<br />
									ground breaking solutions for enterprises.
								</span>
							</div>
							<div class="mt-5 pt-2">
								<button class="btn btn--primary text-uppercase">
									<span>Explore Our Solutions</span>
								</button>
							</div>
						</div>
					</b-col>
					<!--  -->
				</b-row>
			</b-container>
		</section>
		<section>
			<b-container>
				<b-row class="mb-4">
					<b-col cols="12">
						<div class="section-title text-uppercase text-center">
							<span>What We Do</span>
						</div>
					</b-col>
				</b-row>
				<b-row>
					<b-col cols="12" class="mb-4" md="4">
						<b-card>
							<div class="tp-lbl"></div>
							<b-row no-gutters class="mx-0">
								<b-col cols="12">
									<div class="text-center mb-4">
										<!-- <img src="" alt="" /> -->
										<fa
											:icon="['fas', 'mobile-alt']"
											size="3x"
											class="rw-color-primary-2"
										/>
									</div>
									<div class="text-center card-title mb-4">
										<span>
											Mobile App
											<br />
											Development
										</span>
									</div>
									<div class="text-center card-sub-text">
										<span>
											Mobile Responsive, WordPress,
											<br />
											Javascript, PHP&amp;MySQL, App
											<br />
											Development
										</span>
									</div>
								</b-col>
							</b-row>
						</b-card>
					</b-col>
					<b-col cols="12" class="mb-4" md="4">
						<b-card>
							<div class="tp-lbl"></div>
							<b-row no-gutters class="mx-0">
								<b-col cols="12">
									<div class="text-center mb-4">
										<!-- <img src="" alt="" /> -->
										<fa
											:icon="['fas', 'mobile-alt']"
											size="3x"
											class="rw-color-primary-2"
										/>
									</div>
									<div class="text-center card-title mb-4">
										<span>
											Web App
											<br />
											Development
										</span>
									</div>
									<div class="text-center card-sub-text">
										<span>
											Mobile Responsive, WordPress,
											<br />
											Javascript, PHP&amp;MySQL, App
											<br />
											Development
										</span>
									</div>
								</b-col>
							</b-row>
						</b-card>
					</b-col>
					<b-col cols="12" class="mb-4" md="4">
						<b-card>
							<div class="tp-lbl"></div>
							<b-row no-gutters class="mx-0">
								<b-col cols="12">
									<div class="text-center mb-4">
										<!-- <img src="" alt="" /> -->
										<fa
											:icon="['fas', 'mobile-alt']"
											size="3x"
											class="rw-color-primary-2"
										/>
									</div>
									<div class="text-center card-title mb-4">
										<span>
											Graphics Design
											<br />
											&amp; UI/UX Design
										</span>
									</div>
									<div class="text-center card-sub-text">
										<span>
											We specialize in online and offline
											<br />
											fintech solutions for banks and
											<br />
											fintech eneblers.
										</span>
									</div>
								</b-col>
							</b-row>
						</b-card>
					</b-col>
				</b-row>
			</b-container>
		</section>
	</div>
</template>

<script>
export default {
	layout: "all-pages",
};
</script>

<style lang="scss" scoped>
.landing-text {
	font-size: 48px;
	font-weight: 700;
}
@media only screen and (max-width: 500px) {
	.landing-text {
		font-size: 37px;
	}
}
.landing-sub-text {
	font-size: 18px;
	font-weight: 400;
	line-height: 1.25rem;
}
section {
	&:not(.main-section) {
		padding-top: 100px;
	}
}
.section-title {
	font-size: 30px;
	font-weight: 600;
}
</style>
