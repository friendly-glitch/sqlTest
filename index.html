<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>

    <form action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]) ?>" method='post'>
        <input type="text" name="title">
        <input type="text" name="post">
        <input type="submit">
    </form>
    <?php
    var_dump($_POST);
    // var_dump(isset($_POST['title']));
    $title = '';
    $post = '';
    // $isTableEmpty = ($_POST['isTableEmpty'] === NULL) ? $isTableEmpty = true : $isTableEmpty = $_POST['isTableEmpty'];
    // $isSubmit = ($_POST['isSubmit'] === NULL) ? $isSubmit = false : $isSubmit = !$_POST['isSubmit'];
    // $_POST['isSubmit'] = true;
    // var_dump ($isSubmit);
    
    //    if ($_POST['title'] === NULL || $_POST['post'] === NULL) {
    //       echo 'not yet created';
    //      return;
    //   }
    $title = htmlspecialchars($_POST['title']);
    $post = htmlspecialchars($_POST['post']);
    $servername = "localhost";
    $username = "root";
    $password = "";
    $dbName = 'myPostsDb';
    // Create connection
    $conn = new mysqli($servername, $username, $password, $dbName);

    // Check connection
    if ($conn->connect_error) {
        die("Connection failed: " . $conn->connect_error);
    }
    //echo "Connected successfully";
    // prepare and bind
    $stmt = $conn->prepare("INSERT INTO myPosts (title, post) VALUES (?, ?)");
    $stmt->bind_param("ss", $title, $post);
    ////
        $sql = "SELECT * FROM myPosts";
        $result = $conn->query($sql);

        if ($result->num_rows > 0) {
            echo "<table border = 1><tr><th>ID</th><th>Title</th><th>Post</th></tr>";
            // output data of each row
            while ($row = $result->fetch_assoc()) {
                echo "<tr><td>" . $row["id"] . "</td><td>" . $row["title"] . "</td><td> " . $row["post"] . "</td></tr>";
            }
        } else {
            echo "0 results";
        }
    
    //var_dump($_COOKIE);
    if ($title !== '' && $post !== '') {
        $sql = "INSERT INTO myPosts (title, post)
        VALUES ('{$title}', '{$post}')";

        if ($conn->query($sql) === TRUE) {
            //echo "New record created successfully";
            $sql = "SELECT * FROM myPosts";
            $result = $conn->query($sql);
        } else {
            echo "Error: " . $sql . "<br>" . $conn->error;
        }
        var_dump($_POST);
        header("Location: http://phplessons/someTablesProject/index.php");
        // Инициализируем cURL сессию
    }
    //SQL connection
    
    //////
    $stmt->close();
    $conn->close();

    ?>
</body>

</html>