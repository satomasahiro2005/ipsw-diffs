## FSKit

> `/System/Library/PrivateFrameworks/FSKit.framework/FSKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x536b4` | `0x53b8c` | **`+0x4d8`** |
| `__TEXT.__objc_methlist` | `0x6288` | `0x6348` | **`+0xc0`** |
| `__AUTH_CONST.__objc_const` | `0xb258` | `0xb2b8` | **`+0x60`** |
| `__DATA.__data` | `0x14d8` | `0x1538` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1828` | `0x1848` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2c08` | `0x2c18` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x1b0` | `0x1b8` | **`+0x8`** |

### Other Changes

```diff

-974.0.11.0.0
+974.0.13.0.2

-  Functions: 2695
-  Symbols:   4242
+  Functions: 2705
+  Symbols:   4255
Symbols:
+ -[FSBlockDeviceResource hash]
+ -[FSFileName isEqual:]
+ -[FSGenericURLResource hash]
+ -[FSModuleInstance hash]
+ -[FSPathURLResource hash]
+ -[FSServerURLResource hash]
+ -[FSTaskOption hash]
+ -[FSVolumeDescription isEqual:]
+ -[FSVolumeSupportedCapabilities hash]
+ GCC_except_table62
+ GCC_except_table72
+ GCC_except_table82
+ __OBJC_$_PROP_LIST_FSVolumeCommonOperations
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_FSVolumeCommonOperations
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_FSVolumeCommonOperations
+ __OBJC_$_PROTOCOL_METHOD_TYPES_FSVolumeCommonOperations
+ __OBJC_LABEL_PROTOCOL_$_FSVolumeCommonOperations
+ __OBJC_PROTOCOL_$_FSVolumeCommonOperations
- GCC_except_table23
- GCC_except_table61
- GCC_except_table70
- GCC_except_table81
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_FSVolumeHandler
Functions:
+ -[FSFileName isEqual:]
~ -[FSModuleConnector deactivateVolume:numericOptions:replyHandler:] : 488 -> 556
+ -[FSModuleInstance hash]
+ -[FSServerURLResource hash]
+ -[FSTaskOption hash]
+ -[FSVolumeDescription isEqual:]
+ -[FSVolumeSupportedCapabilities hash]
+ -[FSBlockDeviceResource hash]
+ -[FSGenericURLResource hash]
+ -[FSPathURLResource hash]
~ -[FSClient handleInvalidated] : 256 -> 264
~ -[FSVolumeConnector otherAttributeOf:named:requestID:replyHandler:] : 4064 -> 4076
+ sub_261808d38
```
