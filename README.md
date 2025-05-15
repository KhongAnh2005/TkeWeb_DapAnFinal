<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>English-Learning</title>

    <style>
        :root {
            --yellow: #ffe700; 
            --greenlight: #00e56b; 
            --greendark: #00b253; 
            --bluelight: #2fcbff; 
            --bluedark: #2f63ff; 
        }

        * {
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
            padding: 0px;
            margin: 0px;
        }

        .cau1 header {
            width: 100%;
            height: 85px;
            background-color: var(--bluedark);
            display: flex;
            align-items: center;
        }

        .cau1 header .logo {
            margin: 10px 5px 10px 15px;
        }

        .cau1 header .tenWeb {
            margin: 10px;
            border: 2px solid var(--greendark);
            padding: 5px;
            background-color: var(--bluelight);
        }

        .cau1 .logo svg {
            height: 65px;
            weight: 65px; 
        }

        .cau1 .nav {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
            height: 40px;
            background-color: var(--bluelight);
        }

        .cau1 .nav .item {
            margin: 20px;
        }

        .cau1 .nav .item a {
            text-decoration: none;
        }

        .cau1 .nav .item:hover {
            background-color: var(--yellow);
            font-style: italic;
        }

        .cau2 .box {
            display: flex;
            justify-content: space-around;
            width: 100%;
            height: 150px;
            margin: 10px 0px;
        }

        .cau2 .box .item {
            background-color: var(--greenlight);
            border: 2px solid var(--yellow); 
            width: 18%;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .cau2 .advert {
            background-color: var(--bluelight);
            width: 100%;
            height: 200px;
            margin: 10px 0px; 
            border: 2px solid var(--greenlight);
            display: flex;
            justify-content: center;
            align-items: center;
        }
    </style>
</head>
<body>
    <div class="cau1">
        <header>
            <div class="logo">
                <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" aria-label="English Learning Logo">
                    <circle cx="32" cy="32" r="32" fill="#2fcbff"/>
                    <text x="32" y="38" font-size="28" text-anchor="middle" fill="#2f63ff" font-family="Arial" font-weight="bold">EL</text>
                </svg>
            </div>
            <div class="tenWeb">
                Hoc Tieng Anh cung DSTE !
            </div>
        </header>

        <div class="nav">
            <div class="item"><a href="https://www.youtube.com/watch?v=PsVEpKthrcg&list=RDPsVEpKthrcg&start_radio=1">Trang chu</a></div>
            <div class="item">Khoa Hoc</div>
            <div class="item">Dien Dan</div>
            <div class="item">Lien He</div>
        </div>

        <section class="baiviet">
            <h2>Khoá học Ielts dành cho người mới bắt đầu:</h2>
            <p>Như chúng ta đã biết, tiếng anh ngày nay rất hữu dụng và cần thiết cho công việc và học tập của mỗi người, vậy nên trong bài viết này chúng tôi sẽ giới thiệu cho những người mới bắt đầu học tiếng anh khoá học Ielts dành cho người mới bắt đầu - <strong>Ielts 1.0-3.0</strong></p>
            <img src="https://ieltsthetutors.edu.vn/wp-content/uploads/2025/04/lo-trinh-hoc-ielts-tu-0-den-3.0-thumbnail.webp" alt="Khoa hoc Ielts 1.0-3.0">
            <p>Khoa hoc Ielts 1.0-3.0 sẽ dạy kỹ năng nghe nói cơ bản, từ vựng cơ bản, v...</p>
        </section>
    </div>

    <div class="cau2">
        <div class="box">
            <div class="item">item1</div>
            <div class="item">item2</div>
            <div class="item">item3</div>
            <div class="item">item4</div>
        </div>
        <div class="advert">advert</div>
    </div>

    <div class="cau3">
        
    </div>

    <script>
        courses = [
            {
                "ten khoa hoc": "Khoa hoc Ielts 1.0-3.0", 
                "mo ta": "danh cho nguoi moi bat dau", 
                "hoc phi": "4000000 VND", 
                "Thoi gian khai giang": "12/03/2025"
            },

            {
                "ten khoa hoc": "Khoa hoc Ielts 3.0-5.0", 
                "mo ta": "Danh cho nguoi co nen tang tieng anh", 
                "hoc phi": "5000000 VND", 
                "Thoi gian khai giang": "15/3/2025"
            },

            {
                "ten khoa hoc": "Khoa hoc Ielts 5.0-6.5", 
                "mo ta": "Danh cho nguoi co nen tang tieng anh tot", 
                "hoc phi": "6000000 VND", 
                "Thoi gian khai giang": "17/3/2025"
            },

            {
                "ten khoa hoc": "Khoa hoc Ielts 6.5-7.5", 
                "mo ta": "Danh cho nguoi co nen tang tieng anh tot", 
                "hoc phi": "7500000 VND", 
                "Thoi gian khai giang": "20/03/2025"
            }
    ]



    </script>

</body>
</html>
