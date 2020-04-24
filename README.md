## Replace FakeStore with Play Store mod and install DroidGuard [Not Maintained Anymore!]

#### This is a module that replaces FakeStore with a modified Play Store and installs DroidGuard Helper on **[LineageOS for microG](https://lineage.microg.org/)**.

<h2 align="center"><a href="https://github.com/Shabinder/Replace-fakestore-with-playstore-mod-and-install-Droidguard/raw/master/replace%20fakestore%20with%20playstore%20and%20install%20droidguard.zip">Download</a></h2>

---

### What does this module do?

LineageOS for microG comes with the FakeStore and *not with the Play Store client*. **This prevents user from purchasing apps**, as to purchase apps you need the Play Store client. **This modules fixes this by replacing Fake Store with a modified Play Store**.

* For updating the Play Store, add this repo to F-Droid: https://nanolx.org/fdroid/repo?fingerprint=862ED9F13A3981432BF86FE93D14596B381D75BE83A1D616E2D44A12654AD015

Also, LOS for microG doesn't come with the DroidGuard Helper because it is a proprietary app. **This unfortunately breaks SafetyNet**, which is needed for many apps. **This module fixes this by installing DroidGuard Helper**.

---

### Is this systemless and OTA survivable?

**Yes!** This is a Magisk module that does all the work ***systemlessly and is also OTA survivable.***

---

#### Known issues:

* DroidGuard Helper crashes during SafetyNet check!
  * Please install the [DroidGuard.apk](https://github.com/Shabinder/Replace-fakestore-with-playstore-mod-and-install-Droidguard/raw/master/system/priv-app/DroidGuard/DroidGuard.apk) as an update over the installed DroidGuard Helper.

* SafetyNet isn't passing!
  * Go to Magisk Manager -> Magisk Hide and activate it for `microG DroidGuard Helper`.
  * **Currently, SafetyNet is broken on microG**. This isn't due to this module, as it is to due Google's own changes.
    [Please follow this microG issue](https://github.com/microg/android_packages_apps_RemoteDroidGuard/issues/24).

---

#### NEED HELP?: WRITE TO ***@SHABINDER*** ON TELEGRAM

###### Credits: [MARVIN](https://github.com/mar-v-in) FOR MICROG, [NANOLX](https://gitlab.com/Nanolx) FOR MODDED PLAY STORE and TECHNO SHAB *(aka Shabinder, aka me)* for this module.
