## libauthinstall.dylib

> `/usr/lib/libauthinstall.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb92b4` | `0xb9248` | **`-0x6c`** |
| `__DATA_CONST.__got` | `0x3e8` | `0x410` | **`+0x28`** |
| `__TEXT.__cstring` | `0x1ff79` | `0x1ff7d` | **`+0x4`** |

### Other Changes

```diff

-1155.0.0.0.0
+1155.0.3.0.0
Functions:
~ __AMAuthInstallUpdaterInitLocalSigning : 184 -> 188
~ __AMAuthInstallApFtabCopyFtabFromFile : 312 -> 188
~ _AMAuthInstallApImg4GetTypeForEntryName : 120 -> 128
~ _AMAuthInstallMonetMeasureDbl : 428 -> 420
~ _AMAuthInstallMonetMeasureMav20ElfMBN : 944 -> 932
~ _AMAuthInstallMonetMeasureElfMBN : 972 -> 960
~ _b64_ntop : 364 -> 352
~ __ZNSt3__134__uninitialized_allocator_relocateB9nqe220106INS_9allocatorI18ACFUErrorContainerEEPS2_EEvRT_T0_S7_S7_ : 200 -> 192
~ -[FTABFileOS parseFileData] : 844 -> 832
~ -[MantaFTABFile parseFileData] : 812 -> 800
~ __ZN13SERestoreInfo11UpdateTableC2ERK7DERItem : 2000 -> 2012
~ __ZNSt3__16vectorIN13SERestoreInfo4BLOBENS_9allocatorIS2_EEE26__swap_out_circular_bufferERNS_14__split_bufferIS2_RS4_EE : 268 -> 248
~ __ZNSt3__16vectorIN13SERestoreInfo4BLOBENS_9allocatorIS2_EEE16__init_with_sizeB9fqe220106IPS2_S7_EEvT_T0_m : 196 -> 188
~ __ZNSt3__16vectorIN13SERestoreInfo4BLOBENS_9allocatorIS2_EEE16__destroy_vectorclB9fqe220106Ev : 172 -> 152
~ __ZNSt3__134__uninitialized_allocator_relocateB9fqe220106INS_9allocatorIN13SERestoreInfo8ApduBLOBEEEPS3_EEvRT_T0_S8_S8_ : 252 -> 244
~ _AMAuthInstallApFtabStitchTicketData : 388 -> 384
~ __AMAuthInstallApFtabCopyFtabFromFile.cold.1 : 44 -> 192
~ _AMAuthInstallMonetMeasureElf : 784 -> 772
~ _AMAuthInstallMonetMeasureBootSbl : 436 -> 428
CStrings:
+ "HelsinkiRestore-58.0.42"
+ "VinylRestore-178~2206"
+ "libauthinstall_device-1155.0.3"
- "HelsinkiRestore-58.0.41"
- "VinylRestore-178~1394"
- "libauthinstall_device-1155"
```
