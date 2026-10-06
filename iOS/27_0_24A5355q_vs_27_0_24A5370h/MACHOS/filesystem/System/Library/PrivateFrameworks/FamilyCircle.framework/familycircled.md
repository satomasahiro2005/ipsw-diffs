## familycircled

> `/System/Library/PrivateFrameworks/FamilyCircle.framework/familycircled`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9ccc` | `0xbccb4` | **`+0x2fe8`** |
| `__TEXT.__eh_frame` | `0x89dc` | `0x8c24` | **`+0x248`** |
| `__TEXT.__oslogstring` | `0x660d` | `0x67cd` | **`+0x1c0`** |
| `__TEXT.__const` | `0x4244` | `0x43d4` | **`+0x190`** |
| `__TEXT.__constg_swiftt` | `0x185c` | `0x19a8` | **`+0x14c`** |
| `__DATA_CONST.__const` | `0x54a8` | `0x55e8` | **`+0x140`** |
| `__DATA.__objc_data` | `0x26d8` | `0x2800` | **`+0x128`** |
| `__DATA.__objc_const` | `0x8990` | `0x8aa0` | **`+0x110`** |
| `__TEXT.__objc_methname` | `0x7cab` | `0x7d6b` | **`+0xc0`** |
| `__DATA.__data` | `0x2a68` | `0x2b18` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0x3638` | `0x36e8` | **`+0xb0`** |
| `__TEXT.__swift5_typeref` | `0x1b49` | `0x1bdb` | **`+0x92`** |
| `__TEXT.__swift5_fieldmd` | `0xf7c` | `0x100c` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x101c` | `0x1096` | **`+0x7a`** |
| `__TEXT.__objc_stubs` | `0x5c00` | `0x5c60` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x29b0` | `0x2a00` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x276c` | `0x27a4` | **`+0x38`** |
| `__DATA_CONST.__auth_ptr` | `0x800` | `0x830` | **`+0x30`** |
| `__TEXT.__cstring` | `0x31a2` | `0x31d2` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x14e8` | `0x1510` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x704` | `0x72c` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0xf8c` | `0xfb0` | **`+0x24`** |
| `__TEXT.__objc_classname` | `0xd6d` | `0xd8d` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1c08` | `0x1c20` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x9c8` | `0x9e0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xa0` | `0xb4` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x15c` | `0x170` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x400` | `0x410` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2d0` | `0x2d8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x224` | `0x228` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x24` | `0x28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_mpenum`

### Other Changes

```diff

-279.3.1.2.0
+282.0.0.0.0

-  Functions: 3413
-  Symbols:   1190
-  CStrings:  2364
+  Functions: 3457
+  Symbols:   1199
+  CStrings:  2380
Symbols:
+ _$sSON
+ _$sScT6cancelyyF
+ _$sScTss5NeverORszABRs_rlE11isCancelledSbvgZ
+ _$ss8DurationVMn
+ _$ss8DurationVN
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterRemoveEveryObserver
+ _OBJC_CLASS_$_NSLock
CStrings:
+ "AgeVerification: %s"
+ "AgeVerification: AgeAssurance feature flag disabled. returning errorUnsupportedOperation"
+ "AgeVerification: Cached info for DSID: %{private}s"
+ "AgeVerification: Empty or invalid response after language change, preserving existing cache"
+ "AgeVerification: Failed to refresh after language change, preserving existing cache: %s"
+ "AgeVerification: Fetched fresh info after language change: %{private}s"
+ "AgeVerification: Got URL for endpoint: %s"
+ "AgeVerification: Language preference changed, fetching fresh info for DSID: %{private}s"
+ "AgeVerification: Received response: %@"
+ "AppleLanguagePreferencesChangedNotification"
+ "FALanguagePreferenceObserver"
+ "addLanguageHeadersToHeaderDictionary:"
+ "ageVerificationFetcher"
+ "dsidProvider"
+ "languagePreferenceChanged"
+ "lock"
+ "refreshTask"
+ "started"
+ "unlock"
- "FAAgeVerificationOperation.%s: AgeAssurance feature flag disabled. returning errorUnsupportedOperation"
- "Got URL for ageVerificationInfo endpoint: %s"
- "Received ageVerificationInfo: %@"
```
