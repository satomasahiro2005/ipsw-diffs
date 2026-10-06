## BrailleFoundation

> `/System/Library/PrivateFrameworks/BrailleFoundation.framework/BrailleFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cb64` | `0x6ce04` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0xf83` | `0xfcb` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x960` | `0x9a0` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x12f0` | `0x1320` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x624` | `0x63c` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2bc8` | `0x2be0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e8` | `0x3f8` | **`+0x10`** |
| `__TEXT.__const` | `0xcd80` | `0xcd90` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x176d` | `0x177d` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x120` | `0x118` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2108` | `0x2110` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xa4` | `0xa8` | **`+0x4`** |

### Other Changes

```diff

-467.3.0.0.0
+467.3.1.0.0

-  - /usr/lib/swift/libswiftNaturalLanguage.dylib

-  Functions: 3214
-  Symbols:   10844
-  CStrings:  147
+  Functions: 3217
+  Symbols:   10847
+  CStrings:  150
Symbols:
+ -[BRLElement placeholderValue]
+ -[BRLElement setPlaceholderValue:]
+ _$s17BrailleFoundation0A13LayoutElementV16placeholderValueSSvg
+ _$s17BrailleFoundation0A13LayoutElementV16placeholderValueSSvpMV
+ _OBJC_IVAR_$_BRLElement._placeholderValue
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
- __swift_FORCE_LOAD_$_swiftNaturalLanguage_$_BrailleFoundation
CStrings:
+ "_placeholderValue"
+ "placeholderValue"
+ "placeholderValue = %@"
```
