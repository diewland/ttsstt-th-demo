# Web Speech API Demo for Thai

* Speech-to-Text - https://diewland.github.io/ttsstt-th-demo/stt/
* Text-to-Speech - https://diewland.github.io/ttsstt-th-demo/tts/

### Install Thai TTS Engine for Win10

Follow steps below

https://support.office.com/en-us/article/d5a6b612-b3ae-423f-afa5-4f6caf1ec5d3

If new installed TTS language not found, mod some regedit

```
Export installed languages from

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Speech_OneCore\Voices\Tokens
to
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Speech\Voices\Tokens
```

### TODO
* Android STT duplicate phrases - https://stackoverflow.com/questions/35112561/speech-recognition-api-duplicated-phrases-on-android

### References
* https://github.com/w3c/speech-api
* https://www.google.com/intl/en/chrome/demos/speech.html
* https://hacks.mozilla.org/2016/01/firefox-and-the-web-speech-api/
* https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API/Using_the_Web_Speech_API
* https://mdn.github.io/web-speech-api/speak-easy-synthesis/
