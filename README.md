# Trodev_FM!

# Made With
![forthebadge](https://img.shields.io/badge/Android_Studio-5C2D91?style=for-the-badge&logo=android%20studio&logoColor=white)
![forthebadge](https://img.shields.io/badge/Firebase-00000F?style=for-the-badge&logo=firebase&logoColor=white)
![forthebadge](https://img.shields.io/badge/Java-5C2D91?style=for-the-badge&logo=java&logoColor=white)

# Download
[Download Now](https://github.com/zobayerdev/Trodev_FM.git)

## Features
- You can upload music to storage
- You can listen your music from storage
- You can easily modify the program code
- Availability of notifications
- Track covers


## How to setup my application
1. Clone this repository
2. Open with Adroid Studio
3. Create new Firebase project
4. Rename the project package name
5. Add **google-services.json** in /app folder
6. In the Firebase console switch on Storage & Real-time Database
7. Edit the Firebase Storage rules
8. Thank you


# Firebase Storage Rules
```
service firebase.storage {
    match /b/YOUR_APP_ID.appspot.com/o {
        match /{allPaths=**} {
            allow read, write: if true;
        }
    }
}
```
# Firebase Realtime Database Rules
```
{
  "rules": {
    ".read": true,
    ".write": true
  }
}
```

# Contributing
Your contributions are always welcome!

# License
BUBT - [Md. Zobayer Hasan Nayem](https://github.com/zobayerdev/)

# Contact
[![forthebadge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&fs=1&to=zobayers.cse@gmail.com)

<img src="https://user-images.githubusercontent.com/74914169/191067010-99ae89b6-7df9-4134-9865-0551e7945e7f.png" width=25% height=25%>
<img src="https://user-images.githubusercontent.com/74914169/191066597-5dc94882-b679-4fb5-94da-3991df763f0f.jpg" width=25% height=25%>
<img src="https://user-images.githubusercontent.com/74914169/191066586-4f127cad-b2c7-42b2-ad53-41c25c2ca3fd.jpg" width=25% height=25%>
