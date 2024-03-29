<html lang="fr">
{% include head.markdown %}

<body>
	
	{% include page-loading.markdown %}

	<div class="wrapper">
			
		<header>
			{% include header.markdown %}
		</header><!--header end-->

		{% include responsive-menu.markdown %}

		<section class="main-banner">
			<div class="container">
				<div class="row align-items-center">
					<div class="col-lg-6">
						<div class="banner-content">
							<h2 class="wow fadeInUp" data-wow-duration="1000ms">{{ site.data.i18n.home[page.lang].subtitle }}</h2>
							<p class="wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="300ms">{{ site.data.i18n.home[page.lang].subtitle2 }}</p>
							<a href="nos_dernieres_realisations" title="" class="lnk-default wow fadeInUp" data-wow-duration="1000ms" data-wow-delay="500ms">{{ site.data.i18n.home[page.lang].mainbutton }} <i class="la la-arrow-right"></i> <span></span></a>
							
							<div class="clearfix"></div>
						</div><!--banner-content end-->
					</div>
					<div class="col-lg-6">
						<div class="banner-slider">
							<div class="banner-slide">
								<a href="nos_inspirations" title=""><img src="{{ site.baseurl }}/assets/images/photo-home-page.jpg" alt="" /></a>
							</div><!--banner-slide end-->
							<div class="banner-slide">
								<a href="nos_inspirations" title=""><img src="{{ site.baseurl }}/assets/images/home_slider_2.png" alt=""/></a>
							</div><!--banner-slide end-->
							<div class="banner-slide">
								<a href="nos_inspirations" title=""><img src="{{ site.baseurl }}/assets/images/home_slider_3.png" alt=""/></a>
							</div><!--banner-slide end-->
						</div><!--banner-slider end-->
					</div>
				</div>
			</div>
		</section><!--main-banner end-->

		<section class="block pb-0">
			<div class="container">
				<div class="about-us-section">
					<div class="row align-items-center">
						<div class="col-lg-6">
							<div class="abt-imgz" >
								<img class="wow fadeInUp" data-wow-duration="1000ms" src="{{ site.baseurl }}/assets/images/photo-profil.jpg" alt="">
								<img class="wow fadeInRight" data-wow-duration="1000ms" data-wow-delay="400ms" src="{{ site.baseurl }}/assets/images/photo-profil2.jpg" alt="">
							</div><!--abt-imgz end-->
							
						</div>
						<div class="col-lg-6">
							<div class="about-text">
								<h2 class="sub-title">Caroline Sebrien, Designer d'espace et décoratrice d'intérieur à {{ page.town }}</h2>
								<p>{{ site.data.i18n.home[page.lang].section1_subtitle }}</p>
							</div><!--about-text end-->
						</div>
					</div>
				</div><!--about-us-section end-->
			</div>
		</section>

		<section class="block">
			<div class="container">
				<div class="section-title align-items-center">
					<h3 class="sub-title">{{ site.data.i18n.home[page.lang].section2_title }}</h3>
					<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.portfolio[page.lang].path }}" title="" class="lnk-default2">{{ site.data.i18n.home[page.lang].section2_button }} <i class="la la-arrow-right"></i></a>
				</div><!--section-title end-->
				<div class="process-section">
					<ul>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section2_subtitle1 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section2_subdescription1 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section2_subtitle2 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section2_subdescription2 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section2_subtitle3 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section2_subdescription3 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						
					</ul>
					<div class="clearfix"></div>
				</div><!--process-section end-->
			</div>
		</section>

		<section class="block">
			<div class="container">
				<div class="section-title align-items-center">
					<h3 class="sub-title">{{ site.data.i18n.home[page.lang].section3_title }}</h3>
					<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.portfolio[page.lang].path }}" title="" class="lnk-default2">{{ site.data.i18n.home[page.lang].section3_button }} <i class="la la-arrow-right"></i></a>
				</div><!--section-title end-->
				<div class="process-section">
					<ul>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section3_subtitle1 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section3_subdescription1 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section3_subtitle2 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section3_subdescription2 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						<li>
							<div class="proz-mint">
								<h3>{{ site.data.i18n.home[page.lang].section3_subtitle3 }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section3_subdescription3 }}</p>
								<h2 class="p-num"></h2>
							</div><!--proz-mint end-->
						</li>
						
					</ul>
					<div class="clearfix"></div>
				</div><!--process-section end-->
			</div>
		</section>

		<section class="block2">
			<div class="fixed-bg bg1"></div>
			<div class="container">
				<div class="latest-projects-section">
					<div class="row">
						<div class="col-lg-5">
							<div class="project-text">
								<h3 class="sub-title">{{ site.data.i18n.home[page.lang].section4_title }}</h3>
								<p>{{ site.data.i18n.home[page.lang].section4_subtitle }}</p>
								<a href="{{ site.baseurl }}/{{ page.lang }}/{{ site.data.i18n.portfolio[page.lang].path }}" title="" class="lnk-default2">{{ site.data.i18n.home[page.lang].section4_button }} <i class="la la-arrow-right"></i></a>
							</div><!--project-text end-->
						</div>
						<div class="col-lg-7">
							<div class="project-carousel">
								<div class="project-item">
									<a href="/fr/sejour_projet_madeleine" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_13.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/sejour_projet_madeleine" title="">Séjour projet Madeleine</a></h3>
										<span></span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<a href="/fr/suite_parentale" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_12.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/suite_parentale" title="">Suite Parentale</a></h3>
										<span></span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<a href="/fr/agencement_meuble_tv" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_11.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/agencement_meuble_tv" title="">Agencement de meuble TV</a></h3>
										<span></span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<a href="/fr/maison_de_famille" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_9.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/maison_de_famille" title="">Maison de famille 1850</a></h3>
										<span></span>
									</div><!--project-info end-->
								</div><!--project-item end-->
								<div class="project-item">
									<a href="/fr/home_staging_old_house" title=""><img src="{{ site.baseurl }}/assets/images/images_portfolio_473x373_10.jpg" alt=""></a>
									<div class="project-info">
										<h3><a href="/fr/home_staging_old_house" title="">Home staging</a></h3>
										<span></span>
									</div><!--project-info end-->
								</div><!--project-item end-->
							</div><!--project-carousel end-->
						</div>
					</div>
				</div><!--latest-projects-section end-->
			</div>
		</section>

		<section class="block testi-section">
			<div class="container">
				<div class="section-title">
					<h3 class="sub-title">{{ site.data.i18n.home[page.lang].section5_title }}</h3>
				</div><!--section-title end-->
				<div class="testimonial-section">
					<div class="row testi-carousel">
						<div class="col-lg-12">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="{{ site.baseurl }}/assets/images/yves.jpg" alt="">
									<div class="user-info">
										<h3>Yves</h3>
										<span></span>
									</div>
								</div>
								<p>Caroline a su capturer parfaitement mes préférences tout en ajoutant sa touche distinctive. Le résultat final a dépassé toutes mes attentes, et je suis ravi des plans proposés pour les différentes pièces de mon appartement. Je recommande chaleureusement Caroline à tous ceux qui cherchent à donner vie à leurs idées de décoration. Merci encore pour cette expérience exceptionnelle, j'ai hâte que les travaux soient terminés !</p>
								<ul class="rating">
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
								</ul>
							</div><!--testi-slide end-->
						</div>
						<div class="col-lg-12">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="{{ site.baseurl }}/assets/images/myriam.jpg" alt="">
									<div class="user-info">
										<h3>Myriam</h3>
										<span></span>
									</div>
								</div>
								<p>Caroline a été d'une efficacité incroyable concernant notre projet d'aménagement ! Après notre demande, nous avons très vite reçu les plans d'intérieur et l'agencement. C'était parfait ! Tous nos critères étaient remplis (Rangement, verrière, bureau, bibliothèque, luminosité, etc.) Grâce à elle j'ai enfin réussi à me projeter dans ce futur appartement qu'on achète ! Je recommande chaudement.</p>
								<ul class="rating">
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
								</ul>
							</div><!--testi-slide end-->
						</div>
						<div class="col-lg-12">
							<div class="testi-slide">
								<div class="testi-head">
									<img src="{{ site.baseurl }}/assets/images/laura.jpg" alt="">
									<div class="user-info">
										<h3>Laura</h3>
										<span></span>
									</div>
								</div>
								<p>Caroline s’est occupé de mon intérieur comme personne !
Mes travaux ont été réalisé assez rapidement et j’ai pu donc emménagé vite dans mon appartement grâce à une logistique très bien menée de sa part.
Je suis ravie de la prestation !
Je recommande !</p>
								<ul class="rating">
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
									<li><i class="la la-star"></i></li>
								</ul>
							</div><!--testi-slide end-->
						</div>
						
						
					</div>
				</div><!--testimonial-section end-->
			</div>
		</section>

		<footer>
			{% include footer.markdown %}
		</footer><!--footer end-->

	</div><!--wrapper end-->

{% include scripts.markdown %}


</body>

</html>
