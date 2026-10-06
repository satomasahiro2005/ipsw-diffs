## ShazamKit

> `/System/Library/Frameworks/ShazamKit.framework/ShazamKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0xa78` | `0x1c70` | **`+0x11f8`** |
| `__DATA.__data` | `0x1b2530` | `0x1b1678` | **`-0xeb8`** |
| `__AUTH.__data` | `0x338` | `—` | **`-0x338`** |
| `__TEXT.__text` | `0xa69c8` | `0xa6aa8` | **`+0xe0`** |
| `__AUTH.__objc_data` | `0xa0` | `—` | **`-0xa0`** |
| `__DATA_DIRTY.__objc_data` | `0x2288` | `0x2328` | **`+0xa0`** |
| `__DATA.__bss` | `0x2c28` | `0x2ba8` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x160` | `0x1e0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x14e1` | `0x1531` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x2b68` | `0x2b90` | **`+0x28`** |
| `__TEXT.__const` | `0x22a97` | `0x22aa7` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x36c8` | `0x36d0` | **`+0x8`** |

### Other Changes

```diff

-427.2.4.0.0
+427.2.6.0.0

-  Functions: 3816
+  Functions: 3817

-  CStrings:  590
+  CStrings:  591
CStrings:
+ "Unable to get localized name for bundle identifier %{mask.hash}@: %{public}@"
```
