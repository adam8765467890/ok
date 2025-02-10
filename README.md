welcome

<!DOCTYPE html>

<html lang="ar">
<head>
  
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الفعاليات الرياضية القادمة</title>
    <meta name="description" content="اكتشف الفعاليات الرياضية القادمة في قطر مع العد التنازلي لكل حدث">
    <meta name="keywords" content="فعاليات رياضية، قطر، بطولات، كأس العالم، ماراثون، تنس">
    <meta name="author" content="اسمك هنا">
    <!-- إضافة الـWeb Fonts لتحسين العرض -->
    <link href="https://fonts.googleapis.com/css2?family=Amiri&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            background-color: #fafafa;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .header {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 30px;
            color: #333333;
        }
        .events {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-between;
        }
        .event {
            background-color: #ffffff;
            border-radius: 10px;
            padding: 20px;
            width: 32%; /* عرض كل حدث ليكون 32% */
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .event:hover {
            transform: translateY(-5px); /* تأثير التحريك عند التمرير */
        }
        .event h3 {
            font-size: 1.8em;
            margin-bottom: 10px;
            color: #3498db;
        }
        .event p {
            font-size: 1em;
            margin-bottom: 10px;
            color: #666666;
        }
        .event .countdown {
            font-size: 1.2em;
            margin: 20px 0;
            font-weight: bold;
            color: #e67e22;
        }
        .event .more-info {
            text-decoration: none;
            color: #2ecc71;
            font-weight: bold;
            display: inline-block;
            margin-top: 10px;
        }
        .event .more-info:hover {
            text-decoration: underline;
        }
        @media screen and (max-width: 768px) {
            .event {
                width: 100%; /* عند الشاشات الصغيرة يتم تعديل العرض إلى 100% */
            }
        }
    </style>
    

</head>
<body>
  
    <div class="container">
        <h1 class="header">الفعاليات الرياضية القادمة</h1>
        <div class="events">
            <div class="container">
                <div class="events">
                    <!-- دورة الألعاب الرياضية العربية 2025 -->
                    <div class="event" data-category="sport">
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
            
        </div>
    </div>
    <script>
        function setCountdown(elementId, targetDate) {
            const countdownElement = document.getElementById(elementId);
            const targetTime = new Date(targetDate).getTime();
            const interval = setInterval(() => {
                const currentTime = new Date().getTime();
                const timeDifference = targetTime - currentTime;

                if (timeDifference <= 0) {
                    clearInterval(interval);
                    countdownElement.innerHTML = "الحدث قد بدأ!";
                } else {
                    const days = Math.floor(timeDifference / (1000 * 60 * 60 * 24));
                    const hours = Math.floor((timeDifference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                    const minutes = Math.floor((timeDifference % (1000 * 60 * 60)) / (1000 * 60));
                    const seconds = Math.floor((timeDifference % (1000 * 60)) / 1000);
                    countdownElement.innerHTML = `${days} أيام و ${hours} ساعات و ${minutes} دقائق و ${seconds} ثواني`;
                }
            }, 1000);
        }

        document.addEventListener("DOMContentLoaded", function() {
            // العد التنازلي لجميع الفعاليات
            const eventsDates = [
                { id: "countdown1", date: "2025-05-15T00:00:00" },
                { id: "countdown2", date: "2025-11-01T00:00:00" },
                { id: "countdown3", date: "2025-01-22T00:00:00" },
                { id: "countdown4", date: "2025-03-05T00:00:00" },
                { id: "countdown5", date: "2025-02-18T00:00:00" },
                { id: "countdown6", date: "2025-04-11T00:00:00" },
                { id: "countdown7", date: "2025-06-15T00:00:00" },
                { id: "countdown8", date: "2025-08-07T00:00:00" },
                { id: "countdown9", date: "2025-02-10T00:00:00" },
                { id: "countdown10", date: "2025-07-30T00:00:00" },
                { id: "countdown11", date: "2025-09-20T00:00:00" },
                { id: "countdown12", date: "2025-12-01T00:00:00" },
                { id: "countdown13", date: "2025-10-05T00:00:00" },
                { id: "countdown14", date: "2025-12-15T00:00:00" },
                { id: "countdown15", date: "2025-02-25T00:00:00" },
                { id: "countdown16", date: "2025-03-15T00:00:00" }
            ];
            
            eventsDates.forEach(event => setCountdown(event.id, event.date));
        });
    </script>
</body>
</html>
