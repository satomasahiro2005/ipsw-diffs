## CoreRepairUI

> `/System/Library/PrivateFrameworks/CoreRepairUI.framework/CoreRepairUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e3a8` | `0x1e648` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x3d1c` | `0x3dd9` | **`+0xbd`** |
| `__AUTH_CONST.__cfstring` | `0x49c0` | `0x4a00` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x428` | `0x450` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x1724` | `0x1734` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xdb8` | `0xdc0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x538` | `0x540` | **`+0x8`** |

### Other Changes

```diff

-1307.40.46.0.0
+1307.40.51.0.0

-  Functions: 516
+  Functions: 518

-  CStrings:  730
+  CStrings:  733
CStrings:
+ "-[MRBaseComponentHandler sendFinishRepairNotificationShownAnalytics]_block_invoke"
+ "CoreAnalyticsEvent: ModuleType(%@), EventType(FinishRepairNotificationShown)"
+ "FinishRepairNotificationShown"
```
