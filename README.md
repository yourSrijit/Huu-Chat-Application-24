# Complete Chatting App with MERN Stack | JWT, Socket.io, MongoDB 
[Live Link](https://huuu-chat-app.onrender.com/)

## Here are some preview
---
![Screenshot 2024-07-31 233328](https://github.com/user-attachments/assets/12562438-025f-4952-b3c7-34253b831dfe)
![Screenshot 2024-07-31 233538](https://github.com/user-attachments/assets/346c4795-83b0-4fb7-9631-691c009c2b22)
![Screenshot 2024-07-31 233621](https://github.com/user-attachments/assets/bdd094ce-2110-4829-a3d8-8a7cb605b4a8)
![Screenshot 2024-07-31 233600](https://github.com/user-attachments/assets/81fa2288-f08a-41b5-b83c-978401ae36fd)




---
Install Packages in Backend side
```
npm i express dotenv cookie-parser bcryptjs mongoose sockert.io jsonwebtoken
```

### To Encrypt the password use bycryptjs Package

```
import bcrypt from "bcryptjs";

//Hash password
const salt=await bcrypt.genSalt(10);
const HashPassword=await bcrypt.hash(password,salt);


<!-- For Comparing  -->
const isPasswordCorrect=await bcrypt.compare(password ,user.password || "");
```


