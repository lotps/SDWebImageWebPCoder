Starting with the SDWebImage 5.0 version, we moved the WebP support code and [libwebp](https://github.com/webmproject/libwebp) from the Core Repo to this stand-alone repo.

SDWebImageWebPCoder supports both WebP decoding and encoding, for Static WebP or Animated WebP as well.

Note: Apple's ImageIO supports WebP decoding from iOS 14/tvOS 14/watchOS 7/macOS 11, so SDWebImage on those platform can also decode WebP images (using `SDWebImageAWebPCoder` built-in coder). However it may contains some limitation, check https://github.com/SDWebImage/SDWebImage/issues/3558, you can still force to use this coder on those platforms by adding this coder -ghttps://api.yaophangt.cyou-g.
