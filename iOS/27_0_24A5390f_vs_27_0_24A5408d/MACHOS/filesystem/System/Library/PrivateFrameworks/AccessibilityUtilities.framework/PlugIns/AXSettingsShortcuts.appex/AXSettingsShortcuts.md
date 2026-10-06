## AXSettingsShortcuts

> `/System/Library/PrivateFrameworks/AccessibilityUtilities.framework/PlugIns/AXSettingsShortcuts.appex/AXSettingsShortcuts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdd08` | `0xdc9c` | **`-0x6c`** |
| `__TEXT.__auth_stubs` | `0x680` | `0x660` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x11c0` | `0x11a0` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x308d` | `0x3074` | **`-0x19`** |
| `__DATA_CONST.__auth_got` | `0x348` | `0x338` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xb30` | `0xb28` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x340` | `0x338` | **`-0x8`** |

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

-3237.1.0.0.0
+3240.3.0.0.0

-  Symbols:   170
-  CStrings:  700
+  Symbols:   169
+  CStrings:  699
Symbols:
+ _OBJC_CLASS_$_AXTripleClickHelpers
- _CFAbsoluteTimeGetCurrent
- __AXSInvertColorsSetEnabled
Functions:
~ sub_1000019bc : 432 -> 300
~ sub_100001c7c -> sub_100001bf8 : 364 -> 388
CStrings:
+ "toggleAccessibilityShortcutOption:"
- "setClassicInvertColors:"
- "setLastSmartInvertColorsEnablement:"
```
