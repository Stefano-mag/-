<!DOCTYPE html>
<html lang="bg">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Продукти с намалени цени в магазин "Стефано"</title>
</head>
<body>
    <h1>Качете промоционален продукт</h1>
    <form action="upload.php" method="post" enctype="multipart/form-data">
        <label for="productImage">Качете снимка на продукта:</label>
        <input type="file" name="productImage" id="productImage" required>
        
        <label for="productTitle">Заглавие на продукта:</label>
        <input type="text" name="productTitle" id="productTitle" required>
        
        <label for="productDescription">Описание на продукта:</label>
        <textarea name="productDescription" id="productDescription" required></textarea>
        
        <input type="submit" value="Качване">
    </form>
</body>
</html>
