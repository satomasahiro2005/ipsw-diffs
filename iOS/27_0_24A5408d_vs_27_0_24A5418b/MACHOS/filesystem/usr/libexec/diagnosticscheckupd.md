## diagnosticscheckupd

> `/usr/libexec/diagnosticscheckupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b264` | `0x4b2d8` | **`+0x74`** |
| `__DATA.__data` | `0x2850` | `0x2880` | **`+0x30`** |
| `__DATA.__objc_const` | `0xe2f0` | `0xe310` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x15f0` | `0x1610` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xe54` | `0xe6c` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x8291` | `0x82a1` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1516` | `0x1526` | **`+0x10`** |
| `__DATA.__common` | `0xe8` | `0xf0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1370` | `0x1378` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1374.2.1.0.0
+1374.2.2.0.0

-  CStrings:  2389
+  CStrings:  2390
Functions:
~ sub_10002d8cc : 180 -> 184
~ sub_10002d980 -> sub_10002d984 : 100 -> 80
~ sub_10002d9e4 -> sub_10002d9d4 : 80 -> 100
~ sub_10003ae18 -> sub_10003ae1c : 404 -> 424
~ sub_10003b058 -> sub_10003b070 : 264 -> 272
~ sub_10003c750 -> sub_10003c770 : 496 -> 564
~ sub_100040c0c -> sub_100040c70 : 680 -> 696
~ sub_100043578 -> sub_1000435ec : 180 -> 4
~ sub_10004362c -> sub_1000435f0 : 56 -> 180
~ sub_100043664 -> sub_1000436a4 : 40 -> 56
~ sub_1000436b4 -> sub_100043704 : 8 -> 40
~ sub_1000436bc -> sub_10004372c : 4 -> 8
CStrings:
+ "ticket"
```
