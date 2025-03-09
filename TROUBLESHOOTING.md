# Troubleshooting

**Known issues**

- **It [has been reported](https://github.com/speech-translator-ext/speech-translator-readme/issues/50) that speech recognition engine (Web Speech API) may not work in the Edge Browser starting with version 134 on Windows. If you experience the same issue or if it works on your system, please provide feedback [here](https://github.com/speech-translator-ext/speech-translator-readme/issues/50).**
- If you want to use the extension on the websites that belong to Meta (facebook.com, instagram.com, whatsapp.com, etc.) and tiktok.com, please start the translation in a popup window or in a side panel (buttons on the left side from **START LISTENING**).
- Speech recognition sometimes works poorly in Google Chrome with certain languages (like Japanese). If you experience a such issue, please try to use the extension in [Microsoft Edge](https://www.microsoft.com/edge).
- The extension may not work in the Edge Browser on some versions of Linux and macOS. Sometimes using [the Beta or Dev version of the Edge Browser](https://www.microsoft.com/en-us/edge/download/insider?form=MA13FJ) helps to make it work.
---

**Troubleshooting**

1. Make sure you are using [Google Chrome](https://www.google.com/chrome/) or [Microsoft Edge](https://www.microsoft.com/edge) web browser with version 114+.
2. Try to follow the audio setup guide one more time with extra attention and make sure your settings are correct.
3. Make sure your audio source is set up correctly and verify the audio level bars change in your system audio settings.
4. Click **Grant Audio Permission** one more time and make sure the correct audio input device is selected. Alternatively, you can set the input audio device on this page: `chrome://settings/content/microphone`
5. Make sure you have the correct **Speech Language** selected.
6. Make sure you have access to speech recognition services.
   
   - For **Google Chrome**: https://www.google.com/intl/en/chrome/demos/speech.html
   - For **Microsoft Edge**: https://speech.microsoft.com/portal/speechtotexttool

Choose your speech language on the page and choose the audio source by clicking the microphone icon on the right side of the address bar. If recognized text is not displaying, it may be caused by network restrictions. You can try to disable VPN or use a private VPN that has access to Google and Microsoft services and try again. Also, you can try to use a different supported web browser, usually it helps.

7. If the speech gets correctly recognized, then you can check that you have access to **Google Translate** services.
  - **Check Translation Services Access** on the Instruction page right after you have experienced the issue:
  
    - `chrome-extension://jodfjmaiakpnmeddgpeflpafebmlhppn/options.html#instruction#check-translation-services`

  - Additionally, you can try to open [Google Translate](https://translate.google.com/) and make sure you don’t have captcha and the translation works on this page. If you experience some issues, you can try to disable VPN or use a private VPN that has access to Google or Microsoft services and try again.
  - An alternative option and it is also useful if speech recognition works fine, but translation works unstable is to set up and use **Google Translate (Script)** method. You can find the instruction on the extension page:

    - `chrome-extension://jodfjmaiakpnmeddgpeflpafebmlhppn/options.html#instruction#google-translate-script`
 
8. If you still experience issues with the extension, feel free to [create an issue](https://github.com/speech-translator-ext/speech-translator-readme/issues). Please include:
   - Your OS
   - Web browser name and version
   - The extension version
   - Your audio setup method
   - Selected **Speech language**, **Translation Service**, **Translate To Language**
   - Listening method: **iFrame** (START LISTENING button), **Popup**, **Side Panel**. For **iFrame** method please specify the website where you are starting listening
   - The issue description
   - Steps to reproduce the issue
   - Errors from the extension (if you have any): `chrome://extensions/?errors=jodfjmaiakpnmeddgpeflpafebmlhppn` (you might need to enable **Collect errors** first here: `chrome://extensions/?id=jodfjmaiakpnmeddgpeflpafebmlhppn` )
   - Errors from your browser Console Log on the page where you experience the issue (if you have any)
