<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[EVENT] กีฬาสีชาวหมอ</title>
    <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;700&display=swap" rel="stylesheet">
    <style> 
        :root {
            --primary-red: #ff4d4d;
            --primary-blue: #00ccff;
            --primary-pink: #ff66cc;
            --primary-yellow: #ffcc00;
            --dark-bg: #1a1a1a;
            --card-bg: #2d2d2d;
            --text-white: #ffffff;
        }

        body {
            font-family: 'Kanit', sans-serif;
            background-color: var(--dark-bg);
            color: var(--text-white);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1538108197003-8ad238b691e3?auto=format&fit=crop&q=80&w=1500') center/cover;
            padding: 80px 20px;
            text-align: center;
            border-bottom: 5px solid var(--primary-red);
        }

        .header-content h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: var(--primary-red);
            text-shadow: 2px 2px 10px rgba(255, 77, 77, 0.5);
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .announcement {
            background: #441111;
            border-left: 10px solid var(--primary-red);
            padding: 20px;
            margin-bottom: 40px;
            border-radius: 5px;
        }

        .color-groups {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-bottom: 50px;
            gap: 15px;
        }

        .color-box {
            padding: 15px 30px;
            border-radius: 30px;
            font-weight: bold;
            text-align: center;
            flex: 1;
            min-width: 120px;
        }

        .event-card {
            background-color: var(--card-bg);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 40px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.3);
            border-bottom: 3px solid #444;
        }

        .event-card h2 {
            color: var(--primary-blue);
            border-bottom: 2px solid #555;
            padding-bottom: 10px;
        }

        .rules {
            background: #3d3d3d;
            padding: 15px;
            border-radius: 8px;
            margin-top: 15px;
        }

        .photo-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-top: 20px;
        }

        .photo-placeholder {
            background: #444;
            height: 250px;
            display: flex;
            align-items: center;
            justify-content: center;
            border: 2px dashed #666;
            border-radius: 10px;
            overflow: hidden;
            position: relative;
        }

        .photo-placeholder img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .footer {
            text-align: center;
            padding: 40px;
            background: #111;
            color: #888;
        }

        /* Responsive */
        @media (max-width: 600px) {
            .photo-grid { grid-template-columns: 1fr; }
            .header-content h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>

<header>
    <div class="header-content">
        <h1>[EVENT] กีฬาสีชาวหมอ</h1>
        <p>พักมือจากเข็มฉีดยา แล้วมาหยิบอาวุธในงานกีฬาสีสุดเดือด!</p>
    </div>
</header>

<div class="container">
    
    <div class="announcement">
        <h2>⚠️ ประกาศปิดโรงพยาบาลชั่วคราว</h2>
        <p>เวลา: <strong>20:00 น. - 23:00 น.</strong></p>
        <p><em>(กรุณาเคลียร์เคสให้เรียบร้อยก่อนเริ่มกิจกรรม ใครติดเคสผ่าตัดฝากเวรด่วน!)</em></p>
    </div>

    <div class="color-groups">
        <div class="color-box" style="background-color: var(--primary-red); color: white;">สีแดง</div>
        <div class="color-box" style="background-color: var(--primary-blue); color: black;">สีฟ้า</div>
        <div class="color-box" style="background-color: var(--primary-pink); color: white;">สีชมพู</div>
        <div class="color-box" style="background-color: var(--primary-yellow); color: black;">สีเหลือง</div>
    </div>

    <div class="event-card">
        <h2>กิจกรรมที่ 1: รวมพลคนไว</h2>
        <p>ภารกิจแรกคือความไว! ใครรวมทีมครบก่อน รับแต้มประเดิมไปเลย</p>
        <div class="rules">
            <strong>เงื่อนไข:</strong> หัวหน้าสี 1 คน (ยศแพทย์ชำนาญการขึ้นไป) + สมาชิก 4 คน<br>
            <strong>กติกา:</strong> ทีมที่รายงานตัวครบเป็นทีมแรก ชนะ! (มีคะแนนสะสม)
        </div>
        <div class="photo-grid">
            <div class="photo-placeholder"><img src="https://media.discordapp.net/attachments/1477304401155588096/1493644027856289842/FiveM_GTAProcess_2026-04-14_21-15-59_857.png?ex=69e303a6&is=69e1b226&hm=64230bf96e359be1ab308f4b7c8add8a941a24e7ec75326bb36f3172805dfa07&=&format=webp&quality=lossless&width=1421&height=800" alt="Photo 1"></div>
            <div class="photo-placeholder"><img src="https://media.discordapp.net/attachments/1477304401155588096/1493644028212940952/FiveM_GTAProcess_2026-04-14_21-16-07_164.png?ex=69e303a6&is=69e1b226&hm=1603f705208c4b75bdaff606bbbeeacf1fbc7de7dcbf85dbc050556b3263f33f&=&format=webp&quality=lossless&width=1421&height=800" alt="Photo 2"></div>
        </div>
    </div>

    <div class="event-card">
        <h2>กิจกรรมที่ 2: มวยทะเล (ECO Pool)</h2>
        <p>จัดกันที่บริเวณสระน้ำ ECO ใครอึด ใครทน อยู่บนคานให้ได้!</p>
        <div class="rules">
            <strong>กติกา:</strong> 
            <ul>
                <li>ส่งตัวแทนทีมละ 1 คนต่อรอบ (ทั้งหมด 5 รอบต่อไฟต์)</li>
                <li><strong>ห้ามปั๊มเกราะ ห้ามเติมเลือด</strong> โดยเด็ดขาด!</li>
                <li>ใช้ได้เพียง "หมัด" เท่านั้น</li>
            </ul>
        </div>
        <div class="photo-grid">
            <div class="photo-placeholder"><img src="https://media.discordapp.net/attachments/1477304401155588096/1493644116007850004/FiveM_GTAProcess_2026-04-14_21-03-04_321.png?ex=69e303bb&is=69e1b23b&hm=0f7b2fd6399e76958ad4d6203de767d760bfb6a8e61ca14b0488d54bff061baa&=&format=webp&quality=lossless&width=1421&height=800" alt="Photo 1"></div>
            <div class="photo-placeholder"><img src="https://media.discordapp.net/attachments/1477304401155588096/1493644116503036104/FiveM_GTAProcess_2026-04-14_21-03-25_822.png?ex=69e303bb&is=69e1b23b&hm=193e4af4a4674d96749230f5ea91ddc58186dd482f32cc4b7ae4ea3d8b7f59e3&=&format=webp&quality=lossless&width=1421&height=800" alt="Photo 2"></div>
        </div>
    </div>

    <div class="event-card">
        <h2>กิจกรรมที่ 3: แย่งศพชิงเดือด!</h2>
        <p>วิญญาณยังไม่ไปไหน แต่หมอจะตีกันเพราะศพนี่แหละ!</p>
        <div class="rules">
            <strong>กติกา:</strong> ดูรูปใบ้ในช่อง <code>#Discord-หมอ</code> แล้วตามหาศพที่ซ่อนอยู่บนภูเขา แย่งชิงและนำไปส่งที่หมู่บ้านหลังโรงพยาบาลให้สำเร็จ!
            <strong>ปล:</strong> กิจกรรมนี้ไม่มีจุดที่แน่นอนขึ้นตามดุลยพินิจของผู้ที่นำศพไปซ่อน โดยแต่ละทีมจะต้องหาศพจากคำใบ้ที่คนซ่อนถ่ายลงดิสคอร์ด
        </div>
    </div>

    <div class="event-card">
        <h2>กิจกรรมที่ 4: โดดร่ม & ปั่นสู้ฟัด</h2>
        <p>ทดสอบความแม่นยำและกล้ามเนื้อขาของเหล่าคุณหมอ</p>
        <div class="rules">
            <strong>เส้นทาง:</strong> โหนสลิงเขาโคเคน ➔ ลงพาวด์เมืองบน ➔ ปั่นจักรยานไปโฮมโปร<br>
            <strong>การตัดสิน:</strong> เข้าเส้นชัยตามลำดับเพื่อรับคะแนนสะสม
        </div>
        <div class="photo-grid">
            <div class="photo-placeholder"><img src="https://media.discordapp.net/attachments/1477304401155588096/1493644294890979338/FiveM_GTAProcess_2026-04-14_21-06-19_191.png?ex=69e303e6&is=69e1b266&hm=908ddead7e7d0c7d51aef49f22292358615fd215bd2272778afa6504152a4fc2&=&format=webp&quality=lossless&width=1421&height=800" alt="Photo 1"></div>
            <div class="photo-placeholder"><img src="https://media.discordapp.net/attachments/1477304401155588096/1493644295373062174/FiveM_GTAProcess_2026-04-14_20-33-26_134.png?ex=69e303e6&is=69e1b266&hm=a5f6ef299cacf51aecc7d8313279c3281bc8134c4306270a900aed4729876a1a&=&format=webp&quality=lossless&width=1421&height=800" alt="Photo 2"></div>
        </div>
    </div>

    <div class="event-card" style="border-left: 5px solid gold;">
        <h2 style="color: var(--primary-red);">กิจกรรมที่ 5: สังเวียนเลือด ยกพวกตีกัน</h2>
        <p>ปิดท้ายด้วยความเดือด สีไหนจะเหลือรอดเป็นสีสุดท้าย?</p>
        <div class="rules">
            <strong>กติกา:</strong> ตะลุมบอน 4 สีพร้อมกัน ใช้อาวุธได้ทุกชนิด (ถ้าไม่มีให้ใช้หมัด) สู้จนกว่าจะตายกันไปข้าง!
        </div>
        <div class="photo-grid">
            <div class="photo-placeholder"><img src="https://media.discordapp.net/attachments/1477304401155588096/1493644375702634716/FiveM_GTAProcess_2026-04-14_21-11-11_369.png?ex=69e303f9&is=69e1b279&hm=046ef2655a46702d502fd81720028606d7ac9aec767c8c4994db5a242f60fd83&=&format=webp&quality=lossless&width=1421&height=800" alt="Photo 1"></div>
            <div class="photo-placeholder"><img src="https://media.discordapp.net/attachments/1477304401155588096/1493644375119368343/FiveM_GTAProcess_2026-04-14_20-51-33_172.png?ex=69e303f9&is=69e1b279&hm=bc4de4b353ea648ff804aae7d20a68a0d882f394a393ab4e727cb402f7c5bc67&=&format=webp&quality=lossless&width=1421&height=800" alt="Photo 2"></div>
        </div>
    </div>

    <div style="text-align: center; background: #222; padding: 20px; border-radius: 10px;">
        <p><strong>หมายเหตุ:</strong> การตัดสินของกรรมการถือเป็นที่สิ้นสุด ขอให้หมอทุกท่านรักษาน้ำใจนักกีฬา และใส่กันให้ยับในเวลาที่กำหนด!</p>
    </div>

</div>

<div class="footer">
    <p>&copy; 2024 Hospital Sports Day - Medical Staff Only</p>
</div>

</body>
</html>
