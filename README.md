# Beeper Bits

This is just an assortment of Beeper enhancements/tricks/etc.

## Elganter Theme

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

## How to change conversation (room) name (desktop)

_This may not work on some chats, especially group chats._

1.  From **Room Info** icon (top right corner, little “i”), go to **Chat Settings >** **Advanced > Open DevTools > Explore Room State**
2.  Click **m.room.name**
3.  Click **Edit**
4.  In the **Event Content** panel, edit the text after `"name:"` to whatever you wish (see screenshot below.)
5.  Click **Send**
6.  _Et voila!_

![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/e556795e-5a0b-46f1-9d1d-e4704a2e4685/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220305%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220305T205023Z&X-Amz-Expires=86400&X-Amz-Signature=85fac594c15560647fb3bbe8d8a35eef856cd9be9e2ae31c5b26ca9324f7c502&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)
