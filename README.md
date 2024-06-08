<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PERALTA Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #716666;
        }
        header {
            background-color: #333;
            color: #fffefe;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #746f6f;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }
        .form-group button {
            padding: 10px 20px;
            background-color: #333;
            color: #f3f0f0;
            border: none;
            cursor: pointer;
        }
        .friends-list {
            list-style-type: none;
            padding: 0;
        }
        .friend-item {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }
        .friend-item img {
            border-radius: 50%;
            margin-right: 10px;
        }
        .friend-item .friend-info {
            display: flex;
            flex-direction: column;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My PERALTA Webpage</h1>
</header>

<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Me</a></li>
        <li><a href="#logout">Log-out</a></li>
    </ul>
</nav>

<div class="container" id="home">
    <h2>Home Page</h2>
    <h3>Friends List</h3>
    <ul class="friends-list">
        <li class="friend-item">
            <img src="https://scontent.fcrk1-3.fna.fbcdn.net/v/t39.30808-6/429561266_1575225813228963_919333474236652592_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGzHafT0eVteR-O-qpKzRlD-Aj_4-ZDhkL4CP_j5kOGQhfd49ELVQHmODi5blMByB4WL0kM50k_dWeLfUTW6ft2&_nc_ohc=m-T6KEYVgusQ7kNvgH0ycVS&_nc_ht=scontent.fcrk1-3.fna&oh=00_AYDoTrgoKMlBAkpyiCLa68ANVh8SM1mwtNKPaqhFCIcRxQ&oe=6669FAA2" alt="Friend 1" width="50" height="50">
            <div class="friend-info">
                <strong>Friend 1</strong>
                <span>P-jay Peralta</span>
            </div>
        </li>
        <li class="friend-item">
            <img src="https://scontent.fcrk1-1.fna.fbcdn.net/v/t39.30808-6/441932197_1166630178101715_8496142221495110948_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGQHd5EXlsorZmVPGpUiDR7n0mfvqdQ0umfSZ--p1DS6cHUaWwZn6pGwwLRXuhqxb4nPLsadHzyDS1Ss9Tj0s3X&_nc_ohc=8NmUVpvVHwoQ7kNvgF2np6G&_nc_ht=scontent.fcrk1-1.fna&oh=00_AYC2-W97AudQrNMH_nJ4qkTGjWg-cvt-Ga9-1xES1li38Q&oe=666A166F" alt="Friend 2" width="50" height="50">
            <div class="friend-info">
                <strong>Friend 2</strong>
                <span>Ayam Rosario</span>
            </div>
        </li>
        <li class="friend-item">
            <img src="https://scontent.fcrk1-4.fna.fbcdn.net/v/t39.30808-1/437172601_3712716159054927_4427575096885231969_n.jpg?stp=dst-jpg_p200x200&_nc_cat=111&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHX28ZpHbR6EuEDwRrrhuFovbLTIuTV4qe9stMi5NXip1XXe6IILiy6FxfeRJwHkFpEYtCsGMqQ4kYBiCll7V9c&_nc_ohc=Xyk9swS7-SEQ7kNvgHZNKYQ&_nc_ht=scontent.fcrk1-4.fna&oh=00_AYDeUhuYt6Gv2htWzY1ilMsOgNnH0WcQ6JReoneNNrFWPw&oe=666A038C" alt="Friend 3" width="50" height="50">
            <div class="friend-info">
                <strong>Friend 3</strong>
                <span>Dinalyn Miranda</span>
            </div>
        </li>
        <li class="friend-item">
            <img src="https://scontent.fcrk1-4.fna.fbcdn.net/v/t39.30808-1/278747121_702863500955001_1057541797979021663_n.jpg?stp=dst-jpg_p200x200&_nc_cat=103&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeH1lTAtteYbtffAb4EvUE07_gl5N5SUweT-CXk3lJTB5KOr9QXiBPJAO-ekgciduFH48fUJFgX9cqOiUwS7xQkt&_nc_ohc=FpXtnulH1ToQ7kNvgEkQzNS&_nc_ht=scontent.fcrk1-4.fna&oh=00_AYBuLuuwBcO4BVFObRMK9NxBLJ4zeuBvRvqEnO9CnmQqbA&oe=666A0758" alt="Friend 4" width="50" height="50">
            <div class="friend-info">
                <strong>Friend 4</strong>
                <span>Mij Bitao</span>
            </div>
        </li>
        <li class="friend-item">
            <img src="https://scontent.fcrk1-1.fna.fbcdn.net/v/t39.30808-6/344759948_755994356310471_5091015743367331445_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeF78po0K4LLB8h-qnltie_r4yJ3HQaC4GDjIncdBoLgYOJB1mhNj7eLfm77ejgRnK47VKTYyaFkj14zD1ZPu4mP&_nc_ohc=woWVQy7-EIsQ7kNvgGgylgC&_nc_ht=scontent.fcrk1-1.fna&oh=00_AYA29RTCZOTFZFI3Ar1Kjm_C-9HaGEiSEs50L2k5kAANZw&oe=6669EDC9" alt="Friend 5" width="50" height="50">
            <div class="friend-info">
                <strong>Friend 5</strong>
                <span>Karl Davin Real</span>
            </div>
        </li>
    </ul>
</div>

<div class="container" id="about" style="display: none;">
    <h2>About Me</h2>
    <div>
        <h2>JOHN RAY A. PERALTA</h2>
        <h3>TUROD NARVACAN ILOCOS SUR</h3> 
        <h3>09275803869</h3>
        <h3>johnrayperalta22@gmail.com</h3>
        <p>Objectives:To be able have entry job level where I can apply my knowledge, potentials and other skills and learn and grow professionally with it.</p>
        <p>PERSONAL INFORMATION: DATE OF BIRTH: July 22 2003, AGE: 21, CIVIL STATUS: Single, HEIGHT: 5’6, WEIGHT: 55, GENDER: Male, RELIGION: Roman Catholic</p>
        <p>EDUCATIONAL ATTAINMENT: PRIMARY: Turod elementary school Turod narvacan Ilocos sur</p>
        <p>SECONDARY: Narvacan National Central High School –JHS Paraton Narvacan Ilocos sur</p>
        <P>TERTIARY: Ilocos sur polytechnic state college – Main campus San nicolas Candon city</P>
        <p>Skills: Gaming</p>
        <p>REFERENCES: FRANCISCO RAMIREZ
            SK Chairman
            09937537452</p>
    </div>
</div>

<div class="container" id="login" style="display: none;">
    <h2>Log-in</h2>
    <form>
        <div class="form-group">
            <label for="login-email">Email:</label>
            <input type="email" id="login-email" name="login-email">
        </div>
        <div class="form-group">
            <label for="login-password">Password:</label>
            <input type="password" id="login-password" name="login-password">
        </div>
        <div class="form-group">
            <button type="submit">Log-in</button>
        </div>
    </form>
</div>

<div class="container" id="signup" style="display: none;">
    <h2>Sign-Up</h2>
    <form>
        <div class="form-group">
            <label for="signup-name">Name:</label>
            <input type="text" id="signup-name" name="signup-name">
        </div>
        <div class="form-group">
            <label for="signup-email">Email:</label>
            <input type="email" id="signup-email" name="signup-email">
        </div>
        <div class="form-group">
            <label for="signup-password">Password:</label>
            <input type="password" id="signup-password" name="signup-password">
        </div>
        <div class="form-group">
            <button type="submit">Sign-Up</button>
        </div>
    </form>
</div>

<script>
    document.querySelector('nav ul li a[href="#home"]').addEventListener('click', function() {
        document.getElementById('home').style.display = 'block';
        document.getElementById('about').style.display = 'none';
        document.getElementById('login').style.display = 'none';
        document.getElementById('signup').style.display = 'none';
    });

    document.querySelector('nav ul li a[href="#about"]').addEventListener('click', function() {
        document.getElementById('home').style.display = 'none';
        document.getElementById('about').style.display = 'block';
        document.getElementById('login').style.display = 'none';
        document.getElementById('signup').style.display = 'none';
    });

    document.querySelector('nav ul li a[href="#logout"]').addEventListener('click', function() {
        document.getElementById('home').style.display = 'none';
        document.getElementById('about').style.display = 'none';
        document.getElementById('login').style.display = 'block';
        document.getElementById('signup').style.display = 'none';
    });

    document.getElementById('login').addEventListener('submit', function(event) {
        event.preventDefault();
        document.getElementById('home').style.display = 'block';
        document.getElementById('about').style.display = 'none';
        document.getElementById('login').style.display = 'none';
        document.getElementById('signup').style.display = 'none';
    });

    document.getElementById('signup').addEventListener('submit', function(event) {
        event.preventDefault();
        document.getElementById('home').style.display = 'block';
        document.getElementById('about').style.display = 'none';
        document.getElementById('login').style.display = 'none';
        document.getElementById('signup').style.display = 'none';
    });
</script>

</body>
</html>
