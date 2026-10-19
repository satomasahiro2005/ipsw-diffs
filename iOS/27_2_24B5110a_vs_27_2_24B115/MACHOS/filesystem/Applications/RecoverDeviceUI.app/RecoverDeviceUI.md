## RecoverDeviceUI

> `/Applications/RecoverDeviceUI.app/RecoverDeviceUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13cbc` | `0x13068` | **`-0xc54`** |
| `__DATA_CONST.__cfstring` | `0x1d00` | `0x1d60` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x46bc` | `0x471c` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x3260` | `0x32c0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x164b` | `0x168d` | **`+0x42`** |
| `__DATA_CONST.__const` | `0x518` | `0x558` | **`+0x40`** |
| `__DATA.__bss` | `0x10` | `0x30` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x12c0` | `0x12d8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x19fe` | `0x1a07` | **`+0x9`** |
| `__DATA_CONST.__got` | `0x240` | `0x248` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x5d4` | `0x5dc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2718.40.17.0.0
+2718.42.1.0.0

+  - /System/Library/Frameworks/UniformTypeIdentifiers.framework/UniformTypeIdentifiers

-  Functions: 277
-  Symbols:   1023
-  CStrings:  1281
+  Functions: 285
+  Symbols:   1035
+  CStrings:  1287
Symbols:
+ GCC_except_table10
+ GCC_except_table101
+ GCC_except_table150
+ GCC_except_table153
+ GCC_except_table5
+ GCC_except_table7
+ GCC_except_table94
+ RecoveryHomeAccessoryName
+ RecoveryHomeAccessoryName.name
+ RecoveryHomeAccessoryName.onceToken
+ RecoveryLocalizedString
+ _OBJC_CLASS_$_UTType
+ _OUTLINED_FUNCTION_0
+ _RecoveryHomeAccessoryName
+ _RecoveryLocalizedString
+ ___RecoveryHomeAccessoryName_block_invoke
+ _objc_msgSend$_typeWithDeviceModelCode:
+ _objc_msgSend$localizedDescription
+ _objc_msgSend$stringByReplacingOccurrencesOfString:withString:
- GCC_except_table148
- GCC_except_table151
- GCC_except_table4
- GCC_except_table6
- GCC_except_table8
- GCC_except_table92
- GCC_except_table99
CStrings:
+ "@HOME_ACCESSORY_NAME@"
+ "DEVICE_TYPE_J490_FALLBACK"
+ "Device needing recovery is a %{public}@"
+ "HomeAccessory17,1"
+ "_typeWithDeviceModelCode:"
+ "localizedDescription"
+ "stringByReplacingOccurrencesOfString:withString:"
- "Device needing recovery is TBD"
```
