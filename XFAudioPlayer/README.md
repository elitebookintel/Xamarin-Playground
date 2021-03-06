Playing Audio with the MediaManager Plugin for Xamarin.Forms!
==============
Let me show you how to play Audio in Xamarin.Forms across Android, iOS and Windows UWP using the super easy plug and play MediaManager Plugin! :wink:

Blog post: https://theconfuzedsourcecode.wordpress.com/2020/06/28/playing-audio-with-the-mediamanager-plugin-for-xamarin-forms/

It's easy as,
```csharp
var audioUrl = "https://ia800605.us.archive.org/32/items/Mp3Playlist_555/Daughtry-Homeacoustic.mp3";
await CrossMediaManager.Current.Play(audioUrl);
```

In this little demo, I've explored:
- Playing Audio in a Music Player style
- Queueing the Audio playlist
- Loading local Audio files 
- Maintain Audio playback even during app backgrounding/minimizing/lock screen

Here'a this awesomeness in action:  <br /><br />
iOS: <br /><br />
<img src="/XFAudioPlayer/screenshots/Full Functionality iOS.gif" width="203"/> <img src="/XFAudioPlayer/screenshots/Home Page iOS.png" width="203"/> <img src="/XFAudioPlayer/screenshots/Audio List Page iOS.png" width="203"/> <br />

Android: <br /><br />
<img src="/XFAudioPlayer/screenshots/Full Functionality Android.gif" width="203"/> <img src="/XFAudioPlayer/screenshots/Home Page Android.png" width="203"/> <img src="/XFAudioPlayer/screenshots/Audio List Page Android.png" width="203"/> <br />

UWP: <br /><br />
<img src="/XFAudioPlayer/screenshots/Full Functionality UWP.gif" width="203"/> <img src="/XFAudioPlayer/screenshots/Home Page UWP.png" width="203"/> <img src="/XFAudioPlayer/screenshots/Audio List Page UWP.png" width="203"/> <br />

Loading local Audio files in (iOS, Android, UWP): <br /><br />
<img src="/XFAudioPlayer/screenshots/File Picking iOS.gif" height="425"/> <img src="/XFAudioPlayer/screenshots/File Picking Android.gif" height="425"/> <img src="/XFAudioPlayer/screenshots/File Picking UWP.gif" height="425"/> <br />

Continous playback activity:
| Android  | UWP Windows |
| ------------- | ------------- |
| <img src="/XFAudioPlayer/screenshots/Android Status Bar.png" height="425" /> <img src="/XFAudioPlayer/screenshots/Android Lock Screen.png" height="425"/> | <img src="/XFAudioPlayer/screenshots/UWP Windows Desktop Preview Player.png" height="212.5" /> <br /><img src="/XFAudioPlayer/screenshots/UWP Lock Screen.png" height="212.5" />|
