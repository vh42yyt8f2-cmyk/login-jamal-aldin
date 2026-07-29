#<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>تسجيل الدخول</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;

    background-image:
    linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
    url("background.jpg");

    background-size:cover;
    background-position:center;
    background-repeat:no-repeat;
}

.box{
    width:400px;
    background:rgba(0,0,0,.75);
    padding:35px;
    border-radius:20px;
    color:white;
    box-shadow:0 10px 30px rgba(0,0,0,.5);
}

.box h1{
    text-align:center;
    margin-bottom:10px;
}

.box h2{
    text-align:center;
    font-size:18px;
    margin-bottom:25px;
    color:#ddd;
}

label{
    display:block;
    margin-bottom:8px;
}

input{
    width:100%;
    padding:12px;
    border:none;
    border-radius:8px;
    margin-bottom:18px;
    font-size:16px;
}

button{
    width:100%;
    padding:14px;
    border:none;
    border-radius:10px;
    background:#16a34a;
    color:white;
    font-size:18px;
    cursor:pointer;
    transition:.3s;
}

button:hover{
    background:#15803d;
}

</style>

</head>
<body>

<div class="box">

<h1>النصر التقنية</h1>

<h2>صفحة تسجيل الدخول</h2>

<form>

<label>اسم المستخدم</label>
<input type="text" placeholder="أدخل اسم المستخدم" required>

<label>كلمة المرور</label>
<input type="password" placeholder="أدخل كلمة المرور" required>

<button type="submit">تسجيل الدخول</button>

</form>

</div>

</body>
</html>

