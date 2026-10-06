## DeviceDiscoveryUI

> `/System/Library/Frameworks/DeviceDiscoveryUI.framework/DeviceDiscoveryUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12acbc` | `0x12b158` | **`+0x49c`** |
| `__TEXT.__eh_frame` | `0x5374` | `0x533c` | **`-0x38`** |
| `__TEXT.__unwind_info` | `0x30f8` | `0x30f0` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-2122.10.2.2.1
+2124.10.2.2.2

-  Functions: 4291
+  Functions: 4290
CStrings:
+ "Ignoring transfer update for %s, not the tracked endpoint %s"
- "Ignoring PIN failure for transfer %s, not our current endpoint"
```
