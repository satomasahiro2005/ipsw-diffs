## BackBoardServices

> `/System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x897a4` | `0x8a250` | **`+0xaac`** |
| `__AUTH_CONST.__objc_const` | `0x121b8` | `0x123c0` | **`+0x208`** |
| `__AUTH_CONST.__cfstring` | `0xa2a0` | `0xa400` | **`+0x160`** |
| `__TEXT.__cstring` | `0xb8c3` | `0xba23` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x8ca4` | `0x8d94` | **`+0xf0`** |
| `__AUTH.__objc_data` | `0x2440` | `0x24e0` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x2651` | `0x26b6` | **`+0x65`** |
| `__DATA_CONST.__objc_selrefs` | `0x3078` | `0x30a0` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1608` | `0x1628` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2368` | `0x2388` | **`+0x20`** |
| `__DATA.__bss` | `0x5f0` | `0x600` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1938` | `0x1948` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x7d0` | `0x7e0` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x5e0` | `0x5f0` | **`+0x10`** |
| `__TEXT.__const` | `0x3e8` | `0x3f8` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x918` | `0x924` | **`+0xc`** |
| `__DATA_CONST.__objc_superrefs` | `0x418` | `0x420` | **`+0x8`** |

### Other Changes

```diff

-868.0.0.0.0
+873.100.0.0.0

-  Functions: 3466
-  Symbols:   6553
-  CStrings:  1944
+  Functions: 3485
+  Symbols:   6591
+  CStrings:  1957
Symbols:
+ +[BKSHardwareButtonLongPressDescriptor supportsSecureCoding]
+ +[BKSHardwareButtonService sharedInstance]
+ -[BKSHIDTouchRoutingPolicy setAvoidCancelingContinuingClients:]
+ -[BKSHIDTouchRoutingPolicy shouldAvoidCancelingContinuingClients]
+ -[BKSHardwareButtonLongPressDescriptor copyWithZone:]
+ -[BKSHardwareButtonLongPressDescriptor copy]
+ -[BKSHardwareButtonLongPressDescriptor description]
+ -[BKSHardwareButtonLongPressDescriptor encodeWithCoder:]
+ -[BKSHardwareButtonLongPressDescriptor hash]
+ -[BKSHardwareButtonLongPressDescriptor initWithCoder:]
+ -[BKSHardwareButtonLongPressDescriptor initWithPage:usage:timeout:]
+ -[BKSHardwareButtonLongPressDescriptor isEqual:]
+ -[BKSHardwareButtonLongPressDescriptor page]
+ -[BKSHardwareButtonLongPressDescriptor timeout]
+ -[BKSHardwareButtonLongPressDescriptor usage]
+ -[BKSHardwareButtonService setLongPressTimeouts:]
+ GCC_except_table1212
+ GCC_except_table1231
+ GCC_except_table1232
+ GCC_except_table1348
+ GCC_except_table136
+ GCC_except_table1372
+ GCC_except_table1395
+ GCC_except_table1569
+ GCC_except_table1574
+ GCC_except_table1584
+ GCC_except_table1722
+ GCC_except_table1831
+ GCC_except_table1964
+ GCC_except_table2092
+ GCC_except_table2101
+ GCC_except_table2230
+ GCC_except_table2344
+ GCC_except_table2346
+ GCC_except_table2392
+ GCC_except_table2623
+ GCC_except_table2817
+ GCC_except_table2824
+ GCC_except_table286
+ GCC_except_table287
+ GCC_except_table3138
+ GCC_except_table3164
+ GCC_except_table3326
+ GCC_except_table3360
+ GCC_except_table3361
+ _OBJC_CLASS_$_BKSHardwareButtonLongPressDescriptor
+ _OBJC_CLASS_$_BKSHardwareButtonService
+ _OBJC_IVAR_$_BKSHardwareButtonLongPressDescriptor._page
+ _OBJC_IVAR_$_BKSHardwareButtonLongPressDescriptor._timeout
+ _OBJC_IVAR_$_BKSHardwareButtonLongPressDescriptor._usage
+ _OBJC_METACLASS_$_BKSHardwareButtonLongPressDescriptor
+ _OBJC_METACLASS_$_BKSHardwareButtonService
+ __BKSHIDServicesSetButtonLongPressTimeouts
+ __BKSHIDSetButtonLongPressTimeouts
+ __OBJC_$_CLASS_METHODS_BKSHardwareButtonLongPressDescriptor
+ __OBJC_$_CLASS_METHODS_BKSHardwareButtonService
+ __OBJC_$_CLASS_PROP_LIST_BKSHardwareButtonLongPressDescriptor
+ __OBJC_$_INSTANCE_METHODS_BKSHardwareButtonLongPressDescriptor
+ __OBJC_$_INSTANCE_METHODS_BKSHardwareButtonService
+ __OBJC_$_INSTANCE_VARIABLES_BKSHardwareButtonLongPressDescriptor
+ __OBJC_$_PROP_LIST_BKSHardwareButtonLongPressDescriptor
+ __OBJC_CLASS_PROTOCOLS_$_BKSHardwareButtonLongPressDescriptor
+ __OBJC_CLASS_RO_$_BKSHardwareButtonLongPressDescriptor
+ __OBJC_CLASS_RO_$_BKSHardwareButtonService
+ __OBJC_METACLASS_RO_$_BKSHardwareButtonLongPressDescriptor
+ __OBJC_METACLASS_RO_$_BKSHardwareButtonService
+ ___42+[BKSHardwareButtonService sharedInstance]_block_invoke
- GCC_except_table1209
- GCC_except_table1226
- GCC_except_table1228
- GCC_except_table134
- GCC_except_table1345
- GCC_except_table1369
- GCC_except_table1392
- GCC_except_table1566
- GCC_except_table1571
- GCC_except_table1581
- GCC_except_table1719
- GCC_except_table1828
- GCC_except_table1961
- GCC_except_table2089
- GCC_except_table2098
- GCC_except_table2227
- GCC_except_table2341
- GCC_except_table2343
- GCC_except_table2389
- GCC_except_table2620
- GCC_except_table2814
- GCC_except_table2821
- GCC_except_table283
- GCC_except_table284
- GCC_except_table3135
- GCC_except_table3161
- GCC_except_table3323
- GCC_except_table3357
- GCC_except_table3358
CStrings:
+ "<%@: %p 0x%X/0x%X timeout:%.3gs>"
+ "BKSHardwareButtonLongPressDescriptor.m"
+ "BKSSystemShellDidReconnect-21000327"
+ "ConfigA"
+ "ConfigB"
+ "Error encoding button long press timeouts: %{public}@"
+ "Error setting button long press timeouts: 0x%x"
+ "Failed to decode BKSHardwareButtonLongPressDescriptor: timeout <= 0"
+ "Failed to decode BKSHardwareButtonLongPressDescriptor: zero page"
+ "Failed to decode BKSHardwareButtonLongPressDescriptor: zero usage"
+ "avoidCancelingContinuingClients"
+ "backboardd-attr-cache-21000327"
+ "page != 0"
+ "timeout > 0"
+ "usage != 0"
- "BKSSystemShellDidReconnect-21000325"
- "backboardd-attr-cache-21000325"
```
