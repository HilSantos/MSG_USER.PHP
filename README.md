# MSG_USER.PHP
Criação do msg_user.php

<?php
// Verifica se existe uma mensagem passada via parâmetro GET na URL //
if(isset($_GET['msg'])){
?>
<br>
<p id="menssagem"><?=$_GET['msg']?></p>
<?php
}
?>
