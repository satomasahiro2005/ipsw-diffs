## TextInputUI

> `/System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x134df0` | `0x1350f4` | **`+0x304`** |
| `__TEXT.__oslogstring` | `0x6081` | `0x618c` | **`+0x10b`** |
| `__AUTH_CONST.__const` | `0x2be0` | `0x2c30` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0xfebc` | `0xfe84` | **`-0x38`** |
| `__TEXT.__swift5_typeref` | `0x196a` | `0x198c` | **`+0x22`** |
| `__TEXT.__swift5_capture` | `0x4e4` | `0x4f8` | **`+0x14`** |
| `__AUTH.__objc_data` | `0x39e0` | `0x39d0` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x17d8` | `0x17c8` | **`-0x10`** |
| `__AUTH_CONST.__objc_const` | `0x197f8` | `0x197f0` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x4228` | `0x4220` | **`-0x8`** |

### Other Changes

```diff

-9127.0.84.1.901
+9127.0.84.1.112

-  Functions: 6865
+  Functions: 6866

-  CStrings:  2727
+  CStrings:  2729
Symbols:
+ -[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]
+ ___92-[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke
+ ___92-[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke_2
+ _symbolic So28TIKeyboardCandidateResultSetC
- +[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]
- __OBJC_$_CLASS_METHODS_TUIInputSession
- ___92+[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke
- ___92+[TUIInputSession _shouldUseSecureDisplayForCandidates:withBundleId:usesCandidateSelection:]_block_invoke_2
CStrings:
+ "Autocorrection list contains candidates to be redacted.  Unsupported selector `redactedList`.  Sending empty autocorrection list instead."
+ "Candidate result set contains candidates to be redacted.  Unsupported selector `redactedSet`.  Sending empty result set instead."
```
