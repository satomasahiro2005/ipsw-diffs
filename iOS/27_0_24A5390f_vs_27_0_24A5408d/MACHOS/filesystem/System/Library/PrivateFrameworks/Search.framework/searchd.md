## searchd

> `/System/Library/PrivateFrameworks/Search.framework/searchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61b6c` | `0x61868` | **`-0x304`** |
| `__TEXT.__oslogstring` | `0x37a3` | `0x3663` | **`-0x140`** |
| `__TEXT.__cstring` | `0x52a2` | `0x523b` | **`-0x67`** |
| `__TEXT.__auth_stubs` | `0x1910` | `0x18c0` | **`-0x50`** |
| `__DATA_CONST.__auth_got` | `0xca0` | `0xc78` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0x4b00` | `0x4ae0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x1fa8` | `0x1f88` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0xa7c0` | `0xa7a0` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xec8` | `0xee8` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xaea6` | `0xae91` | **`-0x15`** |
| `__DATA_CONST.__got` | `0x11d8` | `0x11c8` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x3010` | `0x3008` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x2b40` | `0x2b38` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-2454.100.0.0.0
+2459.102.0.0.0

-  Functions: 1238
-  Symbols:   982
-  CStrings:  3331
+  Functions: 1231
+  Symbols:   975
+  CStrings:  3324
Symbols:
- _CFPreferencesSetValue
- _CFPreferencesSynchronize
- _SSAppExclusionsEnabled
- _SSCopyTCCDisabledBundlesForSiriAccess
- _SSSubscribeTCCEventsForSiriAccess
- _kCFPreferencesAnyHost
- _kCFPreferencesCurrentUser
CStrings:
+ "isSpotlightUIClientBundle:"
- "DisabledBundlesFromSiriTCC"
- "SSCopyTCCDisabledBundlesForSiriAccess returned nil; feature flag disabled or tccd temporarily unavailable — preserving existing CFPreferences cache"
- "SSSubscribeTCCEventsForSiriAccess failed to arm — TCC changes will not propagate to search filter this session"
- "_setupTCCSubscription"
- "com.apple.searchd.tcc-prefs-write"
- "com.apple.spotlight.tcc.siriAccessChanged"
- "notify_post(kSSSiriAccessChangedNotification) failed: %u"
- "sortedArrayUsingSelector:"
```
