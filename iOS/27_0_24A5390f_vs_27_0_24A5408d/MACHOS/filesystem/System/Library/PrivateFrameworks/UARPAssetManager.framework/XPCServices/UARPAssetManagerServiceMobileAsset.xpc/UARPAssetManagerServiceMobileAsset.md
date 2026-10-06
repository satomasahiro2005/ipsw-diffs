## UARPAssetManagerServiceMobileAsset

> `/System/Library/PrivateFrameworks/UARPAssetManager.framework/XPCServices/UARPAssetManagerServiceMobileAsset.xpc/UARPAssetManagerServiceMobileAsset`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x103c4` | `0x10aec` | **`+0x728`** |
| `__TEXT.__objc_methname` | `0x2305` | `0x2444` | **`+0x13f`** |
| `__TEXT.__cstring` | `0x12b5` | `0x13d1` | **`+0x11c`** |
| `__TEXT.__objc_stubs` | `0x22c0` | `0x23a0` | **`+0xe0`** |
| `__DATA_CONST.__cfstring` | `0x1160` | `0x1200` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0xa08` | `0xa48` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xd14` | `0xd4c` | **`+0x38`** |
| `__DATA.__objc_const` | `0x1b70` | `0x1ba0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x14cf` | `0x14fe` | **`+0x2f`** |
| `__TEXT.__auth_stubs` | `0x4a0` | `0x4c0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x260` | `0x270` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x148` | `0x150` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3c0` | `0x3c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xd0` | `0xd4` | **`+0x4`** |
| `__TEXT.__objc_methtype` | `0x5f1` | `0x5f4` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1587.0.27.0.0
+1587.2.2.0.0

-  Functions: 342
-  Symbols:   238
-  CStrings:  756
+  Functions: 347
+  Symbols:   240
+  CStrings:  773
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ _objc_retain_x27
CStrings:
+ "%s: Failed to read managedPrefs at %@ error %@"
+ "+[UARPAssetSubscriptioniCloud developmentEnvironmentForContainerID:]"
+ "+[UARPAssetSubscriptioniCloud resolvedContainerIDForContainerID:]"
+ "/Library/Managed Preferences/mobile/com.apple.UARPiCloud.plist"
+ "<%@: pgpn=%@-%@, containerID=%@ releaseNotes=%@ development=%@ domain=%@>"
+ "@60@0:8@16@24@32B40B44B48@52"
+ "TB,R,V_developmentEnvironment"
+ "_developmentEnvironment"
+ "cacheSubdirectoryForContainerID:developmentEnvironment:"
+ "com.apple.UARPiCloud"
+ "com.apple.chip"
+ "containsString:"
+ "development"
+ "developmentEnvironment"
+ "developmentEnvironmentForContainerID:"
+ "initWithContentsOfURL:error:"
+ "initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:developmentEnvironment:domain:"
+ "resolvedContainerIDForContainerID:"
+ "stringByAppendingString:"
+ "substringFromIndex:"
- "<%@: pgpn=%@-%@, containerID=%@ releaseNotes=%@ domain=%@>"
- "@56@0:8@16@24@32B40B44@48"
- "initWithProductGroup:productNumber:containerID:releaseNotesAsset:downloadOnCellularAllowed:domain:"
```
