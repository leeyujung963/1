<!DOCTYPE html>

<html>

	<head>

	<meta charset="utf-8">

		<title>blog sample</title>

		<style>

			*{

				margin: 0; padding: 0;

				font-family: '맑은 고딕', 'Malgun Gothic', Gothic, sans-serif;

			}

			a {text-decoration: none;}

			li {list-style: none;}

			body {

				width: 960px; margin: 0 auto;

				background: #E6E6E6;

				}

			#page-wrapper{

				background: white;

				margin: 40px 0; padding: 10px 20px;

				border-radius: 5px;

				box-shadow: 0 4px 10px rgba(100, 100, 100, 0.3);

			}

			#main-header{padding: 40px 50px;}

			.master-title{

				font-size: 23px;

				color: #181818;

			}

			.master-description{

				font-size: 15px; font-weight: 500;

				color: #383838;

			}

			

			#main-navigation{

				border-top: 1px solid #C8C8C8;

				border-bottom: 1px solid #C8C8C8;

				margin-bottom: 20px;

				height: 40px;

			}

			.pull-left{float: left;}

			.outer-menu-item{

				float: left;

				position: relative;

			}

			.menu-title{

				display: block;

				height: 30px; line-height: 30px;

				text-align: center;

				padding: 5px 20px;

			}

			.outer-menu-item:hover{

				background: black;

				color: white;
 
			}

			.pull-right{float:right;}

			.search-bar{

				height: 26px;

				padding: 7px;

			}

			.input-search{

				display: block;

				float: left;

				

				background-color: #FFFFFF;

				border: 1px solid #CCCCCC;

				border-radius: 15px 0 0 15px;

				box-shadow: inset 0 1px 1px rgba(0,0,0,0.05);

				

				width: 120px; height: 24px;

				padding: 0 0 0 10px;

				font-size: 12px;

				color: #555555;

			}

			.input-search-submit{

				display: block;

				float: left;

				

				width: 50px; height: 26px;

				border-radius: 0 15px 15px 0;

				border: 1px solid #CCCCCC;

				

				margin-left: -1px;

				vertical-align: top;

				display: inline-block;

			}

			.input-search:focus{

				border-color: rgba(82,168,236, 0.8);

				outline: 0;

				box-shadow: inset 0 1px 1px rgba(0,0,0, 0.05);

			}

			.inner-menu{

				display: none;

				position: absolute;

				top: 40px; left: 0;

				width: 100%;

				

				background: white;

				box-shadow: 0 2px 6px rgba(5,5,5, 0.9);

				z-index: 1000;

				

				text-align: center;

			}

			.inner-menu-item > a {

				display: block;

				padding: 5px 10px;

				color: black;

			}

			.inner-menu-item > a:hover{

				background: black;

				color: white;

			}



			#content{

				overflow: hidden;

				padding: 0 50px;

			}

			#main-section{

				float: left;

				width: 510px;

			}

			#main-aside{

				float: right;

				width: 200px;

			}

			article{

				padding: 0 10px 20px 10px;

				border-bottom: 1px solid #C8C8C8;

			}

			.article-header{padding: 20px 0;}

			.article-title{

				font-size: 25px;

				font-weight: 500;

				padding-bottom: 10px;

			}

			.article-date{font-size: 13px;}

			.article-body{font-size: 14px;}

			

			.aside-list{padding: 10px 0 30px 0;}

			.aside-list > h3{

				font-size: 15px;

				font-weight: 600;

			}

			.aside-list li a{

				margin-left: 8px;

				font-size: 13px;

				color: #6C6C6C;

			}

			#main-footer{

				padding: 10px 50px;

			}

		</style>

		

		<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>

		<script>

			$(document).ready(function () {

				$('.outer-menu-item').hover(function () {

					$(this).find('.inner-menu').show();

					}, function () {

				$(this).find('.inner-menu').hide();

				});

			});

		</script>

	</head>

	

	<body>

		<div id="page-wrapper">

			<header id="main-header">

				<hgroup>

					<h1 class="master-title">blog sample</h1>

					<h2 class="master-description">*swu*</h2>

				</hgroup>

				<nav id="main-navigation">

					<div class="pull-left">

						<ul class="outer-menu">

							<li class="outer-menu-item">

								<span class="menu-title">Paper</span>

								<ul class="inner-menu">

									<li class="inner-menu-item"><a href="#">공구 신청서</a></li>

									<li class="inner-menu-item"><a href="#">입양 신청서</a></li>

								</ul>

							</li>

							<li class="outer-menu-item">

								<span class="menu-title">Trip</span>

								<ul class="inner-menu">

									<li class="inner-menu-item"><a href="#">국내</a></li>

									<li class="inner-menu-item"><a href="#">국외</a></li>

								</ul>


							</li>

							<li class="outer-menu-item">

								<span class="menu-title">Product</span>

								<ul class="inner-menu">

									<li class="inner-menu-item"><a href="#">스타벅스 텀블러</a></li>

									<li class="inner-menu-item"><a href="#">셀퓨전씨 크림</a></li>

								</ul>


							</li>

						</ul>

					</div>

					<div class="pull-right">

						<div class="search-bar">

							<form>

								<input type="text" class="input-search" />

								<input type="submit" class="input-search-submit" value="Search" />

							</form>

						</div>

					</div>

				</nav>

			</header>

			<div id="content">

				<section id="main-section">

					<article>

						<div class="article-header">

							<h1 class="article-title">html</h1>

							<p class="article-date">2020.8.07</p>

						</div>

						<div class="article-body">

							<img src="http://image.dongascience.com/Photo/2018/12/2d5efe44bdd02f3e2ec4e99189d89d18.jpg" />

							<br />

							<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptas architecto dolores dolor vel omnis aut, possimus quam tempore alias, sint voluptates dignissimos eveniet cumque minus, aliquid expedita. Recusandae, accusamus, libero. </p>

							<br />

							<p>Praesent</p>

						</div>

					</article>

				</section>

				<aside id = "main-aside">

					<div class="aside-list">

						<h3>category</h3>

						<ul>

							<li><a href="https://www.ijoa.co.kr/?gclid=EAIaIQobChMI-snH94iJ6wIVBFdgCh3uaQezEAAYASAAEgKlzfD_BwE">유기견 입양</a></li>

							<li><a href="https://post.naver.com/viewer/postView.nhn?volumeNo=16573099&memberNo=37257120">여행지 소개</a></li>

							<li><a href="https://m.blog.naver.com/PostView.nhn?blogId=eyashoppinginla&logNo=220923733175&proxyReferer=https:%2F%2Fwww.google.com%2F">물건 공구</a></li>

						</ul>

					</div>

					<div class="aside-list">

						<h3>newest</h3>

						<ul>

							<li><a href="#">입양 신청서</a></li>

							<li><a href="#">속초 맛집</a></li>

							<li><a href="#">스타벅스 리유저블컵 공구</a></li>

						</ul>

					</div>

				</aside>

			</div>			

			<footer id="main-footer">

				<a href="#"></a>

			</footer>

		</div>

	</body>

</html>
