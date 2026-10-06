## AccessibilityDataMigration

> `/System/Library/DataClassMigrators/AccessibilityDataMigration.migrator/AccessibilityDataMigration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2700` | `0x2860` | **`+0x160`** |
| `__TEXT.__cstring` | `0x988` | `0xa1c` | **`+0x94`** |
| `__DATA_CONST.__cfstring` | `0x800` | `0x860` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0xf30` | `0xf6b` | **`+0x3b`** |
| `__TEXT.__objc_stubs` | `0x10a0` | `0x10c0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x17c` | `0x188` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x480` | `0x488` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  Functions: 33
+  Functions: 34

-  CStrings:  225
+  CStrings:  229
Functions:
~ sub_12a0 : 200 -> 208
+ sub_16f4
CStrings:
+ "AssistiveTouchMouseAlwaysShowSoftwareKeyboard"
+ "_AccessibilityMigration__AssistiveTouchAlwaysShowOnscreenKeyboardDomain_27.0"
+ "_raveMigrateAssistiveTouchAlwaysShowOnscreenKeyboardDomain"
+ "com.apple.AssistiveTouch"
```
