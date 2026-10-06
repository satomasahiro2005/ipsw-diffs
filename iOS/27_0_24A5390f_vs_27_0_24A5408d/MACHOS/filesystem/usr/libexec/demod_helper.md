## demod_helper

> `/usr/libexec/demod_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e80c` | `0x2eaf4` | **`+0x2e8`** |
| `__TEXT.__cstring` | `0x6465` | `0x6605` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x62c7` | `0x63fd` | **`+0x136`** |
| `__DATA_CONST.__cfstring` | `0x50c0` | `0x5160` | **`+0xa0`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1871.0.42.0.0
+1871.0.51.0.0

-  Functions: 1051
+  Functions: 1054

-  CStrings:  2174
+  CStrings:  2182
CStrings:
+ "/private/var/mobile/Library/Preferences/com.apple.powerui.democec.plist"
+ "/var/mobile/Library/AgentSessionKitBackupStaging"
+ "/var/mobile/Library/IdentityServices/Persistence/com.apple.identityservices.dailyDeviceAddedNotificationData"
+ "/var/mobile/Library/IdentityServices/Persistence/com.apple.identityservicesd.offgrid.provisioning.store"
+ "/var/mobile/Library/IdentityServices/Persistence/com.apple.identityservicesd.waking-push-priority"
+ "Backup AgentSessionKitBackupStaging - Cannot find RelativePathsNotToBackupInMegaBackup under HomeDomain."
+ "Backup AgentSessionKitBackupStaging - Cannot find RelativePathsNotToBackupToService under HomeDomain."
+ "Backup AgentSessionKitBackupStaging - Cannot find RelativePathsToOnlyBackupEncrypted under HomeDomain."
+ "Library/AgentSessionKitBackupStaging"
- "/Library/Preferences/com.apple.powerui.democec.plist"
```
