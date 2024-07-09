---
title: DeepLopener for Android | How to use
class: DeepLopener for Android
repository_url: https://github.com/T3aHat/DeepLopenerSeries
---

# How to start
  
1. **Get your [DeepL API_KEY](https://www.deepl.com/en/pro/change-plan#developer)**   
   ![price.png](/assets/images/price.png)  
   _from [deepl.com](https://www.deepl.com/en/pro/change-plan#developer)_  

   If you use DeepL API Free, you can translate text for max 500,000 characters/month.  

2.  **Download [DeepLopener for Android](https://play.google.com/store/apps/details?id=com.teahat.deeplopener)**  
<a href="https://play.google.com/store/apps/details?id=com.teahat.deeplopener" target="_blank" rel="noopener noreferrer"><img src="https://play.google.com/intl/ja/badges/static/images/badges/en_badge_web_generic.png" alt="GooglePlay" width="200px" ></a>

3.  **Input your API_KEY and change a setting of API version on settings page** ![settings.png](/assets/images/outline_settings_black_24dp.png)  
    - If you don't have API_KEY and want to try this app, please select `Trial`. Otherwise, select the API version you have.
      - The `Trial` version can translate up to 5000 words per month by Free API, so please do not translate confidential information.

<img src="/assets/images/settings_api.png" alt="settings_api.png" style="width: 50%;">


# How to translate
  
## Normal mode
<img src="/assets/images/normalMode.png" alt="normalMode.png" style="width: 50%;">

1. Execute this app
2. Input text you want to translate in the textarea above
3. Select the target language in the spinner
    - For example, if you want to translate English text into Japanese one, select `日本語`
4. Tap `TRANSLATE` button  

- ![outline_close_black_24dp.png](/assets/images/outline_close_black_24dp.png): flush text in the input and output textarea  
- ![outline_content_paste_black_24dp.png](/assets/images/outline_content_paste_black_24dp.png): paste text in the clipboard and translate automatically
- ![outline_content_copy_black_24dp.png](/assets/images/outline_content_copy_black_24dp.png): copy text in the output textarea

## ContextMenu mode
This mode can be used in some applications like GoogleChrome, FireFox, etc.

1. Select text you want to translate like below  
<img src="/assets/images/select.png" alt="select.png" style="width: 50%;">
2. Tap `DeepLopener`
    - `DeepLopener` may be hidden in some environments. If so, check `︙` to find it.
    - If you can't find it (Ex. this happens in Gmail app), We are so sorry but you can't use this mode by technical issue.
3. The translation window will appear on top of the opening application  
<img src="/assets/images/select_trans.png" alt="select_trans.png" style="width: 50%;">


## Share mode
If you can't use ContextMenu mode, please try this mode.

1. Select text you want to translate like below  
<img src="/assets/images/share.png" alt="share.png" style="width: 50%;">
2. Tap `Share` → `DeepLopener`  
<img src="/assets/images/share_deepl.png" alt="share_deepl.png" style="width: 50%;">
4. The translation window will appear on top of the opennig application

## Notification mode
You can't find share or ContextMenu in some applications (Ex. long tap to copy text in twitter app).  
This mode may help your experiences.  

※ This mode is beta version now. I found a problem that notification will be removed when I close the history of this app on MIUI devices.  

1. Switch `Tap to Translate` to enabled.  
<img src="/assets/images/tap_settings.png" alt="tap_settings.png" style="width: 50%;">
2. Notification will appear  
<img src="/assets/images/notify.png" alt="notify.png" style="width: 50%;">
3. Tap it and the translation result of clipboard text will appear on top of the opennig application