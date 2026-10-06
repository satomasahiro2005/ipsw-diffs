## Feedback

> `/System/Library/PrivateFrameworks/Feedback.framework/Feedback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10ae9c` | `0x10bb7c` | **`+0xce0`** |
| `__TEXT.__oslogstring` | `0x3c2a` | `0x3cba` | **`+0x90`** |
| `__TEXT.__cstring` | `0x4376` | `0x43f6` | **`+0x80`** |
| `__DATA_DIRTY.__data` | `0x22e8` | `0x2348` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x3290` | `0x32d0` | **`+0x40`** |
| `__DATA_DIRTY.__objc_data` | `0x19e8` | `0x1a28` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x242a` | `0x246a` | **`+0x40`** |
| `__TEXT.__const` | `0xafe4` | `0xb014` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x39e0` | `0x3a10` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x508` | `0x528` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xa50` | `0xa70` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2748` | `0x2760` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x32d8` | `0x32c0` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x9b0` | `0x9c0` | **`+0x10`** |

### Other Changes

```diff

-232.0.0.0.0
+235.0.0.0.0

-  Functions: 5180
+  Functions: 5195

-  CStrings:  659
+  CStrings:  664
Symbols:
+ _keypath_get.18Tm
+ _keypath_get.38Tm
+ _keypath_get.44Tm
+ _keypath_set.45Tm
- _keypath_get.16Tm
- _keypath_get.36Tm
- _keypath_get.40Tm
- _keypath_set.43Tm
CStrings:
+ "Did start Feedback Session with Form [%{public}s]"
+ "Form [%{public}s]: disableGatherAndSubmit: [%{bool,public}d]"
+ "Form [%{public}s]: removesDeletedDEAttachments: [%{bool,public}d]"
+ "Will start draft with form [%{public}s]"
+ "disableGatherAndSubmit"
+ "feedbackDraftViewControllerDidFinishBackgroundCleanup(_:)"
+ "removesDeletedDEAttachments"
- "Did start Feedback Session with Form [%{public}ld]"
- "Will start draft with form [%{public}ld]"
```
