  # Privacy Policy for ChessBySid

  **Effective date:** 14 June 2026
  **App:** ChessBySid
  **Version:** 1.5.0
  **Package:** com.chessbysid
  **Developer:** Sid ("Designed by Sid")

  ## Overview

  ChessBySid is a chess game for Android built with a privacy-first mindset.
  The core of the app — learning, puzzles, single-player vs the computer,
  pass-and-play, and Bluetooth matches — works **fully offline** and sends
  nothing off your device. It displays **no ads**.

  A few **optional** features (Online Invite and the Global Leaderboard) use the
  internet through Google Firebase. These are never used unless you choose them,
  and they share only the minimum needed to make them work — never personal or
  device-tracking data. This policy explains exactly what is and isn't collected.

  ## Summary

  - **No ads, no sign-up, no account.**
  - **Offline by default** — Single Player, pass-and-play, and Bluetooth Match
    use no internet.
  - **Optional online features** share only your **self-chosen display name and
    chess data** (moves, rating), never your identity or device IDs.
  - **Crash diagnostics** (Firebase Crashlytics) are collected in the published
    app to help us fix crashes — no personal data.

  ## Data stored locally on your device

  This data **never leaves your device** unless an online feature explicitly
  syncs it (see below), and is not accessible to us.

  **App settings** (DataStore `chessbysid_settings`): AI difficulty, board theme,
  show-legal-moves / highlight-last-move / sound toggles, and the
  leaderboard opt-in flag.

  **Profile** (DataStore `chessbysid_elo`): your chosen display name, avatar
  choice, Elo rating, games-played count, and a random local player ID.

  **Saved game** (DataStore `chessbysid_saved_game`, only when you tap Save): the
  board position (FEN), moves, captured pieces, mode, difficulty, and your color.
  At most one saved game exists; it is cleared when a game ends or you start a
  new one.

  You can erase all of it via **Android Settings → Apps → ChessBySid → Storage →
  Clear storage**.

  ## Optional online features (network-using)

  These use Google Firebase and only run when you actively choose them:

  - **Online Invite (online multiplayer).** When you create or join an online
    game, the app signs in to Firebase **anonymously** — Firebase issues a random
    anonymous ID with **no name, email, or account** attached. The game "room"
    (the moves played, your chosen display name, and the chosen color/time
    control) is stored in the Firebase Realtime Database so your opponent's device
    can sync in real time. **The room is automatically deleted when your session
    ends** (you close or leave the game). No personal or device identifiers are
    sent.

  - **Global Leaderboard — opt-in, OFF by default.** Only if you turn on
    *Settings → Join global leaderboard* (or tap *Join* on the Leaderboard screen)
    does the app publish your **self-chosen display name, Elo rating, games-played
    count, and avatar choice** so you can be ranked. No device data is included.
    You can remove yourself at any time by turning the toggle off, which deletes
    your leaderboard entry.

  - **Bluetooth Match** uses Bluetooth only (device-to-device) and sends **no data
    over the internet**.

  Because you pick your own display name, please avoid entering real personal
  information (full name, email, phone, etc.) as your name if you join online
  features.

  ## Crash diagnostics

  The published app uses **Firebase Crashlytics** to report crashes so we can fix
  them. When the app crashes, Crashlytics may send a crash stack trace plus basic
  technical context (device model, OS version, app version, and a random
  Crashlytics install identifier). This contains **no personal information** and
  is not used for advertising or tracking. Crashlytics is disabled automatically
  in development builds.

  ## Third-party services

  ChessBySid uses **Google Firebase** for the optional online features and crash
  diagnostics:

  - **Firebase Authentication** (anonymous sign-in)
  - **Firebase Realtime Database** (online game and leaderboard data)
  - **Firebase Crashlytics** (crash reporting)

  Your use of these is also governed by Google's Privacy Policy:
  https://policies.google.com/privacy

  We do **not** use any advertising network, analytics/marketing SDK, or
  social-login provider.

  ## Permissions

  ChessBySid requests only what its features need:

  - **INTERNET** and **ACCESS_NETWORK_STATE** — for Online Invite and the
    leaderboard. Not used during offline play.
  - **Bluetooth** (`BLUETOOTH_CONNECT`, `BLUETOOTH_SCAN`, `BLUETOOTH_ADVERTISE`
    on Android 12+, or legacy `BLUETOOTH`/`BLUETOOTH_ADMIN` and, on Android 11 and
    below, `ACCESS_FINE_LOCATION` solely for Bluetooth device discovery) — used
    **only** for Bluetooth Match. Location is never read for positioning and is
    declared with the `neverForLocation` flag on Android 12+.

  The app requests no camera, microphone, contacts, photos, or background-location
  permissions.

  ## Data retention

  - **Online game rooms** are deleted automatically when a player's session ends.
  - **Leaderboard entries** persist until you opt out (which deletes your entry)
    or clear app data.
  - **Crash reports** are retained per Google Firebase Crashlytics' standard
    retention policy.

  ## Children's privacy

  ChessBySid is suitable for all ages and does not knowingly collect personal
  information from anyone, including children under 13. The app has no ads and no
  in-app purchases. The only information that can leave the device is what a user
  explicitly opts into sharing through the online features — a self-chosen display
  name and chess statistics. We encourage parents to ensure children do not use a
  real name as their display name. If you believe a child has shared personal
  information, contact us and we will remove it.

  ## Security

  Local data is stored in the app's private sandbox via Android's `DataStore`,
  accessible only to ChessBySid. Online data is transmitted to Google Firebase
  over encrypted (HTTPS/TLS) connections and is protected by Firebase security
  rules that restrict access to authenticated app instances.

  ## Changes to this policy

  If we update this policy in a future version, we will update the "Effective
  date" above and publish the revised policy at the same URL. Continued use of the
  app after such updates means you accept the revised policy.

  ## Contact

  **Email:** lamarulife@gmail.com
