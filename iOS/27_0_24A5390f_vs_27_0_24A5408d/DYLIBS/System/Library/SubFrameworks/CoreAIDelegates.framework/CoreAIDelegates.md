## CoreAIDelegates

> `/System/Library/SubFrameworks/CoreAIDelegates.framework/CoreAIDelegates`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33a38` | `0x391fc` | **`+0x57c4`** |
| `__DATA.__bss` | `0x2a00` | `0x2c00` | **`+0x200`** |
| `__TEXT.__cstring` | `0x157d` | `0x174d` | **`+0x1d0`** |
| `__AUTH_CONST.__const` | `0x23f8` | `0x2520` | **`+0x128`** |
| `__TEXT.__const` | `0x1cbc` | `0x1dd4` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0xa18` | `0xab8` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x1858` | `0x18f0` | **`+0x98`** |
| `__TEXT.__swift5_fieldmd` | `0x78c` | `0x818` | **`+0x8c`** |
| `__AUTH.__data` | `0x3c0` | `0x448` | **`+0x88`** |
| `__TEXT.__swift5_reflstr` | `0x69e` | `0x70e` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0xc88` | `0xce0` | **`+0x58`** |
| `__TEXT.__constg_swiftt` | `0x4e0` | `0x534` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0xbf` | `0x10f` | **`+0x50`** |
| `__DATA.__data` | `0x6d0` | `0x718` | **`+0x48`** |
| `__DATA_CONST.__got` | `0x2c0` | `0x2f0` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x630` | `0x660` | **`+0x30`** |
| `__DATA.__common` | `0xa0` | `0xb8` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x168` | `0x180` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x154` | `0x164` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x80` | `0x84` | **`+0x4`** |
| `__TEXT.__swift5_types2` | `—` | `0x4` | **`+0x4`** |

### Other Changes

```diff

-3600.79.1.0.0
+3600.83.2.11.1

-  Functions: 818
-  Symbols:   153
-  CStrings:  152
+  Functions: 862
+  Symbols:   157
+  CStrings:  164
Symbols:
+ _objc_retain_x21
+ _objc_retain_x28
+ _swift_bridgeObjectRetain_n
+ _swift_initStructMetadata
+ _swift_release_x22
- _swift_dynamicCastClassUnconditional
CStrings:
+ "AIModel.compiledModuleBytecode unavailable as model's directory information could not be retrieved."
+ "COREAI_FORCE_DEBUG_OPTIONS"
+ "COREAI_FORCE_DEBUG_OPTIONS override active — ignoring caller-supplied debugConfiguration"
+ "Could not coalesce asset in app-group "
+ "Failed to move external delegate resources to app-group accessible location"
+ "aotSpecialized"
+ "bookmarkResolve"
+ "cacheHit"
+ "coldSpecialize"
+ "failed"
+ "fileOrDirectorySize: enumeration error at %{public}s: %{public}s"
+ "specializationOptions"
```
