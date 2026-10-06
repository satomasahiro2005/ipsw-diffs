## com.apple.MobileInstallationHelperService

> `/System/Library/PrivateFrameworks/MobileInstallation.framework/XPCServices/com.apple.MobileInstallationHelperService.xpc/com.apple.MobileInstallationHelperService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14ce8` | `0x14cb4` | **`-0x34`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1655.0.0.0.0
+1660.0.0.0.0
Functions:
~ sub_1000039c0 : 380 -> 376
~ _hardlink_copy_hierarchy : 5512 -> 5508
~ sub_10000607c -> sub_100006074 : 436 -> 432
~ sub_1000063a4 -> sub_100006398 : 116 -> 124
~ sub_10000b534 -> sub_10000b530 : 1512 -> 1508
~ sub_10000c034 -> sub_10000c02c : 304 -> 300
~ _patchFile : 1604 -> 1600
~ _MIGetFirstTrueBooleanEntitlement : 300 -> 296
~ _MIHasRequiredEntitlements : 412 -> 408
~ _MIArrayContainsOnlyClass : 272 -> 268
~ _MIArrayFilteredToContainOnlyClass : 352 -> 348
~ sub_10000eae4 -> sub_10000eac4 : 280 -> 276
~ sub_10000f398 -> sub_10000f374 : 600 -> 596
~ sub_10000fc74 -> sub_10000fc4c : 1476 -> 1472
~ sub_100010368 -> sub_10001033c : 2716 -> 2708
~ sub_100011554 -> sub_100011520 : 1204 -> 1200
~ sub_10001246c -> sub_100012434 : 832 -> 828
~ sub_10001576c -> sub_100015730 : 272 -> 280
CStrings:
+ "22:08:41"
+ "Jun  9 2026"
- "09:36:26"
- "May 21 2026"
```
