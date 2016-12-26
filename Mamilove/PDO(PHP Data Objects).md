在寫 PHP 時要知道, 有一個 Class 是 PDO PHP Data Objects, 它是Represents a connection between PHP and a database server. <br />
我們原本 php 5 想要升級到 php 7 <br />
But php5 從資料庫吐出來的, 都是String, 轉乘 php 7 卻變成有 type (ex: int, boolean ... <br />   
所以原本以為要去修改很多 API, 改成傳回正常值,  <br />    
後來很厲害的 dahung 就找到 PDO 這個 class 裡面有參數 PDO::ATTR_STRINGIFY_FETCHES: Convert numeric values to strings when fetching. Requires bool. <br />   
reference : http://php.net/manual/en/pdo.setattribute.php
