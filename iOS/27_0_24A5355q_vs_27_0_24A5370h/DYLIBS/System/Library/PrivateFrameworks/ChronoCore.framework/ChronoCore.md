## ChronoCore

> `/System/Library/PrivateFrameworks/ChronoCore.framework/ChronoCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4153cc` | `0x4159fc` | **`+0x630`** |
| `__AUTH_CONST.__const` | `0x13668` | `0x135c8` | **`-0xa0`** |
| `__TEXT.__oslogstring` | `0x15807` | `0x15887` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x5564` | `0x551c` | **`-0x48`** |
| `__TEXT.__eh_frame` | `0xc4b8` | `0xc488` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x1db0` | `0x1db8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x7520` | `0x7518` | **`-0x8`** |

### Other Changes

```diff

-721.0.0.0.0
+727.0.0.0.0

-  Functions: 10898
+  Functions: 10895

-  CStrings:  1973
+  CStrings:  1974
CStrings:
+ "Activity [%{public}s] not authorized for accessory [%{public}s - activityBundleID: %{public}s]"
+ "Activity[%{public}s] for alert coordination didn't have a valid title and body for presentation, ignoring."
+ "Error clearing temporary directory contents on startup: %{public}@"
+ "Error raising Jetsam Inactive Priority: %{public}s"
+ "Successfully cleared temporary directory (%{public}@) contents on startup."
- "Activity [%{public}s] not authorized for accessory [%{public}s - activityBundleID: %s]"
- "Error clearing temporary directory contents on startup: %@"
- "Error raising Jetsam Inactive Priority: %s"
- "Successfully cleared temporary directory (%@) contents on startup."
```
