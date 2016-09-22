#### Encryption & Decryption With a Key
```
 var input = "hello world!";
 var key = Guid.NewGuid().ToString();
 var en = Security.Encrypt(input, key);
 var de = Security.Decrypt(en, key)
 
```