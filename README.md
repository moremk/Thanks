
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Thank You</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body{
      min-height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      //background:linear-gradient(135deg,#2563eb,#7c3aed);
      background-color:#10233f;
      padding:20px;
    }

    .card{
      width:100%;
      max-width:560px;
      background:#fff;
      border-radius:24px;
      padding:45px 35px;
      text-align:center;
      box-shadow:0 25px 50px rgba(0,0,0,.18);
      animation:pop .6s ease;
    }

    @keyframes pop{
      from{transform:translateY(20px);opacity:0}
      to{transform:translateY(0);opacity:1}
    }

    .check{
      width:90px;
      height:90px;
      margin:0 auto 25px;
      border-radius:50%;
      background:linear-gradient(135deg,#22c55e,#16a34a);
      display:flex;
      align-items:center;
      justify-content:center;
      color:#fff;
      font-size:42px;
      box-shadow:0 10px 25px rgba(34,197,94,.35);
    }

    h1{
      color:#1e293b;
      font-size:34px;
      margin-bottom:12px;
    }

    p{
      color:#64748b;
      font-size:16px;
      line-height:1.7;
      margin-bottom:30px;
    }

    .info{
      background:#f8fafc;
      border:1px solid #e2e8f0;
      border-radius:14px;
      padding:18px;
      margin-bottom:30px;
    }

    .info h3{
      color:#334155;
      margin-bottom:8px;
      font-size:18px;
    }

    .btn{
      display:inline-block;
      text-decoration:none;
      background:linear-gradient(135deg,#2563eb,#7c3aed);
      color:#fff;
      padding:14px 28px;
      border-radius:50px;
      font-weight:600;
      transition:.3s;
    }

    .btn:hover{
      transform:translateY(-2px);
      box-shadow:0 12px 24px rgba(37,99,235,.3);
    }

    .footer{
      margin-top:25px;
      color:#94a3b8;
      font-size:13px;
    }

    @media (max-width:480px){
      .card{
        padding:35px 22px;
      }
      h1{
        font-size:28px;
      }
      p{
        font-size:15px;
      }
    }
  </style>
</head>

<body>

  <div class="card">

    <div class="check">✓</div>

    <h1>Thank You!</h1>

    <p>
      Your information has been successfully submitted.
      Our team has received your inquiry and will contact you as soon as possible.
    </p>

  </div>

</body>
</html>
