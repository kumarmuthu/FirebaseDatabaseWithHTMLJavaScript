# FirebaseDatabaseWithHTMLJavaScript
HTML JavaScript to Write and Read on the Google Firebase
***
**Steps to go:**

The lightweight project can use this logic to validate the username and password or we can monitor the web app's stored data.  


**Firebase:**

**Step-1:**
Firebase login with google account.
Create a new firebase project and web apps then continue the below steps.

**Step-2:**
Go to Build ==> Realtime Database.

**Step-3:**
Click ==>Data field to store the data in key-value format.

**Step-4:**
Click ==>Rules, update the rules as per your project requirements (Less security if we set read as true).

**HTML/javascript:**

**Step-5:**
Download the source code from Github: https://github.com/kumarmuthu/FirebaseDatabaseWithHTMLJavaScript

**Step-6:**
Edit your Google firebase web app token, firebase_validation.js lineno:7 const firebaseConfig 

**Step-6.1** Go to project settings ==> go to your web app project.

**Step-6.2** click ==>CDN, copy the firebaseConfig then replace your config to the line as mentioned in the earlier number.

**Step-7:**
Replace your google firebase DB path(I have used a nested path) with wherever seeing this path.
var create_db_table = ref(db, 'ESP32_DB/' + 'ESP32_User_Login_Table/');

**Step-8:**
open the firebase_validation_index.html then execute the read and write operations.

**the end...**

***
**Execution video available on Youtube:** https://www.youtube.com/watch?v=YYh6T4lCxxc

**Email:-** kumarmuthuece5@gmail.com

***
