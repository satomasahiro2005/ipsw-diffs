## SiriProcessing

> `/System/Library/PrivateFrameworks/SiriProcessing.framework/SiriProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3954` | `0xd4304` | **`+0x9b0`** |
| `__TEXT.__oslogstring` | `0x1f60` | `0x2070` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0x1cc2` | `0x1cf2` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x810` | `0x820` | **`+0x10`** |
| `__TEXT.__const` | `0x9f90` | `0x9f80` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x34b0` | `0x34c0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x25e4` | `0x25f0` | **`+0xc`** |
| `__AUTH_CONST.__const` | `0x5ec0` | `0x5ec8` | **`+0x8`** |

### Other Changes

```diff

-2.8.0.0.0
+2.9.0.0.0

-  Functions: 3786
-  Symbols:   1575
-  CStrings:  239
+  Functions: 3791
+  Symbols:   1576
+  CStrings:  241
Symbols:
+ _OBJC_CLASS_$_LRSchemaLRRedactionExclusionSignal
CStrings:
+ "Composite predicate for %s has a .not carve-out but its SensitiveConditionTag wasn't marked with a known exclusion reason; dropping the exclusion instead of guessing."
+ "Failed to allocate LRSchemaLRRedactionExclusionSignal for %s; dropping this exclusion."
```
