## CoreFoundation

> `/System/Library/Frameworks/CoreFoundation.framework/CoreFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d1fac` | `0x1d2304` | **`+0x358`** |
| `__TEXT.__cstring` | `0x14b234` | `0x14b349` | **`+0x115`** |
| `__AUTH_CONST.__cfstring` | `0x140d00` | `0x140d80` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x5e2c` | `0x5e20` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x4a8` | `0x4b0` | **`+0x8`** |

### Other Changes

```diff

-5027.0.55.1.0
+5027.0.59.0.0

-  Functions: 8595
+  Functions: 8592

-  CStrings:  44291
+  CStrings:  44295
Symbols:
+ __CFBundleCopyMostAppropriateLocTableDeviceAndPlatformSpecificVariants
+ ___CFStringContainsNullCharacter
+ ____CFBundleCopyMostAppropriateLocTableDeviceAndPlatformSpecificVariants_block_invoke
- _OUTLINED_FUNCTION_47
- __CFBundleGetMostAppropriateLocTableDeviceAndPlatformSpecificVariants
- ____CFBundleGetMostAppropriateLocTableDeviceAndPlatformSpecificVariants_block_invoke
CStrings:
+ "%@ <redacted reason>"
+ "Unexpected end of file while parsing unicode character escape sequence on line %d"
+ "property list dictionary keys cannot contain embedded null characters for XML format"
+ "property list strings cannot contain embedded null characters for XML or OpenStep format"
```
