## PowerlogAccounting

> `/System/Library/PrivateFrameworks/PowerlogAccounting.framework/PowerlogAccounting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36420` | `0x36604` | **`+0x1e4`** |
| `__TEXT.__oslogstring` | `0x1328` | `0x13e0` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x9b0` | `0x978` | **`-0x38`** |
| `__AUTH_CONST.__const` | `0x420` | `0x440` | **`+0x20`** |
| `__TEXT.__cstring` | `0x55b3` | `0x55cb` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x1c30` | `0x1c48` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x2960` | `0x2970` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xe08` | `0xe10` | **`+0x8`** |

### Other Changes

```diff

-3468.0.0.502.1
+3486.0.21.502.1

-  Functions: 957
-  Symbols:   1506
-  CStrings:  600
+  Functions: 961
+  Symbols:   1509
+  CStrings:  602
Symbols:
+ -[PLAccountingDistributionEventForwardEntry requiresOrderedDelivery]
+ -[PLAccountingEventEntry requiresOrderedDelivery]
+ GCC_except_table148
+ ___59-[PLAccountingEngine createEventWithEvent:withActionBlock:]_block_invoke_3
- GCC_except_table147
CStrings:
+ "[FORWARD_RACE PLAccountingEngine] Out-of-order delivery detected and resolved: superseding last event (entryID=%lld, distributionID=%d) with new event in-place at startDate=%{public}@"
+ "accounting_forward_race"
```
