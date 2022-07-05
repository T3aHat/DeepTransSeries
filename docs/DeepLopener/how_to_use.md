---
title: DeepLopener | How to use
class: DeepLopener
repository_url: https://github.com/T3aHat/DeepLopener
---

日本語解説記事は [コチラ](https://t3ahat.hateblo.jp/entry/How_to_use_DeepLopener)  
# How to Start

<iframe width="100%" height="400" src="https://www.youtube.com/embed/cHW5yKZlGGQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  
1. **Get your [DeepL API_KEY](https://www.deepl.com/en/pro/change-plan#developer)**   
   ![price.png](/assets/images/price.png)
   If you use DeepL API Free, you can translate text for max. 500,000 characters/month.

2.  **Download [DeepLopener](https://chrome.google.com/webstore/detail/deepl-opener-pro/almdndhiblbhbnoaakhgefcpmbaoljde)**
    <iframe class="embed-card embed-webcard" style="display: block; width: 100%; height: 155px; max-width: 500px; margin: 10px 0px;" title="DeepLopener" src="https://hatenablog-parts.com/embed?url=https%3A%2F%2Fchrome.google.com%2Fwebstore%2Fdetail%2Fdeeplopener%2Falmdndhiblbhbnoaakhgefcpmbaoljde" frameborder="0" scrolling="no"></iframe>

3.  **【Recommend】 Login to Chrome and enable synchronization**  
    This allows you to save your API_KEY with simple obfuscation, but you can use it without logging in. [More details](http://deeplopener.ml/DeepLopener/sync).  
    ![syncon.png](https://github.com/T3aHat/DeepLopener/raw/main/images/syncon.png)  

4.  **Input your API_KEY and change a setting of API version on options page**  
    ![options.png](https://github.com/T3aHat/DeepLopener/raw/main/images/options.png)
    - If you want to use Free version, change to `Free`, otherwise to `Pro`.


# How to Use
![thumb.png](https://github.com/T3aHat/DeepLopener/raw/main/images/thumb.png)  

## Layout-oriented Mode

Click the icon ![icon24.png](https://github.com/T3aHat/DeepLopener/raw/main/icon24.png) in the upper right corner
or right-click without selecting the text,
move the cursor and right-click to translate, and left-click to cancel to select.  
![layoutContextMenu.png](https://github.com/T3aHat/DeepLopener/raw/main/images/layoutContextMenu.png)  
![layout-oriented.gif](https://github.com/T3aHat/DeepLopener/raw/main/images/layout-oriented.gif)  
The selected frame will be translated on layout-oriented mode keeping the original style.  
If you click the icon ![icon24.png](https://github.com/T3aHat/DeepLopener/raw/main/icon24.png) in the right-hand corner and
select `Translate this page`, the whole page contents will be translated like below.  
![pagetrans.gif](https://github.com/T3aHat/DeepLopener/raw/main/images/pagetrans.gif)

## PDF Mode

On PDF, select the text you want to translate and right-click on the text and click on `DeepL:selected_text`.  
![pdfmode.gif](https://github.com/T3aHat/DeepLopener/raw/main/images/pdfmode.gif)  
For sites whose MIME type is `application/pdf` (local PDF files available!), the `transition mode` changes to `PDF mode` and the other modes are disabled.  
You can move the translation frame around freely in Drag-and-Drop, and right-clicking on the translation result frame will remove it.

- To use PDF mode in local PDF files, check "Allow access to file URLs" on options page of this extension like below.
  ![allowAccessToFileURL.png](https://github.com/T3aHat/DeepLopener/raw/main/images/allowAccessToFileURL.png)

## Text-oriented Mode

With the text to be translated selected, press `Ctrl+Shift+K` (`⌘+Shift+K` on mac) twice within 1 second or click the icon ![icno24.png](https://github.com/T3aHat/DeepLopener/raw/main/icon24.png) that appears after selecting the text.  
![text-oriented.gif](https://github.com/T3aHat/DeepLopener/raw/main/images/text-oriented.gif)  
The selected text is highlighted in red first. After traslation , it turns yellow.  
Right-click the translation to display the original text.If you do it again, the letters will be toggled back to translation.  
It is recommended to use this mode separately from the layout-oriented mode because the original layout will be destroyed.

**Shortcuts**  
Several modes can be executed by shortcuts.  
These shortcuts can be edited from `chrome://extensions/shortcuts`  
![shortcuts.png](https://github.com/T3aHat/DeepLopener/raw/main/images/shortcuts.png)  
- Layout-oriented mode: `Ctrl+Shift+L` (`⌘+Shift+L` on mac)
- Text-oriented mode: `Ctrl+Shift+K` (`⌘+Shift+K` on mac) twice within 1 second  


## Transition Mode

Right click on the text you want to translate → Click on `DeepL:selected_text`.  
![openDeepL.gif](https://github.com/T3aHat/DeepLopener/raw/main/images/openDeepL.gif)  
Move to https://www.deepl.com/translator#ja/en/selected_text

# Documents Translation

![doctrans.gif](https://github.com/T3aHat/DeepLopener/raw/main/images/doctrans.gif)

## How to Translate

1. Click <img src="https://github.com/T3aHat/DeepLopener/raw/main/file.png"  height="20px"/> in the upper right corner of the popup window  
![popupDocs.png](https://github.com/T3aHat/DeepLopener/raw/main/images/popupDocs.png)  

2. Select a target language  
![translating.png](https://github.com/T3aHat/DeepLopener/raw/main/images/translating.png)
3. Choose documents you want to translate  
   The following file types and extensions are supported:
- "docx" - Microsoft Word Document
- "pptx" - Microsoft PowerPoint Document
- "htm / html" - HTML Document
- "txt" - Plain Text Document  
- "pdf" - Portable Document Format  
  Please note that in order to translate PDF documents you need to give one-time consent to using the Adobe API via [the account interface](https://www.deepl.com/pro-account/translationSettings).  
  ![PDFTranslationSettings.png](https://github.com/T3aHat/DeepLopener/raw/main/images/PDFTranslationSettings.png)  

  Please check out [the official reference document](https://www.deepl.com/docs-api/translating-documents/uploading/) for details.
4. click `Translate` button and translate!
   Translation status will be shown in `Translation status`.
   - `Date`: Date and time of translation
   - `Name`: File name
   - `Language`: The selected target language
   - `Progress`: Translation progress (is automatically updated at 5-second intervals)
     - `translating`: Now translating. 
     - `done`: Translation completed. Click to download the translated document.
     - `error`: Translation failed. The error will be alerted and removed from `Translation status`.


## Glossaries

### Use a Glossary
1. Select the name of the glossary you want to use  
![selectGlos.png](https://github.com/T3aHat/DeepLopener/raw/main/images/selectGlos.png)  


### Create Glossaries
1. Click <img src="https://github.com/T3aHat/DeepLopener/raw/main/glossary.png"  height="20px"/> in the upper right corner of the popup window  
![popupGlos.png](https://github.com/T3aHat/DeepLopener/raw/main/images/popupGlos.png)  

2. Click `[+]New Glossary`  
![glosTable.png](https://github.com/T3aHat/DeepLopener/raw/main/images/glosTable.png)

3. Input `Glossary Name`, `Language Pair`, `SourceText`, and `TargetText`
4. Click <img src="https://github.com/T3aHat/DeepLopener/raw/main/add.png"  height="20px"/>

### Delete Glossaries
1. Click <img src="https://github.com/T3aHat/DeepLopener/raw/main/delete.png"  height="20px"/> in the right of the name of the glossary you want to delete

### Add Entries
1. Click the name of the glossary to which you want to add a entry
2. Enter SourceText and TargetText in the top entry field
3. Click <img src="https://github.com/T3aHat/DeepLopener/raw/main/add.png"  height="20px"/>

### Modify Entries
1. Change SourceText or TargetText you want to modify
2. Click <img src="https://github.com/T3aHat/DeepLopener/raw/main/save.png"  height="20px"/>

### Delete Entries
1. Empty either or both of the input fields for the entry you want to delete
2. Click <img src="https://github.com/T3aHat/DeepLopener/raw/main/save.png"  height="20px"/>

The name of glossary and language pair cannot be changed after the glossary is created.  
Please re-create a new glossary.




# Usage in the current billing period

The Characters translated so far in the current billing period are displayed in the upper right icon.  
 ![usage.png](https://github.com/T3aHat/DeepLopener/raw/main/images/usage.png)  
↑ I translated 11% (55000/500000) characters in the current billing period with DeepL API Free.
