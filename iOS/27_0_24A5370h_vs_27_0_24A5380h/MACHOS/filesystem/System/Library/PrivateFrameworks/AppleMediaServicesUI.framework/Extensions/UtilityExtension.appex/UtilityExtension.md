## UtilityExtension

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/Extensions/UtilityExtension.appex/UtilityExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x475dc` | `0x45c64` | **`-0x1978`** |
| `__DATA.__bss` | `0x3310` | `0x3010` | **`-0x300`** |
| `__TEXT.__cstring` | `0x1677` | `0x14c7` | **`-0x1b0`** |
| `__TEXT.__const` | `0x2960` | `0x27d0` | **`-0x190`** |
| `__TEXT.__eh_frame` | `0x1e90` | `0x1d50` | **`-0x140`** |
| `__TEXT.__objc_methname` | `0x1b37` | `0x1a17` | **`-0x120`** |
| `__TEXT.__auth_stubs` | `0x1de0` | `0x1ef0` | **`+0x110`** |
| `__DATA_CONST.__const` | `0x20e0` | `0x1fe8` | **`-0xf8`** |
| `__TEXT.__objc_stubs` | `0x1520` | `0x1460` | **`-0xc0`** |
| `__DATA_CONST.__auth_got` | `0xef8` | `0xf80` | **`+0x88`** |
| `__TEXT.__swift5_capture` | `0x7d0` | `0x748` | **`-0x88`** |
| `__TEXT.__unwind_info` | `0x1428` | `0x13b0` | **`-0x78`** |
| `__TEXT.__objc_methlist` | `0xbf4` | `0xb94` | **`-0x60`** |
| `__TEXT.__constg_swiftt` | `0x1328` | `0x12d4` | **`-0x54`** |
| `__DATA.__objc_selrefs` | `0x8e8` | `0x8a0` | **`-0x48`** |
| `__TEXT.__swift5_typeref` | `0x14c9` | `0x148f` | **`-0x3a`** |
| `__TEXT.__swift5_assocty` | `0xb0` | `0x80` | **`-0x30`** |
| `__DATA.__objc_const` | `0x2630` | `0x2610` | **`-0x20`** |
| `__DATA.__objc_data` | `0x10b8` | `0x1098` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x4d` | `0x6a` | **`+0x1d`** |
| `__TEXT.__swift5_fieldmd` | `0xdc4` | `0xda8` | **`-0x1c`** |
| `__TEXT.__swift5_proto` | `0x1b0` | `0x198` | **`-0x18`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x28` | **`-0x14`** |
| `__DATA.__data` | `0x2328` | `0x2338` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x558` | `0x560` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x448` | `0x440` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x13c` | `0x138` | **`-0x4`** |

### Same-size Content Changes

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

-8.0.38.0.0
+8.0.43.0.0

-  Functions: 1738
-  Symbols:   252
-  CStrings:  604
+  Functions: 1703
+  Symbols:   251
+  CStrings:  590
Symbols:
+ _OBJC_CLASS_$_OS_os_log
+ __os_signpost_emit_with_name_impl
- _AMSAccountMediaTypeAppStoreBeta
- _AMSAccountMediaTypeAppStoreSandbox
- _AMSAccountMediaTypeProduction
CStrings:
+ "JSInvocation"
+ "JetpackDownload"
+ "JetpackLoad"
+ "[Error] Interval already ended"
+ "failed"
+ "succeeded"
+ "success=%ld"
- " promise, reason:"
- "Could not reject "
- "Could not resolve "
- "Failed to fetch selected profile. Error:"
- "Failed to fetch simple profiles. Error:"
- "Invalid media type"
- "Simple profile not found: "
- "Sponsor not found: "
- "ams_isSimpleProfile"
- "ams_selectedProfileForMediaType:"
- "ams_simpleProfileAccounts"
- "ams_simpleProfileAccountsForMediaType:"
- "ams_sponsorAccount"
- "selectedProfileForMediaType(_:)"
- "selectedProfileForMediaType(_:) called without active JS worker thread"
- "selectedProfileForMediaType:"
- "simpleProfilesForMediaType(_:)"
- "simpleProfilesForMediaType(_:) called without active JS worker thread"
- "simpleProfilesForMediaType:"
- "simpleProfilesForSponsor:"
- "sponsorForSimpleProfile:"
```
