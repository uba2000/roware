<template>
	<div class="contact">
		<div>
			<div class="logo-container"></div>
			<div class="main-contact">
				<b-row class="mx-0" no-gutters>
					<b-col offset="0" cols="12" offset-md="2" md="8">
						<header class="contact-header">
							<div>
								<div class="header-title text-center">
									<h2 class="mb-0">
										<span> Get in touch! </span>
									</h2>
									<p>
										<span
											>Contact for a quote, job or
											complain</span
										>
									</p>
								</div>
							</div>
						</header>
						<div class="contact-sub-header mt-5">
							<div>
								<b-row no-gutters class="mx-0">
									<b-col cols="12" class="mb-5" md="4">
										<div class="sub-content">
											<div
												class="content-ico text-center"
											>
												<!-- <img src="" alt="" /> -->
												<fa
													:icon="[
														'fas',
														'map-marker-alt',
													]"
													size="2x"
													class="rw-icon"
												/>
											</div>
											<div
												class="div content_content mt-2"
											>
												<div
													class="text-center rw-text-bm rw-color-white"
												>
													77 Herbert Macaulay,
													<br />
													Yaba Lagos
												</div>
											</div>
										</div>
									</b-col>
									<b-col cols="12" class="mb-5" md="4">
										<div class="sub-content">
											<div
												class="content-ico text-center"
											>
												<!-- <img src="" alt="" /> -->
												<fa
													:icon="['fas', 'phone-alt']"
													size="2x"
													class="rw-icon"
												/>
											</div>
											<div
												class="div content_content mt-2"
											>
												<div
													class="text-center rw-text-bm rw-color-white"
												>
													+234 803 720 9221
												</div>
											</div>
										</div>
									</b-col>
									<b-col cols="12" class="mb-5" md="4">
										<div class="sub-content">
											<div
												class="content-ico text-center"
											>
												<!-- <img src="" alt="" /> -->
												<fa
													:icon="['fas', 'envelope']"
													size="2x"
													class="rw-icon"
												/>
											</div>
											<div
												class="div content_content mt-2"
											>
												<div
													class="text-center rw-text-bm rw-color-white"
												>
													help@roware.com
												</div>
											</div>
										</div>
									</b-col>
								</b-row>
							</div>
						</div>
						<div class="contact-body p-4">
							<div class="m-2">
								<b-form class="contact-form">
									<header class="contact-form-header mb-2">
										<div>
											<span> Contact Form </span>
										</div>
									</header>
									<div>
										<b-row class="">
											<b-col md="6" cols="12">
												<div>
													<b-form-group
														label="Your Name"
														label-for="name"
													>
														<b-form-input
															id="name"
															type="text"
														></b-form-input>
													</b-form-group>
													<b-form-group
														label="Mail"
														label-for="mail"
													>
														<b-form-input
															id="mail"
															type="email"
														></b-form-input>
													</b-form-group>
													<b-form-group
														label="Phone"
														label-for="phone"
														class="mb-0"
													>
														<b-form-input
															id="phone"
															type="tel"
														></b-form-input>
													</b-form-group>
												</div>
											</b-col>
											<b-col md="6" cols="12">
												<div class="h-100">
													<div
														class="h-100 d-flex"
														style="
															flex-direction: column;
														"
													>
														<label
															for="msg"
															class="d-block"
															>Your Message</label
														>
														<textarea
															id="msg"
															placeholder="Message"
															wrap="soft"
															class="flex-grow-1 form-control"
														></textarea>
													</div>
												</div>
											</b-col>
										</b-row>
										<div class="mt-3">
											<div
												class="h-100 d-flex"
												style="flex-direction: column"
											>
												<label for="srv" class="d-block"
													>Service</label
												>
												<b-row
													class="selection-container"
												>
													<b-col cols="12" md="4">
														<div>
															<div
																class="selection-item d-flex"
															>
																<input
																	type="radio"
																	class="mb"
																	id="mb-radio"
																	name="service"
																	checked
																/>
																<label
																	for="mb-radio"
																	class="contact-selection"
																>
																	<span
																		>Mobile
																		App</span
																	>
																</label>
															</div>
															<!--  -->
														</div>
													</b-col>
													<b-col cols="12" md="4">
														<div>
															<div
																class="selection-item d-flex"
															>
																<input
																	type="radio"
																	class="mb"
																	id="wb-radio"
																	name="service"
																/>
																<label
																	for="wb-radio"
																	class="contact-selection"
																>
																	<span
																		>Web
																		App</span
																	>
																</label>
															</div>
															<!--  -->
														</div>
													</b-col>
													<b-col cols="12" md="4">
														<div>
															<div
																class="selection-item d-flex"
															>
																<input
																	type="radio"
																	class="mb"
																	id="ui-radio"
																	name="service"
																/>
																<label
																	for="ui-radio"
																	class="contact-selection"
																>
																	<span
																		>UI/UX</span
																	>
																</label>
															</div>
															<!--  -->
														</div>
													</b-col>
												</b-row>
											</div>
										</div>
										<div class="text-center mt-3">
											<button class="btn btn--primary">
												<span>Send Message</span>
											</button>
										</div>
									</div>
								</b-form>
							</div>
						</div>
					</b-col>
				</b-row>
			</div>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.header-title {
	color: var(--white);
}
.selection-container {
	.selection-item {
		justify-content: center;
		input[type="radio"] {
			display: none;
			& ~ label {
				width: 100%;
				border-radius: calc(var(--def-border-radius) - 6px);
				padding: 12px 25px;
				text-align: center;
				max-width: 210px;
				background-color: var(--disabled);
				cursor: pointer;
				transition: all 0.3s ease;
			}
			&:checked ~ label {
				border: 1px solid var(--primary-color);
				color: var(--primary-color);
				background-color: transparent;
			}
		}
	}
}
.contact {
	&-body {
		background-color: var(--white);
		border-radius: var(--def-border-radius);
	}
	&-form-header {
		font-size: 18px;
		font-weight: 600;
	}
	&-form {
		label {
			font-weight: 500;
		}
	}
	background-color: var(--primary-color);
	padding: 30px 0;
	min-height: 100vh;
}
.sub-content {
	font-weight: 600 !important;
}
</style>