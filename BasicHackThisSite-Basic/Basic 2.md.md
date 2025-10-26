📅 Date: 2025-10-19

---

#### 🧩 Problem
Network Security Sam set up a password protection script. He made it load the real password from an unencrypted text file and compare it to the password the user enters. However, he neglected to upload the password file...

#### 📸 Screenshot
![[Pasted image 20251019194528.png]]

#### 📝 Notes
- We took a look at the code again and we found *missions/basic/2/index.php* 
- Changed out the url and added *index.php* then clicked submit and moved to the next room
- Quick run down so Sam put the password into *index.php* file so when you advance it using the submit button it sends the password to the server. If we are not in *index.php* it will return a error

---
#### 🔐 Flag
/missions/basic/2/index.php
