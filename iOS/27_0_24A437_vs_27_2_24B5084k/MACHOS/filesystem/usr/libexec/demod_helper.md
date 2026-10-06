## demod_helper

> `/usr/libexec/demod_helper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x6605` | `0x6877` | **`+0x272`** |
| `__TEXT.__text` | `0x2eaf4` | `0x2ec34` | **`+0x140`** |
| `__DATA_CONST.__cfstring` | `0x5160` | `0x5280` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x63fd` | `0x6430` | **`+0x33`** |
| `__TEXT.__objc_methname` | `0x4c11` | `0x4c2c` | **`+0x1b`** |
| `__TEXT.__objc_methlist` | `0x1bc8` | `0x1bd8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1578` | `0x1580` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1871.2.1.0.0
+1871.40.45.0.0

-  Functions: 1054
+  Functions: 1055

-  CStrings:  2182
+  CStrings:  2194
CStrings:
+ "%s - Found system container backup: %{public}@"
+ "-[MSDSignedManifestV7 mergedBackupManifest:]"
+ "/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles"
+ "/var/mobile/Library/BulletinBoard/VersionedSectionInfo.plist"
+ "/var/mobile/Library/Preferences/com.apple.AppStore.plist"
+ "/var/mobile/Library/Preferences/com.apple.NanoHomeScreen.PrivacyDefaults.plist"
+ "/var/mobile/Library/Preferences/com.apple.RelevancePlatform.AudioUnderstanding.plist"
+ "/var/mobile/Library/Preferences/com.apple.compass.plist"
+ "/var/mobile/Library/Preferences/com.apple.health.shared.plist"
+ "/var/mobile/Library/Preferences/com.apple.private.health.respiratory.plist"
+ "HighlightSecretGestureView"
+ "System container backup only allowed on Watch, TV or Ha devices."
+ "highlightSecretGestureView"
- "System container backup only allowed on Watch or Ha devices."
```
