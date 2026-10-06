## AccessibilityTextSizeModule

> `/System/Library/ControlCenter/Bundles/AccessibilityTextSizeModule.bundle/AccessibilityTextSizeModule`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd13c` | `0xd2e0` | **`+0x1a4`** |
| `__AUTH_CONST.__cfstring` | `0x440` | `0x480` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0xdb8` | `0xde0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x10a0` | `0x10b8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x42d` | `0x43b` | **`+0xe`** |
| `__TEXT.__gcc_except_tab` | `0x68` | `0x5c` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x548` | `0x550` | **`+0x8`** |
| `__TEXT.__const` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0xf9` | `0xf3` | **`-0x6`** |

### Other Changes

```diff

-3245.7.1.0.0
+3245.8.2.0.0

-  Functions: 378
-  Symbols:   266
-  CStrings:  57
+  Functions: 380
+  Symbols:   267
+  CStrings:  59
Symbols:
+ _CGRectOffset
CStrings:
+ "Hidden"
+ "Skipping non-user-facing foreground process %{private}@"
+ "hidden"
- "Got too many foreground applications, should be 1 for a phone"
```
