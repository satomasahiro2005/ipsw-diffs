## ClockKit

> `/System/Library/Frameworks/ClockKit.framework/ClockKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xfc50` | `0xfc20` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x97fc` | `0x97ec` | **`-0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x36b8` | `0x36b0` | **`-0x8`** |
| `__TEXT.__text` | `0x6c184` | `0x6c17c` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xb0c` | `0xb08` | **`-0x4`** |

### Other Changes

```diff

-2483.523.0.4.0
+2483.543.0.0.0

-  Functions: 3857
-  Symbols:   6851
+  Functions: 3856
+  Symbols:   6849
Symbols:
+ GCC_except_table183
- -[CLKDevice supportsSkeletons]
- GCC_except_table184
- _OBJC_IVAR_$_CLKDevice._supportsSkeletons
Functions:
+ -[CLKDevice setSupportedCapabilitiesCache:]
- -[CLKDevice setSupportedCapabilitiesCache:]
- -[CLKDevice setSupportsCompanionSync:]
```
