## icloudmailagent

> `/usr/libexec/icloudmailagent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3fedc` | `0x42d48` | **`+0x2e6c`** |
| `__TEXT.__const` | `0x2340` | `0x24c0` | **`+0x180`** |
| `__DATA.__objc_const` | `0x1708` | `0x17e0` | **`+0xd8`** |
| `__DATA.__data` | `0xf68` | `0x1038` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x735` | `0x805` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x1b91` | `0x1c61` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0x18e0` | `0x1960` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1617` | `0x1697` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1c98` | `0x1cf8` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xb00` | `0xb60` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0xde8` | `0xe38` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x16d0` | `0x1718` | **`+0x48`** |
| `__DATA.__bss` | `0x3090` | `0x30d0` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xc78` | `0xcb8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x9d0` | `0xa0c` | **`+0x3c`** |
| `__TEXT.__objc_classname` | `0x2c7` | `0x2f7` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x810` | `0x838` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0xabe` | `0xae4` | **`+0x26`** |
| `__DATA_CONST.__got` | `0x560` | `0x580` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x4d8` | `0x4f0` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x4c0` | `0x4d8` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x3c0` | `0x3d4` | **`+0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb4` | `0xb8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.0.5.0.0
+2027.1.1.0.0

-  Functions: 1205
-  Symbols:   3552
-  CStrings:  491
+  Functions: 1243
+  Symbols:   3613
+  CStrings:  503
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/icloudMCCKit/install/TempContent/Objects/icloudMCCKit.build/icloudmailagent.build/Objects-normal/arm64e/PendingRequestStore.o
+ PendingRequestStore.swift
+ _$s10Foundation3URLV36_unconditionallyBridgeFromObjectiveCyACSo5NSURLCSgFZ
+ _$s10Foundation3URLV4pathSSvg
+ _$s10Foundation3URLVACSQAAWL
+ _$s10Foundation3URLVMn
+ _$s10Foundation3URLVSQAAMc
+ _$s10Foundation3URLVSgMR
+ _$s10Foundation3URLVSgMd
+ _$s10Foundation3URLVSgWOc
+ _$s10Foundation3URLVSgWOhTm
+ _$s10Foundation3URLVSg_ADtMR
+ _$s10Foundation3URLVSg_ADtMd
+ _$s15icloudmailagent10APIManagerC5store33_D65B718F5C28AC3F7B0CC41A5A0186BCLLAA19PendingRequestStoreCvpWvd
+ _$s15icloudmailagent15APIRequestModelCAC9SwiftData010PersistentC0AAWlTm
+ _$s15icloudmailagent19PendingRequestStoreC013migrateLegacyD8IfNeeded33_7D66F202B357FC7F5C3FB249A93B200DLLyyF
+ _$s15icloudmailagent19PendingRequestStoreC013migrateLegacyD8IfNeeded33_7D66F202B357FC7F5C3FB249A93B200DLLyyFyyYbcfU_
+ _$s15icloudmailagent19PendingRequestStoreC013migrateLegacyD8IfNeeded33_7D66F202B357FC7F5C3FB249A93B200DLLyyFyyYbcfU_TA
+ _$s15icloudmailagent19PendingRequestStoreC12modelContext33_7D66F202B357FC7F5C3FB249A93B200DLL9SwiftData05ModelF0CSgvpWvd
+ _$s15icloudmailagent19PendingRequestStoreC12modelContext33_7D66F202B357FC7F5C3FB249A93B200DLL9SwiftData05ModelF0CSgvpfi
+ _$s15icloudmailagent19PendingRequestStoreC14modelContainer33_7D66F202B357FC7F5C3FB249A93B200DLL9SwiftData05ModelF0CSgvpWvd
+ _$s15icloudmailagent19PendingRequestStoreC14modelContainer33_7D66F202B357FC7F5C3FB249A93B200DLL9SwiftData05ModelF0CSgvpfi
+ _$s15icloudmailagent19PendingRequestStoreC15getModelContext9SwiftData0fG0CSgyF
+ _$s15icloudmailagent19PendingRequestStoreC18appGroupIdentifierSSvau
+ _$s15icloudmailagent19PendingRequestStoreC18appGroupIdentifierSSvgZ
+ _$s15icloudmailagent19PendingRequestStoreC18appGroupIdentifierSSvpZ
+ _$s15icloudmailagent19PendingRequestStoreC18appGroupIdentifierSSvpZMV
+ _$s15icloudmailagent19PendingRequestStoreC22makeModelConfiguration14groupContainer9SwiftData0fG0VAH05GroupI0V_tF
+ _$s15icloudmailagent19PendingRequestStoreC22resolvedGroupContainer05isAppfG9Available9SwiftData18ModelConfigurationV0fG0VSbyXE_tF
+ _$s15icloudmailagent19PendingRequestStoreC22resolvedGroupContainer05isAppfG9Available9SwiftData18ModelConfigurationV0fG0VSbyXE_tFfA_
+ _$s15icloudmailagent19PendingRequestStoreC22resolvedGroupContainer05isAppfG9Available9SwiftData18ModelConfigurationV0fG0VSbyXE_tFfA_SbycfU_
+ _$s15icloudmailagent19PendingRequestStoreC28makeLegacyModelConfiguration9SwiftData0gH0VyF
+ _$s15icloudmailagent19PendingRequestStoreC5queue33_7D66F202B357FC7F5C3FB249A93B200DLLSo012OS_dispatch_E7_serialCvpWvd
+ _$s15icloudmailagent19PendingRequestStoreC5queueACSo012OS_dispatch_E7_serialC_tcfC
+ _$s15icloudmailagent19PendingRequestStoreC5queueACSo012OS_dispatch_E7_serialC_tcfCTq
+ _$s15icloudmailagent19PendingRequestStoreC5queueACSo012OS_dispatch_E7_serialC_tcfc
+ _$s15icloudmailagent19PendingRequestStoreC6schema33_7D66F202B357FC7F5C3FB249A93B200DLL9SwiftData6SchemaCvpZ
+ _$s15icloudmailagent19PendingRequestStoreC6schema33_7D66F202B357FC7F5C3FB249A93B200DLL_WZ
+ _$s15icloudmailagent19PendingRequestStoreC6schema33_7D66F202B357FC7F5C3FB249A93B200DLL_Wz
+ _$s15icloudmailagent19PendingRequestStoreC7migrate4from2toSi9SwiftData12ModelContextC_AItKF
+ _$s15icloudmailagent19PendingRequestStoreC7migrate4from2toSi9SwiftData12ModelContextC_AItKFTf4nnd_n
+ _$s15icloudmailagent19PendingRequestStoreCMF
+ _$s15icloudmailagent19PendingRequestStoreCMa
+ _$s15icloudmailagent19PendingRequestStoreCMf
+ _$s15icloudmailagent19PendingRequestStoreCMm
+ _$s15icloudmailagent19PendingRequestStoreCMn
+ _$s15icloudmailagent19PendingRequestStoreCN
+ _$s15icloudmailagent19PendingRequestStoreCfD
+ _$s15icloudmailagent19PendingRequestStoreCfd
+ _$s8Dispatch0A9PredicateO7onQueueyACSo17OS_dispatch_queueCcACmFWC
+ _$s8Dispatch0A9PredicateOMa
+ _$s8Dispatch25_dispatchPreconditionTestySbAA0A9PredicateOF
+ _$s9SwiftData18ModelConfigurationV14GroupContainerV10identifieryAESSFZ
+ _$s9SwiftData18ModelConfigurationV3url10Foundation3URLVvg
+ _$sSay8Dispatch0A13WorkItemFlagsVGSayxGSTsWl
+ _OBJC_CLASS_$_NSFileManager
+ __DATA__TtC15icloudmailagent19PendingRequestStore
+ __IVARS__TtC15icloudmailagent19PendingRequestStore
+ __METACLASS_DATA__TtC15icloudmailagent19PendingRequestStore
+ _objc_msgSend$containerURLForSecurityApplicationGroupIdentifier:
+ _objc_msgSend$defaultManager
+ _objc_msgSend$fileExistsAtPath:
+ _symbolic _____ 15icloudmailagent19PendingRequestStoreC
+ _symbolic _____Sg 10Foundation3URLV
+ _symbolic _____Sg_ABt 10Foundation3URLV
+ _symbolic _____XDXMT 15icloudmailagent19PendingRequestStoreC
- _$s15icloudmailagent10APIManagerC12modelContext33_D65B718F5C28AC3F7B0CC41A5A0186BCLL9SwiftData05ModelD0CSgvpWvd
- _$s15icloudmailagent10APIManagerC12modelContext33_D65B718F5C28AC3F7B0CC41A5A0186BCLL9SwiftData05ModelD0CSgvpfi
- _$s15icloudmailagent10APIManagerC14modelContainer33_D65B718F5C28AC3F7B0CC41A5A0186BCLL9SwiftData05ModelD0CSgvpWvd
- _$s15icloudmailagent10APIManagerC14modelContainer33_D65B718F5C28AC3F7B0CC41A5A0186BCLL9SwiftData05ModelD0CSgvpfi
- _$s15icloudmailagent10APIManagerC15getModelContext33_D65B718F5C28AC3F7B0CC41A5A0186BCLL9SwiftData0dE0CSgyF
CStrings:
+ "App group container unavailable, falling back to unscoped pending request store"
+ "Migrated %ld legacy pending requests to app group store"
+ "Unable to create app-group model context for migration"
+ "Unable to migrate legacy pending request store: %s"
+ "_TtC15icloudmailagent19PendingRequestStore"
+ "com.apple.icloudmailagent.PendingRequestStore"
+ "com.apple.icloudmailagent.didMigrateAPIRequestStoreToAppGroup"
+ "containerURLForSecurityApplicationGroupIdentifier:"
+ "defaultManager"
+ "fileExistsAtPath:"
+ "group.com.apple.mail"
+ "store"
```
