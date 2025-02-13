# Azistour.com
Private VIP Tours to Azerbaijan,Georgia, Kazakhstan, Uzbekistan
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIP Private Tours</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            direction: ltr;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }
        .language-selector {
            margin-bottom: 20px;
        }
        .language-selector button {
            padding: 10px 15px;
            margin: 5px;
            cursor: pointer;
            border: none;
            background-color: #007BFF;
            color: white;
            font-size: 16px;
            border-radius: 5px;
        }
        .language-selector button:hover {
            background-color: #0056b3;
        }
        .text-content {
            display: none;
        }
        .show {
            display: block;
        }
    </style>
    <script>
        function changeLanguage(lang) {
            document.querySelectorAll('.text-content').forEach(el => el.classList.remove('show'));
            document.getElementById(lang).classList.add('show');
            document.body.style.direction = lang === 'hebrew' ? 'rtl' : 'ltr';
        }
    </script>
</head>
<body>

    <div class="container">
        <h1>VIP Private Tours</h1>

        <div class="language-selector">
            <button onclick="changeLanguage('english')">English</button>
            <button onclick="changeLanguage('russian')">Русский</button>
            <button onclick="changeLanguage('hebrew')">עברית</button>
        </div>

        <div id="english" class="text-content show">
            <h2>Exclusive VIP Tours to Azerbaijan, Georgia, Kazakhstan, and Uzbekistan</h2>
            <p>Join us for an unforgettable travel experience in Azerbaijan and Georgia with private, luxurious VIP service. We offer a fully customized experience, tailored to your needs.</p>
            <p>Travel with a highly experienced local company specializing in luxury tourism. Professional English- and Russian-speaking guides will accompany you at every stage, ensuring you enjoy everything these countries have to offer.</p>
            <p>Enjoy private transportation in luxury vehicles, high-end hotels, and a choice of attractions, restaurants, and treatments. The itinerary is flexible and can be adapted to your interests – whether you love wild nature, rich culture, or culinary tours.</p>
            <p>One trip, endless possibilities – all you have to do is sit back and indulge in this luxurious experience.</p>
        </div>

        <div id="russian" class="text-content">
            <h2>Эксклюзивные VIP-туры в Азербайджан, Грузию, Казахстан и Узбекистан</h2>
            <p>Присоединяйтесь к нам в незабываемое путешествие по Азербайджану и Грузии с частным, роскошным VIP-сервисом. Мы предлагаем полностью персонализированный опыт, адаптированный под ваши желания.</p>
            <p>Путешествуйте с опытной местной компанией, специализирующейся на роскошном туризме. Профессиональные гиды, говорящие на английском и русском языках, будут сопровождать вас на каждом этапе и обеспечат незабываемые впечатления.</p>
            <p>Вы получите частный трансфер на автомобиле класса люкс, проживание в лучших отелях, а также выбор экскурсий, ресторанов и оздоровительных процедур. Маршрут гибкий и адаптируется под ваши интересы – будь то дикая природа, богатая культура или гастрономические туры.</p>
            <p>Одно путешествие – бесконечные возможности. Вам остается только расслабиться и насладиться этим роскошным отдыхом.</p>
        </div>

        <div id="hebrew" class="text-content">
            <h2>IP לאזרבייג'ן, גאורגיה, קזחסטן, אוזבקיסטן – חווית יוקרה אישית ומיוחדת</h2>
            <p>הצטרפו אלינו לחוויית טיול בלתי נשכחת בשתי מדינות מרהיבות, אזרבייג'ן וגאורגיה, בשירות VIP פרטי ומפנק. אנחנו מציעים לכם חוויה מותאמת אישית, שמותאמת לכל בקשה ודרישה שלכם.</p>
            <p>טיול פרטי עם חברה מקומית בעלת ניסיון רב בשירותי תיירות יוקרה. מדריכים מקצועיים דוברי אנגלית ורוסית ילוו אתכם בכל שלב, ויוודאו שתחוו את כל מה שיש לכל מדינה להציע – מהמראות הייחודיים ועד החוויות המקומיות.</p>
            <p>במהלך הטיול תיהנו מהסעה ברכב יוקרה, בתי מלון ברמה הגבוהה ביותר, ובחירה ממגוון אפשרויות לאטרקציות, מסעדות וטיפולים. תכנון המסלול יוכל להיות גמיש ומותאם אישית לפי האינטרסים וההעדפות שלכם – האם אתם אוהבים טבע פראי, תרבות עשירה או סיורים קולינריים? אנחנו נדאג לכל פרט ופרט.</p>
            <p>טיול אחד, המון אפשרויות – כל מה שנשאר לכם זה להתרווח ולהתמסר לחוויה היוקרתית.</p>
        </div>
    </div>

</body>
</html>
