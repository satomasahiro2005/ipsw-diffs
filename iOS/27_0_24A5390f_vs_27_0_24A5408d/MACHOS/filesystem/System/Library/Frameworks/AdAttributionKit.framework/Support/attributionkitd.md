## attributionkitd

> `/System/Library/Frameworks/AdAttributionKit.framework/Support/attributionkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b3978` | `0x1b3734` | **`-0x244`** |
| `__TEXT.__auth_stubs` | `0x2b00` | `0x2ad0` | **`-0x30`** |
| `__TEXT.__eh_frame` | `0x149f4` | `0x14a1c` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x2940` | `0x2920` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x4e65` | `0x4e49` | **`-0x1c`** |
| `__DATA_CONST.__auth_got` | `0x1590` | `0x1578` | **`-0x18`** |
| `__DATA.__data` | `0x62a0` | `0x6290` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x7778` | `0x7788` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xc48` | `0xc40` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x62e8` | `0x62e0` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x748` | `0x740` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0x139c` | `0x13a0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4.0.6.0.0
+4.0.7.0.0

-  Functions: 8851
-  Symbols:   1087
-  CStrings:  1680
+  Functions: 8853
+  Symbols:   1082
+  CStrings:  1679
Symbols:
- _$s10Foundation11MeasurementV5value4unitACyxGSd_xtcfC
- _$s10Foundation11MeasurementVAASo11NSDimensionCRbzrlE9converted2toACyxGx_tF
- _$s10Foundation11MeasurementVAASo11NSDimensionCRbzrlE9formattedSSyF
- _$s10Foundation11MeasurementVMn
- _OBJC_CLASS_$_NSUnitDuration
CStrings:
+ "[TXN%hx] Beginning transaction (%s)"
+ "[TXN%hx] Ending transaction (%s) (%f ms)"
+ "[TXN%hx] Releasing transaction (%s)"
+ "finishTasksAndInvalidate"
- "[TXN%hx] 🐏 Beginning transaction (%s)"
- "[TXN%hx] 🐏 Ending transaction (%s) (%s)"
- "[TXN%hx] 🐏 Releasing transaction (%s)"
- "milliseconds"
- "nanoseconds"
```
