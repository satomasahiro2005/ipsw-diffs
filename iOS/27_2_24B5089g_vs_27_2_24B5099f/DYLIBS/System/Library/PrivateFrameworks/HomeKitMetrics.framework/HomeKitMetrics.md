## HomeKitMetrics

> `/System/Library/PrivateFrameworks/HomeKitMetrics.framework/HomeKitMetrics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x85950` | `0x878dc` | **`+0x1f8c`** |
| `__TEXT.__oslogstring` | `0x1dca` | `0x1eaa` | **`+0xe0`** |
| `__AUTH.__data` | `0xe10` | `0xeb0` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x3a80` | `0x39e8` | **`-0x98`** |
| `__AUTH_CONST.__objc_const` | `0x6408` | `0x6378` | **`-0x90`** |
| `__DATA.__bss` | `0x24b0` | `0x2420` | **`-0x90`** |
| `__DATA_DIRTY.__bss` | `0x1c30` | `0x1cc0` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x2828` | `0x27a8` | **`-0x80`** |
| `__DATA.__data` | `0x14b0` | `0x1520` | **`+0x70`** |
| `__AUTH.__objc_data` | `0xbe8` | `0xc38` | **`+0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x11a0` | `0x11f0` | **`+0x50`** |
| `__DATA_DIRTY.__data` | `0x2478` | `0x24b8` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x190d` | `0x194d` | **`+0x40`** |
| `__TEXT.__const` | `0x4c80` | `0x4c50` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1018` | `0x1038` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2150` | `0x2170` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1e88` | `0x1ea2` | **`+0x1a`** |
| `__TEXT.__swift5_fieldmd` | `0x1bdc` | `0x1bf4` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x598` | `0x588` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x24f4` | `0x2504` | **`+0x10`** |
| `__DATA.__common` | `0x60` | `0x68` | **`+0x8`** |

### Other Changes

```diff

-1516.0.0.0.0
+1520.2.3.0.2

-  Functions: 2984
+  Functions: 3006

-  CStrings:  317
+  CStrings:  319
Symbols:
+ _symbolic _____ySSSgG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G 15Synchronization5_CellVAARi_zrlE 14HomeKitMetrics20ReadableCounterGroupC5StateV
- ___swift_memcpy56_8
- _type_layout_string 14HomeKitMetrics20ReadableCounterGroupC5StateV
CStrings:
+ "Wall clock diverged from uptime by %{public}fs over %{public}fs. Deriving the segment start from the monotonic clock."
+ "Wall clock moved %{public}fs behind time already credited. Dropping a %{public}fs segment."
```
