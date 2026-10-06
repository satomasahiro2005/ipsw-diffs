## libFDR.dylib

> `/usr/lib/libFDR.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b6dc` | `0x8b7d0` | **`+0xf4`** |
| `__TEXT.__cstring` | `0x23549` | `0x2359d` | **`+0x54`** |
| `__AUTH_CONST.__cfstring` | `0xfaa0` | `0xfac0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1220` | `0x1228` | **`+0x8`** |

### Other Changes

```diff

-1636.0.12.0.0
+1636.0.16.0.0

-  Functions: 4632
-  Symbols:   1725
-  CStrings:  4190
+  Functions: 4634
+  Symbols:   1726
+  CStrings:  4191
Symbols:
+ _AMFDRSealingMapCopyMultiInstanceForClassWithOptions
CStrings:
+ "AMFDRSealingMapCopyMultiInstanceForClassWithOptions"
+ "there's something wrong with subCC digest for %@:%@, subCC check failing"
- "AMFDRSealingMapCopyMultiInstanceForClass"
```
