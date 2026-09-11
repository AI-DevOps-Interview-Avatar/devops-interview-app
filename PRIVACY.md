# Privacy Policy — DevOps Interview AI

**Effective date:** 11 September 2026
**Application:** DevOps Interview AI (`com.devopsai.interview`)
**Developer:** Alex Korchenko
**Contact:** mainoceanm@gmail.com

---

## The short version

DevOps Interview AI runs the entire interview on your phone. Your answers, the
questions, the transcript and the interviewer's replies are produced and stored
on the device and are never transmitted anywhere. There is no account, no
server, no analytics and no advertising.

The app connects to the internet exactly twice in its life, and neither
connection carries anything you said:

1. **Once, on first launch** — to download the AI model file (about 528 MB) from
   a public GitHub release.
2. **On start, in the GitHub version only** — to ask GitHub whether a newer
   version of the app has been published. The Google Play version does not do
   this; Play handles its own updates.

After the model has downloaded, the app works with the network switched off.

---

## What the app collects

**Nothing.** No personal data is collected, transmitted, sold or shared with any
third party. There is no user account and no way to sign in, so the app has no
identity to attach data to in the first place.

## What stays on your device

| Data | Where it lives | How to remove it |
|---|---|---|
| Interview transcripts and history | App-private storage | Clear app data, or uninstall |
| The downloaded AI model file | App-private storage | Uninstall (re-downloads on next install) |
| Your settings (language, chosen interviewer) | App-private storage | Clear app data, or uninstall |

Uninstalling the app removes all of it. Nothing survives elsewhere, because
nothing was sent elsewhere.

The app declares `allowBackup="false"`, so Android does not copy this data into
a cloud or ADB backup either.

## Permissions, and what each is actually for

| Permission | Why | What leaves the device |
|---|---|---|
| **Microphone** (`RECORD_AUDIO`) | Speech recognition converts your spoken answer to text so the interviewer can respond | Nothing. Audio is processed for the live session and not recorded, stored or uploaded |
| **Camera** (`CAMERA`) | Optional self-view preview in the Meet-style interview screen, so you can see yourself as in a real call | Nothing. The preview is never captured, saved or transmitted. Denying it falls back to a silhouette and the interview works normally |
| **Internet** (`INTERNET`, `ACCESS_NETWORK_STATE`) | The one-time model download, and the update check in the GitHub version | Only ordinary HTTP requests to `github.com`. No interview content is ever included |
| **Install unknown apps** (`REQUEST_INSTALL_PACKAGES`) | **GitHub version only.** Lets the app hand a downloaded update to the Android installer | Nothing. Not present in the Google Play version at all |

Speech recognition uses the speech service built into your Android device. If
your device is configured to use a cloud-based recogniser, that processing is
governed by your device manufacturer's and speech provider's privacy policies,
not by this app — this is an Android system setting you control.

## The AI model

Interviewer responses are generated on-device by Google's Gemma 3 1B model
running through MediaPipe. The model file is downloaded once from a public
GitHub release and then runs locally. No prompt and no answer is sent to Google,
to the developer, or to any inference service.

Because responses are machine-generated, they may be inaccurate or unexpected.
The app is a practice tool. It does not make hiring decisions, it is not a real
job application, and no output from it should be treated as professional career
advice.

## Children

The app is not directed at children and collects no data from anyone, including
children. Because AI-generated dialogue cannot be fully predicted, the app is
rated for teenage and adult users in line with its store content rating.

## Third-party services

The app embeds no analytics SDK, no advertising SDK, no crash reporter and no
social login. The only third party involved is **GitHub**, which serves the
model file and the release metadata; GitHub will see the ordinary request
information any web server sees, such as your IP address. GitHub's privacy
statement applies to those requests: https://docs.github.com/site-policy/privacy-policies/github-privacy-statement

If the app is installed from Google Play, Google's own policies apply to the
installation and update process.

## Your rights

There is no data to request, correct or delete on any server, because none is
held. Everything the app knows about you is inside app storage on your phone,
under your control: clear app data or uninstall, and it is gone.

## Changes to this policy

Material changes will be published on this page with a new effective date. The
document's history is public in this repository, so any revision can be compared
against the previous text.

## Contact

Questions about this policy: **mainoceanm@gmail.com**
