<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر فيلوريا - عرض خاص ومحدود</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --main-pink: #fff5f6;
            --dark-pink: #f06292;
            --gold: #d4af37;
            --black: #1a1a1a;
            --green-wa: #25D366;
        }

        * { box-sizing: border-box; }
        body {
            font-family: 'Cairo', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
            text-align: center;
            line-height: 1.6;
        }

        /* 1. الشريط الأسود - الوسط */
        .promo-bar { 
            background: var(--black); 
            color: #fff; 
            padding: 12px; 
            font-weight: bold; 
            font-size: 14px; 
            width: 100%;
        }

        /* 2. العد التنازلي */
        .timer-container {
            background: #fff3f3;
            padding: 15px;
            border-bottom: 2px solid #ffcdd2;
        }
        #timer { font-size: 28px; font-weight: bold; color: #d32f2f; letter-spacing: 2px; }

        /* 3. الهيدر والعنوان */
        .hero { padding: 30px 15px; }
        h1 { color: var(--dark-pink); font-size: 1.8rem; margin-bottom: 15px; }
        .hero-img { width: 95%; max-width: 500px; border-radius: 20px; box-shadow: 0 10px 20px rgba(0,0,0,0.1); margin-bottom: 20px; }

        /* 4. الأثمنة */
        .price-box { margin: 20px 0; padding: 15px; background: #fafafa; }
        .old-price { text-decoration: line-through; color: #999; font-size: 20px; }
        .new-price { font-size: 32px; color: #e91e63; font-weight: bold; display: block; }
        .badge { background: #ff5252; color: #fff; padding: 5px 12px; border-radius: 4px; font-size: 14px; display: inline-block; margin-top: 5px; }

        /* 5. صور الشرح (3 صور) */
        .info-section { padding: 40px 15px; background: #fff; }
        .info-card { margin-bottom: 50px; border-bottom: 1px dashed #eee; padding-bottom: 30px; }
        .info-card img { width: 95%; max-width: 450px; border-radius: 15px; margin-bottom: 15px; }
        .info-card h3 { color: var(--dark-pink); font-size: 1.4rem; margin-bottom: 10px; }
        .info-card p { font-size: 1.1rem; max-width: 500px; margin: 0 auto; color: #555; }

        /* 6. تعاليق البنات (10 تعاليق) */
        .reviews-container { background: var(--main-pink); padding: 50px 15px; }
        .review-card {
            background: #fff;
            padding: 20px;
            border-radius: 15px;
            margin: 15px auto;
            width: 100%;
            max-width: 500px;
            text-align: right;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
            display: flex;
            gap: 15px;
        }
        .profile-img { width: 55px; height: 55px; border-radius: 50%; object-fit: cover; border: 2px solid var(--dark-pink); }
        .stars { color: #ffc107; font-size: 14px; margin-bottom: 5px; }
        .review-content { flex: 1; }
        .review-name { font-weight: bold; font-size: 16px; color: #333; }
        .review-text { font-size: 14px; color: #666; margin-top: 5px; }

        /* 7. الفوتر وزر الواتساب */
        .spacer { height: 120px; }
        .sticky-footer {
            position: fixed;
            bottom: 0;
            left: 0;
            right: 0;
            background: rgba(255, 255, 255, 0.95);
            padding: 15px;
            box-shadow: 0 -5px 20px rgba(0,0,0,0.1);
            z-index: 9999;
            display: flex;
            justify-content: center;
        }
        .cta-btn {
            background: var(--green-wa);
            color: #fff;
            width: 90%;
            max-width: 400px;
            padding: 16px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.4rem;
            box-shadow: 0 6px 20px rgba(37, 211, 102, 0.3);
            animation: pulse 2.5s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        h2 { font-size: 1.6rem; color: var(--dark-pink); margin-bottom: 30px; }
    </style>
</head>
<body>

    <div class="promo-bar">🚚 توصيل مجاني + الدفع عند الاستلام في جميع المدن 🤝</div>

    <div class="timer-container">
        <p style="margin:0; font-weight: bold;">ينتهي الخصم (50%-) خلال:</p>
        <div id="timer">05:00:00</div>
    </div>

    <section class="hero">
        <h1>احصلي على شعر حريري وجذاب في دقائق ✨</h1>
        <p>المشط الاحترافي الأصلي لنتائج الصالون في منزلك</p>
        <img src="https://via.placeholder.com/600x600" class="hero-img" alt="صورة المنتج الرئيسية">
        
        <div class="price-box">
            <span class="old-price">499 درهم</span>
            <span class="new-price">249 درهم فقط</span>
            <span class="badge">تخفيض محدود 50%-</span>
        </div>
    </section>

    <section class="info-section">
        <h2>علاش غادي تعشقي هاد المشط؟ 😍</h2>
        
        <div class="info-card">
            <img src="https://via.placeholder.com/500x400" alt="شرح 1">
            <h3>سهولة واحترافية فـ الاستعمال 💆‍♀️</h3>
            <p>بلا ما تضيعي وقتك فـ الصالونات، هاد المشط كيسخن فـ 30 ثانية وكيسرح ليك شعرك من الدوزة اللولة بكل انسيابية.</p>
        </div>

        <div class="info-card">
            <img src="https://via.placeholder.com/500x400" alt="شرح 2">
            <h3>حماية فائقة لشعرك من الحرق 🔥</h3>
            <p>بفضل تقنية السيراميك المتقدمة، شعرك كيبقى محمي من الحرارة الزايدة، وكيعطيه لمعان طبيعي كيدوم النهار كامل.</p>
        </div>

        <div class="info-card">
            <img src="https://via.placeholder.com/500x400" alt="شرح 3">
            <h3>تصميم ذكي لكل أنواع الشعر 🎀</h3>
            <p>سواء كان شعرك خشن، كيرلي أو رقيق، هاد المشط كيناسبك تماماً وكيخليك تحكمي فـ الحرارة اللي بغيتي.</p>
        </div>
    </section>

    <section class="reviews-container">
        <h2>شنو قالو البنات على المنتج ديالنا؟ ⭐</h2>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=a" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <span class="review-name">سناء</span>
                <p class="review-text">بصراحة واعر بزااااف، هناني من تمارة السيشوار. كيسرح دغيا ❤️</p>
            </div>
        </div>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=b" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <span class="review-name">ليلى من طنجة</span>
                <p class="review-text">وصلني اليوم، التوصيل سريع والسلعة جودتها عالية برافو 👍</p>
            </div>
        </div>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=c" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐</div>
                <span class="review-name">مريم</span>
                <p class="review-text">عجبني بزااف، غير هو تعطل عليا الليفرور شوية ولكن المنتج طوب.</p>
            </div>
        </div>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=d" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <span class="review-name">خديجة</span>
                <p class="review-text">خديت جوج ليا ولختي، عجبنا بزااف كيسرح دغيا ومكيحرقش الشعر 🎀</p>
            </div>
        </div>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=e" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <span class="review-name">إيمان</span>
                <p class="review-text">أحسن حاجة شريتها هاد العام، كيهني فاش كتكوني زربانة ومحتاجة تقادي شعرك.</p>
            </div>
        </div>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=f" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐</div>
                <span class="review-name">فاطمة الزهراء</span>
                <p class="review-text">ممتاز، كيرد الشعر حرير فـ 5 دقايق. كنصحكم بيه البنات والله.</p>
            </div>
        </div>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=g" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <span class="review-name">كوثر</span>
                <p class="review-text">تبارك الله عليكم، السلعة واصلة مقادة وكيفما فالتصاور ✨</p>
            </div>
        </div>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=h" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <span class="review-name">حنان</span>
                <p class="review-text">عجبني بزااف وخاصة أنه خفيف فاليد، شكراً ليكم بزااف.</p>
            </div>
        </div>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=i" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐</div>
                <span class="review-name">سلمى</span>
                <p class="review-text">تجربة زوينة، النتيجة عجباتني بزااف 😍 وكيلمع الشعر.</p>
            </div>
        </div>

        <div class="review-card">
            <img src="https://i.pravatar.cc/100?u=j" class="profile-img">
            <div class="review-content">
                <div class="stars">⭐⭐⭐⭐⭐</div>
                <span class="review-name">نادية</span>
                <p class="review-text">التعامل ديالكم راقي والمنتج يستاهل كل درهم 👌 شكراً فيلوريا.</p>
            </div>
        </div>
    </section>

    <div class="spacer"></div>

    <div class="sticky-footer">
        <a href="https://wa.me/212691444558" class="cta-btn">اطلبي الآن عبر الواتساب</a>
    </div>

    <script>
        function startTimer(duration, display) {
            var timer = duration, hours, minutes, seconds;
            setInterval(function () {
                hours = parseInt(timer / 3600, 10);
                minutes = parseInt((timer % 3600) / 60, 10);
                seconds = parseInt(timer % 60, 10);
                hours = hours < 10 ? "0" + hours : hours;
                minutes = minutes < 10 ? "0" + minutes : minutes;
                seconds = seconds < 10 ? "0" + seconds : seconds;
                display.textContent = hours + ":" + minutes + ":" + seconds;
                if (--timer < 0) { timer = duration; }
            }, 1000);
        }
        window.onload = function () {
            var fiveHours = 60 * 60 * 5, display = document.querySelector('#timer');
            startTimer(fiveHours, display);
        };
    </script>

</body>
</html>
