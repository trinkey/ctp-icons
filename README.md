# ctp-icons
this repository holds a collection of app icons remade using the
[catppuccin color scheme](https://github.com/catppuccin/catppuccin). all icons
are 960x960px in size, so you should be able to use them in any context without
any noticeable drop in quality.

these images are licensed under the mit license. i don't claim to own any of the
logos depicted in any icons

## i want an icon but it doesn't exist
submit [an issue](issues)

## how to contribute
1. you need to get the raw icon of the app that you want to create a new
icon for.
   * **apps on the ios app store:**

     search "`[app name] site:apps.apple.com`" on  your preferred search engine,
and then select the link that says "`[app name] on the App Store`" (there might
be other stuff in the link but like it really doesn't matter its probably gonna
be the first result unless its some niche app). the reason we use the ios app
store over the google play store is that the play store limits icon sizes to
512x512px however on the ios app store, the icons can be sized to any size (up
to a ridiculus number). then, open inspect element and reload the page. the app
icon will likely be the first image to be loaded, and should have the filename
"`230x0w.webp`". you next want to copy the image url and open it up, however
changing the 230 in the filename to be 960. this will upscale the image to the
preferred size.
   * **apps not on the ios app store**

     go to the [google play store](https://play.google.com) and go to the app
page. then, right click the image and open it in a new tab. in that new tab, and
change the end of the link (`=s[number]`) to `=s512`. any size above 512 doesn't
affect anything. then, you can use that image for your photo editor, however you
need to make sure that you make the size in your photo editor is 960x960px and
scale up the icon to fit.
2. in your photo editor, remake the icon using catppuccin colors. some useful
features to keep in mind:
   * in most photo editors, you can select part of an image, and the selection
will be the limits for what can be filled/drawn, which is useful for getting
sharp edges
   * i thought i could think of multiple but i can't and don't feel like
rewriting this

   you can do one or more of the "themes". the colors you can use are below:
   color name|latte|frappe|macchiato|mocha|other notes
   -:|:-:|:-:|:-:|:-:|-
   rosewater|#dc8a78|#f2d5cf|#f4dbd6|#f5e0dc|
   flamingo|#dd7878|#eebebe|#f0c6c6|#f2cdcd|
   pink|#ea76cb|#f4b8e4|#f5bde6|#f5c2e7|
   mauve|#8839ef|#ca9ee6|#c6a0f6|#cba6f7|
   red|#d20f39|#e78284|#ed8796|#f38ba8|
   maroon|#e64553|#ea999c|#ee99a0|#eba0ac|
   peach|#fe640b|#ef9f76|#f5a97f|#fab387|
   yellow|#df8e1d|#e5c890|#eed49f|#f9e2af|
   green|#40a02b|#a6d189|#a6da95|#a6e3a1|
   teal|#179299|#81c8be|#8bd5ca|#94e2d5|
   sky|#04a5e5|#99d1db|#91d7e3|#89dceb|
   sapphire|#209fb5|#85c1dc|#7dc4e4|#74c7ec|
   blue|#1e66f5|#8caaee|#8aadf4|#89b4fa|
   lavender|#7287fd|#babbf1|#b7bdf8|#b4befe|
   text|#4c4f69|#c6d0f5|#cad3f5|#cdd6f4|
   subtext1|#5c5f77|#b5bfe2|#b8c0e0|#bac2de|only use if needed, prefer subtext0
   subtext0|#6c6f85|#a5adce|#a5adcb|#a6adc8|
   overlay2|#7c7f93|#949cbb|#939ab7|#9399b2|
   overlay1|#8c8fa1|#838ba7|#8087a2|#7f849c|
   overlay0|#9ca0b0|#737994|#6e738d|#6c7086|
   surface2|#acb0be|#626880|#5b6078|#585b70|
   surface1|#bcc0cc|#51576d|#494d64|#45475a|
   surface0|#ccd0da|#414559|#363a4f|#313244|preferred over surface1-2 and overlay0-2
   base|#eff1f5|#303446|#24273a|#1e1e2e|should only be used for background
   mantle|#e6e9ef|#292c3c|#1e2030|#181825|only use if needed, prefer crust
   crust|#dce0e8|#232634|#181926|#11111b|
3. submit a pull request with your changes
