<template>
	<div class="portfolio">
		<b-container>
			<header class="header-title">
				<h1 class="text-center">
					<span>Portfolio</span>
				</h1>
			</header>
			<div>
				<section class="portfolio-section">
					<header class="section-title">
						<h3>
							<span>Twink</span>
						</h3>
					</header>
					<div>
						<b-row no-gutters>
							<b-col md="9" cols="12">
								<div class="mt-3">
									<rw-blockquote>
										<p>
											Lorem ipsum dolor sit, amet
											consectetur adipisicing elit. Error,
											est aperiam quos ea placeat sapiente
											quia repellat vero consequuntur
											porro aliquid asperiores labore
											libero dolores, fugiat aut obcaecati
											sunt! Sapiente!
										</p>
										<p class="mb-0">
											Lorem, ipsum dolor sit amet
											consectetur adipisicing elit.
											Tempora numquam reprehenderit
											expedita veritatis voluptatibus
											nesciunt maiores reiciendis placeat
											explicabo provident officiis atque
											obcaecati, illum vitae! Similique
											consequuntur ex molestias
											aspernatur.
										</p>
									</rw-blockquote>
								</div>
							</b-col>
						</b-row>
						<b-row no-gutters class="justify-content-end mt-3">
							<b-col md="9" class="text-right" cols="12">
								<img
									:src="require('~/assets/img-1.jpg')"
									class="w-100 h-auto quote-img"
									alt=""
								/>
							</b-col>
						</b-row>
					</div>
				</section>
				<section class="portfolio-section">
					<header class="section-title">
						<h3>
							<span>Twink</span>
						</h3>
					</header>
					<div>
						<b-row no-gutters>
							<b-col md="9" cols="12">
								<div class="mt-3">
									<rw-blockquote>
										<p>
											Lorem ipsum dolor sit, amet
											consectetur adipisicing elit. Error,
											est aperiam quos ea placeat sapiente
											quia repellat vero consequuntur
											porro aliquid asperiores labore
											libero dolores, fugiat aut obcaecati
											sunt! Sapiente!
										</p>
										<p class="mb-0">
											Lorem, ipsum dolor sit amet
											consectetur adipisicing elit.
											Tempora numquam reprehenderit
											expedita veritatis voluptatibus
											nesciunt maiores reiciendis placeat
											explicabo provident officiis atque
											obcaecati, illum vitae! Similique
											consequuntur ex molestias
											aspernatur.
										</p>
									</rw-blockquote>
								</div>
							</b-col>
						</b-row>
						<b-row no-gutters class="justify-content-end mt-3">
							<b-col md="9" class="text-right" cols="12">
								<img
									:src="require('~/assets/img-1.jpg')"
									class="w-100 h-auto quote-img"
									alt=""
								/>
							</b-col>
						</b-row>
					</div>
				</section>
				<section class="portfolio-section">
					<header class="section-title">
						<h3>
							<span>Twink</span>
						</h3>
					</header>
					<div>
						<b-row no-gutters>
							<b-col md="9" cols="12">
								<div class="mt-3">
									<rw-blockquote>
										<p>
											Lorem ipsum dolor sit, amet
											consectetur adipisicing elit. Error,
											est aperiam quos ea placeat sapiente
											quia repellat vero consequuntur
											porro aliquid asperiores labore
											libero dolores, fugiat aut obcaecati
											sunt! Sapiente!
										</p>
										<p class="mb-0">
											Lorem, ipsum dolor sit amet
											consectetur adipisicing elit.
											Tempora numquam reprehenderit
											expedita veritatis voluptatibus
											nesciunt maiores reiciendis placeat
											explicabo provident officiis atque
											obcaecati, illum vitae! Similique
											consequuntur ex molestias
											aspernatur.
										</p>
									</rw-blockquote>
								</div>
							</b-col>
						</b-row>
					</div>
				</section>
			</div>
		</b-container>
	</div>
</template>

<script>
export default {
	layout: "all-pages",
};
</script>

<style lang="scss" scoped>
.portfolio-section {
	padding-top: 40px;
	&:not(:nth-child(1)) {
		padding-top: 80px;
	}
}
.quote-img {
	max-height: 240.5px;
	object-fit: cover;
}
</style>