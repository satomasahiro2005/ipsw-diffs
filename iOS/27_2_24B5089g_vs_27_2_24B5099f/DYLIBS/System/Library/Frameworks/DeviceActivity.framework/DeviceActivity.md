## DeviceActivity

> `/System/Library/Frameworks/DeviceActivity.framework/DeviceActivity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x97310` | `0x96db4` | **`-0x55c`** |
| `__DATA.__bss` | `0x4380` | `0x4300` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x1480` | `0x1500` | **`+0x80`** |
| `__DATA.__common` | `0x60` | `0x30` | **`-0x30`** |
| `__DATA_DIRTY.__common` | `0xa0` | `0xd0` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x10e8` | `0x1118` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x2ef8` | `0x2f28` | **`+0x30`** |
| `__DATA.__data` | `0x968` | `0x950` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0xcf8` | `0xd08` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1aa0` | `0x1ab0` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-407.1.4.0.0
+407.1.5.0.0

-  Functions: 2506
-  Symbols:   802
+  Functions: 2508
+  Symbols:   803
Symbols:
+ _swift_retain_x8
CStrings:
+ "Refreshing all activity due to queryStart (%{public}s) being after now (%{public}s)"
- "Skipping refresh because query start: %{public}s, is out of bounds: %{public}s - %{public}s"
```
