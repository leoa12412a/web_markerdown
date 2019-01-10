# Web_markerdown

# 1.PHP

 明碼加密

// 會員註冊時, 將 $hash 寫入到 mysql 的 user.user_password 
 $hash = password_hash("123456", PASSWORD_DEFAULT);
  

  // 會員登入時, 將 $hash 從 user.user_password
  $bool = password_verify('1234256', $hash);
  if($bool) {
   // success
  } else {
   // fail
  }
