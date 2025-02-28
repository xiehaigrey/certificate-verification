<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CertificateVerification</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
        }
        .container {
            border: 2px dashed green;
            padding: 20px;
            display: inline-block;
        }
        .quit-btn {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            background-color: grey;
            color: white;
            border: none;
            cursor: pointer;
        }
        .logo {
            width: 200px;
            margin-bottom: 20px;
        }
        .footer {
            margin-top: 30px;
            font-size: 14px;
            color: gray;
        }
    </style>
</head>
<body>
    <img src="https://lh6.googleusercontent.com/proxy/Iq8TCFFRl_4Jn_2May1wD2DIdjYOho8DnIdvf6hX7WyZ2VXQSrQf-m5bFkIWXj_F4o3i1gn83tJgm6je3u9ZnWeJFtn11agsSJhc-sbW4O2QDzQ" 
         alt="TEFL Logo" class="logo">

    <h1>QR Certification Verification</h1>
    <div class="container">
        <h2>Certificate Found</h2>
        <p><strong>Name:</strong> Antypov Serhii</p>
        <p><strong>Qualification Achieved:</strong><br>The Master 150 Hour TEFL/TESOL Certification</p>
        <p><strong>Award Date:</strong> 09/16/2024</p>
    </div>
    <br>
    <button class="quit-btn" onclick="closeWindow()">QUIT</button>

    <div class="footer">
        Copyright © AmericanTEFLLink
    </div>

    <script>
        function closeWindow() {
            window.close();
        }
    </script>
</body>
</html>
