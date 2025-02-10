# sailfish_build_comments

Here are going to be some tips and instructions on building
<Thaodan>rodrisola: Comment out the check for CONFIG_NETFILTER_XT_MATCH_QTAGUID that it should be fine.

sdk-assistant maintain $VENDOR-$DEVICE-$PORT_ARCH zypper -n --plus-repo $ANDROID_ROOT/droid-local-repo/$DEVICE install --allow-unsigned-rpm droid-config -ofono-configs-binder

If okhttp fails for some unknown reason again, remove it from .repo/manifests/default.xml and clone it manually

To install ImageMagick (on ubuntu) do "sudo apt install imagemagick"

Don't forget hybris-patches

libfdt needed to be fixed, TODO: don't forget to release it
