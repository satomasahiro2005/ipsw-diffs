## deleted

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a190` | `0x5a8a4` | **`+0x714`** |
| `__DATA.__objc_const` | `0x48a8` | `0x4a68` | **`+0x1c0`** |
| `__TEXT.__objc_methname` | `0x7c09` | `0x7d7f` | **`+0x176`** |
| `__TEXT.__objc_stubs` | `0x6780` | `0x6880` | **`+0x100`** |
| `__TEXT.__objc_methlist` | `0x2f24` | `0x2fcc` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0xab5b` | `0xabe3` | **`+0x88`** |
| `__TEXT.__cstring` | `0x48da` | `0x493b` | **`+0x61`** |
| `__DATA_CONST.__cfstring` | `0x4ae0` | `0x4b40` | **`+0x60`** |
| `__DATA.__objc_data` | `0xb40` | `0xb90` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x1e90` | `0x1ee0` | **`+0x50`** |
| `__DATA.__bss` | `0x1f8` | `0x230` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x230` | `0x268` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xdd8` | `0xe00` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1ce8` | `0x1d08` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x384` | `0x39c` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1c8` | `0x1e0` | **`+0x18`** |
| `__TEXT.__objc_classname` | `0x3f1` | `0x407` | **`+0x16`** |
| `__TEXT.__gcc_except_tab` | `0x28fc` | `0x2910` | **`+0x14`** |
| `__DATA_CONST.__objc_arraydata` | `0x568` | `0x578` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x120` | `0x128` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0xe73` | `0xe7b` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-904.0.0.0.0
+904.0.5.0.0

