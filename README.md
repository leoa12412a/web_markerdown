# Web_markerdown

# 1.PHP

 明碼加密1:不可解密 只可以判斷

   // 會員註冊時, 將 $hash 寫入到 mysql 的 user.user_password 
    $hash = password_hash("123456", PASSWORD_DEFAULT);


     // 會員登入時, 將 $hash 從 user.user_password
     $bool = password_verify('1234256', $hash);
     if($bool) {
      // success
     } else {
      // fail
     }


 明碼加密2:可以加解密(md5)
   
   https://github.com/leoa12412a/web_markerdown/blob/master/%E5%8A%A0%E5%AF%86%E8%A7%A3%E5%AF%86.txt
   
   
# 2.SEVER : centos

  建立mysql UI
   
