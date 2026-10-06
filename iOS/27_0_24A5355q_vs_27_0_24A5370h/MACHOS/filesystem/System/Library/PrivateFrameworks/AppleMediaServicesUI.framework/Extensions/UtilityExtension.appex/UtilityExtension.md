## UtilityExtension

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Extensions/UtilityExtension.appex/UtilityExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x44164` | `0x475dc` | **`+0x3478`** |
| `__DATA.__bss` | `0x3010` | `0x3310` | **`+0x300`** |
| `__TEXT.__cstring` | `0x1457` | `0x1677` | **`+0x220`** |
| `__TEXT.__const` | `0x27c0` | `0x2960` | **`+0x1a0`** |
| `__TEXT.__objc_methname` | `0x19f7` | `0x1b37` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x1d58` | `0x1e90` | **`+0x138`** |
| `__DATA_CONST.__const` | `0x1fc0` | `0x20e0` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x1440` | `0x1520` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x1380` | `0x1428` | **`+0xa8`** |
| `__TEXT.__swift5_capture` | `0x738` | `0x7d0` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0xb94` | `0xbf4` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x146d` | `0x14c9` | **`+0x5c`** |
| `__DATA.__objc_selrefs` | `0x898` | `0x8e8` | **`+0x50`** |
| `__DATA.__objc_const` | `0x25f0` | `0x2630` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x12ec` | `0x1328` | **`+0x3c`** |
| `__DATA.__data` | `0x22f8` | `0x2328` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x80` | `0xb0` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x947` | `0x977` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0xd9c` | `0xdc4` | **`+0x28`** |
| `__DATA.__objc_data` | `0x1098` | `0x10b8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x430` | `0x448` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x1dd0` | `0x1de0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xef0` | `0xef8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x138` | `0x13c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-8.0.35.2.1
+8.0.38.0.0

-  Functions: 1673
-  Symbols:   249
-  CStrings:  580
+  Functions: 1738
+  Symbols:   252
+  CStrings:  604
Symbols:
+ _AMSAccountMediaTypeAppStoreBeta
+ _AMSAccountMediaTypeAppStoreSandbox
+ _AMSAccountMediaTypeProduction
CStrings:
+ " promise, reason:"
+ "Could not reject "
+ "Could not resolve "
+ "Failed to fetch selected profile. Error:"
+ "Failed to fetch simple profiles. Error:"
+ "Invalid media type"
+ "Simple profile not found: "
+ "Sponsor not found: "
+ "ams_isSelectedProfile"
+ "ams_isSimpleProfile"
+ "ams_selectedProfileForMediaType:"
+ "ams_simpleProfileAccounts"
+ "ams_simpleProfileAccountsForMediaType:"
+ "ams_sponsorAccount"
+ "isSelectedProfile"
+ "selectedProfileForMediaType(_:)"
+ "selectedProfileForMediaType(_:) called without active JS worker thread"
+ "selectedProfileForMediaType:"
+ "simpleProfilesForMediaType(_:)"
+ "simpleProfilesForMediaType(_:) called without active JS worker thread"
+ "simpleProfilesForMediaType:"
+ "simpleProfilesForSponsor:"
+ "sponsorForSimpleProfile:"
+ "underlyingAccountStore"
```
