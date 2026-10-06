## libCellularDecoders.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libCellularDecoders.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a140` | `0x2a0ec` | **`-0x54`** |
| `__DATA.__bss` | `0x40` | `0x10` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `—` | `0x30` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x880` | `0x8a0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x428` | `0x430` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1c04` | `0x1c00` | **`-0x4`** |
| `__TEXT.__cstring` | `0x2454` | `0x2457` | **`+0x3`** |

### Other Changes

```diff

-13473.1.0.0.0
+13478.3.1.3.0

-  Symbols:   1361
-  CStrings:  479
+  Symbols:   1362
+  CStrings:  480
Symbols:
+ _kCTPhoneNumberRegistrationRequestIdKey
Functions:
~ __ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE25__parse_equivalence_classIPKcEET_S7_S7_PNS_20__bracket_expressionIcS2_EE : 548 -> 524
~ __ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE23__parse_character_classIPKcEET_S7_S7_PNS_20__bracket_expressionIcS2_EE : 176 -> 152
~ __ZNSt3__111basic_regexIcNS_12regex_traitsIcEEE24__parse_collating_symbolIPKcEET_S7_S7_RNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEE : 228 -> 204
~ __ZNSt3__15dequeINS_7__stateIcEENS_9allocatorIS2_EEE19__add_back_capacityEv : 484 -> 472
CStrings:
+ "id"
```
