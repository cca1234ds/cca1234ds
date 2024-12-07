<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>เว็บไซต์ลงทะเบียน</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>ลงทะเบียน</h1>
        <form id="registrationForm">
            <label for="username">ชื่อผู้ใช้:</label>
            <input type="text" id="username" name="username" required>

            <label for="email">อีเมล:</label>
            <input type="email" id="email" name="email" required>

            <label for="password">รหัสผ่าน:</label>
            <input type="password" id="password" name="password" required>

            <button type="submit">ลงทะเบียน</button>
        </form>
        <div id="message"></div>
    </div>

    <script src="script.js"></script>
</body>
</html>
