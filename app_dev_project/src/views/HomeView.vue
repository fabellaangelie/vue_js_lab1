<template>
	<div id="app">
	   <nav class="navbar navbar-expand-lg navbar-light bg-light">
		 <a class="navbar-brand" href="#"></a>
		 <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
		   <span class="navbar-toggler-icon"></span>
		 </button>
		 <div class="collapse navbar-collapse" id="navbarNav">
		   <ul class="navbar-nav">
			 <li class="nav-item active">
			   <a class="nav-link" href="#">Home <span class="sr-only"></span></a>
			 </li>
			 <li class="nav-item">
			   <a class="nav-link" href="Manage">Manage</a>
			 </li>
			 <li class="nav-item">
			   <a class="nav-link" href="#">About</a>
			 </li>
			 <li class="nav-item">
			   <a class="nav-link" href="#">Cart</a>
			 </li>
			 <li class="nav-item">
			   <a class="nav-link" href="#">Contact</a>
			 </li>
			 <li class="nav-item">
			   <a class="nav-link" href="#">New</a>
			 </li>
			 <li class="nav-item">
			   <a class="nav-link" href="#">Shop</a>
			 </li>
		   </ul>
		 </div>
	   </nav>
	   <div class="col-lg-12 col-sm-12 text-center">
			<div class="hero-img-wrap">
				<img src="../img/icons/hero-bg.jpg" class="img-fluid">
			</div>
		</div>
	</div>

	<!-- latest news -->
	<div class="latest-news pt-150 pb-150">
		<div class="container">

			<div class="row">
				<div class="col-lg-8 offset-lg-2 text-center">
					<div class="section-title">	
						<h3><span class="orange-text">Our</span> News</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid, fuga quas itaque eveniet beatae optio.</p>
					</div>
				</div>
			</div>

			<div class="row">
				<div class="col-lg-4 col-md-6">
					<div class="card" style="width: 18rem;">
						<img src="../img/icons/news-bg-3.jpg" class="card-img-top" alt="...">
						<a href="single-news.html"><div class=" news-bg-1"></div></a>
						<div class="news-text-box">
							<h3><a href="single-news.html">You will vainly look for fruit on it in autumn.</a></h3>
							<p class="blog-meta">
								<span class="author"><i class="fas fa-user"></i> Admin</span>
								<span class="date"><i class="fas fa-calendar"></i> 27 December, 2019</span>
							</p>
							<p class="excerpt">Vivamus lacus enim, pulvinar vel nulla sed, scelerisque rhoncus nisi. Praesent vitae mattis nunc, egestas viverra eros.</p>
							<a href="single-news.html" class="read-more-btn"> <i class="fas fa-angle-right"></i></a>
						</div>
					</div>
				</div>
				<div class="col-lg-4 col-md-6">
					<div class="card" style="width: 18rem;">
						<img src="../img/icons/news-bg-2.jpg" class="card-img-top" alt="...">
						<a href="single-news.html"><div class="latest-news-bg news-bg-2"></div></a>
						<div class="news-text-box">
							<h3><a href="single-news.html">A man's worth has its season, like tomato.</a></h3>
							<p class="blog-meta">
								<span class="author"><i class="fas fa-user"></i> Admin</span>
								<span class="date"><i class="fas fa-calendar"></i> 27 December, 2019</span>
							</p>
							<p class="excerpt">Vivamus lacus enim, pulvinar vel nulla sed, scelerisque rhoncus nisi. Praesent vitae mattis nunc, egestas viverra eros.</p>
							<a href="single-news.html" class="read-more-btn"> <i class="fas fa-angle-right"></i></a>
						</div>
					</div>
				</div>
				<div class="col-lg-4 col-md-6 offset-md-3 offset-lg-0">
					<div class="card" style="width: 18rem;">
						<img src="../img/icons/news-bg-1.jpg" class="card-img-top" alt="...">
						<a href="single-news.html"><div class="latest-news-bg news-bg-3"></div></a>
						<div class="news-text-box">
							<h3><a href="single-news.html">Good thoughts bear good fresh juicy fruit.</a></h3>
							<p class="blog-meta">
								<span class="author"><i class="fas fa-user"></i> Admin</span>
								<span class="date"><i class="fas fa-calendar"></i> 27 December, 2019</span>
							</p>
							<p class="excerpt">Vivamus lacus enim, pulvinar vel nulla sed, scelerisque rhoncus nisi. Praesent vitae mattis nunc, egestas viverra eros.</p>
							<a href="single-news.html" class="read-more-btn"><i class="fas fa-angle-right"></i></a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<!-- end latest news -->

   </template>

<script>
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap/dist/js/bootstrap.js';

export default {
 name: 'App',
};
</script>

