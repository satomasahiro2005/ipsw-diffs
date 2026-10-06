## UIKitServices

> `/System/Library/PrivateFrameworks/UIKitServices.framework/UIKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21098` | `0x21400` | **`+0x368`** |
| `__AUTH_CONST.__objc_const` | `0x61f0` | `0x6440` | **`+0x250`** |
| `__TEXT.__objc_methlist` | `0x2e8c` | `0x2f3c` | **`+0xb0`** |
| `__AUTH_CONST.__cfstring` | `0x3960` | `0x39c0` | **`+0x60`** |
| `__DATA.__data` | `0x800` | `0x860` | **`+0x60`** |
| `__AUTH.__objc_data` | `0xf50` | `0xfa0` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x2e0` | `0x300` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x1b0` | `0x1c8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xbd0` | `0xbe8` | **`+0x18`** |
| `__TEXT.__cstring` | `0x45dc` | `0x45f1` | **`+0x15`** |
| `__DATA_CONST.__got` | `0x480` | `0x490` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x750` | `0x760` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x17d0` | `0x17e0` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x170` | `0x180` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2a4` | `0x2b0` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x250` | `0x258` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1d8` | `0x1e0` | **`+0x8`** |

### Other Changes

```diff

-9127.0.71.1.102
+9127.0.75.1.101

-  Functions: 998
-  Symbols:   2350
-  CStrings:  624
+  Functions: 1008
+  Symbols:   2380
+  CStrings:  626
Symbols:
+ +[UISDictationVariant allVariants]
+ +[UISDictationVariant variantForSecureName:]
+ +[UISDictationVariant variantForSelector:]
+ -[UISDictationVariant .cxx_destruct]
+ -[UISDictationVariant glyph]
+ -[UISDictationVariant initWithSecureName:selector:glyph:]
+ -[UISDictationVariant localizedStringForLocalization:]
+ -[UISDictationVariant secureName]
+ -[UISDictationVariant selector]
+ _OBJC_CLASS_$_UISDictationVariant
+ _OBJC_IVAR_$_UISDictationVariant._glyph
+ _OBJC_IVAR_$_UISDictationVariant._secureName
+ _OBJC_IVAR_$_UISDictationVariant._selector
+ _OBJC_METACLASS_$_UISDictationVariant
+ __OBJC_$_CLASS_METHODS_UISDictationVariant
+ __OBJC_$_CLASS_PROP_LIST_UISDictationVariant
+ __OBJC_$_INSTANCE_METHODS_UISDictationVariant
+ __OBJC_$_INSTANCE_VARIABLES_UISDictationVariant
+ __OBJC_$_PROP_LIST_UISDictationVariant
+ __OBJC_$_PROP_LIST_UISSecureVariant
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_UISSecureVariant
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UISSecureVariant
+ __OBJC_$_PROTOCOL_REFS_UISSecureVariant
+ __OBJC_CLASS_PROTOCOLS_$_UISDictationVariant
+ __OBJC_CLASS_PROTOCOLS_$_UISPasteVariant
+ __OBJC_CLASS_RO_$_UISDictationVariant
+ __OBJC_LABEL_PROTOCOL_$_UISSecureVariant
+ __OBJC_METACLASS_RO_$_UISDictationVariant
+ __OBJC_PROTOCOL_$_UISSecureVariant
+ ___34+[UISDictationVariant allVariants]_block_invoke
CStrings:
+ "Dictation"
+ "microphone"
```
