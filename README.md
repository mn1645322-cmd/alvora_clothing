    <!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alvora Clothing - ألوفورا للملابس</title>
    <style>
        * { box-sizing: border-box; }
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; background-color: #f8f9fa; color: #333; }
        header { background-color: #111; color: white; padding: 20px; text-align: center; }
        header h1 { margin: 0; font-size: 2.2rem; letter-spacing: 2px; }
        nav { display: flex; justify-content: center; background-color: #222; padding: 12px; gap: 15px; flex-wrap: wrap; }
        nav a { color: #fff; text-decoration: none; font-weight: 500; padding: 6px 12px; border-radius: 4px; transition: 0.3s; }
        nav a:hover { background-color: #d9534f; }
        
        .hero { background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://via.placeholder.com/1200x400?text=Alvora+Collection') center/cover; color: white; text-align: center; padding: 80px 20px; }
        .hero h2 { font-size: 2.5rem; margin-bottom: 10px; }
        
        .container { max-width: 1200px; margin: 30px auto; padding: 0 20px; }
        .section-title { text-align: center; font-size: 1.8rem; margin: 40px 0 20px; color: #111; border-bottom: 2px solid #d9534f; display: inline-block; padding-bottom: 5px; }
        .center-title { text-align: center; }
        
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 25px; }
        .card { background: white; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 8px rgba(0,0,0,0.1); text-align: center; transition: 0.3s; }
        .card:hover { transform: translateY(-5px); }
        .card img { width: 100%; height: 280px; object-fit: cover; }
        .card-body { padding: 15px; }
        .card h3 { margin: 10px 0 5px; font-size: 1.2rem; }
        .card p { color: #666; font-size: 0.9rem; margin-bottom: 10px; }
        .price { font-size: 1.1rem; font-weight: bold; color: #d9534f; margin-bottom: 15px; }
        .btn { display: inline-block; background-color: #111; color: white; padding: 10px 18px; text-decoration: none; border-radius: 5px; transition: 0.3s; border: none; cursor: pointer; }
        .btn:hover { background-color: #d9534f; }
        
        footer { background-color: #111; color: white; text-align: center; padding: 20px; margin-top: 50px; }
    </style>
</head>
<body>

<header>
    <h1>ALVORA CLOTHING</h1>
    <p>تشكيلة الأزياء المتميزة</p>
</header>

<nav>
    <a href="#tshirts">تيشرتات</a>
    <a href="#pants">بناطيل</a>
    <a href="#shorts">شورتات</a>
    <a href="#hoodies">هوديز</a>
    <a href="#jackets">جواكت</a>
</nav>

<section class="hero">
    <h2>أحدث صيحات الموضة لعصرك</h2>
    <p>اكتشفوا جودة الخامات وأناقة التصميم</p>
</section>

<div class="container">

    <!-- قسم التيشرتات -->
    <div class="center-title"><h2 id="tshirts" class="section-title">التيشرتات (T-Shirts)</h2></div>
    <div class="grid">
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=تيشرت+أوفرسايز" alt="تيشرت">
            <div class="card-body">
                <h3>تيشرت اوفرسايز أسود</h3>
                <p>قطن 100% مريح وعصري</p>
                <div class="price">350 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=تيشرت+بولو" alt="تيشرت">
            <div class="card-body">
                <h3>تيشرت بولو كلاسيك</h3>
                <p>مناسب للخروج والعمل</p>
                <div class="price">400 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
    </div>

    <!-- قسم البناطيل -->
    <div class="center-title"><h2 id="pants" class="section-title">جميع أنواع البناطيل (Pants)</h2></div>
    <div class="grid">
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=بنطال+جينز" alt="جينز">
            <div class="card-body">
                <h3>بنطال جينز واسع (Wide Leg)</h3>
                <p>خامة جينز ممتازة وتصميم عصري</p>
                <div class="price">650 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=بنطال+ميلتون" alt="ميلتون">
            <div class="card-body">
                <h3>بنطال ميلتون (Sweatpants)</h3>
                <p>مريح جداً للرياضة والاستخدام اليومي</p>
                <div class="price">450 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=بنطال+كارجو" alt="كارجو">
            <div class="card-body">
                <h3>بنطال كارجو (Cargo)</h3>
                <p>مزود بجيوب متعددة وأناقة عالية</p>
                <div class="price">580 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=بنطال+قماش" alt="قماش">
            <div class="card-body">
                <h3>بنطال قماش فورمال</h3>
                <p>للمناسبات والإطلالات الرسمية</p>
                <div class="price">500 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
    </div>

    <!-- قسم الشورتات -->
    <div class="center-title"><h2 id="shorts" class="section-title">الشورتات (Shorts)</h2></div>
    <div class="grid">
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=شورت+ميلتون" alt="شورت">
            <div class="card-body">
                <h3>شورت ميلتون مريح</h3>
                <p>مثالي للصيف والأجواء الكاجوال</p>
                <div class="price">300 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=شورت+جينز" alt="شورت">
            <div class="card-body">
                <h3>شورت جينز عصري</h3>
                <p>تصميم أنيق لخروج الصيف</p>
                <div class="price">380 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
    </div>

    <!-- قسم الهوديز -->
    <div class="center-title"><h2 id="hoodies" class="section-title">الهوديز (Hoodies)</h2></div>
    <div class="grid">
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=هودي+أوفرسايز" alt="هودي">
            <div class="card-body">
                <h3>هودي أوفرسايز ثقيل</h3>
                <p>بطانة خامة ميلتون معالجة للشتاء</p>
                <div class="price">750 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=هودي+بسوستة" alt="هودي">
            <div class="card-body">
                <h3>هودي سوستة (Zip-up)</h3>
                <p>عملي وسهل الارتداء يومياً</p>
                <div class="price">700 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
    </div>

    <!-- قسم الجواكت -->
    <div class="center-title"><h2 id="jackets" class="section-title">الجواكت (Jackets)</h2></div>
    <div class="grid">
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=جاكيت+جينز" alt="جاكيت جينز">
            <div class="card-body">
                <h3>جاكيت جينز كلاسيك</h3>
                <p>تصميم أنيق يناسب كل الأوقات</p>
                <div class="price">850 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=جاكيت+جلد" alt="جاكيت جلد">
            <div class="card-body">
                <h3>جاكيت جلد عصري</h3>
                <p>إطلالة فاخرة وجودة عالية</p>
                <div class="price">1200 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x350?text=جاكيت+بامب" alt="جاكيت بامب">
            <div class="card-body">
                <h3>جاكيت بامب شتوي (Puffer)</h3>
                <p>تدفئة عالية وتصميم خفيف الوزن</p>
                <div class="price">950 ج.م</div>
                <button class="btn">إضافة للسلة</button>
            </div>
        </div>
    </div>

</div>

<footer>
    <p>&copy; 2026 Alvora Clothing - جميع الحقوق محفوظة</p>
</footer>

</body>
</html>                                                                                             
