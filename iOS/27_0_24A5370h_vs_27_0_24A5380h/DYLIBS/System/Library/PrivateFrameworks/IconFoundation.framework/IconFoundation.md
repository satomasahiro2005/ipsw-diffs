## IconFoundation

> `/System/Library/PrivateFrameworks/IconFoundation.framework/IconFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x618` | `0x410` | **`-0x208`** |
| `__DATA_DIRTY.__objc_data` | `0x938` | `0xb40` | **`+0x208`** |
| `__TEXT.__text` | `0x39668` | `0x39560` | **`-0x108`** |
| `__TEXT.__oslogstring` | `0xcf8` | `0xc2c` | **`-0xcc`** |
| `__AUTH.__data` | `0x98` | `—` | **`-0x98`** |
| `__DATA_DIRTY.__data` | `—` | `0x98` | **`+0x98`** |
| `__TEXT.__cstring` | `0x12bf7` | `0x12c77` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x1b40` | `0x1ba0` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x4c88` | `0x4cc8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x3e8` | `0x3d0` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f08` | `0x1ef8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xf18` | `0xf08` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x30b4` | `0x30bc` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x338` | `0x33c` | **`+0x4`** |

### Other Changes

```diff

-779.0.0.0.0
+785.0.100.0.0

-  - /System/Library/PrivateFrameworks/RenderBox.framework/RenderBox

-  Functions: 1538
-  Symbols:   2532
-  CStrings:  2888
+  Functions: 1534
+  Symbols:   2531
+  CStrings:  2887
Symbols:
+ -[IFPlistParser iconDictionaryExists]
+ -[IFPlistParser isIPadOnly]
+ -[IFPlistParser promoteVariants]
+ -[IFPlistParser setIsIPadOnly:]
+ -[IFPlistParser setPromoteVariants:]
+ -[IFPlistParser(IconContentCapture) dictionaryWithPromotedAlternateIconWithName:variants:]
+ _OBJC_IVAR_$_IFPlistParser._isIPadOnly
+ _OBJC_IVAR_$_IFPlistParser._promoteVariants
- -[IFConcreteImage finalizedIcon]
- -[IFConcreteImage initWithCGImage:scale:finalizedIcon:]
- -[IFConcreteImage setFinalizedIcon:]
- -[IFImage initWithCGImage:scale:finalizedIcon:]
- -[IFPlistParser(IconContentCapture) subDictionaryForAlternateIconName:variants:]
- _OBJC_CLASS_$_ICRFinalizedIcon
- _OBJC_CLASS_$_ICRIconLayer
- _OBJC_CLASS_$_RBDevice
- _OBJC_IVAR_$_IFConcreteImage._finalizedIcon
CStrings:
+ "B"
+ "Failed to extract Info.plist icon keys for %@"
+ "No catalog asset specified in Info.plist for %@"
+ "No such asset with name %@ in bundle: %@"
- "C"
- "Failed to create ICRIconLayer from finalized icon %@"
- "Failed to create finalized icon from serialized data. Error: %@"
- "Failed to serialize finalized icon. Error: %@"
- "No catalog asset specified in Info.plist"
```
