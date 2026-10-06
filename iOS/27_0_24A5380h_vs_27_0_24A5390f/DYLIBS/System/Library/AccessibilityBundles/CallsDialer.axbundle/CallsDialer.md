## CallsDialer

> `/System/Library/AccessibilityBundles/CallsDialer.axbundle/CallsDialer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d80` | `0x2e3c` | **`+0xbc`** |
| `__DATA_CONST.__const` | `0x170` | `0x1c0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xcc0` | `0xce0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0xa0` | `0xc0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x4e0` | `0x500` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x198` | `0x1a8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x962` | `0x970` | **`+0xe`** |
| `__DATA_CONST.__objc_selrefs` | `0x368` | `0x370` | **`+0x8`** |

### Other Changes

```diff

-3042.0.0.0.0
+3045.0.0.0.0

-  Functions: 105
-  Symbols:   319
-  CStrings:  120
+  Functions: 109
+  Symbols:   323
+  CStrings:  121
Symbols:
+ -[PHHandsetDialerViewAccessibility _accessibilityLoadAccessibilityInformation]
+ -[PHHandsetDialerViewAccessibility _axAnnotateCallButton]
+ -[PHHandsetDialerViewAccessibility newCallButton]
+ GCC_except_table18
+ GCC_except_table57
+ GCC_except_table94
+ GCC_except_table97
+ ___57-[PHHandsetDialerViewAccessibility _axAnnotateCallButton]_block_invoke
- GCC_except_table14
- GCC_except_table53
- GCC_except_table90
- GCC_except_table93
CStrings:
+ "newCallButton"
```
