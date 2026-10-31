# Maintainer requirements

To maintain a device officially, you need to meet all of these.

1. **You own the device.** No blind or untested builds. One build can cover close variants, such as regional models, if you test the one you own.
2. **You know git.** Cherry-picking, rebasing, squashing and resolving conflicts are everyday work.
3. **Your trees are clean.** Every commit keeps its original author, has a clear message, and imports say where they came from.
4. **Your sources are public.** That means the device tree, common trees, kernel and any vendor repos you changed. The kernel is GPL, so its source must be public before any build is.
5. **Your build is SELinux enforcing.**
6. **You can read a logcat** and fix most device-side bugs yourself.
7. **You have released an unofficial RR build** for the device, and you link it in your application. Build it with `export RELEASE_TYPE=UNOFFICIAL` so it isn't labelled OFFICIAL.
8. **Your device meets the [device requirements](device-requirements.md).**
9. **You follow the RR setup:**
   - an `rr_<codename>.mk` that inherits `vendor/rr/config/common_full_phone.mk`
   - `RR_MAINTAINER` set to your name
   - `WITH_GMS := true`, because official builds ship with Google apps
   - Remixer and the Updater working
10. **You stay reachable** on Telegram and answer your users' bug reports.

Once you're accepted, the team adds your device to the OTA server, the download site and the [device list](../devices.md).

Ready? [Apply here](https://github.com/ResurrectedRemix-Devices/official_devices/issues/new?template=maintainer-application.yml).
