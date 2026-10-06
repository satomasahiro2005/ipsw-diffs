## FilesystemMetadataSnapshotService

> `/System/Library/PrivateFrameworks/DiskSpaceDiagnostics.framework/XPCServices/FilesystemMetadataSnapshotService.xpc/FilesystemMetadataSnapshotService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2653` | `0x2660` | **`+0xd`** |
| `__TEXT.__text` | `0x14238` | `0x14240` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x358` | `0x360` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1021.0.0.0.0
+1022.0.0.0.0

-  CStrings:  945
+  CStrings:  946
Functions:
~ _getPIDsAndProcNames : 1584 -> 1588
~ _populateFDs : 2624 -> 2632
~ _cacheDeleteItemizedPurgeable : 396 -> 388
~ sub_100005c1c -> sub_100005c20 : 2232 -> 2224
~ sub_1000069a0 -> sub_10000699c : 4828 -> 4824
~ sub_1000088e0 -> sub_1000088d8 : 1820 -> 1816
~ sub_1000095dc -> sub_1000095d0 : 3468 -> 3484
~ sub_10000a368 -> sub_10000a36c : 836 -> 832
~ sub_10000bd60 : 308 -> 328
~ sub_10000c6fc -> sub_10000c710 : 380 -> 364
~ sub_10000cb6c -> sub_10000cb70 : 404 -> 388
~ sub_10000ce2c -> sub_10000ce20 : 744 -> 740
~ sub_10000d114 -> sub_10000d104 : 8728 -> 8764
~ sub_10000fe98 -> sub_10000feac : 620 -> 616
~ sub_10001048c -> sub_10001049c : 1328 -> 1316
~ sub_100011750 -> sub_100011754 : 284 -> 288
CStrings:
+ "%llu\t%llu\t%c\t%llu\t%ld\t%ld\t%ld\t%u\t%u\t%u\t%llu\t%s\n"
+ "%s\t%s\t%s\t%s\t%s\t%s\t%s\t%s\t%s\t%s\t%s\t%s\n"
+ "1022"
+ "btime"
- "%llu\t%llu\t%c\t%llu\t%ld\t%ld\t%u\t%u\t%u\t%llu\t%s\n"
- "%s\t%s\t%s\t%s\t%s\t%s\t%s\t%s\t%s\t%s\t%s\n"
- "1021"
```
