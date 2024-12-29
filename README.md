<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مصباح مبروكي - صفحة شخصية</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
	
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fd7e14; 
            color: #343a40;
            text-align: center;
        }
        .header {
            background-color: #007bff;
            color: white;
            padding: 10px 0;
			text-align: center;
        }
        .header h1 {
            margin: 0;
            padding: 0;
        }
        .profile-img {
            max-width: 200px;
            border-radius: 50%;
        }
        .content {
            padding: 20px;
        }
        .section-title {
            border-bottom: 5px solid #007bff;
            padding-bottom: 10px;
            margin-bottom: 20px;
            text-align: center;
        }
        .lang-toggle {
            margin: 20px 0;
            text-align: center;
        }
        .btn-submit {
            background-color: #41d354;
            border: none;
        }
        .btn-submit:hover {
            background-color: #36b046;
        }
        .cert-img {
            max-width: 150px;
            height: auto;
            margin: 10px;
        }
		{
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            direction: rtl; /* لتنسيق النصوص من اليمين لليسار */
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        nav ul li a img {
            width: 20px;
            height: 20px;
            margin-right: 5px;
            vertical-align: middle;
        }

        .contact-info {
            background-color: #fff;
            margin: 20px auto;
            padding: 20px;
            max-width: 600px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        .contact-info h2 {
            text-align: center;
            color: #333;
        }

        .contact-info p {
            font-size: 16px;
            margin: 10px 0;
            color: #555;
        }

        .contact-info p i {
            margin-left: 10px;
            color: #333;
        }

        .contact-info p a {
            color: #007bff;
            text-decoration: none;
        }

        .contact-info p a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header text-center">
            <img src="profile.jpg" alt="Profile Photo" class="profile-img">
            <h1 id="name-ar">مصباح مبروكي</h1>
            <h1 id="name-en" style="display: none;">Mosbah Mabrouki</h1>
			<h1 id="name-ru" style="display: none;">Mosbah Mabrouki</h1>
			<h1 id="name-zh" style="display: none;">Mosbah Mabrouki</h1>
			<h1 id="name-de" style="display: none;">Mosbah Mabrouki</h1>
			<h1 id="name-tr" style="display: none;">Mosbah Mabrouki</h1>
            <p id="role-ar"> علم الآثار التجريبي ماقبل التاريخ
			تاريخ وعلم اثار و تراث و انثروبولوجيا </p>
            <p id="role-en" style="display: none;"> Experimental prehistoric archeology History, archeology, heritage and anthropology</p>
			<p id="role-ru" style="display: none;"> Экспериментальная доисторическая археология История, археология, наследие и антропология</p>
			<p id="role-zh" style="display: none;"> 实验史前考古学 历史、考古学、遗产和人类学</p>
			<p id="role-de" style="display: none;"> Experimentelle prähistorische Archäologie Geschichte, Archäologie, Kulturerbe und Anthropologie</p>
			<p id="role-tr" style="display: none;"> Deneysel tarih öncesi arkeoloji Tarih, arkeoloji, miras ve antropoloji</p>
		<nav>
            <ul>
		<p><i class="fab fa-orcid"></i> <a href="https://orcid.org/0009-0008-5925-2727" target="_blank"class="btn btn-orcid">ORCID</a></p>
        <p><i class="fab fa-google"></i> <a href="https://scholar.google.com.ly/citations?user=JXUwyOAAAAAJ&hl=ar" target="_blank"class="btn btn-google Scholar">Google Scholar</a></p>
        <p><i class="fab fa-researchgate"></i> <a href="https://www.researchgate.net/profile/Mosbah-Mabrouki-2" target="_blank"class="btn btn-ResearchGate">ResearchGate</a></p>
        <p><i class="fas fa-graduation-cap"></i> <a href="https://flm.academia.edu/MosbahMabrouki" target="_blank"class="btn btn-Academia">Academia.edu</a></p>
            </ul>
        </nav>
	</div>
	</section>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
        
<header>
        <nav>
            <ul>
                <li><a href="#" class="lang-button"><img src="flags/ar.jpeg" alt="Arabic"><button class="btn btn-secondary" onclick="toggleLang('ar')">العربية</button> </a></li>
				<li><a href="#" class="lang-button"><img src="flags/en.jpeg" alt="English"><button class="btn btn-secondary" onclick="toggleLang('en')">English</button> </a></li>
				<li><a href="#" class="lang-button"><img src="flags/ru.jpeg" alt="English"><button class="btn btn-secondary" onclick="toggleLang('ru')">Русский</button> </a></li>
				<li><a href="#" class="lang-button"><img src="flags/zh.jpeg" alt="English"><button class="btn btn-secondary" onclick="toggleLang('zh')">中文</button> </a></li>
				<li><a href="#" class="lang-button"><img src="flags/de.jpeg" alt="English"><button class="btn btn-secondary" onclick="toggleLang('de')">Deutsch</button> </a></li>
				<li><a href="#" class="lang-button"><img src="flags/tr.jpeg" alt="English"><button class="btn btn-secondary" onclick="toggleLang('tr')">Türkçe</button> </a></li>
            </ul>
        </nav>
    </header>
        <div class="lang-toggle">
        </div>
 
        <!-- Sections for "About Me" in different languages -->
<section class="container my-5" id="about-ar">
    <h2 class="section-title">عنّي</h2>
    <p>أكثر من 15 عامًا من الخبرة في الحفريات الأثرية، وتنظيم الندوات العلمية، وإعداد التقارير، والحفاظ على السرية المطلقة.
        لدي درجة الماجستير في التاريخ والحضارة، ودرجة البكالوريوس في علم الآثار، وخبرة في الإعلام المكتبي.
        أتطلع إلى الاستفادة من معرفتي وخبرتي في دور مدير مشروع.</p>
</section>
<section class="container my-5" id="about-en" style="display: none;">
    <h2 class="section-title">About Me</h2>
    <p>More than 15 years of experience in archaeological excavations, organizing scientific seminars, preparing reports and maintaining absolute confidentiality.
        I have a master's degree in history and civilization, a bachelor's degree in archaeology, and experience in desktop media.
        I look forward to benefiting from my knowledge and experience in the role of Project Manager.</p>
</section>
<section class="container my-5" id="about-ru" style="display: none;">
    <h2 class="section-title">Обо мне</h2>
    <p>Более 15 лет опыта в археологических раскопках, организации научных семинаров, подготовке отчетов и соблюдении абсолютной конфиденциальности.
        У меня есть степень магистра истории и цивилизации, степень бакалавра археологии и опыт работы в настольных СМИ.
        Я с нетерпением жду возможности использовать свои знания и опыт в роли менеджера проекта.</p>
</section>
<section class="container my-5" id="about-zh" style="display: none;">
    <h2 class="section-title">关于我</h2>
    <p>在考古发掘、组织科学研讨会、准备报告和保持绝对保密方面拥有超过15年的经验。
        我拥有历史与文明的硕士学位、考古学学士学位，并具有桌面媒体的经验。
        我期待着在项目经理的角色中受益于我的知识和经验。</p>
</section>
<section class="container my-5" id="about-de" style="display: none;">
    <h2 class="section-title">Über mich</h2>
    <p>Mehr als 15 Jahre Erfahrung in archäologischen Ausgrabungen, der Organisation wissenschaftlicher Seminare, der Erstellung von Berichten und der Wahrung der absoluten Vertraulichkeit.
        Ich habe einen Master-Abschluss in Geschichte und Zivilisation, einen Bachelor-Abschluss in Archäologie und Erfahrung in der Desktop-Medienarbeit.
        Ich freue mich darauf, mein Wissen und meine Erfahrung in der Rolle des Projektmanagers einzubringen.</p>
</section>
<section class="container my-5" id="about-tr" style="display: none;">
    <h2 class="section-title">Hakkımda</h2>
    <p>15 yılı aşkın arkeolojik kazılar, bilimsel seminerler düzenleme, rapor hazırlama ve tam gizliliği sağlama deneyimine sahibim.
        Tarih ve Medeniyet alanında yüksek lisans, Arkeoloji alanında lisans diplomasına sahibim ve masaüstü medya alanında deneyimim var.
        Bilgi ve deneyimlerimi Proje Yöneticisi rolünde kullanmayı dört gözle bekliyorum.</p>
</section>

<!-- Sections for "CV" in different languages -->
<section class="container my-5" id="cv-ar">
    <h2 class="section-title">السيرة الذاتية</h2>
    <embed src="Curriculum Vitae.pdf" type="application/pdf" width="70%" height="600px" />
</section>
<section class="container my-5" id="cv-en" style="display: none;">
    <h2 class="section-title">Curriculum Vitae</h2>
    <embed src="Curriculum Vitae.pdf" type="application/pdf" width="70%" height="600px" />
</section>
<section class="container my-5" id="cv-ru" style="display: none;">
    <h2 class="section-title">Резюме</h2>
    <embed src="Curriculum Vitae.pdf" type="application/pdf" width="70%" height="600px" />
</section>
<section class="container my-5" id="cv-zh" style="display: none;">
    <h2 class="section-title">简历</h2>
    <embed src="Curriculum Vitae.pdf" type="application/pdf" width="70%" height="600px" />
</section>
<section class="container my-5" id="cv-de" style="display: none;">
    <h2 class="section-title">Lebenslauf</h2>
    <embed src="Curriculum Vitae.pdf" type="application/pdf" width="70%" height="600px" />
</section>
<section class="container my-5" id="cv-tr" style="display: none;">
    <h2 class="section-title">Özgeçmiş</h2>
    <embed src="Curriculum Vitae.pdf" type="application/pdf" width="70%" height="600px" />
</section>

<!-- Sections for "Certificates" in different languages -->
<section class="container my-5" id="certificates-ar">
    <h2 class="section-title">الشهادات</h2>
    <div class="row">
        <!-- الشهادات العلمية -->
        <div class="col-md-4">
            <h3>الشهادات العلمية</h3>
            <img src="dip master.jpeg" alt="شهادة ماجستير" class="img-thumbnail" width="200">
            <img src="licence.jpg" alt="شهادة علمية 1" class="img-thumbnail" width="200">
            <img src="bacaloriat.jpg" alt="شهادة علمية 2" class="img-thumbnail" width="200">
        </div>
        <!-- التربصات -->
        <div class="col-md-4">
            <h3>التربصات</h3>
            <img src="ICOM.jpg" alt="تربص 1" class="img-thumbnail" width="200">
            <img src="qadasi.jpg" alt="تربص 2" class="img-thumbnail" width="200">
            <img src="sebha.jpg" alt="تربص 3" class="img-thumbnail" width="200">
        </div>
        <!-- أنشطة مختلفة -->
        <div class="col-md-4">
            <h3>أنشطة مختلفة</h3>
            <img src="علم الفلك.jpg" alt="نشاط مختلف 1" class="img-thumbnail" width="200">
            <img src="12moroco n.jpg" alt="نشاط مختلف 2" class="img-thumbnail" width="200">
            <img src="saic.jpg" alt="نشاط مختلف 3" class="img-thumbnail" width="200">
        </div>
    </div>
</section>
<section class="container my-5" id="certificates-en" style="display: none;">
    <h2 class="section-title">Certificates</h2>
    <div class="row">
        <!-- Academic Certificates -->
        <div class="col-md-4">
            <h3>Academic Certificates</h3>
            <img src="images/certificates/dip_master.jpeg" alt="Master's Certificate" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate1.jpg" alt="Academic Certificate 1" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate2.jpg" alt="Academic Certificate 2" class="img-thumbnail" width="200">
        </div>
        <!-- Internships -->
        <div class="col-md-4">
            <h3>Internships</h3>
            <img src="images/certificates/internship1.jpg" alt="Internship 1" class="img-thumbnail" width="200">
            <img src="images/certificates/internship2.jpg" alt="Internship 2" class="img-thumbnail" width="200">
            <img src="images/certificates/internship3.jpg" alt="Internship 3" class="img-thumbnail" width="200">
        </div>
        <!-- Various Activities -->
        <div class="col-md-4">
            <h3>Various Activities</h3>
            <img src="images/certificates/activity1.jpg" alt="Activity 1" class="img-thumbnail" width="200">
            <img src="images/certificates/activity2.jpg" alt="Activity 2" class="img-thumbnail" width="200">
            <img src="images/certificates/activity3.jpg" alt="Activity 3" class="img-thumbnail" width="200">
        </div>
    </div>
</section>
<section class="container my-5" id="certificates-ru" style="display: none;">
    <h2 class="section-title">Сертификаты</h2>
    <div class="row">
        <!-- Академические сертификаты -->
        <div class="col-md-4">
            <h3>Академические сертификаты</h3>
            <img src="images/certificates/dip_master.jpeg" alt="Сертификат магистра" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate1.jpg" alt="Академический сертификат 1" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate2.jpg" alt="Академический сертификат 2" class="img-thumbnail" width="200">
        </div>
        <!-- Стажировки -->
        <div class="col-md-4">
            <h3>Стажировки</h3>
            <img src="images/certificates/internship1.jpg" alt="Стажировка 1" class="img-thumbnail" width="200">
            <img src="images/certificates/internship2.jpg" alt="Стажировка 2" class="img-thumbnail" width="200">
            <img src="images/certificates/internship3.jpg" alt="Стажировка 3" class="img-thumbnail" width="200">
        </div>
        <!-- Разные активности -->
        <div class="col-md-4">
            <h3>Разные активности</h3>
            <img src="images/certificates/activity1.jpg" alt="Активность 1" class="img-thumbnail" width="200">
            <img src="images/certificates/activity2.jpg" alt="Активность 2" class="img-thumbnail" width="200">
            <img src="images/certificates/activity3.jpg" alt="Активность 3" class="img-thumbnail" width="200">
        </div>
    </div>
</section>
<section class="container my-5" id="certificates-zh" style="display: none;">
    <h2 class="section-title">证书</h2>
    <div class="row">
        <!-- 学术证书 -->
        <div class="col-md-4">
            <h3>学术证书</h3>
            <img src="images/certificates/dip_master.jpeg" alt="硕士证书" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate1.jpg" alt="学术证书 1" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate2.jpg" alt="学术证书 2" class="img-thumbnail" width="200">
        </div>
        <!-- 实习 -->
        <div class="col-md-4">
            <h3>实习</h3>
            <img src="images/certificates/internship1.jpg" alt="实习 1" class="img-thumbnail" width="200">
            <img src="images/certificates/internship2.jpg" alt="实习 2" class="img-thumbnail" width="200">
            <img src="images/certificates/internship3.jpg" alt="实习 3" class="img-thumbnail" width="200">
        </div>
        <!-- 各种活动 -->
        <div class="col-md-4">
            <h3>各种活动</h3>
            <img src="images/certificates/activity1.jpg" alt="活动 1" class="img-thumbnail" width="200">
            <img src="images/certificates/activity2.jpg" alt="活动 2" class="img-thumbnail" width="200">
            <img src="images/certificates/activity3.jpg" alt="活动 3" class="img-thumbnail" width="200">
        </div>
    </div>
</section>
<section class="container my-5" id="certificates-de" style="display: none;">
    <h2 class="section-title">Zertifikate</h2>
    <div class="row">
        <!-- Akademische Zertifikate -->
        <div class="col-md-4">
            <h3>Akademische Zertifikate</h3>
            <img src="images/certificates/dip_master.jpeg" alt="Master-Zertifikat" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate1.jpg" alt="Akademisches Zertifikat 1" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate2.jpg" alt="Akademisches Zertifikat 2" class="img-thumbnail" width="200">
        </div>
        <!-- Praktika -->
        <div class="col-md-4">
            <h3>Praktika</h3>
            <img src="images/certificates/internship1.jpg" alt="Praktikum 1" class="img-thumbnail" width="200">
            <img src="images/certificates/internship2.jpg" alt="Praktikum 2" class="img-thumbnail" width="200">
            <img src="images/certificates/internship3.jpg" alt="Praktikum 3" class="img-thumbnail" width="200">
        </div>
        <!-- Verschiedene Aktivitäten -->
        <div class="col-md-4">
            <h3>Verschiedene Aktivitäten</h3>
            <img src="images/certificates/activity1.jpg" alt="Aktivität 1" class="img-thumbnail" width="200">
            <img src="images/certificates/activity2.jpg" alt="Aktivität 2" class="img-thumbnail" width="200">
            <img src="images/certificates/activity3.jpg" alt="Aktivität 3" class="img-thumbnail" width="200">
        </div>
    </div>
</section>
<section class="container my-5" id="certificates-tr" style="display: none;">
    <h2 class="section-title">Sertifikalar</h2>
    <div class="row">
        <!-- Akademik Sertifikalar -->
        <div class="col-md-4">
            <h3>Akademik Sertifikalar</h3>
            <img src="images/certificates/dip_master.jpeg" alt="Yüksek Lisans Sertifikası" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate1.jpg" alt="Akademik Sertifika 1" class="img-thumbnail" width="200">
            <img src="images/certificates/science_certificate2.jpg" alt="Akademik Sertifika 2" class="img-thumbnail" width="200">
        </div>
        <!-- Stajlar -->
        <div class="col-md-4">
            <h3>Stajlar</h3>
            <img src="images/certificates/internship1.jpg" alt="Staj 1" class="img-thumbnail" width="200">
            <img src="images/certificates/internship2.jpg" alt="Staj 2" class="img-thumbnail" width="200">
            <img src="images/certificates/internship3.jpg" alt="Staj 3" class="img-thumbnail" width="200">
        </div>
        <!-- Çeşitli Aktiviteler -->
        <div class="col-md-4">
            <h3>Çeşitli Aktiviteler</h3>
            <img src="images/certificates/activity1.jpg" alt="Aktivite 1" class="img-thumbnail" width="200">
            <img src="images/certificates/activity2.jpg" alt="Aktivite 2" class="img-thumbnail" width="200">
            <img src="images/certificates/activity3.jpg" alt="Aktivite 3" class="img-thumbnail" width="200">
        </div>
    </div>
</section>

<!-- Sections for "Books & Publications" in different languages -->
<section class="container my-5" id="books-ar">
    <h2 class="section-title">الكتب والمنشورات</h2>
    <ul>
        <li><a href="https://www.amazon.com/dp/B0B9X4G6NH" target="_blank">الكتابي</a></li>
        <li><a href="https://www.amazon.com/dp/B09LPQ6R3J" target="_blank">المنشور العلمي</a></li>
    </ul>
</section>
<section class="container my-5" id="books-en" style="display: none;">
    <h2 class="section-title">Books & Publications</h2>
    <ul>
        <li><a href="https://www.amazon.com/dp/B0B9X4G6NH" target="_blank">My Book</a></li>
        <li><a href="https://www.amazon.com/dp/B09LPQ6R3J" target="_blank">Scientific Publication</a></li>
    </ul>
</section>
<section class="container my-5" id="books-ru" style="display: none;">
    <h2 class="section-title">Книги и публикации</h2>
    <ul>
        <li><a href="https://www.amazon.com/dp/B0B9X4G6NH" target="_blank">Моя книга</a></li>
        <li><a href="https://www.amazon.com/dp/B09LPQ6R3J" target="_blank">Научная публикация</a></li>
    </ul>
</section>
<section class="container my-5" id="books-zh" style="display: none;">
    <h2 class="section-title">书籍与出版物</h2>
    <ul>
        <li><a href="https://www.amazon.com/dp/B0B9X4G6NH" target="_blank">我的书</a></li>
        <li><a href="https://www.amazon.com/dp/B09LPQ6R3J" target="_blank">学术出版物</a></li>
    </ul>
</section>
<section class="container my-5" id="books-de" style="display: none;">
    <h2 class="section-title">Bücher & Veröffentlichungen</h2>
    <ul>
        <li><a href="https://www.amazon.com/dp/B0B9X4G6NH" target="_blank">Mein Buch</a></li>
        <li><a href="https://www.amazon.com/dp/B09LPQ6R3J" target="_blank">Wissenschaftliche Veröffentlichung</a></li>
    </ul>
</section>
<section class="container my-5" id="books-tr" style="display: none;">
    <h2 class="section-title">Kitaplar & Yayınlar</h2>
    <ul>
        <li><a href="https://www.amazon.com/dp/B0B9X4G6NH" target="_blank">Kitabım</a></li>
        <li><a href="https://www.amazon.com/dp/B09LPQ6R3J" target="_blank">Bilimsel Yayın</a></li>
    </ul>
</section>
<!--section id="contact"-->
    <!-- Arabic -->
    <form>
        <div class="form-group">
            <label for="name">İsim*Имя*الاسم*Name*姓名*Name</label>
            <input type="text" class="form-control" id="name" name="name" required>
        </div>
        <div class="form-group">
            <label for="email">E-posta*Электронная почта*البريد الإلكتروني*Email*电子邮件*E-Mail</label>
            <input type="email" class="form-control" id="email" name="email" required>
        </div>
        <div class="form-group">
            <label for="message">Mesaj*Сообщение*الرسالة*Message*消息*Nachricht</label>
            <textarea class="form-control" id="message" name="message" rows="4" required></textarea>
        </div>
        <button type="submit" class="btn btn-submit">Gönder*Отправить*إرسال*Send*发送*Senden</button>
    </form>
  
</section>
<!-- Footer -->
<footer class="bg-dark text-light text-center py-4">
    <p>&copy; 2024 Mosbah Mabrouki. جميع الحقوق محفوظة.</p>
    
	<p>هاتف:phone <a href="tel:+21621705272" class="text-light">+216 21 70 52 72</a> | واتساب:WhatsApp <a href="https://wa.me/+21621705272" class="text-light">+216 21 70 52 72</a></p>
</footer>

<!-- JavaScript for language switching -->
<script>
document.addEventListener('DOMContentLoaded', function() {
    const languageSelectors = document.querySelectorAll('.language-switcher a');
    languageSelectors.forEach(selector => {
        selector.addEventListener('click', function(event) {
            event.preventDefault();
            const lang = this.getAttribute('data-lang');
            document.querySelectorAll('.container').forEach(section => {
                section.style.display = 'none';
            });
            document.querySelector(`#${lang}`).style.display = 'block';
        });
    });
});
</script>

<!-- Font Awesome Icons -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/js/all.min.js" integrity="sha512-5DZKJTA7XwVgzg+P0s1nFg+gp7gjcCH4bHf3t4vI0G4ZCq6DzlbjvnR9iZ6Fv4vC4P/ybM5sh70Ww3QzD8mEg==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
</body>
</html>
 <div class="container my-5">
        <!-- Page Content -->
        <div class="front-box-icon animated"></div>
        <!-- Other sections remain unchanged -->
        
        <!-- Footer -->
 <footer class="container my-5">
            <p>تابعني على:</p>
            <a href="https://www.linkedin.com/in/mosba7-mabrouki/" class="btn btn-primary">
                <i class="fab fa-linkedin"></i> LinkedIn
            </a>
            <a href="https://github.com/mosbah-mabrouki" class="btn btn-dark">
                <i class="fab fa-github"></i> GitHub
            </a>
            <a href="https://x.com/mosbahmabrouki" class="btn btn-info">
                <i class="fab fa-twitter"></i> Twitter
            </a>
            <a href="https://www.facebook.com/mosbah7mabrouki.7/" target="_blank" class="btn btn-info">
                <i class="fab fa-facebook"></i> Facebook
            </a>
			<a href="https://www.youtube.com/user/yourchannel" class="btn btn-danger">
                <i class="fab fa-youtube"></i> YouTube
            </a>
            <a href="https://www.tiktok.com/@yourprofile" class="btn btn-dark">
                <i class="fab fa-tiktok"></i> TikTok
            </a>
            <a href="https://www.instagram.com/yourprofile" class="btn btn-danger">
                <i class="fab fa-instagram"></i> Instagram
			</a>
			<a href="https://wa.me/+21621705272" class="btn btn-success">
                <i class="fab fa-whatsapp"></i> WhatsApp
            </a>
            
			<a href="tel:+21621705272" class="btn btn-danger">
                <i class="fas fa-phone"></i> +21621705272اتصل بي
            </a>
            
        </footer>
    </div>

		<!-- Scroll to Top Button -->
        <button id="scroll-to-top" class="btn btn-primary" onclick="window.scrollTo({ top: 0, behavior: 'smooth' });">↑</button>
		<!-- Footer -->
        <footer class="container my-5 text-center">
            <p>&copy; 2024 Mosbah Mabrouki. All rights reserved.</p>
		</div>
		
    </div>

    <script>
        function toggleLang(lang) {
            const elements = document.querySelectorAll('section, h1, p');
            elements.forEach(el => {
                if (el.id.includes(lang)) {
                    el.style.display = 'block';
                } else if (el.id.includes('-')) {
                    el.style.display = 'none';
                }
            });
        }
   
   </script>
</body>
</html>
        
