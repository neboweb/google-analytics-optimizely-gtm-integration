# Google Analytics Optimizely Integration Using GTM

## Description
[Optimizely's documentation](https://help.optimizely.com/Integrate_Other_Platforms/Integrate_Optimizely_X_with_Google_Universal_Analytics_using_Google_Tag_Manager) for using Google Tag Manager to integrate with Google Analytics has 11 steps and some inconsistencies, and you might make mistakes, even when copying and pasting.

This JSON file allows you to upload all of the Tags, Triggers and Variables necessary, and after you setup the Google Analytics Settings variable manually, publish immediately to get the integration working.

## Instructions:
1) Download the JSON file
2) Upload to GTM using Admin > Import Container
3) Update the two Tags with your Google Analytics Settings Variable (or use the override option to specify the GA Tracking ID)
4) Publish the workspace

## End Result
Tags: 
- `Optimizely Campaign decided`
- `Optimizely Integration Code`
- `Optimizely Referrer override`

Triggers:
- `Optimizely campaign decided`
- `Optimizely referrer override`

Variables:
- `optimizely-dimension-number`
- `optimizely-dimension-value`
- `optimizely-referrer`

## Issues?
These files are provided as-is and Nebo is not able to provide support. However, if you find a bug, please use the Issues tab above to report it! Thanks for helping to make the Internet a better place!

## Credits
Shoutout to Cael Olsen who did the hard work of finding out that Optimizely library wasn't compatible with dynamicly-named Google Analytics trackers (which is how Google Tag Manager operates, and is preferred)

