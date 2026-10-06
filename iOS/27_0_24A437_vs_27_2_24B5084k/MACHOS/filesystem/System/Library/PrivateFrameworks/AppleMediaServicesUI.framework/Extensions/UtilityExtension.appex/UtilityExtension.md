## UtilityExtension

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Extensions/UtilityExtension.appex/UtilityExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45c8c` | `0x48f44` | **`+0x32b8`** |
| `__DATA.__bss` | `0x3010` | `0x3310` | **`+0x300`** |
| `__TEXT.__cstring` | `0x14c7` | `0x16c7` | **`+0x200`** |
| `__TEXT.__const` | `0x27d0` | `0x2960` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x1d50` | `0x1e98` | **`+0x148`** |
| `__DATA_CONST.__const` | `0x1fe8` | `0x2108` | **`+0x120`** |
| `__TEXT.__objc_methname` | `0x1a17` | `0x1b37` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x1460` | `0x1520` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x13b0` | `0x1450` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x748` | `0x7e0` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0xb94` | `0xbf4` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x12d4` | `0x1328` | **`+0x54`** |
| `__DATA.__objc_selrefs` | `0x8a0` | `0x8e8` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x148f` | `0x14d7` | **`+0x48`** |
| `__DATA.__data` | `0x2338` | `0x2378` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x80` | `0xb0` | **`+0x30`** |
| `__DATA.__objc_const` | `0x2610` | `0x2630` | **`+0x20`** |
| `__DATA.__objc_data` | `0x1098` | `0x10b8` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xda8` | `0xdc4` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x440` | `0x458` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__auth_stubs` | `0x1ef0` | `0x1f00` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xf80` | `0xf88` | **`+0x8`** |
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

-8.0.52.2.8
+8.1.12.2.1

-  Functions: 1708
-  Symbols:   251
-  CStrings:  590
+  Functions: 1766
+  Symbols:   254
+  CStrings:  611
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
+ "ams_isSimpleProfile"
+ "ams_selectedProfileForMediaType:"
+ "ams_simpleProfileAccounts"
+ "ams_simpleProfileAccountsForMediaType:"
+ "ams_sponsorAccount"
+ "selectedProfileForMediaType(_:)"
+ "selectedProfileForMediaType(_:) called without active JS worker thread"
+ "selectedProfileForMediaType:"
+ "simpleProfilesForMediaType(_:)"
+ "simpleProfilesForMediaType(_:) called without active JS worker thread"
+ "simpleProfilesForMediaType:"
+ "simpleProfilesForSponsor:"
+ "sponsorForSimpleProfile:"
```
