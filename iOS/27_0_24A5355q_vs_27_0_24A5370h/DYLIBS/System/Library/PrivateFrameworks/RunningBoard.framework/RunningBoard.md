## RunningBoard

> `/System/Library/PrivateFrameworks/RunningBoard.framework/RunningBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0xd948` | `0xdb70` | **`+0x228`** |
| `__TEXT.__text` | `0x7ae68` | `0x7acc8` | **`-0x1a0`** |
| `__DATA.__data` | `0x12c8` | `0x1388` | **`+0xc0`** |
| `__TEXT.__cstring` | `0x7e03` | `0x7d45` | **`-0xbe`** |
| `__AUTH.__objc_data` | `0x1e0` | `0x280` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x6374` | `0x63fc` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x2f20` | `0x2f40` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x380` | `0x390` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x190` | `0x1a0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x798` | `0x7a0` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2a0` | `0x2a8` | **`+0x8`** |
| `__TEXT.__const` | `0x1f8` | `0x1f0` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0xbabd` | `0xbac5` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1e28` | `0x1e30` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xb88` | `0xb84` | **`-0x4`** |

### Other Changes

```diff

-1066.0.0.0.1
+1071.0.0.0.0

-  Functions: 2824
-  Symbols:   4859
-  CStrings:  1865
+  Functions: 2825
+  Symbols:   4890
+  CStrings:  1861
Symbols:
+ -[RBContainerManager _lookupContainerPathViaLSForIdentity:context:containerIdentifier:persona:]
+ -[RBContainerManager autoUpdatingPluginQuery]
+ -[RBContainerManager initWithPersonaManager:lsProvider:]
+ -[RBLaunchServicesRecord .cxx_destruct]
+ -[RBLaunchServicesRecord dataContainerURLForPersonaWithUniqueString:error:]
+ -[RBLaunchServicesRecord initWithUnderlyingRecord:]
+ -[RBLaunchServicesRecordProvider recordForBundleIdentifier:context:error:]
+ GCC_except_table14
+ GCC_except_table17
+ GCC_except_table37
+ GCC_except_table53
+ _OBJC_CLASS_$_RBLaunchServicesRecord
+ _OBJC_CLASS_$_RBLaunchServicesRecordProvider
+ _OBJC_IVAR_$_RBContainerManager._lsProvider
+ _OBJC_IVAR_$_RBLaunchServicesRecord._underlying
+ _OBJC_METACLASS_$_RBLaunchServicesRecord
+ _OBJC_METACLASS_$_RBLaunchServicesRecordProvider
+ __LSPrimaryPersonaIdentifier
+ __OBJC_$_INSTANCE_METHODS_RBLaunchServicesRecord
+ __OBJC_$_INSTANCE_METHODS_RBLaunchServicesRecordProvider
+ __OBJC_$_INSTANCE_VARIABLES_RBLaunchServicesRecord
+ __OBJC_$_PROP_LIST_RBLaunchServicesRecord
+ __OBJC_$_PROP_LIST_RBLaunchServicesRecordProvider
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_RBLSRecord
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_RBLSRecordProviding
+ __OBJC_$_PROTOCOL_METHOD_TYPES_RBLSRecord
+ __OBJC_$_PROTOCOL_METHOD_TYPES_RBLSRecordProviding
+ __OBJC_$_PROTOCOL_REFS_RBLSRecord
+ __OBJC_$_PROTOCOL_REFS_RBLSRecordProviding
+ __OBJC_CLASS_PROTOCOLS_$_RBLaunchServicesRecord
+ __OBJC_CLASS_PROTOCOLS_$_RBLaunchServicesRecordProvider
+ __OBJC_CLASS_RO_$_RBLaunchServicesRecord
+ __OBJC_CLASS_RO_$_RBLaunchServicesRecordProvider
+ __OBJC_LABEL_PROTOCOL_$_RBLSRecord
+ __OBJC_LABEL_PROTOCOL_$_RBLSRecordProviding
+ __OBJC_METACLASS_RO_$_RBLaunchServicesRecord
+ __OBJC_METACLASS_RO_$_RBLaunchServicesRecordProvider
+ __OBJC_PROTOCOL_$_RBLSRecord
+ __OBJC_PROTOCOL_$_RBLSRecordProviding
- -[RBContainerManager autoUpdatingQueryWithContainerClass:]
- -[RBSLaunchContext(RBLaunchChecks) _applicationRecordForLaunchCheck]
- GCC_except_table38
- GCC_except_table4
- GCC_except_table54
- GCC_except_table8
- _OBJC_IVAR_$_RBContainerManager._appQueryLock
- _OBJC_IVAR_$_RBContainerManager._queryForApps
CStrings:
+ "%{public}@ LS container lookup: no LSApplicationRecord for '%{public}@' (%{public}@); falling back to MCM"
+ "%{public}@ LS container lookup: no dataContainerURL for '%{public}@' persona '%{public}@' (%{public}@); falling back to MCM"
+ "2"
- "-[RBContainerManager autoUpdatingQueryWithContainerClass:]"
- "Could not create LSApplicationRecord from bundleID %@: %{public}@"
- "Could not get bundle ID from %{public}@"
- "RBContainerManager.m"
- "container_class == CONTAINER_CLASS_APPLICATION_DATA || container_class == CONTAINER_CLASS_PLUGINKIT_PLUGIN_DATA"
- "container_query_count_results() failed with error %s"
- "unable to find LSApplicationRecord for identity %@: %{public}@"
```
