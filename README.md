[index.html](https://github.com/user-attachments/files/27559096/index.html)
<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>המארזים המתוקים של אלמוגית</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Assistant:wght@300;400;600;700&family=Bellefair&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-brown: #5D4037;
            --soft-mocha: #A1887F;
            --cream-bg: #FDFBF7;
            --gold-accent: #C5A059;
        }
        
        body {
            background-color: var(--cream-bg); 
            font-family: 'Assistant', sans-serif;
            color: var(--primary-brown);
            margin: 0;
            padding: 0;
        }

        .serif-font {
            font-family: 'Bellefair', serif;
        }

        .main-container {
            background-color: var(--cream-bg);
            min-height: 100vh;
            width: 100%;
        }

        .category-card {
            background: white;
            border: 1px solid rgba(161, 136, 127, 0.2);
            transition: all 0.3s ease;
        }

        .category-card:hover {
            border-color: var(--soft-mocha);
            transform: translateY(-3px);
        }

        .divider {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            color: var(--soft-mocha);
            margin: 30px 0;
        }

        .divider::before, .divider::after {
            content: "";
            height: 1px;
            flex-grow: 1;
            background: linear-gradient(to right, transparent, var(--soft-mocha), transparent);
        }

        .cta-button {
            background-color: var(--primary-brown);
            color: white;
            box-shadow: 0 4px 15px rgba(93, 64, 55, 0.3);
            text-decoration: none;
            display: inline-block;
        }
        
        .logo-container {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            overflow: hidden; /* מבטיח שכל מה שחורג מהעיגול ייחתך */
            background-color: white;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .logo-img {
            width: 100%;
            height: 100%;
            object-fit: cover; /* גורם לתמונה למלא את כל העיגול בלי להשאיר פסים לבנים */
        }
    </style>
</head>
<body>

    <div class="main-container relative">
        
        <!-- Header with Logo -->
        <header class="text-center pt-16 pb-8 px-6 bg-[#F9F5F0]">
            <div class="mx-auto mb-6 flex items-center justify-center">
                <div class="logo-container">
                    <!-- שימוש ב-object-fit: cover למניעת פסים לבנים -->
                    <img src="https://i.ibb.co/LzpGFs9F/phonto.jpg" alt="לוגו המארזים המתוקים של אלמוגית" class="logo-img" onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">
                    <div style="display:none;" class="w-full h-full border-2 border-dashed border-[#A1887F] rounded-full flex items-center justify-center bg-white">
                        <span class="text-[10px] text-center text-[#A1887F] px-2 italic">אלמוגית</span>
                    </div>
                </div>
            </div>
            
            <h1 class="text-4xl md:text-6xl serif-font font-bold mb-3 tracking-tight">המארזים המתוקים של אלמוגית</h1>
            <div class="h-px w-32 bg-[#C5A059] mx-auto mb-4"></div>
            <p class="text-xl italic text-[#8D6E63] serif-font">מארזים מכל הלב - בעבודת יד וטעם בלתי נשכח</p>
        </header>

        <main class="max-w-4xl mx-auto px-6 md:px-12 py-12">
            
            <!-- Intro Text -->
            <section class="text-center mb-12">
                <h2 class="text-3xl serif-font font-bold mb-6 text-[#8D6E63]">ברוכים הבאים!</h2>
                <p class="text-lg leading-relaxed text-gray-700">
                    אני אלמוג בת 22 מירושלים, קונדיטורית ביתית, ואני מזמינה אתכם להתמכר לטעם ביתי ומוקפד. אצלי תמצאו מגוון מארזים מתוקים לכל אירוע, שנאפים באהבה גדולה ומחומרי הגלם הטובים ביותר.
                </p>
            </section>

            <!-- Categories -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-12">
                <div class="category-card p-6 rounded-xl flex items-start gap-4">
                    <span class="text-3xl">🍪</span>
                    <div>
                        <h3 class="font-bold text-xl mb-1">עוגות ועוגיות</h3>
                        <p class="text-gray-600 leading-snug">עוגות גבינה, עוגות בחושות ומגוון עוגיות בעבודת יד.</p>
                    </div>
                </div>
                <div class="category-card p-6 rounded-xl flex items-start gap-4">
                    <span class="text-3xl">🎁</span>
                    <div>
                        <h3 class="font-bold text-xl mb-1">מארזים אישיים</h3>
                        <p class="text-gray-600 leading-snug">מתנה מושלמת ליולדת, ימי הולדת או סתם תשומת לב.</p>
                    </div>
                </div>
                <div class="category-card p-6 rounded-xl flex items-start gap-4">
                    <span class="text-3xl">🍷</span>
                    <div>
                        <h3 class="font-bold text-xl mb-1">שבתות וחגים</h3>
                        <p class="text-gray-600 leading-snug">חלה ביתית, עוגות שבת ומארזי חג מעוצבים וחגיגיים.</p>
                    </div>
                </div>
                <div class="category-card p-6 rounded-xl flex items-start gap-4">
                    <span class="text-3xl">✨</span>
                    <div>
                        <h3 class="font-bold text-xl mb-1">בהתאמה אישית</h3>
                        <p class="text-gray-600 leading-snug">בניית המארז המדויק לפי בחירתכם האישית.</p>
                    </div>
                </div>
            </div>

            <div class="divider text-sm serif-font uppercase tracking-widest mb-12">
                קצת מתוק על הלב
            </div>

            <!-- Action Section -->
            <section class="text-center mt-12 space-y-8 pb-16">
                <div class="space-y-3">
                    <h4 class="text-2xl font-bold italic serif-font text-[#5D4037]">מוכנים להזמין?</h4>
                    <p class="text-md text-gray-500 italic">איסוף עצמי מירושלים | משלוחים בתיאום מראש</p>
                </div>

                <div class="flex flex-col items-center gap-4">
                    <a href="https://wa.me/972505998399?text=שלום,%20אשמח%20לקבל%20פרטים%20לגבי%20הזמנה✨🍪" target="_blank" class="cta-button w-full max-w-sm py-4 rounded-full font-bold text-xl hover:scale-105 transition-transform text-center">
                        להזמנות: 050-5998399
                    </a>
                    
                    <div class="flex flex-col items-center gap-2 pt-2">
                        <div class="flex items-center gap-2 text-[#A1887F]">
                            <span class="text-sm uppercase tracking-tighter">חפשו אותי באינסטגרם:</span>
                            <a href="https://www.instagram.com/almogit_sweetbox/" target="_blank" class="font-semibold text-lg underline hover:text-[#5D4037]">@almogit_sweetbox</a>
                        </div>
                    </div>
                </div>
            </section>

        </main>

        <!-- Footer -->
        <footer class="bg-[#F9F5F0] py-8 text-center border-t border-[#D7CCC8]">
            <p class="text-xs text-[#A1887F] tracking-widest uppercase italic">The Sweet World of Almogit • 2026</p>
        </footer>

    </div>

</body>
</html>
