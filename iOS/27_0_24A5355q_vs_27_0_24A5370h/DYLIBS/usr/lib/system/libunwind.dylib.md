## libunwind.dylib

> `/usr/lib/system/libunwind.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bac` | `0x6ba0` | **`-0xc`** |

### Other Changes

```text
Functions:
~ __ZN9libunwind12UnwindCursorINS_17LocalAddressSpaceENS_15Registers_arm64EE24setInfoBasedOnIPRegisterEb : 3092 -> 3088
~ __ZN9libunwind12UnwindCursorINS_17LocalAddressSpaceENS_15Registers_arm64EE4stepEb : 2536 -> 2544
~ __ZN9libunwind25findDynamicUnwindSectionsEPvP27unw_dynamic_unwind_sections : 156 -> 152
~ ___unw_add_find_dynamic_unwind_sections : 152 -> 160
~ ___unw_remove_find_dynamic_unwind_sections : 248 -> 252
~ __ZN9libunwind10CFI_ParserINS_17LocalAddressSpaceEE20parseFDEInstructionsINS_15Registers_arm64EEEbRS1_RKNS2_8FDE_InfoERKNS2_8CIE_InfoENT_23link_hardened_reg_arg_tEiPNS2_10PrologInfoE : 2720 -> 2708
~ __ZN9libunwind17DwarfInstructionsINS_17LocalAddressSpaceENS_15Registers_arm64EE16getSavedRegisterERS1_RKS2_mRKNS_10CFI_ParserIS1_E16RegisterLocationE : 480 -> 476
~ __ZN9libunwind17DwarfInstructionsINS_17LocalAddressSpaceENS_15Registers_arm64EE18evaluateExpressionEmRS1_RKS2_m : 2220 -> 2212
```
