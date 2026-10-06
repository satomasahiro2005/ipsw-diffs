## searchd

> `/System/Library/PrivateFrameworks/Search.framework/searchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x618b4` | `0x61b44` | **`+0x290`** |
| `__TEXT.__oslogstring` | `0x3663` | `0x37a3` | **`+0x140`** |
| `__TEXT.__cstring` | `0x523b` | `0x52a2` | **`+0x67`** |
| `__TEXT.__auth_stubs` | `0x18c0` | `0x1900` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0xa7a0` | `0xa7e0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0xae91` | `0xaec1` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0xc78` | `0xc98` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x4ae0` | `0x4b00` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1f88` | `0x1fa8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x11c8` | `0x11e0` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x3008` | `0x3018` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xef0` | `0xf00` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x2b38` | `0x2b40` | **`+0x8`** |

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

-2459.105.0.0.0
+2465.1.2.0.0

-  Functions: 1231
-  Symbols:   975
-  CStrings:  3324
+  Functions: 1238
+  Symbols:   981
+  CStrings:  3332
Symbols:
+ _CFPreferencesSetValue
+ _CFPreferencesSynchronize
+ _SSAppExclusionsEnabled
+ _SSCopyTCCDisabledBundlesForSiriAccess
+ _SSSubscribeTCCEventsForSiriAccess
+ _kCFPreferencesAnyHost
+ _kCFPreferencesCurrentUser
- _MGGetProductType
CStrings:
+ "DisabledBundlesFromSiriTCC"
+ "SSCopyTCCDisabledBundlesForSiriAccess returned nil; feature flag disabled or tccd temporarily unavailable — preserving existing CFPreferences cache"
+ "SSSubscribeTCCEventsForSiriAccess failed to arm — TCC changes will not propagate to search filter this session"
+ "_setupTCCSubscription"
+ "com.apple.searchd.tcc-prefs-write"
+ "com.apple.spotlight.tcc.siriAccessChanged"
+ "notify_post(kSSSiriAccessChangedNotification) failed: %u"
+ "sortedArrayUsingSelector:"
```
