## HomeUI

> `/System/Library/PrivateFrameworks/HomeUI.framework/HomeUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x832624` | `0x8347c4` | **`+0x21a0`** |
| `__DATA.__bss` | `0x14028` | `0x13ea8` | **`-0x180`** |
| `__DATA_DIRTY.__bss` | `0x1650` | `0x17d0` | **`+0x180`** |
| `__DATA.__data` | `0x15ab0` | `0x15990` | **`-0x120`** |
| `__DATA_DIRTY.__data` | `0x1a88` | `0x1b98` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0x15c9c` | `0x15d84` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x3090d` | `0x309dd` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x1c2a8` | `0x1c328` | **`+0x80`** |
| `__TEXT.__const` | `0x1cb80` | `0x1cbc0` | **`+0x40`** |
| `__AUTH.__objc_data` | `0x1d220` | `0x1d250` | **`+0x30`** |
| `__TEXT.__cstring` | `0x437ad` | `0x437dd` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x8053` | `0x8083` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xf5d8` | `0xf5b0` | **`-0x28`** |
| `__TEXT.__constg_swiftt` | `0xe708` | `0xe730` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x4e78` | `0x4e9c` | **`+0x24`** |
| `__AUTH.__data` | `0x62c0` | `0x62a0` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x91918` | `0x91938` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1c22a` | `0x1c20a` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x8c30` | `0x8c4c` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0x7a2c` | `0x7a44` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1c9f8` | `0x1ca10` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x5188` | `0x5198` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xf3c` | `0xf48` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x7150` | `0x7158` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x22480` | `0x22488` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x6d8` | `0x6dc` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x714` | `0x718` | **`+0x4`** |

### Other Changes

```diff

-1263.1.0.1.2
+1265.0.0.1.1

-  Functions: 44615
-  Symbols:   47428
-  CStrings:  9832
+  Functions: 44623
+  Symbols:   47429
+  CStrings:  9836
Symbols:
+ ___swift_closure_destructor.133Tm
+ ___swift_closure_destructor.142Tm
+ ___swift_closure_destructor.89Tm
+ ___swift_closure_destructor.8Tm
+ _keypath_get.16Tm
+ _keypath_get.226Tm
+ _keypath_set.17Tm
+ _keypath_set.227Tm
- ___block_descriptor_48_e8_32s_e28_v24?0"NSNull"8"NSError"16ls32l8
- ___swift_closure_destructor.119Tm
- ___swift_closure_destructor.128Tm
- ___swift_closure_destructor.75Tm
- ___swift_memcpy4_1
- _keypath_get.212Tm
- _keypath_set.213Tm
CStrings:
+ "%s-%s notification clip UUID %{public}s for %{public}s"
+ "Failed to notify post-pairing setup complete for %{public}s: %s"
+ "Notified post-pairing setup is complete for %{public}s"
+ "[ExtendedContentConfigurationOnboardingPolicy] shouldShowExtendedContentConfiguration: hasExtendedContent=%{bool}d, hasExtendedContentConfiguration=%{bool}d, isCommissionedOverNFCWithoutPower=%{bool}d, requiresConfiguration=%{bool}d, isDemoMode=%{bool}d, result=%{bool}d"
+ "init(cameraItem:cameraDelegate:configuration:)"
- "[ExtendedContentConfigurationOnboardingPolicy] shouldShowExtendedContentConfiguration: hasExtendedContent=%{bool}d, hasExtendedContentConfiguration=%{bool}d, isCommissionedOverNFCWithoutPower=%{bool}d, requiresConfiguration=%{bool}d, result=%{bool}d"
```
