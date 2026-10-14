## RecoverDeviceUI

> `/Applications/RecoverDeviceUI.app/RecoverDeviceUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x13904` | `0x13cbc` | **`+0x3b8`** |
| `__DATA_CONST.__cfstring` | `0x1c00` | `0x1d00` | **`+0x100`** |
| `__TEXT.__cstring` | `0x1560` | `0x164b` | **`+0xeb`** |
| `__TEXT.__objc_methname` | `0x465a` | `0x46bc` | **`+0x62`** |
| `__TEXT.__objc_stubs` | `0x3200` | `0x3260` | **`+0x60`** |
| `__DATA.__objc_const` | `0x14a8` | `0x14d8` | **`+0x30`** |
| `__DATA_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x5ac` | `0x5d4` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x4f8` | `0x518` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x10` | `0x30` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x420` | `0x440` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x12a8` | `0x12c0` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x78` | `0x90` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x11b0` | `0x11c8` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x19e7` | `0x19fe` | **`+0x17`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x220` | `0x230` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x318` | `0x328` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x16ad` | `0x16ba` | **`+0xd`** |
| `__DATA.__objc_ivar` | `0xb8` | `0xbc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-2718.40.16.0.0
+2718.40.17.0.0

-  Functions: 273
-  Symbols:   1010
-  CStrings:  1265
+  Functions: 277
+  Symbols:   1023
+  CStrings:  1281
Symbols:
+ -[RecoverDeviceUIExtensionRemoteViewController recoveryProduct]
+ -[RecoverDeviceUIExtensionRemoteViewController setRecoveryProduct:]
+ GCC_except_table4
+ GCC_except_table92
+ GCC_except_table99
+ OBJC_IVAR_$_RecoverDeviceUIExtensionRemoteViewController._recoveryProduct
+ TryResolveRecoveryProductImages
+ TryResolveRecoveryProductImages.onceToken
+ TryResolveRecoveryProductImages.symbolNamesByProduct
+ _OBJC_CLASS_$_NSConstantDictionary
+ _TryResolveRecoveryProductImages
+ ___TryResolveRecoveryProductImages_block_invoke
+ _dispatch_once
+ _objc_autorelease
+ _objc_msgSend$numberWithUnsignedChar:
+ _objc_msgSend$recoveryProduct
+ _objc_msgSend$setRecoveryProduct:
- GCC_except_table100
- GCC_except_table5
- GCC_except_table93
- _NeRDExtraDataFromNSData
CStrings:
+ "B97E01ACA4C94266B87DF4FCE78C0C71.badge.exclamationmark"
+ "B97E01ACA4C94266B87DF4FCE78C0C71.slash"
+ "C"
+ "DEVICE_TYPE_J490"
+ "Device needing recovery is TBD"
+ "Localizable-J490"
+ "NeRDExtraData{valid_bits=%u, version=%u, is_audio_ttr=%u, recovery_product=%u}"
+ "NeRDSupportsEACS"
+ "TC,V_recoveryProduct"
+ "_recoveryProduct"
+ "apps.iphone.duo.badge.exclamationmark"
+ "apps.iphone.duo.badge.slash"
+ "eacs"
+ "extra data: %{public}@"
+ "numberWithUnsignedChar:"
+ "primary"
+ "recoveryProduct"
+ "setRecoveryProduct:"
+ "v20@0:8C16"
- "HomePod extra data: %{public}@"
- "Localizable"
- "NeRDExtraData{valid_bits=%u, version=%u, is_audio_ttr=%u}"
```
