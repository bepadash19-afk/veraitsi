# veraitsi
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Обо мне</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #f5faf5;
            color: #2d3a2d;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background-color: #3a5a40;
            color: white;
            padding: 40px 0;
            text-align: center;
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .header-description {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 700px;
            margin: 0 auto;
        }
        
        section {
            padding: 50px 0;
        }
        
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            color: #3a5a40;
            font-size: 2rem;
            position: relative;
        }
        
        .section-title::after {
            content: '';
            display: block;
            width: 80px;
            height: 3px;
            background-color: #588157;
            margin: 15px auto 0;
        }
        
        .about-me {
            background-color: white;
            border-radius: 8px;
            padding: 30px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        
        .contact-btn {
            display: inline-block;
            background-color: #3a5a40;
            color: white;
            padding: 12px 25px;
            border-radius: 30px;
            text-decoration: none;
            margin-top: 20px;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        .contact-btn:hover {
            background-color: #588157;
            transform: translateY(-2px);
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }
        
        .gallery-item {
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        
        .gallery-item:hover {
            transform: translateY(-5px);
        }
        
        .gallery-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            display: block;
        }
        
        .photo-caption {
            padding: 15px;
            background-color: white;
        }
        
        footer {
            background-color: #2d3a2d;
            color: white;
            text-align: center;
            padding: 30px 0;
            margin-top: 50px;
        }
        
        .social-links {
            margin-top: 20px;
        }
        
        .social-links a {
            color: white;
            margin: 0 10px;
            font-size: 1.2rem;
        }
        
        @media (max-width: 768px) {
            .gallery {
                grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Обо мне</h1>
            <p class="header-description">Привет! Меня зовут Вера. Мне 18 лет. Я приехала из Кемеровской области.</p>
	    <img src="we.jpg">
        </div>
    </header>
    
    <section class="about-section">
        <div class="container">
<h2 class="section-title">Мои хобби</h2>
            <div class="about-me">
                <p>Моим главным хобби является рисование, но, в связи с наступлением учебы в университете, я стала меньше этим заниматься(</p>
                <p>Были попытки в гитару, но мотивации не хватило, и я так и не научилась(</p>
            </div>
        </div>
    </section>
    
    <section>
        <div class="container">
            <h2 class="section-title">Мои интересы и учёба</h2>
            <div class="gallery">
                <div class="gallery-item">
                    <img src="w.jpg">
                    <div class="photo-caption">
                        <h3>Мои заслуги</h3>
                        <p>Я закончила 11 классов с красным аттестатом и золотой медалью!</p>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="ДДЛК.jpg">
                    <div class="photo-caption">
                        <h3>Игра, которой горжусь</h3>
                        <p>Я выполнила это достижение спустя 15 после выхода игры</p>
                    </div>
                </div>
                <div class="gallery-item">
                    <img src="tanki.jpg">
                    <div class="photo-caption">
                        <h3>Игра детства</h3>
                        <p>Игра, в которую я игра всё свое детство, пока она не стала донатной помойкой(</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <section>
        <div class="container">
            <h2 class="section-title">Контакты</h2>
            <div class="about-me" style="text-align: center;">
                <p>Если хотите поболтать о том и о сем, то пишите(но я не отвечу).</p>
                <a href="mailto:bepa.dash19@gmail.com" class="contact-btn">Моя почта</a>
		<a href="https://vk.com/hellothankyou" class="contact-btn">Мой ВК</a>
                </div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <p>&copy; Живите как хотите и жалейте об этом. </p>
        </div>
    </footer>
</body>
</html>
