## SiriVideoIntents

> `/System/Library/PrivateFrameworks/SiriVideoIntents.framework/SiriVideoIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c6574` | `0x1c71bc` | **`+0xc48`** |
| `__TEXT.__oslogstring` | `0xdfd7` | `0xe19d` | **`+0x1c6`** |
| `__TEXT.__eh_frame` | `0x105b8` | `0x106b0` | **`+0xf8`** |
| `__AUTH_CONST.__objc_const` | `0xd838` | `0xd8e8` | **`+0xb0`** |
| `__AUTH.__data` | `0x6a28` | `0x6ac8` | **`+0xa0`** |
| `__TEXT.__const` | `0x150e0` | `0x15170` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x6c50` | `0x6cb4` | **`+0x64`** |
| `__TEXT.__unwind_info` | `0x7960` | `0x79b8` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0x638a` | `0x63da` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x12028` | `0x12060` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x16d8` | `0x1708` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x6368` | `0x6394` | **`+0x2c`** |
| `__TEXT.__swift5_reflstr` | `0x5c17` | `0x5c30` | **`+0x19`** |
| `__DATA.__data` | `0x43d0` | `0x43b8` | **`-0x18`** |
| `__DATA_CONST.__got` | `0x10a8` | `0x10b8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x2a0` | `0x2b0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xab4` | `0xac4` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x400` | `0x408` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x94c` | `0x954` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xd3c` | `0xd40` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x108` | `0x10c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x688` | `0x68c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x82c` | `0x830` | **`+0x4`** |

### Other Changes

```diff

-3600.28.6.0.0
+3600.28.7.0.0
+  - /System/Library/Frameworks/AVRouting.framework/AVRouting

-  Functions: 11601
-  Symbols:   3381
-  CStrings:  1446
+  Functions: 11617
+  Symbols:   3390
+  CStrings:  1450
Symbols:
+ _OBJC_CLASS_$_AVOutputContext
+ _OBJC_CLASS_$_AVOutputDevice
+ __DATA__TtC16SiriVideoIntents26CarPlayVideoOutputProvider
+ __METACLASS_DATA__TtC16SiriVideoIntents26CarPlayVideoOutputProvider
+ ___unnamed_21
+ _symbolic $s16SiriVideoIntents07CarPlayB15OutputProvidingP
+ _symbolic Sccyyt______pG s5ErrorP
+ _symbolic _____ 16SiriVideoIntents07CarPlayB14OutputProviderC
+ _symbolic ______p 16SiriVideoIntents07CarPlayB15OutputProvidingP
CStrings:
+ "CarPlayVideoOutputProvider.setCarPlayVideoActive() attempted to find CarPlay AVDevice, but none found"
+ "CarPlayVideoOutputProvider.setCarPlayVideoActive() attempted to set CarPlayActive, but not allowed in current state (e.g., user might be driving)"
+ "CarPlayVideoOutputProvider.setCarPlayVideoActive() failed to set CarPlay active: %s"
+ "CarPlayVideoOutputProvider.setCarPlayVideoActive() setting video active"
```
