---
title: DeepLopener | sync
class: DeepLopener
repository_url: https://github.com/T3aHat/DeepLopener
---

# Why do I need to log in and enable synchronization?

To securely store your API_KEY, when you enable synchronization, `chrome.identity.getProfileUserInfo()` will get the information of the Google account you are signed in to. This information is used to obfuscate the API_KEY and store it by using `chrome.storage.sync.set()`, but this extension **does not** intentionally send this information to the any server. See the [implementation](https://github.com/T3aHat/DeepLopener/blob/main/options.js) for details. If you don't understand the behavior of this code, please don't use this extension, as stated in the [disclaimer](https://github.com/T3aHat/DeepLopener#%E5%85%8D%E8%B2%AC%E4%BA%8B%E9%A0%85disclaimer).   
If you do not want to log in, you can still use this extension, but be aware that the API_KEY is stored without obfuscation.

We are not satisfied with this implementation. We think that this problem is the most important that needs to be solved ASAP. If you have any good ideas, please contact us via [issue](https://github.com/T3aHat/DeepLopener/issues).
