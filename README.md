**YT—mono** is super easy to develop locally: just open `index.html` in your browser!
For instance, since I cloned this repo into my Mac's "Downloads" folder, I point my browser to `file:///Users/kofi/Documents/yt/index.html`

![Screenshot](/build/screenshot.png)


### Design Decisions

 - All inputs save their state in the URL so that exact configurations are sharable
 - Inline JS and CSS during [deploy step](deploy.rb) so that the production app is one resource
 - "Notes" "sound" for as long as the MIDI/keyboard key is held (see [#1](https://github.com/hkgumbs/yt/pull/1))