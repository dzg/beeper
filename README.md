# Beeper Bits

This is just an assortment of Beeper enhancements/tricks/etc.

1. [Elganter Theme](https://github.com/dzg/beeper/blob/main/README.md#elganter-theme)
1. [How to change conversation (room) name (desktop)](https://github.com/dzg/beeper/blob/main/README.md#how-to-change-conversation-room-name-desktop)

## 1. Eleganter Theme

First, a more elegant (IMHO) theme for the desktop client: https://github.com/dzg/beeper/blob/main/dzg-beeper-eleganter-theme.css

This should work with both Dark and Light themes.

Just copy the source, go to **Settings > Appearance,** paste into the **Custom CSS** box, and click **Apply.**

### Features:

*   Flatter. No borders.
*   Sexier 'Spacebar'
*   Muted rooms: indicator + dimming
*   Less obtrusive unread indicator
*   Full width date separators
*   No 'Send' text, just ▶
*   Bigger monospace text areas in prefs
*   Different fonts for UI and Messages
*   No purple gradient

### Screenshots:

Search / Spacebar — now even flatter!

<img width="314" alt="image" src="https://user-images.githubusercontent.com/466557/157182325-efee82c4-9fe4-41e9-b6df-4399ee2149dd.png"> <img width="316" alt="image" src="https://user-images.githubusercontent.com/466557/157182381-08613180-1a27-4991-b283-4e0ed7253ca6.png">



Muted room:

<img width="326" alt="image" src="https://user-images.githubusercontent.com/466557/156913308-ec4a0c9a-eefb-4506-9a57-b72358217fc7.png"> <img width="352" alt="image" src="https://user-images.githubusercontent.com/466557/156913846-733741c6-5be6-4c74-875c-cb89a8f69c1c.png">


Date separator:

<img width="813" alt="image" src="https://user-images.githubusercontent.com/466557/156913424-ed79623b-14f7-4729-b43e-fe7847ac0d68.png"> <img width="785" alt="image" src="https://user-images.githubusercontent.com/466557/156913864-9ddfa219-299d-4b90-a5bf-00e485d839cf.png">


Unread:

<img width="362" alt="image" src="https://user-images.githubusercontent.com/466557/156913453-43cf7e07-80b5-42d2-b7bb-bc881a3581ca.png"> <img width="357" alt="image" src="https://user-images.githubusercontent.com/466557/156913873-e2458e14-750f-4346-b3f4-750730e83ab0.png">


Send field/button:

<img width="760" alt="image" src="https://user-images.githubusercontent.com/466557/156913500-28586e97-109e-4c3d-a6bd-583cec5c910a.png"> <img width="751" alt="image" src="https://user-images.githubusercontent.com/466557/156913888-17ff212d-9866-4fc1-808a-8a17a33dccf6.png">


No gradient:

<img width="551" alt="image" src="https://user-images.githubusercontent.com/466557/156913511-32e6e710-343e-40b2-bf83-8873ab7be889.png"> 






## 2. How to change conversation (room) name (desktop)

_This may not work on some chats, especially group chats._

1.  From **Room Info** icon (top right corner, little “i”), go to **Chat Settings >** **Advanced > Open DevTools > Explore Room State**
2.  Click **m.room.name**
3.  Click **Edit**
4.  In the **Event Content** panel, edit the text after `"name:"` to whatever you wish (see screenshot below.)
5.  Click **Send**
6.  _Et voila!_

<img width="551" src="https://user-images.githubusercontent.com/466557/156913619-ebde5fb1-5629-49cf-a845-da9b35805196.png">
