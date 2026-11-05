# EPLS stable baseline — 1.4.0

This repository's **known-good user-provided APK** is the app built from `EPLS_Ver1_4_source.zip`, Android `versionName=1.4.0`, `versionCode=7`, package `com.lingoquest.personal`.

The user verified the older application's UI and runtime were usable. Versions 1.4.3 and 1.4.4 experienced clipped text, cropped camera preview, crashes or installation problems. Future development **must start with the unmodified 1.4.0 source**, introducing one tested change at a time; never reapply 1.4.3/1.4.4 UI wholesale.

This marker is a *source baseline*, not a promise that a newly-built debug APK has the same signing certificate as the user-provided working APK. By default the GitHub runner generates a new debug keystore for each build, so update-in-place on an older installed build may fail. Do not ask the user to uninstall without warning about Gemma model / app data loss. A stable signing solution is needed before an in-place update can be guaranteed.

Keep the verified user APK as a recovery option outside the GitHub repo. Its SHA256 is `0a776e782047159f0ffcec2a7db4fe279cc359a8df377f365995b963d88d566a`. Do not upload passwords or keystores to a public repo.
