## JetUI

> `/System/Library/PrivateFrameworks/JetUI.framework/JetUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9676c` | `0x9ac38` | **`+0x44cc`** |
| `__AUTH_CONST.__objc_const` | `0x4160` | `0x4800` | **`+0x6a0`** |
| `__TEXT.__const` | `0x9ff8` | `0xa1d8` | **`+0x1e0`** |
| `__AUTH_CONST.__auth_got` | `0x1400` | `0x1548` | **`+0x148`** |
| `__TEXT.__cstring` | `0x142d` | `0x156d` | **`+0x140`** |
| `__DATA.__data` | `0x1cd8` | `0x1de8` | **`+0x110`** |
| `__AUTH.__objc_data` | `0x318` | `0x418` | **`+0x100`** |
| `__DATA_CONST.__got` | `0x790` | `0x870` | **`+0xe0`** |
| `__AUTH.__data` | `0x5a0` | `0x678` | **`+0xd8`** |
| `__TEXT.__swift5_reflstr` | `0x2148` | `0x2218` | **`+0xd0`** |
| `__TEXT.__swift5_typeref` | `0x2872` | `0x291c` | **`+0xaa`** |
| `__TEXT.__objc_methlist` | `0xcfc` | `0xda4` | **`+0xa8`** |
| `__TEXT.__swift5_fieldmd` | `0x2e9c` | `0x2f40` | **`+0xa4`** |
| `__TEXT.__constg_swiftt` | `0x2cc8` | `0x2d54` | **`+0x8c`** |
| `__TEXT.__unwind_info` | `0x2ae0` | `0x2b58` | **`+0x78`** |
| `__DATA.__bss` | `0xa320` | `0xa350` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x12e8` | `0x1308` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0xc8` | `0xd8` | **`+0x10`** |
| `__AUTH_CONST.__const` | `0x8938` | `0x8940` | **`+0x8`** |
| `__DATA.__common` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x390` | `0x398` | **`+0x8`** |

### Other Changes

```diff

-10.0.42.0.0
+10.0.43.0.0

-  Functions: 4621
-  Symbols:   1695
-  CStrings:  159
+  Functions: 4675
+  Symbols:   1727
+  CStrings:  162
Symbols:
+ _OBJC_CLASS_$__TtC5JetUI29NQMLAttributedStringGenerator
+ _OBJC_METACLASS_$__TtC5JetUI29NQMLAttributedStringGenerator
+ __DATA__TtC5JetUI29NQMLAttributedStringGenerator
+ __DATA__TtC5JetUIP33_E0AC8E89C7CE0B680760ED2541D15C3F18OrderedListTracker
+ __INSTANCE_METHODS__TtC5JetUI29NQMLAttributedStringGenerator
+ __IVARS__TtC5JetUI29NQMLAttributedStringGenerator
+ __IVARS__TtC5JetUIP33_E0AC8E89C7CE0B680760ED2541D15C3F18OrderedListTracker
+ __METACLASS_DATA__TtC5JetUI29NQMLAttributedStringGenerator
+ __METACLASS_DATA__TtC5JetUIP33_E0AC8E89C7CE0B680760ED2541D15C3F18OrderedListTracker
+ __PROTOCOLS__TtC5JetUI29NQMLAttributedStringGenerator
+ ___swift_memcpy89_8
+ _swift_getKeyPath
+ _symbolic Say_____G 10Foundation18AttributeContainerV
+ _symbolic Sny_____G 10Foundation16AttributedStringV5IndexV
+ _symbolic _____ 10Foundation15AttributeScopesO
+ _symbolic _____ 10Foundation15AttributeScopesO7SwiftUIE0D12UIAttributesV
+ _symbolic _____ 10Foundation15AttributeScopesO7SwiftUIE0D12UIAttributesV014UnderlineStyleB0O
+ _symbolic _____ 10Foundation15AttributeScopesO7SwiftUIE0D12UIAttributesV015ForegroundColorB0O
+ _symbolic _____ 10Foundation15AttributeScopesO7SwiftUIE0D12UIAttributesV018StrikethroughStyleB0O
+ _symbolic _____ 10Foundation15AttributeScopesO7SwiftUIE0D12UIAttributesV04FontB0O
+ _symbolic _____ 10Foundation16AttributedStringV
+ _symbolic _____ 5JetUI18OrderedListTracker33_E0AC8E89C7CE0B680760ED2541D15C3FLLC
+ _symbolic _____ 5JetUI29NQMLAttributedStringGeneratorC
+ _symbolic _____ 7SwiftUI4FontV
+ _symbolic _____5lower_AA5uppert 10Foundation16AttributedStringV5IndexV
+ _symbolic _____Sg 10Foundation16AttributedStringV5IndexV
+ _symbolic _____Sg 5JetUI18OrderedListTracker33_E0AC8E89C7CE0B680760ED2541D15C3FLLC
+ _symbolic _____Sg 7SwiftUI4FontV
+ _symbolic _____Sg 7SwiftUI4TextV9LineStyleV
+ _symbolic _____m 10Foundation15AttributeScopesO7SwiftUIE0D12UIAttributesV
+ _symbolic _____y_____G 10Foundation24ScopedAttributeContainerV AA0C6ScopesO7SwiftUIE0F12UIAttributesV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10Foundation18AttributeContainerV
CStrings:
+ "JetUI.NQMLAttributedStringGenerator"
+ "NQML font-name/font-size tag attributes are not supported on the SwiftUI.Font path; ignoring"
+ "NQMLConfiguration was created with a SwiftUI Font but used with the NSAttributedString path; the SwiftUI font is ignored. Use AttributedString.init(ju_nqml:configuration:) instead."
```
