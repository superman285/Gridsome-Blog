<template>
	<!--<Layout>

		&lt;!&ndash; Learn how to use images here: https://gridsome.org/docs/images &ndash;&gt;
		<g-image alt="Example image" src="~/favicon.png" width="135" />

		<h1>Hello, world!</h1>

		<p>
			Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores
		</p>

		<p class="home-links">
			<a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
			<a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
		</p>

	</Layout>-->
	<Layout>
		<!-- Page Header -->
		<!-- /路径直接访问到static目录 -->
		<header class="masthead" style="background-image: url('/img/home-bg.jpg')">
			<div class="overlay"></div>
			<div class="container">
				<div class="row">
					<div class="col-lg-8 col-md-10 mx-auto">
						<div class="site-heading">
							<h1>Clean Blog</h1>
							<span class="subheading">A Blog Theme by Start Bootstrap</span>
						</div>
					</div>
				</div>
			</div>
		</header>

		<!-- Main Content -->
		<div class="container">
			<div class="row">
				<div class="col-lg-8 col-md-10 mx-auto">
					<div class="post-preview">
						<a href="post.html">
							<h2 class="post-title">
								Man must explore, and this is exploration at its greatest
							</h2>
							<h3 class="post-subtitle">
								Problems look mighty small from 150 miles up
							</h3>
						</a>
						<p class="post-meta">Posted by
							<a href="#">Start Bootstrap</a>
							on September 24, 2019</p>
					</div>
					<hr>
					<div class="post-preview">
						<a href="post.html">
							<h2 class="post-title">
								I believe every human has a finite number of heartbeats. I don't intend to waste any of mine.
							</h2>
						</a>
						<p class="post-meta">Posted by
							<a href="#">Start Bootstrap</a>
							on September 18, 2019</p>
					</div>
					<hr>
					<div class="post-preview">
						<a href="post.html">
							<h2 class="post-title">
								Science has not yet mastered prophecy
							</h2>
							<h3 class="post-subtitle">
								We predict too much for the next year and yet far too little for the next ten.
							</h3>
						</a>
						<p class="post-meta">Posted by
							<a href="#">Start Bootstrap</a>
							on August 24, 2019</p>
					</div>
					<hr>
					<div class="post-preview">
						<a href="post.html">
							<h2 class="post-title">
								Failure is not an option
							</h2>
							<h3 class="post-subtitle">
								Many say exploration is part of our destiny, but it’s actually our duty to future generations.
							</h3>
						</a>
						<p class="post-meta">Posted by
							<a href="#">Start Bootstrap</a>
							on July 8, 2019</p>
					</div>
					<hr>
					<!-- Pager -->
					<div class="clearfix">
						<a class="btn btn-primary float-right" href="#">Older Posts &rarr;</a>
					</div>
				</div>
			</div>
		</div>
	</Layout>
</template>

<script>
	export default {
		metaInfo: {
			title: 'Hello, world!'
		},
		name: 'HomePage'
	}
</script>

<style>

</style>
