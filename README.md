**![JamDroidFirechat logo](https://yydsig.dm2303.livefilestore.com/y3p4l_lCAx3W9zg5f9yZlsGV0gy_U_eOSOnn1IP2bPIc9dGV3mQlIJxuCYEZphcstV3w-82e3gR_6hk1SzSKR6h6VeBNbnLH4YhoL_XI3E7eGTqIFmmTm6NAGDgLEZsvC4Ria1mrbSCvsm-cqUtqfuKEbdNEgvwdLH5qqe5Wsr3N78/jamdroid.png?psid=1)JamDroidFirechat**
==================
[![Google Play Link](https://wiawzw.dm2303.livefilestore.com/y3mtKZ3wP8EEfBG_bOMV6KINTP_9T4PvSHSoQHHfUSG7cSncEakPeCK0nDU1vXDXX0FLq_8DQAaIMXPGGUwcS7eOMWzDtxBNgcsotgeT2kF05LyC2IgHNRqHwBRruP4c3U6-_wrxQmFWUJjKtr-GbwzO2zvFhsFcuRjOIszTX5SUNU/google_play_logo.png?psid=1)
](https://play.google.com/store/apps/details?id=com.ygorcesar.jamdroidfirechat)
Aplicação Android, demostrando o uso do Firebase com Android em uma aplicação de chat com troca de mensagens.

Configurando Aplicação
-------------

 - Criar conta no [Firebase](https://www.firebase.google.com)
 - Após criar conta, criar novo App Firebase
 - Habilitar no App criado, login com Google e Facebook, em seguida adicionar Google Client ID, Google Client Secret, Facebook App Id e Facebook App Secret
 - Atualizar [gradle.properties](https://github.com/ygorcesar/JamDroidFireChat/blob/master/gradle.properties)
- Atualizar com seu Facebook App ID: `FacebookAppIdJamdroid="1111111111111111"`
-  Atualizar com sua Key do Firebase Cloud Message: `FirebaseCloudMessageKey="key=1111111111111111111111111111111111"`
- Gerar  google-services.json em **Firebase Console->Select Project->Settings/Configurações** e colocar-lo na pasta **app** do projeto android.
 - Firebase Documentation and Guide: https://firebase.google.com/docs/android
 - Google Login Guide: https://developers.google.com/identity/sign-in/android/start
 - Facebook Login Guide: https://developers.facebook.com/docs/facebook-login/android

App
-------------

Aplicação Android de chat integrado com Firebase para troca de mensagens em tempo real, com chat global e direct com usuários registrados.

 - Slide apresentação [Android Jam 2 - Firebase e Android](http://pt.slideshare.net/YgorCsar/aplicaes-android-realtime-com-firebase)
 - Website Android Jam Aracaju: http://android.gdgaracaju.com.br/
   
 ![Login Screen](https://xydsig.dm2303.livefilestore.com/y3m0WHoMivZCPkTe3yQ7Ul5nYZcjMvw90VSer1ATtOiEpdc1QXcu2W96Rd5hf7G8B__dmoHi3FN1CSqzQ7bGhVnkIOkExsFPzbQ-BDoXOBueF4ItNFWclfLAdXuBssNHcujSNvJP70MWtTo2Kc6RqEf8zXMaNKlXVtMCwcxcXeRJ8A/jamdroid_login.png?psid=1)![Registered Users](https://yiablq.dm2303.livefilestore.com/y3mfA1zN9KKnygG6-Gz9jTmKeDTlQOuzwhMOjipruPo5ZgGsmIJomMdE5S8DjVLsquS0WZ9UhgSjEpuQIdmgfHFI9sZE8o8vR5OUyHnIefvxCmvZtoj1uH9tTm2XToTrdKE0Vb-V_4CrUKskrdKghO2ekRg-m3TDadfa2p1pqPWxVE/jamdroid_main_app.PNG?psid=1)
![Messages](https://ycdsig.dm2303.livefilestore.com/y3mC_n7nBy1DTnKdFfHMtrwuJFgS3xF1J8c_jV8z5Q9HsNR90bBQub_-eqIEu3w7qNG1XMQZ_VOdoLvnHTNs3M8-BPvxkZH5luPxKGqC6SPu8EVL3EBRPqCJn_WijJLnwlq9DSQytBra85OZH7CAtHCwIwSHNBoeilRApj42oF1OyU/jamdroid_messages.png?psid=1)![User Profile](https://xsdsig.dm2303.livefilestore.com/y3mhRtinRsLngb6iCtzb0osU0Asfj9q3GiUfNjKJYuf16YgF0MbO1-0FGGOsBNwPFCpF5fFSId_JyucITo2RR6MrcLaHfJX0IDuv1WUn4TpVQO9iBZ9cuk3rqffsUnLpUU22AiKrl2rJ-sVtJ7xLwti-7jKhrF226dqMc35Pl9kbHo/jamdroid_user.png?psid=1)
