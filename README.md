# Privacy Policy

**Game:** *The Minister's Term* (the "Game")
**Developer / data controller:** Yury Zayets (YZ Apps Studio) (the "Developer", "we", "us")
**Contact:** yzapps.dev@gmail.com
**Effective date:** 2026-07-22
**Last updated:** 2026-07-22

This policy explains what information the Game collects, why, and your choices. We keep data
collection to the minimum needed to keep the Game stable and to understand how it is played.

## Summary (the short version)

- Your **full game saves and settings stay on your device.** We do not upload the save file.
- We collect **anonymous gameplay analytics** and **crash diagnostics** through Google Firebase, to
  fix bugs and improve balance.
- On published builds we also upload an **anonymous gameplay-replay record** (your in-game decisions,
  stat values, and run seed — no personal info) to balance the Game. **You can turn this off** in
  Settings → Privacy.
- We **do not** collect your name, email, contacts, photos, or precise location.
- We **do not** show ads, and we **do not** sell or share your data with advertisers or data brokers.
- The Game has **no account or login**.

## 1. Information stored on your device only

Your progress, run history, achievements, and settings are stored locally on your device (in the
app's private storage). The full save file is **not transmitted to us** and is removed when you
uninstall the Game. (An anonymous replay record derived from a finished run may be uploaded
separately — see §2c.)

## 2. Information collected automatically

We use three Google Firebase services. Through them, Google processes the following on our behalf:

**a. Usage analytics — Google Analytics for Firebase**
- Gameplay events (e.g. a run started, a run ended and its cause, milestones reached, a run
  abandoned) and the difficulty/options chosen.
- Device and app information: device model, operating-system version, app version, language, and
  coarse (country-level) region inferred from IP address.
- A randomly generated app-instance identifier, and — where available — a mobile advertising
  identifier, used only for analytics aggregation.

**b. Crash diagnostics — Firebase Crashlytics**
- Crash and error reports, including the stack trace, device state, OS and app version.
- Technical context we attach to help reproduce a crash: a deterministic run "seed" and gameplay
  parameters (such as in-game week, difficulty, and system settings), plus a short trail of the most
  recent in-game actions leading up to the crash. **This context is gameplay state, not personal
  information**, and is used solely to diagnose the failure.

**c. Gameplay-replay telemetry — Firebase Cloud Storage** (published builds only; opt-out)
- When a run ends, we upload a compact, anonymous record of that run: the ordered list of your
  in-game decisions, periodic stat values, the deterministic run seed, and the app/balance version.
  We re-simulate these runs to balance the Game. The record contains **no personal information** and
  is not linked to your identity.
- This upload happens only on published (non-debug) builds, and only while
  **Settings → Privacy → "Share Gameplay Data"** is on. It is on by default; turn it off to opt out.

We do **not** combine any of the above with information that identifies you personally.

## 3. How we use this information

- To keep the Game stable (diagnose and fix crashes).
- To understand how the Game is played and to balance and improve it.
- To prioritize features and content.

We do **not** use it for advertising, profiling that produces legal effects, or automated
decision-making about you.

## 4. Legal bases (EEA/UK – GDPR)

We process analytics, crash, and gameplay-replay data under our **legitimate interests** in
maintaining, securing, and improving the Game (Article 6(1)(f) GDPR). You have the right to object to this processing (see
§8). Where required by applicable law, we will rely on your **consent** instead and provide an
in-app control.

## 5. Sharing and third parties

We use **Google Firebase** (Google Ireland Ltd. / Google LLC) as our data processor for the services
in §2. Google processes this data on our behalf under its own terms:
- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses data from sites/apps that use its services: https://policies.google.com/technologies/partner-sites
- Firebase privacy & security: https://firebase.google.com/support/privacy

We do **not** sell your personal information and do **not** share it with advertisers or data
brokers. We may disclose information if required by law or to protect our legal rights.

## 6. International transfers

Google may process and store data in the United States and other countries. Such transfers are made
under appropriate safeguards (e.g. the EU Standard Contractual Clauses and applicable adequacy
frameworks).

## 7. Data retention

- **On-device data:** kept until you delete it or uninstall the Game.
- **Analytics:** retained by Firebase per our configured retention period (by default up to 14
  months), then aggregated/deleted.
- **Crash reports:** retained by Crashlytics for approximately 90 days.
- **Gameplay-replay records:** retained in Firebase Cloud Storage until no longer needed for
  balancing, then deleted.

## 8. Your rights

Depending on where you live, you may have the right to access, correct, delete, or port your data,
to object to or restrict processing, and to withdraw consent. California residents have rights under
the CCPA/CPRA, including that we do **not** sell or share personal information.

Because the data we collect is anonymous/pseudonymous and not tied to your identity, we may be unable
to locate data about a specific individual. To make a request or ask a question, email
**yzapps.dev@gmail.com**. You may also lodge a complaint with your local data protection authority.

You can also limit collection at the device level (e.g. reset or delete your advertising ID, or use
your OS privacy controls).

## 9. Children

The Game is **not directed to children** under 13 (or under 16 in the EEA), and we do not knowingly
collect personal information from them. If you believe a child has provided us data, contact us and
we will delete it.

## 10. Security

We rely on the platform's app sandbox for on-device data and on Google's security measures for the
Firebase services. No method of transmission or storage is 100% secure, but we take reasonable steps
to protect information.

## 11. Changes to this policy

We may update this policy. We will revise the "Last updated" date above and, for material changes,
provide a more prominent notice. Continued use after an update constitutes acceptance.

## 12. Contact

Questions or requests: **yzapps.dev@gmail.com**
