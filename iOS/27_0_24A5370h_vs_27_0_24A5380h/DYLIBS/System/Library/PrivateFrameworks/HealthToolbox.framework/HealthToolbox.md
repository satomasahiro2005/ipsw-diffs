## HealthToolbox

> `/System/Library/PrivateFrameworks/HealthToolbox.framework/HealthToolbox`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x62878` | `0x62d44` | **`+0x4cc`** |
| `__DATA_CONST.__const` | `0x1898` | `0x1938` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x47f0` | `0x4828` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0xb020` | `0xb050` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x6ee0` | `0x6f10` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xc48` | `0xc70` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xc28` | `0xc40` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x19b8` | `0x19d0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x7871` | `0x7881` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x688` | `0x68c` | **`+0x4`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 2343
-  Symbols:   4503
-  CStrings:  1068
+  Functions: 2349
+  Symbols:   4516
+  CStrings:  1069
Symbols:
+ +[WDAuthorizationRecord recordCombiningBloodPressureSystolic:diastolic:]
+ -[WDAuthorizationRecord modeInfo]
+ -[WDDisplayTypeDataSourcesTableViewController dealloc]
+ GCC_except_table35
+ GCC_except_table41
+ GCC_except_table62
+ GCC_except_table69
+ GCC_except_table83
+ GCC_except_table84
+ GCC_except_table94
+ _HKUIAuthorizationDidUpdateNotification
+ _OBJC_IVAR_$_WDDisplayTypeDataSourcesTableViewController._authorizationUpdateToken
+ __OBJC_$_CLASS_METHODS_WDAuthorizationRecord
+ ___58-[WDDisplayTypeDataSourcesTableViewController viewDidLoad]_block_invoke_2
+ ___89-[WDDisplayTypeDataSourcesTableViewController _refreshAuthorizationRecordsAndReloadTable]_block_invoke_3
+ ___89-[WDDisplayTypeDataSourcesTableViewController _refreshAuthorizationRecordsAndReloadTable]_block_invoke_4
+ ___block_descriptor_40_e8_32bs_e29_v16?0"NSMutableDictionary"8ls32l8
+ ___block_descriptor_40_e8_32w_e22_v16?0"NSDictionary"8lw32l8
+ ___block_descriptor_48_e8_32bs40w_e5_v8?0lw40l8s32l8
+ ___block_descriptor_56_e8_32s40s48s_e29_v24?0"UIImage"8"NSError"16ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
- GCC_except_table39
- GCC_except_table58
- GCC_except_table65
- GCC_except_table79
- GCC_except_table80
- GCC_except_table90
- _OBJC_CLASS_$__HKAuthorizationModeInfo
- ___block_descriptor_40_e8_32w_e29_v16?0"NSMutableDictionary"8lw32l8
CStrings:
+ "v16@?0@\"NSDictionary\"8"
```
