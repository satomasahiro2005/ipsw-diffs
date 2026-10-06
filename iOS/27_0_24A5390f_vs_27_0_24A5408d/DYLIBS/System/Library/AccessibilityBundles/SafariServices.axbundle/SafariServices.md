## SafariServices

> `/System/Library/AccessibilityBundles/SafariServices.axbundle/SafariServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5974` | `0x584c` | **`-0x128`** |
| `__AUTH_CONST.__cfstring` | `0x2080` | `0x2040` | **`-0x40`** |
| `__TEXT.__cstring` | `0x18ca` | `0x188e` | **`-0x3c`** |
| `__AUTH_CONST.__const` | `0xe0` | `0xc0` | **`-0x20`** |
| `__DATA_CONST.__const` | `0x1b8` | `0x198` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x478` | `0x460` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x298` | `0x290` | **`-0x8`** |

### Other Changes

```diff

-3045.0.0.0.0
+3048.0.0.0.0

-  Functions: 190
-  Symbols:   566
-  CStrings:  297
+  Functions: 189
+  Symbols:   563
+  CStrings:  294
Symbols:
+ GCC_except_table118
+ GCC_except_table120
+ GCC_except_table169
+ GCC_except_table45
- GCC_except_table119
- GCC_except_table121
- GCC_except_table170
- GCC_except_table46
- _OBJC_CLASS_$_NSDictionary
- ___96-[SFRegisterableBarButtonGroupContainerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
- ___block_descriptor_32_e15_v32?0816^B24l
Functions:
~ +[SFRegisterableBarButtonGroupContainerAccessibility _accessibilityPerformValidations:] : 108 -> 32
~ -[SFRegisterableBarButtonGroupContainerAccessibility _accessibilityLoadAccessibilityInformation] : 212 -> 92
- ___96-[SFRegisterableBarButtonGroupContainerAccessibility _accessibilityLoadAccessibilityInformation]_block_invoke
CStrings:
- "SFBarButtonGroupContainer"
- "buttonIdentifiers"
- "v32@?0@8@16^B24"
```
