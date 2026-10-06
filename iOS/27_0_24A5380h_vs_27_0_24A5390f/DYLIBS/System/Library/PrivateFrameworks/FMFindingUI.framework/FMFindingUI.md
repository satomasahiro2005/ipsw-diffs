## FMFindingUI

> `/System/Library/PrivateFrameworks/FMFindingUI.framework/FMFindingUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x172cb0` | `0x1745e0` | **`+0x1930`** |
| `__DATA.__bss` | `0xbc70` | `0xbdf0` | **`+0x180`** |
| `__AUTH_CONST.__const` | `0xe5f1` | `0xe741` | **`+0x150`** |
| `__TEXT.__cstring` | `0x5175` | `0x5295` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x69f0` | `0x6b10` | **`+0x120`** |
| `__TEXT.__const` | `0xe134` | `0xe1e4` | **`+0xb0`** |
| `__DATA.__data` | `0x49f0` | `0x4a40` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xaf8` | `0xab8` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x3750` | `0x3788` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x3270` | `0x32a4` | **`+0x34`** |
| `__TEXT.__swift5_typeref` | `0xa892` | `0xa8b6` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d48` | `0x1d68` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x5300` | `0x531c` | **`+0x1c`** |
| `__TEXT.__constg_swiftt` | `0x8150` | `0x813c` | **`-0x14`** |
| `__AUTH.__data` | `0x3080` | `0x3090` | **`+0x10`** |
| `__DATA.__common` | `0xad8` | `0xac8` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x2494` | `0x24a4` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x6d62` | `0x6d52` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x62c` | `0x638` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x16b0` | `0x16b8` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x10d20` | `0x10d28` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa98` | `0xaa0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x3d4` | `0x3d8` | **`+0x4`** |

### Other Changes

```diff

-104.30.6.14.3
+104.30.6.14.9

-  Functions: 6621
-  Symbols:   499
-  CStrings:  960
+  Functions: 6649
+  Symbols:   501
+  CStrings:  969
Symbols:
+ _OBJC_CLASS_$_UIFontMetrics
+ _swift_task_deinitOnExecutor
CStrings:
+ ".startedWithLowUpdateRate"
+ "FMFindingLocalizedString ORIENTATION_ROTATE_TO_UPSIDE_DOWN_ROTATE"
+ "FMFindingLocalizedString ORIENTATION_ROTATE_TO_UPSIDE_DOWN_UPSIDE_DOWN"
+ "ORIENTATION_ROTATE_TO_UPSIDE_DOWN_ROTATE"
+ "ORIENTATION_ROTATE_TO_UPSIDE_DOWN_UPSIDE_DOWN"
+ "updatePulseNearProgress dropping progress %f, d=%f"
+ "🧭 FMFindingViewCtrl: Turning torch off on finding session end"
+ "🧭 FMR1NIContxt%@: suspendedWithReason is not from expected niSession, returning."
+ "🧭 FMR1NIContxt: activity changed to: %{public}s"
+ "🧭 FMR1NIContxt: itemLocalizerState changed to: %{public}s"
+ "🧭 FMR1NIContxt: itemState changed to: %{public}s"
- "🧭 FMR1NIContxt%@: asked to start localizer (but already is)"
- "🧭 FMR1NIContxt%@: asked to start localizer (but waiting to be stopped first)"
```
