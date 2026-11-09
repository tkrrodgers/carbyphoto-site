# CarByPhoto Privacy Policy

*Last updated: November 9, 2026.*

CarByPhoto is made by Prosperity Simplified. This policy covers the CarByPhoto app for iPhone and iPad, and the
CarByPhoto server it talks to.

## The short version

To identify a car, CarByPhoto sends the photo you take or choose, and the questions you ask Joe, to the CarByPhoto
server, which asks **Anthropic's Claude** AI. The app asks your permission before it sends anything. The server deletes
photos within 30 minutes. CarByPhoto has no account, no ads and no tracking.

## What leaves your iPhone, and where it goes

- **Photos.** Nothing is sent until you tap **Allow and continue** on the "Before you start" screen. Before a photo
  leaves your iPhone, it's made smaller, and its location and camera details are removed. The CarByPhoto server
  (Google Cloud, in Iowa, United States) sends it to Anthropic's Claude to identify the car. The server keeps the photo
  in memory for at most 30 minutes, so Joe can ask a follow-up question, and then deletes it. Photos are never saved to
  disk or written to logs. CarByPhoto sees only the photos you pick in Apple's photo picker, never the rest of your
  library.
- **Questions you ask Joe**, typed or spoken, are sent the same way. Spoken questions are turned into text on your
  iPhone when it can do that; otherwise Apple's speech recognition does it, under Apple's privacy policy. Only the text
  is sent.
- **Anthropic** processes photos and questions for us under its commercial terms, which don't allow it to train its
  models on them. Anthropic's privacy policy: https://www.anthropic.com/legal/privacy
- **Vehicle databases** (the U.S. EPA's fueleconomy.gov, NHTSA for recalls and safety ratings, and CarAPI) receive only
  a car's make, model and year, never your photo, your questions or anything about you.

## What identifies this copy of the app

- **An install ID**: a random number the app makes when it's installed. The server uses it for daily limits (for
  example, 40 photos a day during the pilot). It isn't linked to you, your Apple account or your device, and deleting
  the app discards it.
- **An App Attest key**: Apple's App Attest lets the server check that requests come from the real CarByPhoto app on a
  real Apple device. The app makes a key that never leaves your iPhone's secure chip, and Apple certifies it. The server
  stores the key's public part, a counter and Apple's certificate, so it can check each request. It contains nothing
  about you.

## What the server logs

One line per request: the time, what was asked for (a photo, a question, an info card), whether it worked, how long it
took, the AI model and how much text it processed, and short scrambled fingerprints of the install ID, the network
address and the App Attest key. The fingerprints change every time the server restarts. Logs never contain photos,
questions, install IDs, keys or network addresses. Google Cloud keeps them for 30 days.

## What stays on your iPhone

- **Your Garage**: the cars you save, with their photos and info cards. They're kept in the app's storage on your
  iPhone, and in your iPhone's backups if you use them. CarByPhoto never sends them anywhere. Deleting a car, or the
  app, removes them.
- **Your choices**: whether you allowed Joe to use your photos and questions, and the app's settings.
- **Joe's voice** is made on your iPhone.

## Your choices

- You can tap **Not now** on the "Before you start" screen. The Garage and About still work, and nothing is sent.
- You can withdraw your permission at any time under **About & Privacy**. The app then sends nothing until you allow it
  again.
- The camera, the microphone and speech recognition are used only when you use them, and iOS asks you first.

## Children

CarByPhoto isn't made for young children. It has no ads, no accounts and no purchases, and Joe answers only questions
about cars.

## TestFlight pilot

If you test CarByPhoto through Apple's TestFlight, Apple shares crash reports and any feedback you choose to send with
Prosperity Simplified, as described in Apple's TestFlight terms. Please don't include photos of people in feedback.

## Changes and contact

If this policy changes, the new version will be posted here with a new date. Questions: TestFlight testers can write to
us from TestFlight → CarByPhoto → Send Beta Feedback; everyone else can use the support contact on CarByPhoto's App
Store page.
