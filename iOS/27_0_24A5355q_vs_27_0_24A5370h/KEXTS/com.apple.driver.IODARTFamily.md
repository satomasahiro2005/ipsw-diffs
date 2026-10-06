## com.apple.driver.IODARTFamily

> `com.apple.driver.IODARTFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x470` | **`+0x470`** |
| `__TEXT_EXEC.__text` | `0x13a9c` | `0x13bec` | **`+0x150`** |

### Other Changes

```text
Functions:
~ __ZN6IODART23_initPersistentMappingsEv : 868 -> 852
~ sub_fffffff009f22b54 -> sub_fffffff009fa1164 : 300 -> 328
~ __ZNK6IODART14_dumpPageTableEPKyjmj : 468 -> 432
~ __ZN6IODART29_initPersistentMappingsForSIDEjPK6OSData : 2596 -> 2668
~ sub_fffffff009f23a6c -> sub_fffffff009fa20bc : 56 -> 76
~ sub_fffffff009f23b84 -> sub_fffffff009fa21e8 : 56 -> 76
~ sub_fffffff009f23d38 -> sub_fffffff009fa23b0 : 1184 -> 1188
~ sub_fffffff009f242a0 -> sub_fffffff009fa291c : 376 -> 372
~ sub_fffffff009f25550 -> sub_fffffff009fa3bc8 : 216 -> 244
~ __ZN12IODARTMapper5startEP9IOService : 4308 -> 4324
~ __ZN12IODARTMapper23_initPersistentMappingsEv : 692 -> 704
~ __ZN12IODARTMapper5_initEv : 1516 -> 1636
~ sub_fffffff009f2843c -> sub_fffffff009fa6b64 : 492 -> 508
~ __ZN12IODARTMapper16_iomdCacheLookupEPK18IOMemoryDescriptorP16iomdHistoryEntryyP12IODMACommand : 1528 -> 1516
~ sub_fffffff009f29114 -> sub_fffffff009fa7840 : 344 -> 336
~ sub_fffffff009f29418 -> sub_fffffff009fa7b3c : 340 -> 344
~ __ZN12IODARTMapper16_iomdCacheRemoveEP14iomdCacheEntry : 628 -> 616
~ sub_fffffff009f2a39c -> sub_fffffff009fa8ab8 : 436 -> 464
~ sub_fffffff009f2a550 -> sub_fffffff009fa8c88 : 84 -> 92
~ sub_fffffff009f2a710 -> sub_fffffff009fa8e50 : 224 -> 232
~ __ZN12IODARTMapper20_iovmAllocDMACommandEP12IODMACommandP18IOMemoryDescriptorjyyPyj : 1724 -> 1716
~ __ZN12IODARTMapper10_iovmAllocEjP12IODMACommandjP16iomdHistoryEntryPKy : 1328 -> 1316
~ __ZN12IODARTMapper21_iovmInsertDMACommandEP13IODARTVMSpaceP12IODMACommandP18IOMemoryDescriptoryyjPy : 1760 -> 1756
~ sub_fffffff009f2c50c -> sub_fffffff009faac3c : 576 -> 584
~ sub_fffffff009f2cfa4 -> sub_fffffff009fab6dc : 132 -> 152
~ __ZN12IODARTMapper13_iovmAllocPIOEjP12IODMACommand : 840 -> 832
~ __ZN12IODARTMapper20_findVMSpaceReservedEjj : 552 -> 556
~ sub_fffffff009f2e414 -> sub_fffffff009facb5c : 352 -> 372
~ sub_fffffff009f2e574 -> sub_fffffff009faccd0 : 240 -> 264
~ sub_fffffff009f2e970 -> sub_fffffff009fad0e4 : 392 -> 388
~ __ZN18IODARTMapperClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 1540 -> 1560
~ sub_fffffff009f33ec8 -> sub_fffffff009fb264c : 56 -> 52
~ sub_fffffff009f3490c -> sub_fffffff009fb308c : 164 -> 160
~ sub_fffffff009f349b0 -> sub_fffffff009fb312c : 76 -> 72
~ sub_fffffff009f349fc -> sub_fffffff009fb3174 : 100 -> 96
~ sub_fffffff009f34cb0 -> sub_fffffff009fb3424 : 72 -> 68
```
