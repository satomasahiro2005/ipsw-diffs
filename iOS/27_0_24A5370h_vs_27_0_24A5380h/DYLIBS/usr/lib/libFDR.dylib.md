## libFDR.dylib

> `/usr/lib/libFDR.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8b490` | `0x8b6dc` | **`+0x24c`** |
| `__TEXT.__cstring` | `0x234aa` | `0x23549` | **`+0x9f`** |
| `__AUTH_CONST.__cfstring` | `0xfa60` | `0xfaa0` | **`+0x40`** |
| `__DATA.__bss` | `0xf0` | `0xb8` | **`-0x38`** |
| `__DATA_DIRTY.__bss` | `0x108` | `0x140` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x8f0` | `0x8f8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1228` | `0x1220` | **`-0x8`** |

### Other Changes

```diff

-1636.0.1.0.0
+1636.0.12.0.0

-  Functions: 4626
-  Symbols:   1724
-  CStrings:  4185
+  Functions: 4632
+  Symbols:   1725
+  CStrings:  4190
Symbols:
+ _AMFDRDataAddLegacyDataClassesToExport
CStrings:
+ "AMFDRDataAddLegacyDataClassesToExport"
+ "AppendComponentType"
+ "CERTIFY"
+ "CFArrayCreateMutable failed for legacyDataClassesToExport"
+ "dataClass is not a CFStringRef: %@"
```
