  # Privacy Policy for ChessBySid

  **Effective date:** 24 April 2026
  **App:** ChessBySid
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

  ChessBySid stores a small amount of data locally on your device so the app
  remembers your preferences between sessions. This data **never leaves
  your device** and is not accessible to us.

  **Settings** (in a local DataStore file):

  - Chosen AI difficulty (Easy / Medium / Hard)
  - Selected board theme (one of six styles)
  - Show-legal-moves toggle
  - Highlight-last-move toggle
  - Sound-effects toggle

  **Saved game** (when you tap "Save" on the game screen):

  - The current board position (as a FEN string)
  - The list of moves played in that game (algebraic notation)
  - Captured pieces, last move played, selected game mode and difficulty

  All of the above is stored in the app's private storage directory and is
  removed automatically when you uninstall the app. You can also clear it
  manually at any time via **Android Settings → Apps → ChessBySid →
  Storage → Clear storage**.

  ## Permissions

  ChessBySid declares **no runtime or install-time permissions** in its
  Android manifest. In particular, it does not request:

  - Internet or network access
  - Storage (reads/writes only the app's private sandbox)
  - Camera, microphone, location, contacts, or any other sensitive
    permission

  Sound effects are generated on-device using Android's built-in tone
  generator and do not require any permission.

  ## Third-party services

  ChessBySid does not integrate with any third-party service,
  advertising network, analytics SDK, crash reporter, cloud backend,
  or social-login provider. The app is a single binary that runs
  entirely on your device.

  ## Children's privacy

  ChessBySid is suitable for all ages and does not knowingly collect
  any information from anyone, including children under 13. Because
  the app does not collect personal data, it complies with the spirit
  of the Children's Online Privacy Protection Act (COPPA) and
  similar laws by design.

  ## Security

  Because no personal data is transmitted or stored on remote servers,
  there is no server-side data to protect. Local data is stored in the
  app's private sandbox using Android's standard `DataStore` mechanism,
  which is only accessible to the app itself under the operating system's
  app-sandbox model.

  ## Changes to this policy

  If we update this privacy policy in a future version of the app, we
  will update the "Effective date" above and publish the revised policy
  at the same URL where you found this one. Continued use of the app
  after such updates means you accept the revised policy.

  ## Contact

  If you have questions about this policy, you can reach out at:

  **Email:** kotamraju@vasista.in

  ---

  *This policy describes ChessBySid and its developer only. It does not
  cover any third-party application, website, or service.*

  Tips before publishing

  - Host it publicly — Play Console requires a publicly accessible URL. Easiest options: push the .md to a public GitHub repo and
  link to the raw/rendered file, paste into a free GitHub Pages / Notion / Google Site, or drop it on your personal domain.
  - Keep the effective date current — Update it whenever you change the policy so Play reviewers don't flag it.
  - If you prefer not to publish your email, create a disposable Gmail like chessbysid.support@gmail.com and swap the contact line.
  - Google Play Data Safety form — in Play Console you'll fill a separate form declaring data collection. For ChessBySid, select "No
  data collected" and "No data shared" for every category. This matches the policy above.
