## IMFoundation

> `/System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xa50` | `0xc80` | **`+0x230`** |
| `__DATA_DIRTY.__objc_data` | `0xa50` | `0x820` | **`-0x230`** |
| `__TEXT.__text` | `0x49ed4` | `0x49fdc` | **`+0x108`** |
| `__TEXT.__unwind_info` | `0x18f0` | `0x1940` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x3cd3` | `0x3cfb` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x22a0` | `0x22c0` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x5a0` | `0x5c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x6c37` | `0x6c54` | **`+0x1d`** |
| `__DATA.__bss` | `0xe68` | `0xe58` | **`-0x10`** |

### Other Changes

```diff

-1134.100.1.0.0
+1135.100.1.0.0

-  Functions: 2484
-  Symbols:   1531
-  CStrings:  1645
+  Functions: 2487
+  Symbols:   1532
+  CStrings:  1648
Symbols:
+ _IMXPCLogHandle
CStrings:
+ "Failed to encode codable for key %s: %@"
+ "IMXPC"
+ "com.apple.IMFoundation"
```
