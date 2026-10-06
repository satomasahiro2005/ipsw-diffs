## PriMLFoundation

> `/System/Library/PrivateFrameworks/PriMLFoundation.framework/PriMLFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f4a8` | `0x70aa4` | **`+0x15fc`** |
| `__DATA_DIRTY.__data` | `—` | `0xcb0` | **`+0xcb0`** |
| `__AUTH.__data` | `0x1c38` | `0x11b0` | **`-0xa88`** |
| `__DATA.__data` | `0xb50` | `0x910` | **`-0x240`** |
| `__DATA.__bss` | `0x3710` | `0x3590` | **`-0x180`** |
| `__DATA_DIRTY.__bss` | `—` | `0x180` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x19b0` | `0x1abd` | **`+0x10d`** |
| `__AUTH_CONST.__const` | `0x2678` | `0x2730` | **`+0xb8`** |
| `__TEXT.__const` | `0x3c98` | `0x3d28` | **`+0x90`** |
| `__AUTH.__objc_data` | `0xa0` | `0x50` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x1111` | `0x1161` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x1870` | `0x18b8` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0x35b8` | `0x35e8` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x13f0` | `0x1418` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x1230` | `0x1254` | **`+0x24`** |
| `__TEXT.__cstring` | `0x7e6` | `0x806` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xc70` | `0xc88` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xfc0` | `0xfa8` | **`-0x18`** |
| `__TEXT.__swift5_capture` | `0x24c` | `0x25c` | **`+0x10`** |
| `__DATA.__common` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x268` | `0x270` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x138` | `0x13c` | **`+0x4`** |

### Other Changes

```diff

-35.0.0.0.0
+38.0.0.0.0

-  Functions: 1931
-  Symbols:   683
-  CStrings:  184
+  Functions: 1953
+  Symbols:   686
+  CStrings:  188
Symbols:
+ ___swift__destructor
+ ___swift_assign_boxed_opaque_existential_0
+ ___swift_project_boxed_opaque_existential_0Tm
+ ___swift_project_boxed_opaque_existential_1Tm
+ _swift_getDynamicType
+ _symbolic _____ 15PriMLFoundation22DeviceTargetingSubjectO
- _swift_retain_x26
- _symbolic SS3key_yp5valuetSg
- _symbolic SS_yptSg
CStrings:
+ "Preflight predicate for useCase '%s' -> %{bool}d; predicate: %s; subject: %s"
+ "Preflight predicate for useCase '%s' is a String but does not decode to a JSON object: %s"
+ "Preflight predicate for useCase '%s' is not a String or [String: Any] (type: %s)"
+ "collectionIdPrefix"
+ "preflight_targeting_predicate"
- "privacyBudgetPrefix"
```
