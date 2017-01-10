發生臉書登入自動登出, 後來 enzo 追 FB SDK, 發現是去讀 php.ini 裡面的 session 設定<br />   
不是去讀 laravel session 的設定, 所以在用別人的 SDK 時, php.ini裡面的 session 也要設定跟 laravel 裡面的一樣.
