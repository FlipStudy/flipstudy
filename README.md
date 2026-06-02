# 📚 FlipStudy

A free, ad-free flashcard revision app built for GCSE students. No account needed, no internet required once installed — everything is stored privately on your device.

\---

## Features

* **Multiple card sets** — organise cards by subject or topic, each with its own colour and emoji
* **Archive** — hide old sets from the main screen without deleting them
* **Four study modes:**

  * **Flashcards** — flip through cards at your own pace
  * **Learn** — mark cards as *Got it* or *Still learning*; weak cards come back around until you know them all
  * **Quiz** — four-option multiple choice, questions generated automatically from your cards
  * **Match** — tap matching pairs against the clock
* **Progress tracking** — see how many cards you've mastered per set, and when you last studied it
* **Study streak** — tracks how many days in a row you've studied to keep motivation up
* **Text-to-speech** — tap the speaker button on any card to hear it read aloud; automatically switches to a French voice when French text is detected (other languages to follow)
* **Dictation** — tap the microphone button when adding a card to speak your term or definition instead of typing
* **Import cards** — paste a list of term/definition pairs to bulk-create cards in seconds
* **Backup and restore** — export all your cards as a file and re-import them any time
* **Works offline** — once installed, no internet connection is needed
* **No ads, no account, no cost**

\---

## How to install on Android

1. Open **Chrome** on your Android phone
2. Go to `https://flipstudy.github.io/flipstudy/`
3. Tap the **three dots menu (⋮)** → **Add to Home screen** → **Install**
4. The app icon will appear on your home screen and opens like any other app

\---

## Study modes explained

### Flashcards

Flip through all cards in a set. Tap the card to reveal the answer, then use the *Got it* / *Still learning* buttons to track your progress. Tap the shuffle icon to randomise the order.

### Learn

Cards are shown one at a time. After revealing the answer, mark it *Got it* or *Still learning*. Cards you're still learning come back around a few cards later. The session ends only when every card has been marked *Got it* — so you always finish knowing everything.

### Quiz

The app picks a card and shows the correct answer alongside three plausible wrong answers drawn from other cards in the set. Tap your choice — green means correct, red means wrong — and the next question appears automatically. You get a score at the end.

### Match

All terms and definitions are shown as tiles on screen. Tap a term, then tap its matching definition. Matched pairs disappear. Beat your best time!

\---

## Tips for GCSE revision

* **Create one set per topic**, not one per subject — smaller sets are easier to get through in a single session
* **Use Learn mode first** to get cards into your memory, then use Quiz mode to test yourself properly
* **Use the import feature** to add cards quickly — type them up in Notes or Google Docs, then paste them in
* **Archive sets** after an exam so they don't clutter the home screen, but you can still get them back if needed
* **Study a little every day** — even 10 minutes keeps your streak going and is more effective than one long session before an exam

\---

## Settings

|Setting|What it does|
|-|-|
|Shuffle cards by default|Randomises card order at the start of each study session|
|Show term first|Controls which side of the card faces up|
|Text-to-speech|Shows or hides the speaker button on cards|
|English / French voice|Choose which installed voice to use for each language|
|Playback speed|Slow down or speed up the read-aloud voice|

\---

## Adding a French voice (for language sets)

FlipStudy automatically detects French text and switches to a French voice. If no French voice is installed on the device, a warning will appear in Settings with instructions.

To install a French voice on Android:

1. Go to **Settings → General Management → Text-to-speech**
2. Tap your TTS engine (usually *Google Text-to-speech*)
3. Tap **Install voice data** and download a French voice

\---

## Technical notes

FlipStudy is a **Progressive Web App (PWA)** — a website that behaves like a native app. All data is stored locally on the device using the browser's built-in storage (`localStorage`). Nothing is sent to any server. The app works fully offline after the first load thanks to a service worker that caches all files.

Built with plain HTML, CSS, and JavaScript — no frameworks, no dependencies, no tracking.

