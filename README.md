nav{
    box-shadow: 0 4px 8px 0 rgba(142, 137, 137, 0.2), 0 6px 20px 0 rgba(189, 178, 178, 0.19);
    width: 1280px;
    height:90px;
}

nav ul {
    display: flex; /* استفاده از فلکس‌باکس برای نمایش عناصر */
    flex-flow: nowrap; /* عناصر در یک خط قرار می‌گیرند */
    list-style-type: none; /* حذف نشان‌های لیست */
    flex-basis: 100%; /* تنظیم اندازه اولیه به ۱۰۰٪ */
    align-items: center; /* عناصر در مرکز عمودی قرار می‌گیرند */
    padding-bottom: 30px; 
    padding-top: 10px; /* فاصله ۱۰ پیکسل از بالا */
    box-shadow: inset;
    float:right;
    padding-right:5px;
    border:none;
    gap: 2rem;
    white-space: nowrap;
}

nav ul li {
    flex-basis: 7%; /* تنظیم اندازه اولیه عنصر به ۷٪ */
    text-align: center; /* تنظیم متن در مرکز */
    padding-right: 30px; 
    padding-top: 10px; 
    display: inline; 
}

nav ul li h2{
    display: inline;
    width: 10px;
    height: 10px;
    flex-basis: auto; /* اندازه عنصر به صورت خودکار */
     text-align: left; 
     padding-top: 35px;
     padding-right: 570px;
     white-space: nowrap;
    font-size: 3rem;
}

nav ul a {
    text-decoration: none; /* حذف خط زیر متن */
    color: #0000008C;
    font-family: 80px MyFont;
    font-size: 18px;
    
}


.container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 50px;
    max-width: 1200px;
    margin: 0 auto;
}

.text-section {
    flex: 1;
    padding-right: 20px;
}

.image-section {
    flex: 1;
    display: flex;
    justify-content: center;
}

.image-section img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
}

h2 {
    font-size: 36px;
    color: #333;
}

p {
    font-size: 18px;
    color: #666;
    line-height: 1.6;
    margin-bottom: 15px;
}

.btn {
    background-color: #8D00EB;
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-size: 18px;
    border-radius: 5px;
    cursor: pointer;
}

.btn:hover {
    background-color: #5753c9;
}
