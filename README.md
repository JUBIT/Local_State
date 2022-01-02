# Local State
It's a hardened list of flags for Microsoft Edge focused on privacy &amp; security.

How to use it?

**Windows**: Open File Explorer, navigate to "%localappdata%\Microsoft\Edge\User Data\", and replace "Local State" with SecureEdge's provided "Local State" and the flags will be enabled to let you enjoy the most secure Microsoft Edge!

**Arch Linux**: Please see in "$XDG_CONFIG_HOME/microsoft-edge-stable-flags.conf" and configure manuallly or copy it from the table:
```
edge://flags#enable-webrtc-remote-event-log = Disabled
edge://flags#enable-webrtc-hide-local-ips-with-mdns = Enabled
edge://#show-autofill-type-predictions = Disabled
edge://#enable-quic = Enabled
edge://#block-insecure-private-network-requests = Enabled
edge://#edge-automatic-https = Enabled
edge://flags/#edge-experimental-tracking-prevention-features = Enabled
edge://flags/#edge-log-textfield-lag = Disabled
edge://flags/#edge-widevine-drm = Disabled
edge://flags/#edge-enable-super-duper-secure-mode = Enabled
edge://flags/#strict-extension-isolation = Enabled
edge://flags/#strict-origin-isolation = Enabled
```

Note📝: While replacing the Local State file, make sure Microsoft Edge is closed.

**Want to know about the changes?**

Please refer to the [wiki](https://github.com/SecureEdge/Local_State/wiki)
