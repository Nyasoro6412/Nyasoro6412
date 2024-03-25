- 👋 Hi, I’m @Nyasoro6412
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Nyasoro6412/Nyasoro6412 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor Icecream</title>
    <style>
        *{
            margin: 0;
            padding: 0;
        }
        .icecream{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            width: 100vw;
        }
        .ice{
            background-color: #FF729F;
            width: 100px;
            height: 100px;
            border-radius: 100%;
            position: relative;
        }
        .ice::after{
            content: '';
            position: absolute;
            bottom: 10px;
            left: 0px;
            height: 30px;
            background: #FF729F;
            width: 100px;
            border-radius: 100%;
            z-index: 2;
        }
        .cone{
            margin-top: -20px;
            height: 0px;
            width: 0px;
            border-right: 45px solid transparent;
            border-left: 45px solid transparent;
            border-top: 140px solid #fac559;
            z-index: 1;
        }
    </style>
</head>
<body>
    <div class="icecream">
        <div class="ice"></div>
        <div class="cone"></div>
    </div>
</body>
</html>
