## AppIntentsIndex

> `/System/Library/PrivateFrameworks/AppIntentsIndex.framework/AppIntentsIndex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdfb3c` | `0xe97e0` | **`+0x9ca4`** |
| `__AUTH_CONST.__const` | `0x5c58` | `0x6028` | **`+0x3d0`** |
| `__TEXT.__oslogstring` | `0x1a26` | `0x1d26` | **`+0x300`** |
| `__TEXT.__eh_frame` | `0x9abc` | `0x9cb4` | **`+0x1f8`** |
| `__TEXT.__unwind_info` | `0x3518` | `0x36b8` | **`+0x1a0`** |
| `__TEXT.__swift5_capture` | `0xd34` | `0xeb4` | **`+0x180`** |
| `__DATA_DIRTY.__data` | `0x2b28` | `0x29c8` | **`-0x160`** |
| `__TEXT.__const` | `0x987c` | `0x992c` | **`+0xb0`** |
| `__AUTH.__data` | `0x208` | `0x2a0` | **`+0x98`** |
| `__DATA.__data` | `0xf88` | `0x1018` | **`+0x90`** |
| `__TEXT.__cstring` | `0x24ed` | `0x257d` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x2fb2` | `0x3036` | **`+0x84`** |
| `__TEXT.__swift5_fieldmd` | `0x1c14` | `0x1c90` | **`+0x7c`** |
| `__TEXT.__swift5_reflstr` | `0x17b9` | `0x182b` | **`+0x72`** |
| `__AUTH_CONST.__auth_got` | `0x16e0` | `0x1740` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0x1560` | `0x1588` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x920` | `0x940` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x630` | `0x640` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x21c` | `0x220` | **`+0x4`** |

### Other Changes

```diff

-301.0.45.4.101
+301.0.51.1.102

-  Functions: 4847
-  Symbols:   1614
-  CStrings:  368
+  Functions: 4963
+  Symbols:   1629
+  CStrings:  380
Symbols:
+ _OBJC_CLASS_$_NSFileManager
+ _OUTLINED_FUNCTION_353
+ ___swift_closure_destructor.129Tm
+ ___swift_closure_destructor.57Tm
+ ___swift_closure_destructor.65Tm
+ ___swift_closure_destructor.93Tm
+ ___swift_memcpy184_8
+ ___swift_memcpy192_8
+ ___unnamed_12
+ _swift_deallocBox
+ _symbolic SSyYbc
+ _symbolic Say_____SgG s5Int64V
+ _symbolic _____ 15AppIntentsIndex08MetadataC0V14IndexingResultV
+ _symbolic _____Sg_ABt 10Foundation4UUIDV
+ _symbolic _____ySiG 14GRDBv7Internal21QueryInterfaceRequestV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15AppIntentsIndex18MetadataFileSourceV
+ _symbolic _____y_____SgG s11_SetStorageC s5Int64V
+ _symbolic _____y_____SgG s23_ContiguousArrayStorageC s5Int64V
+ _symbolic _____y__________G s17_NativeDictionaryV s5Int64V 15AppIntentsIndex18MetadataFileSourceV
+ _symbolic _____y__________G s6ResultOsRi_zRi0_zrlE 15AppIntentsIndex08MetadataD0V08IndexingA0V AC06BundleF7FailureV
+ _symbolic _____y__________GSg s6ResultOsRi_zRi0_zrlE 15AppIntentsIndex08MetadataD0V08IndexingA0V AC06BundleF7FailureV
- ___swift_closure_destructor.27Tm
- ___swift_closure_destructor.54Tm
- ___swift_closure_destructor.63Tm
- ___swift_memcpy168_8
- ___swift_memcpy176_8
- _symbolic _____ySS_____GSg s6ResultOsRi_zRi0_zrlE 15AppIntentsIndex21BundleIndexingFailureV
CStrings:
+ "%{public}sPruned %ld metadata source(s) whose backing file is missing (fix-up cleanup): %{public}s"
+ "Checking for SchemaLibrary changes..."
+ "EXISTS (\n    SELECT 1 FROM "
+ "IFNULL(SUM(LENGTH(metadata)), 0)"
+ "No stale sources under previous data container %{public}s for %{public}s"
+ "Previously-failed bundles — "
+ "Removed %ld bundles due to schema library change"
+ "SchemaLibrary hash change detected %s => %s, flagging all bundles with schemas for rebuild"
+ "[%{public}s] Bundle relocated to a new path, re-auditing (stored=%{public}s new=%{public}s)"
+ "[%{public}s] Purged %{public}ld stale metadata source(s) from previous data container %{public}s after relocation: %{public}s"
+ "[%{public}s] Relocated across non-sibling containers, skipping container purge; relying on fix-up cleanup (old=%{public}s new=%{public}s)"
+ "schemaLibraryHash"
```
