## PrivateFederatedLearning

> `/System/Library/PrivateFrameworks/PrivateFederatedLearning.framework/PrivateFederatedLearning`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x83240` | `0x861a4` | **`+0x2f64`** |
| `__TEXT.__eh_frame` | `0x4a40` | `0x4c10` | **`+0x1d0`** |
| `__TEXT.__oslogstring` | `0x1a08` | `0x1b38` | **`+0x130`** |
| `__TEXT.__swift5_reflstr` | `0x20bd` | `0x21ed` | **`+0x130`** |
| `__TEXT.__cstring` | `0x945` | `0x9c5` | **`+0x80`** |
| `__TEXT.__const` | `0x3ae8` | `0x3b58` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1878` | `0x18e8` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x1a98` | `0x1b04` | **`+0x6c`** |
| `__AUTH_CONST.__auth_got` | `0x11e8` | `0x1248` | **`+0x60`** |
| `__DATA.__data` | `0xbd0` | `0xc00` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x2659` | `0x2681` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x112e` | `0x1152` | **`+0x24`** |
| `__AUTH_CONST.__objc_const` | `0x5cf8` | `0x5d18` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x560` | `0x578` | **`+0x18`** |
| `__AUTH.__data` | `0x2da0` | `0x2db0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x264` | `0x274` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x144` | `0x150` | **`+0xc`** |
| `__TEXT.__constg_swiftt` | `0x233c` | `0x2344` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xe0` | `0xe4` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xc4` | `0xc8` | **`+0x4`** |

### Other Changes

```diff

-42.0.0.0.0
+44.0.0.0.0

-  Functions: 1803
-  Symbols:   924
-  CStrings:  218
+  Functions: 1828
+  Symbols:   930
+  CStrings:  226
Symbols:
+ __DATA__TtC24PrivateFederatedLearning22PLEDefaultSinkResolver
+ __IVARS__TtC24PrivateFederatedLearning22PLEDefaultSinkResolver
+ __METACLASS_DATA__TtC24PrivateFederatedLearning22PLEDefaultSinkResolver
+ ___swift_exist.box.addr_destructor
+ _symbolic SDy_____ypG s11AnyHashableV
+ _symbolic _____ 24PrivateFederatedLearning22PLEDefaultSinkResolverC
+ _symbolic _____Sg 15PriMLFoundation6TaskIdV
+ _symbolic ______p 8Morpheus16AnyDictContainerP
+ _symbolic ______p 8Morpheus17AnyArrayContainerP
+ _vDSP_meanv
- __DATA__TtC24PrivateFederatedLearning22PFLDefaultSinkResolver
- __IVARS__TtC24PrivateFederatedLearning22PFLDefaultSinkResolver
- __METACLASS_DATA__TtC24PrivateFederatedLearning22PFLDefaultSinkResolver
- _symbolic _____ 24PrivateFederatedLearning22PFLDefaultSinkResolverC
CStrings:
+ "Failed to parse taskId: %s"
+ "Morpheus program attachment not found: %s"
+ "MorpheusDecoding"
+ "MorpheusExecution"
+ "Recipe for task %s is missing a String value for 'morpheusProgramFileName'; cannot locate the Morpheus program attachment"
+ "Those metrics keys already exist and will be overwritten by the Morpheus result. %s"
+ "morpheusFunction"
+ "morpheusProgramFileName"
```
