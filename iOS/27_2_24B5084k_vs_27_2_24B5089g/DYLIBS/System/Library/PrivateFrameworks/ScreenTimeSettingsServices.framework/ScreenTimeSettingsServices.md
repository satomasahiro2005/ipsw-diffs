## ScreenTimeSettingsServices

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsServices.framework/ScreenTimeSettingsServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16f120` | `0x171f38` | **`+0x2e18`** |
| `__DATA.__data` | `0x2c88` | `0x3150` | **`+0x4c8`** |
| `__DATA.__bss` | `0x213b0` | `0x216b0` | **`+0x300`** |
| `__DATA_DIRTY.__bss` | `0x12200` | `0x11f00` | **`-0x300`** |
| `__AUTH.__data` | `0x988` | `0x6c0` | **`-0x2c8`** |
| `__DATA_DIRTY.__data` | `0x36b0` | `0x3468` | **`-0x248`** |
| `__TEXT.__eh_frame` | `0x9f88` | `0xa098` | **`+0x110`** |
| `__TEXT.__oslogstring` | `0x2310` | `0x23b0` | **`+0xa0`** |
| `__AUTH.__objc_data` | `0x198` | `0x100` | **`-0x98`** |
| `__DATA_DIRTY.__objc_data` | `0x98` | `0x130` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x5ea8` | `0x5ef0` | **`+0x48`** |
| `__DATA.__common` | `0xb8` | `0xd8` | **`+0x20`** |
| `__DATA_DIRTY.__common` | `0x70` | `0x50` | **`-0x20`** |

### Other Changes

```diff

-97.1.6.1.0
+97.1.9.0.0

-  Functions: 9500
+  Functions: 9512

-  CStrings:  633
+  CStrings:  635
CStrings:
+ "Failed to fetch allowed web domains when blocking web domains: %{public}s"
+ "Failed to fetch blocked web domains when allowing web domains: %{public}s"
```
