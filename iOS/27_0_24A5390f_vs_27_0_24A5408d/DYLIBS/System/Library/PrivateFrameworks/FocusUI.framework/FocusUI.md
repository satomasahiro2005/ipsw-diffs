## FocusUI

> `/System/Library/PrivateFrameworks/FocusUI.framework/FocusUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23db8` | `0x23ff0` | **`+0x238`** |
| `__AUTH_CONST.__objc_const` | `0x9ec8` | `0x9fd8` | **`+0x110`** |
| `__TEXT.__objc_methlist` | `0x2fbc` | `0x301c` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x458` | `0x4a8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bc0` | `0x1be0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x928` | `0x918` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xc00` | `0xc10` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x2f8` | `0x304` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x478` | `0x480` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x118` | `0x120` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0xe0` | `0xe8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-508.0.0.0.0
+511.0.0.0.0

-  - /usr/lib/swift/libswiftCallKit.dylib

-  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

-  Functions: 994
-  Symbols:   2030
+  Functions: 1001
+  Symbols:   2043
Symbols:
+ -[FCUIFocusEnablementIndicatorSystemApertureElement _reservedOnOffLabelWidth]
+ -[_FCUIFocusEnablementReservedWidthView .cxx_destruct]
+ -[_FCUIFocusEnablementReservedWidthView initWithContentView:]
+ -[_FCUIFocusEnablementReservedWidthView layoutSubviews]
+ -[_FCUIFocusEnablementReservedWidthView reservedWidth]
+ -[_FCUIFocusEnablementReservedWidthView setReservedWidth:]
+ -[_FCUIFocusEnablementReservedWidthView sizeThatFits:]
+ GCC_except_table31
+ GCC_except_table41
+ _OBJC_CLASS_$__FCUIFocusEnablementReservedWidthView
+ _OBJC_IVAR_$_FCUIFocusEnablementIndicatorSystemApertureElement._onOffTrailingWrapperView
+ _OBJC_IVAR_$__FCUIFocusEnablementReservedWidthView._contentView
+ _OBJC_IVAR_$__FCUIFocusEnablementReservedWidthView._reservedWidth
+ _OBJC_METACLASS_$__FCUIFocusEnablementReservedWidthView
+ __OBJC_$_INSTANCE_METHODS__FCUIFocusEnablementReservedWidthView
+ __OBJC_$_INSTANCE_VARIABLES__FCUIFocusEnablementReservedWidthView
+ __OBJC_$_PROP_LIST__FCUIFocusEnablementReservedWidthView
+ __OBJC_CLASS_RO_$__FCUIFocusEnablementReservedWidthView
+ __OBJC_METACLASS_RO_$__FCUIFocusEnablementReservedWidthView
- GCC_except_table25
- GCC_except_table35
- __swift_FORCE_LOAD_$_swiftCallKit
- __swift_FORCE_LOAD_$_swiftCallKit_$_FocusUI
- __swift_FORCE_LOAD_$_swiftCoreAudio_Private
- __swift_FORCE_LOAD_$_swiftCoreAudio_Private_$_FocusUI
CStrings:
+ "\xb11"
- "\xa11"
```
