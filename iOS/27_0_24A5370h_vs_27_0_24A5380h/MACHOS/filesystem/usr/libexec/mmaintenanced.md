## mmaintenanced

> `/usr/libexec/mmaintenanced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2418c` | `0x24480` | **`+0x2f4`** |
| `__TEXT.__oslogstring` | `0x2d46` | `0x2d76` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x218` | `0x240` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x13d0` | `0x13c0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x9f8` | `0x9f0` | **`-0x8`** |
| `__TEXT.__gcc_except_tab` | `0x868` | `0x864` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-233.0.0.0.0
+233.0.0.502.1

-  Symbols:   1402
-  CStrings:  477
+  Symbols:   1405
+  CStrings:  478
Symbols:
+ _$s13ExclavesStats0aB6ServerCMm
+ _$s13ExclavesStats0aB6ServerCMn
+ _$s13ExclavesStats0aB6ServerCMo
+ _$s13ExclavesStats0aB6ServerCN
- _objc_release_x28
Functions:
~ __Z16get_pid_for_namePKc : 536 -> 552
~ __Z24user_reclaimable_currentP15jetsam_snapshot : 984 -> 960
~ __Z32current_pressure_level_correctedRj : 1156 -> 1204
~ __ZNSt3__15dequeINS_7__stateIcEENS_9allocatorIS2_EEE19__add_back_capacityEv : 484 -> 472
~ __ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE25__parse_equivalence_classIPKcEET_S7_S7_PNS_20__bracket_expressionIcS2_EE : 532 -> 508
~ __ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE23__parse_character_classIPKcEET_S7_S7_PNS_20__bracket_expressionIcS2_EE : 176 -> 152
~ __ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE24__parse_collating_symbolIPKcEET_S7_S7_RNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE : 228 -> 204
~ _$s23MemoryMaintenance_Swift28reportExclavesAddrspaceStatsSbyF : 1116 -> 1516
~ _$s23MemoryMaintenance_Swift24reportExclavesShmemStatsSbyF : 1116 -> 1516
CStrings:
+ "ExclavesStats framework not available"
```
