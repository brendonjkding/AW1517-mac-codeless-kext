Codeless kext for AW1517
=================================

this is codeless kext for AW1517 to prevent Apple drivers from hijacking a device

## Install-OpenCore
```
<dict>
    <key>Arch</key>
    <string>Any</string>
    <key>BundlePath</key>
    <string>AW1517.kext</string>
    <key>Comment</key>
    <string></string>
    <key>Enabled</key>
    <true/>
    <key>ExecutablePath</key>
    <string></string>
    <key>MaxKernel</key>
    <string></string>
    <key>MinKernel</key>
    <string></string>
    <key>PlistPath</key>
    <string>Contents/Info.plist</string>
</dict>
```

[AlienFxLite](https://github.com/bchretien/AlienFxLite) works perfectly with this kext at macOS 10.15.7 Catalina  
Note: you may need my [fork](https://github.com/brendonjkding/AlienFxLite) which fix compilation issues.