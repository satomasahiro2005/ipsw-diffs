## MobileStoreDemoKit

> `/System/Library/PrivateFrameworks/MobileStoreDemoKit.framework/MobileStoreDemoKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x79e5` | `0x7c2a` | **`+0x245`** |
| `__AUTH_CONST.__cfstring` | `0x5180` | `0x52a0` | **`+0x120`** |
| `__TEXT.__text` | `0x2d7e0` | `0x2d88c` | **`+0xac`** |
| `__TEXT.__objc_methlist` | `0x2574` | `0x2584` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1978` | `0x1980` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x3990` | `0x398c` | **`-0x4`** |

### Other Changes

```diff

-1871.2.1.0.0
+1871.40.45.0.0

-  Functions: 1214
-  Symbols:   1715
-  CStrings:  1245
+  Functions: 1215
+  Symbols:   1716
+  CStrings:  1254
Symbols:
+ -[MSDTestPreferences highlightSecretGestureView]
Functions:
~ ___contentRootList_block_invoke : 1288 -> 1372
~ ___systemContainerShouldRestoreList_block_invoke : 208 -> 188
+ -[MSDTestPreferences highlightSecretGestureView]
CStrings:
+ "/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles"
+ "/var/mobile/Library/BulletinBoard/VersionedSectionInfo.plist"
+ "/var/mobile/Library/Preferences/com.apple.AppStore.plist"
+ "/var/mobile/Library/Preferences/com.apple.NanoHomeScreen.PrivacyDefaults.plist"
+ "/var/mobile/Library/Preferences/com.apple.RelevancePlatform.AudioUnderstanding.plist"
+ "/var/mobile/Library/Preferences/com.apple.compass.plist"
+ "/var/mobile/Library/Preferences/com.apple.health.shared.plist"
+ "/var/mobile/Library/Preferences/com.apple.private.health.respiratory.plist"
+ "Failed to get base folder URL - Error:  %{public}@"
+ "HighlightSecretGestureView"
- "Failed to get document folder URL - Error:  %{public}@"
```
