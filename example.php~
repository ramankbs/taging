<?php
 
   include_once('CBC_functions.php');
   include_once('Blowfish.php');




   //NOTE: This is the key or password for encrypting your files.
   // THIS MUST BE 8 CHARACTERS
  echo  $key = "12345678";
   
   //This is the text to be encrypted
   $plaintext = "now is the time for all good men to come to the aid of their country";

   //This is a blowfish cipher object
   $cipher = new Crypt_Blowfish($key); 

   //This is the encrypted text
   $ciphertext = Eencrypt($cipher,$plaintext);

  
   echo  "raman".$ciphertext."\n"; 

   //This is the Decrypted text.
   $plaintext = Edecrypt($cipher,$ciphertext);  

   echo  $plaintext."\n";

?>
