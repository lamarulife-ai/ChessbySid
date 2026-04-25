 # Privacy Policy for ChessBySid

  **Effective date:** 25 April 2026
  
  **App:** ChessBySid
  
  **Version:** 1.0.0
  
  **Package:** com.chessbysid
  
  **Developer:** Sid ("Designed by Sid")

  ## Overview

  ChessBySid is a fully offline chess game for Android. We built it with a
  privacy-first mindset: the app does not require an internet connection to
  function, does not display ads, and does not collect, transmit, or share
  any personal information about you with us or any third party.

  This policy explains what happens on your device, what does *not* happen,
  and how to contact us if you have questions.

  ## What we do NOT collect

  We do not collect, access, or transmit any of the following:

  - Your name, email address, phone number, or any account identifier
  - Device identifiers (IMEI, MAC address, advertising ID, Android ID)
  - Location (GPS, coarse, or network-based)
  - Contacts, calendar, photos, microphone, or camera data
  - Analytics, crash telemetry, or usage metrics
  - Any data over the network — the app does not request the
    `INTERNET` permission and cannot send data off your device

  ## Data stored locally on your device

  ChessBySid stores a small amount of data locally so the app remembers your
  preferences between sessions. This data **never leaves your device** and is
  not accessible to us.

  **App settings** (DataStore file: `chessbysid_settings`):

  - Chosen AI difficulty (Easy / Medium / Hard)
  - Selected board theme (one of six visual presets)
  - Show-legal-moves toggle
  - Highlight-last-move toggle
  - Sound-effects toggle

  **Saved game** (DataStore file: `chessbysid_saved_game`, written only when
  you tap "Save" on the game screen):

  - The current board position (as a FEN string)
  - The list of moves played in that game (algebraic notation)
  - Captured pieces, last move played, selected game mode, AI difficulty,
    and the color you played

  There is at most one saved game at any time. It is overwritten when you
  save again, and cleared automatically when the game ends, when you start
  a New Game from the in-game action bar, or when you uninstall the app.

  You can also clear all stored data manually via **Android Settings →
  Apps → ChessBySid → Storage → Clear storage**.

  ## Learn mode content

  The Learn mode contains 7 piece tutorials and 200 chess puzzles. All of
  this content (text, board positions, hint pool) is bundled into the app
  package at build time. Nothing is fetched at runtime, no progress data
  is sent anywhere, and no analytics record which puzzles you attempt.

  Chess positions are factual board states encoded as FEN strings — they
  are not personal data and have no copyright.

  ## Permissions

  ChessBySid declares **no runtime or install-time permissions** in its
  Android manifest. In particular, it does not request:

  - Internet or network access
  - Storage (reads/writes only the app's private sandbox)
  - Camera, microphone, location, contacts, or any other sensitive
    permission

  Sound effects are generated on-device using Android's built-in tone
  generator (`android.media.ToneGenerator`) and do not require any
  permission. If your device or manufacturer disables tone generation,
  the app silently continues without sound.

  ## Third-party services

  ChessBySid does not integrate with any third-party service,
  advertising network, analytics SDK, crash reporter, cloud backend,
  or social-login provider. The app is a single binary that runs
  entirely on your device.

  ## Children's privacy

  ChessBySid is suitable for all ages and does not knowingly collect
  any information from anyone, including children under 13. Because
  the app does not collect personal data, it complies with the spirit
  of the Children's Online Privacy Protection Act (COPPA) and similar
  laws by design. The app contains no user-to-user communication,
  no in-app purchases, no ads, and no external links.

  ## Security

  Because no personal data is transmitted or stored on remote servers,
  there is no server-side data to protect. Local data is stored in the
  app's private sandbox using Android's standard `DataStore` mechanism,
  which is only accessible to ChessBySid itself under the operating
  system's app-sandbox model.

  ## Changes to this policy

  If we update this privacy policy in a future version of the app, we
  will update the "Effective date" above and publish the revised policy
  at the same URL where you found this one. Continued use of the app
  after such updates means you accept the revised policy.

  ## Contact

  If you have questions about this policy, you can reach out at:

  **Email:** lamarulife@gmail.com
