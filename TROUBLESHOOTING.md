# Troubleshooting

1. Try to follow the audio setup guide one more time with extra attention and make sure your settings are correct.
2. Make sure your audio source is set up correctly and verify the audio level bars change in your system audio settings.
3. Click **Grant Audio Permission** one more time and make sure the correct audio input device is selected.
4. Make sure you have the correct **Speech Language** selected.
5. Make sure you have access to speech recognition services.
   
   - For **Google Chrome**: https://www.google.com/intl/en/chrome/demos/speech.html
   - For **Microsoft Edge**: https://speech.microsoft.com/portal/speechtotexttool

Choose your speech language on the page and choose the audio source by clicking the microphone icon on the right side of the address bar. If recognized text is not displaying, it may be caused by network restrictions. You can try to disable VPN or use a private VPN that has access to Google and Microsoft services and try again.

4. If the text gets correctly recognized, then you can check that you have access to **Google Translate** services. Try to open [Google Translate](https://translate.google.com/), make sure you don’t have captcha and the translation works on this page. If you experience some issues, you can try to disable VPN or use a private VPN that has access to Google or Microsoft services and try again. An alternative option and it is also useful if speech recognition works fine, but translation works unstable is to set up and use **Google Translate (Script)** method. You can find the instruction on the extension page:

    - *chrome-extension://jodfjmaiakpnmeddgpeflpafebmlhppn/options.html#instruction#google-translate-script*
 
6. If you still experience issues with the extension, feel free to [create an issue](https://github.com/speech-translator-ext/speech-translator-readme/issues). Please include:
   - Your OS
   - Web browser name and version
   - The extension version
   - Your audio setup method
   - The issue description
   - Steps to reproduce the issue
   - Errors from the extension (if you have any): *chrome://extensions/?errors=jodfjmaiakpnmeddgpeflpafebmlhppn* (you might need to enable **Collect errors** first here: chrome://extensions/?id=jodfjmaiakpnmeddgpeflpafebmlhppn )
   - Errors from your browser Console Log on the page where you experience the issue (if you have any)
