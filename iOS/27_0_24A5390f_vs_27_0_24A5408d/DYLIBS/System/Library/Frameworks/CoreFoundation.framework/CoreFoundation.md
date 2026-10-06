## CoreFoundation

> `/System/Library/Frameworks/CoreFoundation.framework/CoreFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d29c0` | `0x1d2fc0` | **`+0x600`** |
| `__AUTH_CONST.__const` | `0x4d00` | `0x4d20` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6540` | `0x6560` | **`+0x20`** |
| `__DATA.__bss` | `0x85c` | `0x874` | **`+0x18`** |
| `__TEXT.__cstring` | `0x14b36c` | `0x14b381` | **`+0x15`** |
| `__DATA_CONST.__objc_selrefs` | `0x2b20` | `0x2b28` | **`+0x8`** |

### Other Changes

```diff

-5027.0.63.2.0
+5027.0.69.0.0

-  Functions: 8601
-  Symbols:   11459
-  CStrings:  44298
+  Functions: 8609
+  Symbols:   11466
+  CStrings:  44299
Symbols:
+ _OUTLINED_FUNCTION_47
+ _OUTLINED_FUNCTION_48
+ __CFCharacterSetIsLongCharacterMemberForInline
+ ___CFCharacterSetGetExpandedSetForNSCharacterSet
+ ___CFCharacterSetLongCharacterMemberIMPForSet.onceToken
+ ___CFCharacterSetLongCharacterMemberIMPForSet.swiftIMP
+ ___CFCharacterSetLongCharacterMemberIMPForSet.swiftImmortalIMP
+ _____CFCharacterSetLongCharacterMemberIMPForSet_block_invoke
- ___CFCheckForExapendedSet
CStrings:
+ "_NSSwiftCharacterSet"
```
