## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/FileProvider`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x25f8` | `0x1a90` | **`-0xb68`** |
| `__DATA_DIRTY.__objc_data` | `0x1bf8` | `0x2760` | **`+0xb68`** |
| `__TEXT.__text` | `0x12dd30` | `0x12e3f0` | **`+0x6c0`** |
| `__AUTH_CONST.__cfstring` | `0x115e0` | `0x11640` | **`+0x60`** |
| `__TEXT.__cstring` | `0x14ea3` | `0x14f02` | **`+0x5f`** |
| `__TEXT.__objc_methlist` | `0xe9f4` | `0xea4c` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x5958` | `0x5998` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x70f0` | `0x7128` | **`+0x38`** |
| `__TEXT.__gcc_except_tab` | `0x8b34` | `0x8b64` | **`+0x30`** |
| `__DATA.__bss` | `0xc30` | `0xc50` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x6228` | `0x6240` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x2e8` | `0x2d0` | **`-0x18`** |

### Other Changes

```diff

-4838.40.53.502.1
+4838.40.92.502.1

-  Functions: 7469
-  Symbols:   11221
-  CStrings:  4062
+  Functions: 7478
+  Symbols:   11232
+  CStrings:  4065
Symbols:
+ -[FPItemManager _fetchHierarchyForItemID:recursively:synchronously:depth:completionHandler:]
+ -[FPItemManager _fetchParentItemIDsForItemID:recursively:synchronously:completionHandler:]
+ -[FPItemManager _fetchParentsForItemID:recursively:synchronously:completionHandler:]
+ -[FPItemManager fetchOperationServiceForProviderDomainID:synchronously:handler:]
+ -[FPItemManager parentItemIDsForItemID:recursively:error:]
+ -[FPItemManager parentsForItemID:recursively:error:]
+ -[NSURL(FPFSHelpers) fp_URLWithNoFollow]
+ -[NSURL(FPFSHelpers) fp_hasNoFollow]
+ GCC_except_table144
+ _FPKnownFolderTransitionedCategoryIdentifier
+ _FPKnownFolderTransitionedPreviousPathKey
+ _FPKnownFolderTransitionedShowActionIdentifier
+ ___52-[FPItemManager parentsForItemID:recursively:error:]_block_invoke
+ ___58-[FPItemManager parentItemIDsForItemID:recursively:error:]_block_invoke
+ ___80-[FPItemManager fetchOperationServiceForProviderDomainID:synchronously:handler:]_block_invoke
+ ___84-[FPItemManager _fetchParentsForItemID:recursively:synchronously:completionHandler:]_block_invoke
+ ___90-[FPItemManager _fetchParentItemIDsForItemID:recursively:synchronously:completionHandler:]_block_invoke
+ ___90-[FPItemManager _fetchParentItemIDsForItemID:recursively:synchronously:completionHandler:]_block_invoke_2
+ ___92-[FPItemManager _fetchHierarchyForItemID:recursively:synchronously:depth:completionHandler:]_block_invoke
+ ___92-[FPItemManager _fetchHierarchyForItemID:recursively:synchronously:depth:completionHandler:]_block_invoke_2
+ ___92-[FPItemManager _fetchHierarchyForItemID:recursively:synchronously:depth:completionHandler:]_block_invoke_3
+ ___block_descriptor_58_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
+ ___block_descriptor_66_e8_32s40s48bs_e52_v24?0"FPService<FPXOperationService>"8"NSError"16ls48l8s32l8s40l8
- -[FPItemManager _fetchHierarchyForItemID:recursively:depth:completionHandler:]
- GCC_except_table104
- GCC_except_table137
- ___66-[FPItemManager fetchOperationServiceForProviderDomainID:handler:]_block_invoke
- ___70-[FPItemManager _fetchParentsForItemID:recursively:completionHandler:]_block_invoke
- ___75-[FPItemManager fetchParentItemIDsForItemID:recursively:completionHandler:]_block_invoke
- ___75-[FPItemManager fetchParentItemIDsForItemID:recursively:completionHandler:]_block_invoke_2
- ___78-[FPItemManager _fetchHierarchyForItemID:recursively:depth:completionHandler:]_block_invoke
- ___78-[FPItemManager _fetchHierarchyForItemID:recursively:depth:completionHandler:]_block_invoke_2
- ___78-[FPItemManager _fetchHierarchyForItemID:recursively:depth:completionHandler:]_block_invoke_3
- ___block_descriptor_57_e8_32s40bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8
- ___block_descriptor_65_e8_32s40s48bs_e52_v24?0"FPService<FPXOperationService>"8"NSError"16ls48l8s32l8s40l8
CStrings:
+ "4838.40.92.502.1"
+ "SHOW_FOLDER"
+ "com.apple.FileProvider.knownFolderTransitioned"
+ "knownFolderTransitionedPreviousPath"
- "4838.40.53.502.1"
```
