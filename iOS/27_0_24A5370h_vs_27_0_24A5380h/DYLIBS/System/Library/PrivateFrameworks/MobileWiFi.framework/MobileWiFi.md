## MobileWiFi

> `/System/Library/PrivateFrameworks/MobileWiFi.framework/MobileWiFi`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f83c` | `0x2f88c` | **`+0x50`** |
| `__AUTH.__objc_data` | `—` | `0x28` | **`+0x28`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0x28` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0xb68` | `0xb60` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x9cc` | `0x9cf` | **`+0x3`** |

### Other Changes

```diff

-2027.13.0.0.0
+2027.18.0.0.0

-  Functions: 1209
+  Functions: 1208
CStrings:
+ "%s: dispatching roamBasedCellDupRecStart callback (reason=lowRSSI, rssi=%d)"
+ "%s: skipping roamBasedCellDupRecStart callback (reason=%u, rssi=%d)"
- "%s: dispatching roamBasedCellDupRecStart callback (reason=lowRSSI)"
- "%s: skipping roamBasedCellDupRecStart callback (reason=%u is not lowRSSI)"
```
