# YouTube Musical Spectrum for foo_uie_webview

This is a wrapper of [YouTube Musical Spectrum](https://github.com/mfcc64/youtube-musical-spectrum) browser extension.

## Install

- Install [foo_uie_webview](https://www.foobar2000.org/components/view/foo_uie_webview).
- Download `youtube-musical-spectrum-fb2k.html` from [Releases Page](https://github.com/mfcc64/youtube-musical-spectrum-fb2k/releases).
- Set it as `template file` on `WebView Preferences`.
- You may adjust `reaction alignment` to make visualization in sync with audio (I set it to `-0.4` on my computer).
- Probably, you should close and reopen `foobar2000` player after updating `preferences` because of
  [this bug](https://hydrogenaudio.org/index.php/topic,126042.msg1058199.html#msg1058199).
- You need internet connection because the actual scripts are hosted on [jsdelivr](https://www.jsdelivr.com/).
  Probably, after the first run, you don't need internet connection because of caching.

## Settings

- Go to [YouTube Musical Spectrum Settings](https://github.com/mfcc64/youtube-musical-spectrum#settings).
