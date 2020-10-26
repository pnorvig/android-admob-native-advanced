# Android Admob Native Advanced

Important Resources:

Native ads policies & guidelines: https://support.google.com/admob/answer/6329638
- All native ad assets must be contained inside the native ad view.

Image elements
Publishers are allowed to scale the image down without modifying the aspect ratio

Publishers are allowed to crop the image symmetrically by up to 20% in only one dimension (height or width)


MediaView class is respsonsible to hold the media content. But just has two public methods.
https://developers.google.com/android/reference/com/google/android/gms/ads/formats/MediaView

Image Ad Sizes & Scaling:
https://support.google.com/admob/answer/6177172?hl=en



- [x] (Customized MediaView)



<img src="https://github.com/sharan10salian/android-admob-native-advanced/blob/main/ic_ad_media_view.png">

- [x] (Event Capture)
During creation of the AdLoader above, the withAdListener function sets an AdListener. 

```
.withAdListener(new AdListener() {
    // AdListener callbacks like OnAdFailedToLoad, OnAdOpened, OnAdClicked and
    // so on, can be overridden here.
})
```


- [ ] (click-through)

- [x] Custom Targeting 
  .addCustomTargeting(adKey, adIdentifier) // Sample
   https://developers.google.com/ad-manager/mobile-ads-sdk/android/targeting#custom_targeting

- [x] Aspect Ratio Scaling. 


