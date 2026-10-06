## AppleDeviceQuerySupport

> `/System/Library/PrivateFrameworks/AppleDeviceQuerySupport.framework/AppleDeviceQuerySupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xba50` | `0xba2c` | **`-0x24`** |
| `__TEXT.__unwind_info` | `0x268` | `0x270` | **`+0x8`** |
| `__TEXT.__cstring` | `0x48ec` | `0x48f0` | **`+0x4`** |

### Other Changes

```diff

-458.0.0.0.0
+459.0.2.0.0
Functions:
~ _ZhuGeBulkCopyPrivileges : 756 -> 752
~ _queryPathForConfigAndPref : 1596 -> 1592
~ _ZhuGeBulkCopyValues : 7332 -> 7336
~ +[ZhuGeInternalSupportAssistant executeCacheRefresh] : 316 -> 312
~ +[ZhuGeInternalSupportAssistant getInternalSupportPath] : 1160 -> 1152
~ _getZhuGeCryptexPathsWithError : 748 -> 744
~ _getZhuGeFDIPathsWithError : 1624 -> 1608
~ _isEntitlementExpected : 1460 -> 1452
~ +[NSString(ZhuGe) isDataConvertibleToVisibleString:] : 164 -> 160
~ +[NSString(ZhuGe) hexStringFromData:] : 180 -> 188
~ +[NSString(ZhuGe) macAddressStringFromData:] : 208 -> 224
~ +[NSString(ZhuGe) macAddressStringFromSysconfigDataSixByte:] : 232 -> 248
~ -[NSString(ZhuGe) stringByLeftTrimmingCharacter:] : 148 -> 144
~ -[NSString(ZhuGe) stringByRightTrimmingCharacter:] : 140 -> 136
~ +[NSArray(ZhuGe) graphicInfoArrayFromArray:] : 660 -> 656
~ +[NSArray(ZhuGe) arrayFromShellCommandString:] : 612 -> 596
CStrings:
+ "ZhuGe-459.0.2"
- "ZhuGe-458"
```
