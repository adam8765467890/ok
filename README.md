<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>فعاليات رياضية</title>
    <link rel="icon" href="physical_5388915.png">
        <style>
            body {
                font-family: 'Arial', sans-serif;
                background: linear-gradient(135deg, #121212, #1a1a1a);
                margin: 0;
                padding: 0;
                direction: rtl;
                color: #f1f1f1;
            }
            .container {
                max-width: 1200px;
                margin: 0 auto;
                padding: 30px;
                text-align: center;
            }
            .header {
                font-size: 36px;
                color: #ffffff;
                margin-bottom: 40px;
                background: linear-gradient(135deg, #2c3e50, #8e44ad);
                -webkit-background-clip: text;
                color: transparent;
            }
            .events {
                display: flex;
                flex-wrap: wrap;
                gap: 30px;
                justify-content: center;
            }
            .event {
                background: linear-gradient(135deg, #0d0d0d, #1f1f1f);
                border-radius: 10px;
                box-shadow: 0 4px 10px rgba(0, 0, 0, 0.7);
                width: calc(33% - 20px);
                transition: transform 0.3s ease;
                position: relative;
                margin-bottom: 30px;
            }
            .event img {
                width: 100%;
                height: 250px;
                object-fit: contain;
                background-color: #222;
                padding: 10px;
            }
            .event-details {
                padding: 20px;
                background: linear-gradient(135deg, #1a1a1a, #0f0f0f);
                border-radius: 0 0 10px 10px;
            }
            .event h3 {
                font-size: 22px;
                color: #ffffff;
            }
            .event p {
                color: #d3d3d3;
                font-size: 16px;
            }
            .event:hover {
                transform: translateY(-10px);
            }
            @media screen and (max-width: 768px) {
                .event {
                    width: calc(50% - 20px);
                }
            }
            @media screen and (max-width: 480px) {
                .event {
                    width: 100%;
                }
            }
            @media screen and (max-width: 1024px) {
                .event {
                    width: calc(50% - 20px);
                }
            }

            @media screen and (max-width: 768px) {
                .event {
                    width: 100%;
                }
            }

    </style>

</head>
<body>
    <div class="container">
        <h1 class="header">الفعاليات الرياضية القادمة</h1>
        <div class="events">
            <!-- دورة الألعاب الرياضية العربية 2025 -->
            <div class="event" data-category="sport">
                <img src="one.jpg" alt="دورة الألعاب الرياضية العربية">
                <div class="event-details">
                    <h3>دورة الألعاب الرياضية العربية 2025</h3>
                    <p><strong>التاريخ:</strong> 15-25 مايو 2025</p>
                    <p><strong>الموقع:</strong> استاد خليفة الدولي</p>
                    <p>أكبر دورة رياضية في الوطن العربي بمشاركة 22 دولة.</p>
                    <div class="countdown" id="countdown1"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- تصفيات كأس العالم لكرة القدم 2025 -->
            <div class="event" data-category="sport">
                <img src="download1.jpg" alt="بطولة كأس العالم لكرة القدم">
                <div class="event-details">
                    <h3>بطولة كأس العالم لكرة القدم 2025 (تصفيات)</h3>
                    <p><strong>التاريخ:</strong> 1-15 نوفمبر 2025</p>
                    <p><strong>الموقع:</strong> ملعب لوسيل</p>
                    <p>تصفيات كأس العالم لكرة القدم بمشاركة الفرق الوطنية من جميع القارات.</p>
                    <div class="countdown" id="countdown2"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- اليوم الرياضي -->
            <div class="event" data-category="sport">
                <img src="download.png" alt="اليوم الرياضي">
                <div class="event-details">
                    <h3>اليوم الرياضي 2025</h3>
                    <p><strong>التاريخ:</strong> 10 فبراير 2025</p>
                    <p><strong>الموقع:</strong> مختلف الأماكن في الدوحة</p>
                    <p>يوم مليء بالأنشطة الرياضية والفعاليات المجتمعية في قطر.</p>
                    <div class="countdown" id="countdown9"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- ماراثون الدوحة الدولي -->
            <div class="event" data-category="sport">
                <img src="fon.jpg" alt="ماراثون الدوحة الدولي">
                <div class="event-details">
                    <h3>ماراثون الدوحة الدولي 2025</h3>
                    <p><strong>التاريخ:</strong> 22 يناير 2025</p>
                    <p><strong>الموقع:</strong> شوارع الدوحة</p>
                    <p>أحد أكبر الماراثونات في المنطقة بمشاركة آلاف المتسابقين من جميع أنحاء العالم.</p>
                    <div class="countdown" id="countdown3"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة قطر المفتوحة للتنس 2025 -->
            <div class="event" data-category="sport">
                <img src="medium-1280px.jpeg" alt="بطولة قطر المفتوحة للتنس">
                <div class="event-details">
                    <h3>بطولة قطر المفتوحة للتنس 2025</h3>
                    <p><strong>التاريخ:</strong> 5-12 مارس 2025</p>
                    <p><strong>الموقع:</strong> مجمع خليفة للتنس</p>
                    <p>أكبر بطولات التنس في المنطقة بمشاركة أبرز اللاعبين العالميين.</p>
                    <div class="countdown" id="countdown4"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة قطر المفتوحة لكرة السلة 2025 -->
            <div class="event" data-category="sport">
                <img src="images.jpg" alt="بطولة قطر المفتوحة لكرة السلة">
                <div class="event-details">
                    <h3>بطولة قطر المفتوحة لكرة السلة 2025</h3>
                    <p><strong>التاريخ:</strong> 18-25 فبراير 2025</p>
                    <p><strong>الموقع:</strong> صالة الألعاب الرياضية في الدوحة</p>
                    <p>بطولة دولية بمشاركة أقوى الفرق العالمية في كرة السلة.</p>
                    <div class="countdown" id="countdown5"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة كأس الخليج لكرة القدم 2025 -->
            <div class="event" data-category="sport">
                <img src="Gb9TBuYW0AAq4lQ.jpg" alt="بطولة كأس الخليج لكرة القدم">
                <div class="event-details">
                    <h3>بطولة كأس الخليج لكرة القدم 2025</h3>
                    <p><strong>التاريخ:</strong> 5-15 ديسمبر 2025</p>
                    <p><strong>الموقع:</strong> استاد خليفة الدولي</p>
                    <p>البطولة الأكبر في المنطقة بمشاركة الفرق الخليجية.</p>
                    <div class="countdown" id="countdown6"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- سباق الدراجات الهوائية الدولي -->
            <div class="event" data-category="sport">
                <img src="images (1).jpg" alt="سباق الدراجات الهوائية الدولي">
                <div class="event-details">
                    <h3>سباق الدراجات الهوائية الدولي 2025</h3>
                    <p><strong>التاريخ:</strong> 10-14 أبريل 2025</p>
                    <p><strong>الموقع:</strong> شوارع الدوحة</p>
                    <p>أكبر سباق دراجات هوائية دولي في المنطقة بمشاركة أفضل الدراجين.</p>
                    <div class="countdown" id="countdown7"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة قطر للمصارعة 2025 -->
            <div class="event" data-category="sport">
                <img src="ghf.jpg" alt="بطولة قطر للمصارعة">
                <div class="event-details">
                    <h3>بطولة قطر للمصارعة 2025</h3>
                    <p><strong>التاريخ:</strong> 25-30 أكتوبر 2025</p>
                    <p><strong>الموقع:</strong> صالة المصارعة في الدوحة</p>
                    <p>أكبر منافسة مصارعة في قطر بمشاركة مصارعين عالميين.</p>
                    <div class="countdown" id="countdown8"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة العالم لألعاب القوى 2025 -->
            <div class="event" data-category="sport">
                <img src="images (2).jpg" alt="بطولة العالم لألعاب القوى">
                <div class="event-details">
                    <h3>بطولة العالم لألعاب القوى 2025</h3>
                    <p><strong>التاريخ:</strong> 1-15 أغسطس 2025</p>
                    <p><strong>الموقع:</strong> استاد خليفة</p>
                    <p>بطولة ألعاب القوى العالمية في الدوحة بمشاركة أفضل الرياضيين.</p>
                    <div class="countdown" id="countdown11"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة قطر المفتوحة للجودو 2025 -->
            <div class="event" data-category="sport">
                <img src="images (3).jpg" alt="بطولة قطر المفتوحة للجودو">
                <div class="event-details">
                    <h3>بطولة قطر المفتوحة للتايكوندو 2025</h3>
                    <p><strong>التاريخ:</strong> 15-20 مايو 2025</p>
                    <p><strong>الموقع:</strong> صالة الجودو</p>
                    <p>أحد أقوى بطولات الجودو في العالم بمشاركة أبطال عالميين.</p>
                    <div class="countdown" id="countdown10"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- دورة الألعاب الأولمبية الخاصة 2025 -->
            <div class="event" data-category="sport">
                <img src="yu.jpg" alt="دورة الألعاب الأولمبية الخاصة">
                <div class="event-details">
                    <h3>دورة الألعاب الأولمبية الخاصة 2025</h3>
                    <p><strong>التاريخ:</strong> 5-10 يوليو 2025</p>
                    <p><strong>الموقع:</strong> مختلف الأماكن في الدوحة</p>
                    <p>دورة الألعاب المخصصة لذوي الاحتياجات الخاصة في قطر.</p>
                    <div class="countdown" id="countdown12"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة قطر للسباحة 2025 -->
            <div class="event" data-category="sport">
                <img src="GhRrOKUXsAARGzj.jpg" alt="بطولة قطر للسباحة">
                <div class="event-details">
                    <h3>بطولة قطر للسباحة 2025</h3>
                    <p><strong>التاريخ:</strong> 22-25 نوفمبر 2025</p>
                    <p><strong>الموقع:</strong> حمام السباحة الأولمبي</p>
                    <p>أكبر حدث سباحة في قطر بمشاركة أفضل السباحين.</p>
                    <div class="countdown" id="countdown13"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة قطر لكرة اليد 2025 -->
            <div class="event" data-category="sport">
                <img src="images(4).png" alt="بطولة قطر لكرة اليد">
                <div class="event-details">
                    <h3>بطولة قطر لكرة اليد 2025</h3>
                    <p><strong>التاريخ:</strong> 10-15 يونيو 2025</p>
                    <p><strong>الموقع:</strong> صالة كرة اليد</p>
                    <p>أفضل الفرق لكرة اليد في قطر يتنافسون في البطولة.</p>
                    <div class="countdown" id="countdown14"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة قطر الدولية للفروسية 2025 -->
            <div class="event" data-category="sport">
                <img src="images (5).jpg" alt="بطولة قطر الدولية للفروسية">
                <div class="event-details">
                    <h3>بطولة قطر الدولية للفروسية 2025</h3>
                    <p><strong>التاريخ:</strong> 15-18 فبراير 2025</p>
                    <p><strong>الموقع:</strong> مضمار الفروسية في الدوحة</p>
                    <p>أكبر حدث للفروسية في المنطقة بمشاركة أفضل الفرسان.</p>
                    <div class="countdown" id="countdown15"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>

            <!-- بطولة قطر الدولية للغولف 2025 -->
            <div class="event" data-category="sport">
                <img src="poe.jpg" alt="بطولة قطر الدولية للغولف">
                <div class="event-details">
                    <h3>بطولة قطر الدولية للغولف 2025</h3>
                    <p><strong>التاريخ:</strong> 1-5 مارس 2025</p>
                    <p><strong>الموقع:</strong> ملعب الغولف في الدوحة</p>
                    <p>أفضل لاعبي الغولف يتنافسون في أكبر بطولة في المنطقة.</p>
                    <div class="countdown" id="countdown16"></div>
                    <a href="#" class="more-info" target="_blank">اعرف المزيد</a>
                </div>
            </div>
        </div>
    </div>

    <script>
        // دالة لبدء العد التنازلي
        function startCountdown(id, eventDate) {
            const countdownElement = document.getElementById(id);

            const interval = setInterval(function() {
                const now = new Date().getTime();
                const timeDifference = eventDate - now;

                if (timeDifference < 0) {
                    countdownElement.innerHTML = "الحدث قد بدأ!";
                    clearInterval(interval);
                } else {
                    const days = Math.floor(timeDifference / (1000 * 60 * 60 * 24));
                    const hours = Math.floor((timeDifference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                    const minutes = Math.floor((timeDifference % (1000 * 60 * 60)) / (1000 * 60));
                    const seconds = Math.floor((timeDifference % (1000 * 60)) / 1000);

                    countdownElement.innerHTML = `${days} أيام ${hours} ساعات ${minutes} دقائق ${seconds} ثواني`;
                }
            }, 1000);
        }

        // تواريخ الأحداث
        const events = [
            { id: 'countdown1', date: new Date('May 15, 2025 00:00:00') },
            { id: 'countdown2', date: new Date('November 1, 2025 00:00:00') },
            { id: 'countdown9', date: new Date('February 10, 2025 00:00:00') },
            { id: 'countdown3', date: new Date('March 5, 2025 00:00:00') },
            { id: 'countdown10', date: new Date('May 15, 2025 00:00:00') },
            { id: 'countdown11', date: new Date('August 1, 2025 00:00:00') },
            { id: 'countdown12', date: new Date('July 5, 2025 00:00:00') },
            { id: 'countdown13', date: new Date('March 10, 2025 00:00:00') },
            { id: 'countdown14', date: new Date('June 18, 2025 00:00:00') },
            { id: 'countdown15', date: new Date('October 15, 2025 00:00:00') },
            { id: 'countdown16', date: new Date('November 10, 2025 00:00:00') },
        ];

        // بدء العد التنازلي لكل حدث
        events.forEach(function(event) {
            startCountdown(event.id, event.date);
        });
    </script>
</body>
</html>

        <!-- رياضي
دورة الألعاب الرياضية العربية 2025
بطولة كأس العالم لكرة القدم 2025 (تصفيات)
بطولة قطر المفتوحة للتنس 2025
ماراثون الدوحة الدولي
بطولة قطر المفتوحة لكرة السلة 2025
بطولة كأس الخليج لكرة القدم 2025
سباق الدراجات الهوائية الدولي
بطولة قطر للمصارعة 2025
بطولة العالم لألعاب القوى 2025
بطولة قطر المفتوحة للجودو 2025
دورة الألعاب الأولمبية الخاصة 2025
بطولة قطر للسباحة 2025
بطولة قطر لكرة اليد 2025
بطولة قطر الدولية للفروسية 2025
بطولة قطر الدولية للغولف 2025
اليوم الرياضي
        -->
        <!-- سنمايئي
مهرجان الدوحة للأفلام
مهرجان أفلام الثقافة العربية
مهرجان أفلام البيئة
مهرجان أفلام العائلة
مهرجان أفلام حقوق الإنسان
مهرجان أفلام الرسوم المتحركة
مهرجان أفلام الواقع الافتراضي
مهرجان أفلام الشباب القطريين
مهرجان أفلام الشرق الأوسط
مهرجان الأفلام القصيرة
مهرجان الأفلام الوثائقية
مهرجان أفلام السينما العربية
مهرجان أفلام المخرجين القطريين
مهرجان الأفلام السينمائية النسائية
مهرجان أفلام الأطفال والشباب
        -->
        <!-- معرضًا للكتاب
معرض الدوحة الدولي للكتاب
معرض الكتاب الدولي للأطفال
معرض الكتب المصورة
معرض الكتب الجامعية
معرض الكتاب العربي
معرض الكتب العلمية
معرض الكتب الإلكترونية
معرض الكتاب العربي للأطفال
معرض الكتاب المتخصص في الأدب القطري
معرض الكتاب الرقمي
معرض الكتب الثقافية والفكرية
معرض كتب الشعر العربي
معرض كتب الفنون
معرض الكتب التاريخية
معرض الكتاب الأدبي العالمي
        -->
        <!-- موسيقي  
مهرجان الموسيقى العربية
مهرجان الأوبرا العالمية
مهرجان الجاز الدولي
مهرجان الموسيقى الكلاسيكية
مهرجان الموسيقى الشعبية
مهرجان الموسيقى الإلكترونية
مهرجان الروك العربي
مهرجان موسيقى الأفلام
مهرجان الموسيقى الهندية
مهرجان الموسيقى الفلكلورية
مهرجان الموسيقى الشبابية
مهرجان الموسيقى العالمية
مهرجان موسيقى التراث
مهرجان موسيقى الروح
مهرجان موسيقى الرقص العربي
        -->
