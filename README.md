<Sevinc Kərimli>
<html lang="az">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Sevinc Kərimli</title>
	<link rel="stylesheet" href="style.css">
	<style>
		/* Basic inline styles in case external CSS is missing */
		body{font-family: Arial, sans-serif;margin:0;color:#333}
		.navbar{display:flex;justify-content:space-between;align-items:center;padding:16px 32px;background:#fff;box-shadow:0 2px 6px rgba(0,0,0,0.05)}
		.logo{font-weight:700}
		.nav-links{list-style:none;display:flex;gap:16px;margin:0;padding:0}
		.nav-links a{text-decoration:none;color:inherit}
		.hero{background:linear-gradient(135deg,#f7f3ff,#fff);padding:80px 20px;text-align:center}
		.hero h1{font-size:2.2rem;margin:0 0 12px}
		.highlight{color:#7b61ff}
		.btn{display:inline-block;margin-top:12px;padding:10px 18px;background:#7b61ff;color:#fff;border-radius:6px;text-decoration:none}
		.projects-section{padding:48px 20px;max-width:1100px;margin:0 auto}
		.projects-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:20px;margin-top:20px}
		.project-card{background:#fff;border-radius:8px;overflow:hidden;box-shadow:0 6px 18px rgba(12,12,12,0.06);padding-bottom:18px}
		.project-image{width:100%;height:160px;object-fit:cover;display:block}
		.project-card h3{margin:12px 16px 6px}
		.project-card p{margin:0 16px 12px;color:#555}
		.btn-detail{display:inline-block;margin-left:16px;padding:8px 12px;background:#eee;border-radius:6px;text-decoration:none;color:#333}
		.footer{background:#f8f8fb;padding:36px 20px;text-align:center;margin-top:40px}
		.social-links a{margin:0 8px;color:#7b61ff;text-decoration:none}
		.copy{margin-top:16px;color:#999}
	</style>
</head>
<body>
	<!-- Naviqasiya -->
	<nav class="navbar">
		<div class="logo">Thisscdesign</div>
		<ul class="nav-links">
			<li><a href="#about">Haqqımda</a></li>
			<li><a href="#projects">Layihələr</a></li>
			<li><a href="#contact">Əlaqə</a></li>
		</ul>
	</nav>
	<!-- Giriş Hissəsi (Hero) -->
	<header class="hero">
		<div class="hero-content">
			<h1>Salam, Mən <span class="highlight">Dizaynerəm</span></h1>
			<p>Sizin hekayənizi evinizin hər küncünə toxuyaraq, boş məkanları əsl yuvaya çevirirəm.</p>
			<a href="#projects" class="btn">İşlərimə Bax</a>
		</div>
	</header>
	<!-- Layihələr Bölməsi -->
	<section id="projects" class="projects-section">
		<h2>Seçilmiş Layihələr</h2>
		<div class="projects-grid">
			<!-- 1-ci Layihə -->
			<div class="project-card">
				<img src="https://images.unsplash.com/photo-1616594039964-ae9021a400a0?q=80&w=600&auto=format&fit=crop" alt="Yataq otağı Dizaynı" class="project-image">
				<h3>Yataq otağı Dizaynı</h3>
				<p>Bu yataq otağı dizaynı, məlumat və estetik əsasında hazırlanmışdır.</p>
				<a href="#" class="btn-detail">Daha ətraflı</a>
			</div>
			<!-- 2-ci Layihə -->
			<div class="project-card">
				<img src="https://images.unsplash.com/photo-1618221195710-dd6b41faaea6?q=80&w=600&auto=format&fit=crop" alt="Qonaq Otağı Dizaynı" class="project-image">
				<h3>Qonaq Otağı Dizaynı</h3>
				<p>Məkanın genişliyini və işıqlandırılmasını ön plana çıxaran müasir dizayn konsepti.</p>
				<a href="#" class="btn-detail">Daha ətraflı</a>
			</div>
			<!-- 3-cü Layihə -->
			<div class="project-card">
				<img src="https://images.unsplash.com/photo-1556911220-e15b29be8c8f?q=80&w=600&auto=format&fit=crop" alt="Mətbəx Dizaynı" class="project-image">
				<h3>Mətbəx Dizaynı</h3>
				<p>Erqonomik, funksional və vizual olaraq fərqlənən unikal mətbəx layihəsi.</p>
				<a href="#" class="btn-detail">Daha ətraflı</a>
			</div>
		</div>
	</section>
	<!-- Əlaqə Bölməsi -->
	<footer id="contact" class="footer">
		<h2>Gəlin Birlikdə İşləyək!</h2>
		<p>Layihələriniz və ya əməkdaşlıq üçün mənə yazın.</p>
		<div class="social-links">
			<a href="https://www.linkedin.com/in/thisscdesign" target="_blank">LinkedIn</a>
			<a href="https://www.instagram.com/thisscdesign?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==">Instagram</a>
			<a href="sevinckerimli23@gmail.com">E-poçt</a>
		</div>
		<p class="copy">&copy; 2026 Bütün hüquqlar qorunur.</p>
	</footer>
</body>
</html>
