# sinu-glasses

Alan's personal app for Ray-Ban Meta glasses: talk to the sinu agent through the glasses.

**Step 1 (now):** prove that Meta's toolkit works on Alan's setup (SDK 1.0.1, Gen 2 glasses, iPhone 13, free Apple ID).
The `Build BirdSpotter (unsigned)` workflow builds Meta's BirdSpotter sample, unchanged, on a cloud Mac with Xcode 26.6.
The .ipa is signed and installed from Windows with Sideloadly.

Meta's sample code isn't copied here. The workflow clones
[meta/meta-wearables-dat-ios](https://github.com/meta/meta-wearables-dat-ios) at build time. Use of the toolkit falls
under the [Meta Wearables Developer Terms](https://wearables.developer.meta.com/terms).

Why a cloud Mac: Alan's MacBook (A2289, 2020, two ports) can't run macOS Tahoe, which Xcode 26.4+ needs.
