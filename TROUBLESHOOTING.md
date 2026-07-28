# Troubleshooting

**Known Issues**

- Go to `chrome://extensions` and make sure you are using the latest version of the **Speech Translator** extension: `1.0.0`. If you have an older version (and used Chrome Web Store), enable **Developer Mode** in the top right corner and click the **Update** button that appears. Afterward, you can turn off **Developer Mode**.
- **If you are using Chrome and the speech recognition suddenly stopped working**, and you see a "Network Error" when you open the Console Log, try to fully restart your browser (close all windows, including incognito, and open it again). If it starts working again, it means you are experiencing a bug that Google hasn't fully fixed yet. The workaround is to:
   - Update to the latest version of Chrome
   - Go to **Settings** -> **Accessibility**
   - Enable **Live Captions**
   - Delete all language models and then disable **Live Captions**
   - Restart Chrome
- The extension might not work in Microsoft Edge on devices with ARM processors (like newer MacBooks with Apple silicon or Microsoft Surface tablets). Sometimes, using [the Beta or Dev version of the Edge Browser](https://www.microsoft.com/en-us/edge/download/insider?form=MA13FJ) helps resolve this.
- If the speech recognition performs poorly or is unstable with a certain language, try switching your browser and using the extension in [Microsoft Edge](https://www.microsoft.com/edge) or [Google Chrome](https://www.google.com/chrome/).
- If you want to use the extension on Meta websites (facebook.com, instagram.com, whatsapp.com, etc.) and tiktok.com, please start the translation in a popup window or in the side panel (using the buttons to the left of **START**).

---

**Troubleshooting Steps**

1. Make sure you are using the [Google Chrome](https://www.google.com/chrome/) or [Microsoft Edge](https://www.microsoft.com/edge) web browser, version 150 or newer.
2. Try following the setup guide one more time very carefully: 
   - `chrome-extension://jodfjmaiakpnmeddgpeflpafebmlhppn/options.html#instruction#getting-started`
   - `edge://jmiekopdidkclpmpandbfblpefalpldo/options.html#instruction#getting-started`
3. Make sure you have successfully granted audio permissions under **Grant Audio Permission**.
4. Make sure you have successfully passed the following tests: **Test Speech Recognition Engine** and **Check Translation Services Access**. 

   If you didn't pass **Test Speech Recognition Engine** or **Check Translation Services Access**, try disabling your VPN or using a private VPN that has access to Google and Microsoft services, and try again. Using a different supported web browser also usually helps. If that does not resolve it, there is most likely a problem on Google's or Microsoft's end, and the issue should be reported to them directly: [Microsoft Edge Insider](https://techcommunity.microsoft.com/discussions/edgeinsiderdiscussions/web-speech-api-not-working-in-edge-v-147/4514880), [Report Chrome Issue](https://support.google.com/chrome/answer/95315), and [Chromium Bug Tracker](https://issues.chromium.org/issues).

5. **When input is set to "Input Audio Device (Microphone)":** Make sure the correct audio input device is selected. If you are on Windows, set your capture device to **"Default Communication Device"** in the system recording settings and on the `chrome://settings/content/microphone` page. Additionally, please verify that the audio level bars move in your system audio settings when you speak (or play a looped audio).
6. Make sure you have the correct **Speech Language** selected.
7. If the speech is correctly recognized, but the translation doesn't work (and you use **Google Translate (Public)**), try running the **Check Translation Services Access** test on the Instructions page again right after you experience the issue:
   - Additionally, you can open [Google Translate](https://translate.google.com/) and make sure you don’t have a CAPTCHA prompt and that translation works on that page. If you experience issues, try disabling your VPN or using a private VPN that has access to Google or Microsoft services, and try again.
   - An alternative option (which is also useful if speech recognition works fine but translation is unstable) is to set up and use the **Google Translate (Script)** method. You can find the instructions on the extension page:
     - `chrome-extension://jodfjmaiakpnmeddgpeflpafebmlhppn/options.html#instruction#google-translate-script`
8. If you still experience issues with the extension, feel free to [create an issue](https://github.com/speech-translator-ext/speech-translator-readme/issues). Please include:
   - Your OS
   - Web browser name and version
   - The extension version
   - Your audio setup method
   - Selected **Speech Language**, **Translation Service**, and **Translate To Language**
   - Listening method: **iFrame**, **Popup**, or **Side Panel**. For the **iFrame** method, please specify the website where you started listening
   - A description of the issue
   - Steps to reproduce the issue
   - Errors from the extension (if any): `chrome://extensions/?errors=jodfjmaiakpnmeddgpeflpafebmlhppn` (you might need to enable **Collect errors** first here: `chrome://extensions/?id=jodfjmaiakpnmeddgpeflpafebmlhppn`)
   - Errors from your browser's Console Log on the page where you experienced the issue (if any)
9. **If you are a Premium user**, you can find support contact information on the **Profile** page of the extension after logging in.
