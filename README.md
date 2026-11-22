# LazerLock MDM — public downloads

This public repository holds what phones and parents need to reach without a GitHub login. No app code lives here;
the code is in the private `lazerlock-mdm-private` repository.

- **Releases** — the signed LazerLock APKs. Managed phones check this repository's releases to update themselves
  (stable releases for everyone, pre-releases only for phones on the Test builds channel).
- **`unlock/`** — the forgotten-PIN unlock page, served by GitHub Pages at
  <https://eliezer-devv.github.io/lazerlock-mdm/unlock/>. You type your recovery key and the number the phone shows,
  and it gives the code to type on the phone. Everything is worked out in your browser; nothing is sent or saved.
  It holds no secrets and is useless without your recovery key.
- **`google-id/`** — finds a Google account's ID for LazerLock's reset protection, at
  <https://eliezer-devv.github.io/lazerlock-mdm/google-id/>. You sign in with Google on your own device and it shows
  the account's email and ID. Nothing is saved or sent anywhere else, and no account is added to any phone.

Files here are published from the private repository (`tools/unlock.html`, `tools/google-id.html`); change them there, not here.
