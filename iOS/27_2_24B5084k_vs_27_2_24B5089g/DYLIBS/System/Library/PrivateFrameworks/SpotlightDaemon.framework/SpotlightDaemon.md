## SpotlightDaemon

> `/System/Library/PrivateFrameworks/SpotlightDaemon.framework/SpotlightDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc5d04` | `0xc5f44` | **`+0x240`** |
| `__TEXT.__cstring` | `0x9c05` | `0x9c86` | **`+0x81`** |
| `__AUTH_CONST.__cfstring` | `0x81a0` | `0x8200` | **`+0x60`** |
| `__DATA.__bss` | `0x1a8` | `0x148` | **`-0x60`** |
| `__DATA_DIRTY.__bss` | `0x6d8` | `0x738` | **`+0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x3d68` | `0x3d88` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xd4c0` | `0xd4dc` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x4c6c` | `0x4c84` | **`+0x18`** |
| `__DATA.__data` | `0x418` | `0x410` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x158` | `0x160` | **`+0x8`** |

### Other Changes

```diff

-2465.1.2.0.0
+2465.1.3.0.0

-  Functions: 3412
-  Symbols:   5118
-  CStrings:  2736
+  Functions: 3413
+  Symbols:   5119
+  CStrings:  2739
Symbols:
+ -[SPCoreSpotlightTask _knownDisabledBundleIDsFromBundleIDs:excludingFPBundleIDs:]
+ -[SPCoreSpotlightTask _makeNotificationSourcesQueryStringWithBundleIDs:]
+ -[SPCoreSpotlightTask _makePrefsQueryStringWithPrefsDisabledBundles:]
+ GCC_except_table79
+ GCC_except_table82
+ GCC_except_table88
+ GCC_except_table94
+ GCC_except_table98
- -[SPCoreSpotlightTask _makePrefsQueryStringWithBundleIDs:prefsDisabledBundles:]
- GCC_except_table77
- GCC_except_table78
- GCC_except_table86
- GCC_except_table89
- GCC_except_table90
- GCC_except_table96
CStrings:
+ " && _kMDItemBundleID!=\"com.apple.people.screenTimeRequest\" && _kMDItemBundleID!=\"com.apple.Preferences\""
+ "(!((%@) || (%@) || (%@) || (%@) || ((%@)%@)))"
+ "(_kMDItemBundleID = \"com.apple.usernotificationsd\" && %@)"
+ "(qid=%ld, bid=%s, context) Filtering out prefs disabled bundle %s"
+ "kMDItemCreator"
- "(!((%@) || (%@) || (%@) || ((%@) && _kMDItemBundleID!=\"com.apple.people.screenTimeRequest\")))"
- "Using disabledBundleIDs for (%ld, %s)"
```
