## SwiftData

> `/System/Library/Frameworks/SwiftData.framework/SwiftData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x165f60` | `0x16a950` | **`+0x49f0`** |
| `__TEXT.__eh_frame` | `0x8bb0` | `0x8eb0` | **`+0x300`** |
| `__DATA_DIRTY.__data` | `0x4e30` | `0x5028` | **`+0x1f8`** |
| `__AUTH.__data` | `0xc30` | `0xb70` | **`-0xc0`** |
| `__TEXT.__constg_swiftt` | `0x5d2c` | `0x5dec` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x4938` | `0x49f0` | **`+0xb8`** |
| `__TEXT.__const` | `0xb7f8` | `0xb8a8` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x6cdd` | `0x6d7d` | **`+0xa0`** |
| `__AUTH_CONST.__const` | `0x6438` | `0x64c0` | **`+0x88`** |
| `__DATA.__data` | `0x1e20` | `0x1da8` | **`-0x78`** |
| `__TEXT.__swift5_typeref` | `0x4248` | `0x42a8` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x47f8` | `0x47d8` | **`-0x20`** |
| `__DATA.__common` | `0x118` | `0xf8` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x158` | `0x178` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x2e7c` | `0x2e98` | **`+0x1c`** |
| `__TEXT.__swift5_reflstr` | `0x2901` | `0x28f1` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x2e8` | `0x2ec` | **`+0x4`** |

### Other Changes

```diff

-173.0.0.0.0
+175.0.0.0.0

-  Functions: 6656
-  Symbols:   1863
-  CStrings:  641
+  Functions: 6748
+  Symbols:   1870
+  CStrings:  643
Symbols:
+ ___swift_closure_destructor.86Tm
+ ___swift_project_boxed_opaque_existential_2Tm
+ _symbolic $s9SwiftData01_B24StoreSnapshotValueAccessP
+ _symbolic _____ 9SwiftData6SchemaC12KeyPathCacheC5State33_52274F3E79B95F998A52FD42B9BCF60DLLV
+ _symbolic ______p 9SwiftData01_B24StoreSnapshotValueAccessP
+ _symbolic _____ySDy_____SiG_____G s13ManagedBufferCsRi__rlE 9SwiftData6SchemaC12ModelTypeKeyV So16os_unfair_lock_sV
+ _symbolic _____ySbG 2os21OSAllocatedUnfairLockV
+ _symbolic _____ySb_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 9SwiftData6SchemaC12KeyPathCacheC5State33_52274F3E79B95F998A52FD42B9BCF60DLLV
+ _symbolic _____y_____G s11_SetStorageC 9SwiftData6SchemaC12ModelTypeKeyV
+ _symbolic _____y_____SiG s18_DictionaryStorageC 9SwiftData6SchemaC12ModelTypeKeyV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 9SwiftData6SchemaC12KeyPathCacheC5State33_52274F3E79B95F998A52FD42B9BCF60DLLV So16os_unfair_lock_sV
+ _type_layout_string 9SwiftData6SchemaC12KeyPathCacheC5State33_52274F3E79B95F998A52FD42B9BCF60DLLV
- ___swift_allocate_boxed_opaque_existential_2
- ___swift_closure_destructor.88Tm
- _symbolic $s9SwiftData0B24StoreSnapshotValueAccessP
- _symbolic ______p 9SwiftData0B24StoreSnapshotValueAccessP
- _symbolic ______p 9SwiftData0b31StoreSnapshotValueAccessBackingB0P
- _type_layout_string 9SwiftData6SchemaC16StoredPropertiesV12KnownKeysMapV
CStrings:
+ "': a composite property that stores more than one value has no single column to index. Index a single stored property instead."
+ "Unable to index '"
```
