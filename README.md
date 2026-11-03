# utm-images

Prebuilt `.utm` virtual machine bundles for [UTM](https://getutm.app) and UTM SE on iPhone and iPad.

## Debian 13 (trixie) ARM64, console only

Built from the official Debian "nocloud" cloud image, which boots directly to a root prompt (user `root`, no password). Set a password right away with `passwd`.

**One-tap install on iPhone/iPad (open this link in Safari, with UTM or UTM SE installed):**

    utm://downloadVM?url=https://github.com/Tsukieomie/utm-images/releases/download/debian-13-arm64/debian-13-arm64-utm.zip

Plain download (then open the zip in Files and tap the `Debian 13.utm` folder):

    https://github.com/Tsukieomie/utm-images/releases/download/debian-13-arm64/debian-13-arm64-utm.zip

- Architecture: aarch64 (virt, UEFI), VirtIO disk, 2 GB RAM, built-in serial terminal + virtio-ramfb display
- Disk: 3 GB virtual (grows on first boot), qcow2 ~402 MB
- SHA-256 of zip: see release notes
- Source image: https://cloud.debian.org/images/cloud/trixie/latest/debian-13-nocloud-arm64.qcow2
