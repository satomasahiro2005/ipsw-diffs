## TVRemoteUI

> `/System/Library/PrivateFrameworks/TVRemoteUI.framework/TVRemoteUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd3034` | `0xd3584` | **`+0x550`** |
| `__AUTH_CONST.__objc_const` | `0x15108` | `0x151f0` | **`+0xe8`** |
| `__TEXT.__objc_methlist` | `0xb7e4` | `0xb854` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x3700` | `0x3760` | **`+0x60`** |
| `__AUTH.__objc_data` | `0x6920` | `0x6970` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x1908` | `0x1938` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x5b06` | `0x5b36` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2cb0` | `0x2cd8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0x1cac` | `0x1ccc` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x6b60` | `0x6b78` | **`+0x18`** |
| `__TEXT.__cstring` | `0x4d21` | `0x4d31` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xba8` | `0xbac` | **`+0x4`** |

### Other Changes

```diff

-625.0.0.0.0
+627.0.9.0.0

-  Functions: 4845
-  Symbols:   6964
-  CStrings:  1229
+  Functions: 4854
+  Symbols:   6987
+  CStrings:  1233
Symbols:
+ +[_TVRUIDevicePickerItem itemWithDevice:]
+ -[TVRUICoreDevice device:updatedFindMyRemoteSupport:]
+ -[TVRUICoreDevice findMyRemoteSupport]
+ -[TVRUIDevicePickerViewController _insets]
+ -[TVRUIRemoteViewController device:updatedFindMyRemoteSupport:]
+ -[_TVRUIDevicePickerItem .cxx_destruct]
+ -[_TVRUIDevicePickerItem device]
+ -[_TVRUIDevicePickerItem hash]
+ -[_TVRUIDevicePickerItem isEqual:]
+ GCC_except_table43
+ GCC_except_table51
+ GCC_except_table58
+ GCC_except_table67
+ GCC_except_table84
+ GCC_except_table98
+ _OBJC_CLASS_$__TVRUIDevicePickerItem
+ _OBJC_IVAR_$__TVRUIDevicePickerItem._device
+ _OBJC_METACLASS_$__TVRUIDevicePickerItem
+ __OBJC_$_CLASS_METHODS__TVRUIDevicePickerItem
+ __OBJC_$_INSTANCE_METHODS__TVRUIDevicePickerItem
+ __OBJC_$_INSTANCE_VARIABLES__TVRUIDevicePickerItem
+ __OBJC_$_PROP_LIST__TVRUIDevicePickerItem
+ __OBJC_CLASS_RO_$__TVRUIDevicePickerItem
+ __OBJC_METACLASS_RO_$__TVRUIDevicePickerItem
+ ___47-[TVRUIDevicePickerViewController _toggleState]_block_invoke_3
+ ___47-[TVRUIDevicePickerViewController _toggleState]_block_invoke_4
+ ___block_descriptor_40_e8_32w_e81_"UITableViewCell"32?0"UITableView"8"NSIndexPath"16"_TVRUIDevicePickerItem"24lw32l8
- -[TVRUICoreDevice device:supportsFindMyRemote:]
- -[TVRUIRemoteViewController device:supportsFindMyRemote:]
- GCC_except_table97
- ___block_descriptor_40_e8_32w_e72_"UITableViewCell"32?0"UITableView"8"NSIndexPath"16"<TVRUIDevice>"24lw32l8
CStrings:
+ "@\"UITableViewCell\"32@?0@\"UITableView\"8@\"NSIndexPath\"16@\"_TVRUIDevicePickerItem\"24"
+ "Device query was not active. Skipping query start."
+ "Find My Remote supported state: %@"
+ "Full"
+ "Legacy"
+ "None"
+ "device: '%{public}@' find my remote support: %@"
+ "findMyRemoteSupport"
- "@\"UITableViewCell\"32@?0@\"UITableView\"8@\"NSIndexPath\"16@\"<TVRUIDevice>\"24"
- "Find My Remote state enabled: %d"
- "device: '%{public}@' supportsFindMy: %d"
- "supportsFindMyRemote"
```