-  Functions: 1222
-  Symbols:   2995
-  CStrings:  3128
+  Functions: 1236
+  Symbols:   3030
+  CStrings:  3154
Symbols:
+ +[AppContainerCaches deleteAppCaches:options:]
+ -[AppCacheDeleteOptions .cxx_destruct]
+ -[AppCacheDeleteOptions bytesNeeded]
+ -[AppCacheDeleteOptions fairPurgeMode]
+ -[AppCacheDeleteOptions group]
+ -[AppCacheDeleteOptions setBytesNeeded:]
+ -[AppCacheDeleteOptions setFairPurgeMode:]
+ -[AppCacheDeleteOptions setGroup:]
+ -[AppCacheDeleteOptions setTelemetry:]
+ -[AppCacheDeleteOptions setUrgency:]
+ -[AppCacheDeleteOptions telemetry]
+ -[AppCacheDeleteOptions urgency]
+ -[CDAppClassifier allHiddenAppBundleGroups]
+ -[CDAppClassifier allVisibleAppBundleGroups]
+ -[CDAppClassifier buildAppInfoForBundleGroups:]
+ -[CacheDeleteFairPurgeOperation cloneCorrectionByVolume]
+ -[CacheDeleteFairPurgeOperation setCloneCorrectionByVolume:]
+ GCC_except_table31
+ OBJC_IVAR_$_AppCacheDeleteOptions._bytesNeeded
+ OBJC_IVAR_$_AppCacheDeleteOptions._fairPurgeMode
+ OBJC_IVAR_$_AppCacheDeleteOptions._group
+ OBJC_IVAR_$_AppCacheDeleteOptions._telemetry
+ OBJC_IVAR_$_AppCacheDeleteOptions._urgency
+ _OBJC_CLASS_$_AppCacheDeleteOptions
+ _OBJC_METACLASS_$_AppCacheDeleteOptions
+ __OBJC_$_INSTANCE_METHODS_AppCacheDeleteOptions
+ __OBJC_$_INSTANCE_VARIABLES_AppCacheDeleteOptions
+ __OBJC_$_PROP_LIST_AppCacheDeleteOptions
+ __OBJC_CLASS_RO_$_AppCacheDeleteOptions
+ __OBJC_METACLASS_RO_$_AppCacheDeleteOptions
+ ___43-[CDAppClassifier allHiddenAppBundleGroups]_block_invoke
+ ___44-[CDAppClassifier allVisibleAppBundleGroups]_block_invoke
+ ___47-[CDAppClassifier buildAppInfoForBundleGroups:]_block_invoke
+ ___47-[CDAppClassifier buildAppInfoForBundleGroups:]_block_invoke_2
+ ___FairPurgeSkippedBundleIDs_block_invoke
+ ___block_descriptor_64_e8_32s40bs48r_e5_v8?0ls32l8s40l8r48l8
+ _objc_msgSend$allHiddenAppBundleGroups
+ _objc_msgSend$allVisibleAppBundleGroups
+ _objc_msgSend$buildAppInfoForBundleGroups:
+ _objc_msgSend$bytesNeeded
+ _objc_msgSend$cloneCorrectionByVolume
+ _objc_msgSend$deleteAppCaches:options:
+ _objc_msgSend$fairPurgeMode
+ _objc_msgSend$group
+ _objc_msgSend$setBytesNeeded:
+ _objc_msgSend$setFairPurgeMode:
+ _objc_msgSend$setGroup:
+ _objc_msgSend$setTelemetry:
+ _objc_msgSend$telemetry
- +[AppContainerCaches deleteAppCaches:urgency:telemetry:group:fairPurgeMode:]
- -[CDAppClassifier allHiddenAppBundleIDs]
- -[CDAppClassifier allVisibleAppBundleIDs]
- -[CDAppClassifier buildAppInfoForBundleIDs:]
- ___40-[CDAppClassifier allHiddenAppBundleIDs]_block_invoke
- ___41-[CDAppClassifier allVisibleAppBundleIDs]_block_invoke
- ___44-[CDAppClassifier buildAppInfoForBundleIDs:]_block_invoke
- ___44-[CDAppClassifier buildAppInfoForBundleIDs:]_block_invoke_2
- ___block_descriptor_56_e8_32s40bs48r_e5_v8?0ls32l8s40l8r48l8
- _objc_msgSend$allHiddenAppBundleIDs
- _objc_msgSend$allVisibleAppBundleIDs
- _objc_msgSend$buildAppInfoForBundleIDs:
- _objc_msgSend$deleteAppCaches:urgency:telemetry:group:
- _objc_msgSend$deleteAppCaches:urgency:telemetry:group:fairPurgeMode:
CStrings:
+ "@\"NSObject<OS_dispatch_group>\""
+ "AppCacheDeleteOptions"
+ "CLONE_CORRECTION"
+ "T@\"NSMutableDictionary\",&,N,V_cloneCorrectionByVolume"
+ "T@\"NSObject<OS_dispatch_group>\",&,N,V_group"
+ "T@\"TestTelemetry\",&,N,V_telemetry"
+ "TB,N,V_fairPurgeMode"
+ "TQ,N,V_bytesNeeded"
+ "_bytesNeeded"
+ "_cloneCorrectionByVolume"
+ "_fairPurgeMode"
+ "_group"
+ "_telemetry"
+ "allHiddenAppBundleGroups"
+ "allVisibleAppBundleGroups"
+ "buildAppInfoForBundleGroups:"
+ "bytesNeeded"
+ "cloneCorrectionByVolume"
+ "com.apple.CloudDocs.iCloudDriveFileProvider"
+ "com.apple.FileProvider.LocalStorage"
+ "deleteAppCaches: reached goal (%llu >= %llu bytes), stopping early"
+ "deleteAppCaches:options:"
+ "fairPurgeMode"
+ "group"
+ "plugin updateBlock skipped for urgency %d: refresh already in flight"
+ "setBytesNeeded:"
+ "setCloneCorrectionByVolume:"
+ "setFairPurgeMode:"
+ "setGroup:"
+ "setTelemetry:"
+ "telemetry"
- "@48@0:8@16i24@28@36B44"
- "allHiddenAppBundleIDs"
- "allVisibleAppBundleIDs"
- "buildAppInfoForBundleIDs:"
- "deleteAppCaches:urgency:telemetry:group:fairPurgeMode:"
```
