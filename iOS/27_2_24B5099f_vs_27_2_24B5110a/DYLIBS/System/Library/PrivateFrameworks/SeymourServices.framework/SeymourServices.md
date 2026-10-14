## SeymourServices

> `/System/Library/PrivateFrameworks/SeymourServices.framework/SeymourServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9bad4c` | `0x9c5598` | **`+0xa84c`** |
| `__TEXT.__eh_frame` | `0x79380` | `0x79728` | **`+0x3a8`** |
| `__TEXT.__swift5_typeref` | `0x14b86` | `0x14d48` | **`+0x1c2`** |
| `__TEXT.__const` | `0x29470` | `0x29600` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x148c2` | `0x14a02` | **`+0x140`** |
| `__DATA.__data` | `0x5cd8` | `0x5de0` | **`+0x108`** |
| `__DATA.__bss` | `0xd400` | `0xd500` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x23608` | `0x23698` | **`+0x90`** |
| `__AUTH.__data` | `0x5268` | `0x52e8` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x12778` | `0x127d8` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x3a6e8` | `0x3a698` | **`-0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x9520` | `0x956c` | **`+0x4c`** |
| `__AUTH_CONST.__auth_got` | `0x6658` | `0x6690` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0xb114` | `0xb144` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0xc0c4` | `0xc0f4` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x16e54` | `0x16e30` | **`-0x24`** |
| `__TEXT.__swift_as_cont` | `0x81a4` | `0x8180` | **`-0x24`** |
| `__DATA_DIRTY.__data` | `0xfdb8` | `0xfda8` | **`-0x10`** |
| `__TEXT.__swift5_proto` | `0x1220` | `0x1228` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x934` | `0x938` | **`+0x4`** |

### Other Changes

```diff

-2027.1.63.0.0
+2027.1.69.0.0

-  Functions: 34881
-  Symbols:   7617
-  CStrings:  2956
+  Functions: 34952
+  Symbols:   7642
+  CStrings:  2959
Symbols:
+ ___swift_closure_destructor.167Tm
+ ___swift_closure_destructor.243Tm
+ ___swift_closure_destructor.5Tm
+ _associated conformance 15SeymourServices13SyncDataStoreV0C14OperationGroup33_6616A70F174CAE89D75C17B87A7F689CLLVSHAASQ
+ _symbolic SS______t 11SeymourCore13SyncOperationV
+ _symbolic SS______t 15SeymourServices20ManagedDirtySyncZoneC
+ _symbolic SS______t 15SeymourServices20ManagedSyncChangeTagC
+ _symbolic SS______t 15SeymourServices20ManagedSyncOperationC
+ _symbolic SaySo8CKRecordCG
+ _symbolic _____ 15SeymourServices13SyncDataStoreV0C14OperationGroup33_6616A70F174CAE89D75C17B87A7F689CLLV
+ _symbolic _____3key_Say_____G5valuet 11SeymourCore8ZoneNameO 0A8Services13SyncChangeTagV
+ _symbolic _____3key_Say_____G5valuet 11SeymourCore8ZoneNameO AA13SyncOperationV
+ _symbolic _____3key_Say_____G5valuet 15SeymourServices13SyncDataStoreV0C14OperationGroup33_6616A70F174CAE89D75C17B87A7F689CLLV 0A4Core0cF0V
+ _symbolic _____XDXMT 15SeymourServices24PersonalizationComponentC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 11SeymourCore13SyncOperationV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 15SeymourServices20ManagedDirtySyncZoneC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 15SeymourServices20ManagedSyncChangeTagC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 15SeymourServices20ManagedSyncOperationC
+ _symbolic _____ySS______G SD6ValuesV 11SeymourCore13SyncOperationV
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 11SeymourCore13SyncOperationV
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 15SeymourServices20ManagedDirtySyncZoneC
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 15SeymourServices20ManagedSyncChangeTagC
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 15SeymourServices20ManagedSyncOperationC
+ _symbolic _____ySo10CKRecordIDCG s11_SetStorageC
+ _symbolic _____ySo10CKRecordIDCSaySo0A0CGG s18_DictionaryStorageC
+ _symbolic _____y_____G s11_SetStorageC 15SeymourServices13SyncChangeTagV
+ _symbolic _____y_____G s11_SetStorageC s6UInt64V
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 15SeymourServices19SyncRecordChangesetV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt64V
+ _symbolic _____y_____Say_____GG s18_DictionaryStorageC 11SeymourCore8ZoneNameO 0C8Services13SyncChangeTagV
+ _symbolic _____y_____Say_____GG s18_DictionaryStorageC 15SeymourServices13SyncDataStoreV0E14OperationGroup33_6616A70F174CAE89D75C17B87A7F689CLLV 0C4Core0eH0V
- ___swift_closure_destructor.165Tm
- ___swift_closure_destructor.241Tm
- ___swift_closure_destructor.39Tm
- ___swift_closure_destructor.76Tm
- _symbolic _____y_____G s11_SetStorageC s6UInt32V
- _symbolic _____y_____G s23_ContiguousArrayStorageC s6UInt32V
CStrings:
+ "Applying fetch for %{public}s in %{public}ld chunks"
+ "No registered zone for %{public}ld sync operations in %{public}s"
+ "Omitting workout %{mask.hash}llu from the remote browsing chunk: above UInt32.max"
+ "Sync operations for %{public}s (domain %{public}d) need class C, which is not loaded; passing %{public}ld to the persistence monitors."
- "No registered zone for sync operation: %{public}s"
```
