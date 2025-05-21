# MSG_USER.PHP
Criação do msg_user.php

<?php
if(isset($_GET['msg'])){
?>
<br>
<p id="menssagem"><?=$_GET['msg']?></p>
<?php
}
?>
