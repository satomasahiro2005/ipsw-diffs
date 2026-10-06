## ShareReporting

> `/System/Library/PrivateFrameworks/ShareReporting.framework/ShareReporting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22ec8` | `0x23d54` | **`+0xe8c`** |
| `__TEXT.__eh_frame` | `0x14d8` | `0x1600` | **`+0x128`** |
| `__TEXT.__cstring` | `0xd64` | `0xe44` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0xcb0` | `0xd10` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x872` | `0x8a2` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x590` | `0x5b8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2758` | `0x2780` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x570` | `0x598` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0xdc4` | `0xde8` | **`+0x24`** |
| `__TEXT.__const` | `0x3f18` | `0x3f38` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x78` | `0x8c` | **`+0x14`** |
| `__TEXT.__objc_methlist` | `0x148` | `0x154` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x48` | `0x54` | **`+0xc`** |
| `__AUTH.__objc_data` | `0x318` | `0x320` | **`+0x8`** |
| `__DATA.__common` | `0x68` | `0x70` | **`+0x8`** |
| `__DATA.__data` | `0x910` | `0x918` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xd8` | `0xe0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x85c` | `0x864` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x8d6` | `0x8de` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x30` | `0x38` | **`+0x8`** |

### Other Changes

```diff

-89.0.0.0.0
+92.0.0.0.0

-  Functions: 1169
-  Symbols:   488
-  CStrings:  102
+  Functions: 1181
+  Symbols:   492
+  CStrings:  107
Symbols:
+ _OBJC_CLASS_$_NSString
+ ___swift_memcpy512_8
+ _objc_release_x26
+ _swift_release_x22
+ _swift_release_x27
+ _symbolic ShySSG
+ _symbolic _____yypG s23_ContiguousArrayStorageC
- ___swift_memcpy240_8
- ___swift_memcpy496_8
- _symbolic ShySSGSg
CStrings:
+ "Checking if any URLs are registered."
+ "Failed to check for registered URLs."
+ "Failed to check for registered URLs. "
+ "com.apple.sharereporting.hasAnyRegisteredURLs"
+ "uploadedReportIdentifier"
```
