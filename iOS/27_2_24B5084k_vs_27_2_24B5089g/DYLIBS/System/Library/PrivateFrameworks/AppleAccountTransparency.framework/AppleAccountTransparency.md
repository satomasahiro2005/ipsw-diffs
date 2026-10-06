## AppleAccountTransparency

> `/System/Library/PrivateFrameworks/AppleAccountTransparency.framework/AppleAccountTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71510` | `0x725dc` | **`+0x10cc`** |
| `__TEXT.__eh_frame` | `0x6060` | `0x6130` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x3b7f` | `0x3c3f` | **`+0xc0`** |
| `__TEXT.__const` | `0x4320` | `0x43b0` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0x3610` | `0x3698` | **`+0x88`** |
| `__TEXT.__cstring` | `0x201d` | `0x209d` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x1275` | `0x12f5` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x1300` | `0x1358` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x1c88` | `0x1cc0` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x145c` | `0x1490` | **`+0x34`** |
| `__AUTH.__data` | `0xa30` | `0xa40` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x244` | `0x254` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xac4` | `0xacc` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2cc` | `0x2d4` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x2f4` | `0x2fc` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x195b` | `0x1961` | **`+0x6`** |
| `__TEXT.__swift5_types` | `0x12c` | `0x130` | **`+0x4`** |

### Other Changes

```diff

-448.125.5.1.0
+448.125.5.2.0

-  Functions: 1892
-  Symbols:   909
-  CStrings:  373
+  Functions: 1905
+  Symbols:   912
+  CStrings:  378
Symbols:
+ ___swift_memcpy64_8
+ _symbolic _____ 24AppleAccountTransparency23AATEventSyncCoordinatorC21EligibilityResolution33_54FBD776081054C1793EC4CBDB6201DFLLV
+ _type_layout_string 24AppleAccountTransparency23AATEventSyncCoordinatorC21EligibilityResolution33_54FBD776081054C1793EC4CBDB6201DFLLV
CStrings:
+ "Kill-switch lookup failed; eligibility could not be decided: "
+ "PDP state fetch failed; eligibility could not be decided"
+ "Transparency gate: feature disabled"
+ "Transparency gate: no active account (background cycle)"
+ "[AATEventSyncCoordinator]: Failed to fetch feature-enabled state: %@"
```
