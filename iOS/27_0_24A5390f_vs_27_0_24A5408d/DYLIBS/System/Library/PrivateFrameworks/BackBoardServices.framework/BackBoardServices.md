## BackBoardServices

> `/System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8a250` | `0x8a8e4` | **`+0x694`** |
| `__AUTH_CONST.__objc_const` | `0x123c0` | `0x124a0` | **`+0xe0`** |
| `__DATA.__data` | `0x14b0` | `0x1570` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x26b6` | `0x275d` | **`+0xa7`** |
| `__TEXT.__objc_methlist` | `0x8d94` | `0x8df4` | **`+0x60`** |
| `__TEXT.__cstring` | `0xba23` | `0xba7b` | **`+0x58`** |
| `__AUTH_CONST.__cfstring` | `0xa400` | `0xa440` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x558` | `0x590` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x2388` | `0x23b8` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x30a0` | `0x30c8` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1628` | `0x1648` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x924` | `0x934` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1948` | `0x1958` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x1b8` | `0x1c8` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0xe8` | `0xf8` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x420` | `0x428` | **`+0x8`** |

### Other Changes

```diff

-873.100.0.0.0
+877.0.0.0.0

-  Functions: 3485
-  Symbols:   6591
-  CStrings:  1957
+  Functions: 3495
+  Symbols:   6619
+  CStrings:  1963
Symbols:
+ -[BKSDisplayService .cxx_destruct]
+ -[BKSDisplayService _lock_connectIfNeeded]
+ -[BKSDisplayService _lock_server]
+ -[BKSDisplayService init]
+ -[BKSDisplayService setScreenBlankNotificationSuppressedDisplayUUIDs:]
+ -[BKSHIDUISensorMode proximityDetectionModeWasInherited]
+ -[BKSMutableHIDUISensorMode setProximityDetectionModeWasInherited:]
+ GCC_except_table1220
+ GCC_except_table1237
+ GCC_except_table1239
+ GCC_except_table1240
+ GCC_except_table1356
+ GCC_except_table1380
+ GCC_except_table1403
+ GCC_except_table1577
+ GCC_except_table1582
+ GCC_except_table1592
+ GCC_except_table1730
+ GCC_except_table1839
+ GCC_except_table1972
+ GCC_except_table2100
+ GCC_except_table2109
+ GCC_except_table2238
+ GCC_except_table2352
+ GCC_except_table2354
+ GCC_except_table2400
+ GCC_except_table2631
+ GCC_except_table2825
+ GCC_except_table2832
+ GCC_except_table3148
+ GCC_except_table3174
+ GCC_except_table3336
+ GCC_except_table3370
+ GCC_except_table3371
+ GCC_except_table691
+ GCC_except_table692
+ OBJC_IVAR_$_BKSHIDUISensorMode._proximityDetectionModeWasInherited
+ _BKSDisplayServiceName
+ _BKSDisplayServiceNilDisplayUUID
+ _OBJC_IVAR_$_BKSDisplayService._screenBlankLock
+ _OBJC_IVAR_$_BKSDisplayService._screenBlankLock_connection
+ _OBJC_IVAR_$_BKSDisplayService._screenBlankLock_suppressedDisplayUUIDs
+ __OBJC_$_INSTANCE_VARIABLES_BKSDisplayService
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_BKSDisplayServiceServerInterface
+ __OBJC_$_PROTOCOL_METHOD_TYPES_BKSDisplayServiceServerInterface
+ __OBJC_$_PROTOCOL_REFS_BKSDisplayServiceClientInterface
+ __OBJC_$_PROTOCOL_REFS_BKSDisplayServiceServerInterface
+ __OBJC_LABEL_PROTOCOL_$_BKSDisplayServiceClientInterface
+ __OBJC_LABEL_PROTOCOL_$_BKSDisplayServiceServerInterface
+ __OBJC_PROTOCOL_$_BKSDisplayServiceClientInterface
+ __OBJC_PROTOCOL_$_BKSDisplayServiceServerInterface
+ __OBJC_PROTOCOL_REFERENCE_$_BKSDisplayServiceClientInterface
+ __OBJC_PROTOCOL_REFERENCE_$_BKSDisplayServiceServerInterface
+ ___42-[BKSDisplayService _lock_connectIfNeeded]_block_invoke
+ ___42-[BKSDisplayService _lock_connectIfNeeded]_block_invoke_2
- GCC_except_table1212
- GCC_except_table1229
- GCC_except_table1231
- GCC_except_table1232
- GCC_except_table1348
- GCC_except_table1372
- GCC_except_table1395
- GCC_except_table1569
- GCC_except_table1574
- GCC_except_table1584
- GCC_except_table1722
- GCC_except_table1831
- GCC_except_table1964
- GCC_except_table2092
- GCC_except_table2101
- GCC_except_table2230
- GCC_except_table2344
- GCC_except_table2346
- GCC_except_table2392
- GCC_except_table2623
- GCC_except_table2817
- GCC_except_table2824
- GCC_except_table3138
- GCC_except_table3164
- GCC_except_table3326
- GCC_except_table3360
- GCC_except_table3361
CStrings:
+ "BKDisplayService"
+ "BKSDisplayService: backboardd must be exiting"
+ "BKSDisplayService: cannot get connection for service"
+ "BKSDisplayService: service interruption; reconnecting and resending"
+ "BKSSystemShellDidReconnect-21000331"
+ "_proximityDetectionModeWasInherited"
+ "backboardd-attr-cache-21000331"
+ "proximityDetectionModeWasInherited"
- "BKSSystemShellDidReconnect-21000327"
- "backboardd-attr-cache-21000327"
```
