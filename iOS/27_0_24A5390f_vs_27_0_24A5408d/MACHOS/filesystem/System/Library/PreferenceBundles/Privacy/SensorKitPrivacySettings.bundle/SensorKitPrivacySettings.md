## SensorKitPrivacySettings

> `/System/Library/PreferenceBundles/Privacy/SensorKitPrivacySettings.bundle/SensorKitPrivacySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x14eb` | `0x15a3` | **`+0xb8`** |
| `__TEXT.__objc_stubs` | `0x1740` | `0x17e0` | **`+0xa0`** |
| `__TEXT.__text` | `0x4230` | `0x42a4` | **`+0x74`** |
| `__DATA.__objc_selrefs` | `0x700` | `0x728` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x158` | `0x160` | **`+0x8`** |
| `__TEXT.__cstring` | `0x56f` | `0x572` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1038.0.0.0.0
+1039.0.1.0.0

-  Symbols:   110
-  CStrings:  364
+  Symbols:   111
+  CStrings:  369
Symbols:
+ _OBJC_CLASS_$_UIImageSymbolConfiguration
Functions:
~ sub_3218 : 244 -> 360
CStrings:
+ "_systemImageNamed:withConfiguration:"
+ "configurationByApplyingConfiguration:"
+ "configurationPreferringMonochrome"
+ "configurationWithScale:"
+ "customSymbolName"
+ "imageByApplyingSymbolConfiguration:"
+ "imageNamed:inBundle:withConfiguration:"
+ "iphone"
+ "length"
+ "symbolName"
- "firstObject"
- "imageNamed:inBundle:"
- "lowercaseString"
- "mix"
- "platforms"
```
