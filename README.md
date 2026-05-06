<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROV ID Shop | ร้านสุ่มไอดีตัวตึง</title>
    <style>
        :root {
            --primary: #f1c40f; /* สีเหลืองทอง */
            --secondary: #e74c3c; /* สีแดง */
            --dark: #1a1a1d;
            --card-bg: #2a2a2e;
            --text: #ffffff;
        }

        body {
            font-family: 'Kanit', sans-serif;
            background-color: var(--dark);
            color: var(--text);
            margin: 0;
            padding: 0;
            text-align: center;
        }

        header {
            padding: 50px 20px;
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1542751371-adc38448a05e?auto=format&fit=crop&q=80&w=1000');
            background-size: cover;
            background-position: center;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            padding: 20px;
        }

        h1 { color: var(--primary); font-size: 3rem; margin-bottom: 10px; }
        
        /* สไตล์การ์ดสุ่ม */
        .shop-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: var(--card-bg);
            border-radius: 15px;
            padding: 20px;
            border: 2px solid #333;
            transition: 0.3s;
        }

        .card:hover {
            border-color: var(--primary);
            transform: translateY(-5px);
        }

        .card img {
            width: 100%;
            border-radius: 10px;
        }

        .price {
            font-size: 1.5rem;
            color: var(--primary);
            font-weight: bold;
            margin: 15px 0;
        }

        .btn-buy {
            background: var(--primary);
            color: #000;
            border: none;
            padding: 10px 25px;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
            width: 100%;
            font-size: 1.1rem;
        }

        .btn-buy:hover { background: #d4ac0d; }

        .status {
            font-size: 0.9rem;
            color: #2ecc71;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>ROV DEAD ID SHOP</h1>
    <p>สุ่มไอดีตาย ราคาถูกที่สุด เริ่มต้นแค่ 5-9 บาท!</p>
</header>

<div class="container">
    <div class="shop-grid">
        
        <div class="card">
            <div class="status">● พร้อมส่ง (150 ไอดี)</div>
            <img src="https://via.placeholder.com/300x180/e74c3c/ffffff?text=ROV+RANDOM+V1" alt="ID">
            <h3>สุ่มไอดีตาย (คละเลเวล)</h3>
            <p>มีโอกาสได้สกิน Legend และ Limited</p>
            <div class="price">9 บาท</div>
            <button class="btn-buy" onclick="alert('ไปเชื่อมต่อระบบหลังบ้านเพื่อสุ่ม!')">คลิกเพื่อสุ่ม</button>
        </div>

        <div class="card">
            <div class="status">● พร้อมส่ง (50 ไอดี)</div>
            <img src="https://via.placeholder.com/300x180/f1c40f/000000?text=ROV+VIP+BOX" alt="ID">
            <h3>สุ่มไอดีตึง (เน้นสกินเยอะ)</h3>
            <p>ไอดีตายคุณภาพสูง ไม่มีการดึงชัวร์</p>
            <div class="price">25 บาท</div>
            <button class="btn-buy" onclick="alert('ไปเชื่อมต่อระบบหลังบ้านเพื่อสุ่ม!')">คลิกเพื่อสุ่ม</button>
        </div>

    </div>
</div>

<footer style="margin-top: 50px; padding: 20px; color: #666;">
    <p>&copy; 2026 ROV DEAD ID SHOP - BY PARINTHORN</p>
</footer>

</body>
</html>
