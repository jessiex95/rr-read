# RR Story

An iPad picture-book app for Ruiyou and Ruiyun. Three read-aloud stories at about a level-2 reading level: *Two Leaders*, *Splash Day* and *Mango's Day*.

- Tap any word to hear it; tap the speaker to hear the whole page with word-by-word highlighting.
- Swipe or use the arrows to turn pages. Progress is saved on each iPad.
- Single self-contained `index.html`; no build step.

## Put it on an iPad
Open the site in Safari → Share → **Add to Home Screen**. It opens full screen with the RR Story icon.

For a more natural voice: Settings → Accessibility → Spoken Content → Voices → English → download **Ava (Premium)** or **Zoe (Premium)**.

## Add a story
Stories live in the `BOOKS` array in `index.html`. Each page has `t` (lines of text) and `s` (which scene pieces to draw).
