# gugudan
<!DOCTYPE html>
<html>
<head>
    <title></title>
</head>
<body>
    <h1>Ex. 사용자가 원하는 구구단 출력하기</h1>
    <form method="POST" action="inputGugudan.php">
        <li>구구단을 보고 싶은 숫자를 입력하고 제출을 누르세요.</li>
        <input type="text" name="input"/><br/>
        <input type="submit" name="answer">
    </form>
<?php
if (isset($_POST['input'])){
    $num = (int)($_POST['input']);
    echo $num."단 입니다.<br/>";
    for($j=1;$j<=9;$j++){
        echo $num." X ".$j." = ".($num*$j)."<br/>";
    }
    echo "<br/>";
}
 
?>
</body>
</html>

![image](https://user-images.githubusercontent.com/93318468/168962320-618ed543-e529-4bae-b9b0-f41fb45c4c03.png)

![image](https://user-images.githubusercontent.com/93318468/168962213-954e8ddd-0005-49ac-9a1d-780c2263ecd1.png)


