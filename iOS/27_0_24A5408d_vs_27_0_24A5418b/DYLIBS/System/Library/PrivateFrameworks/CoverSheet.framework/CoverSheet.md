## CoverSheet

> `/System/Library/PrivateFrameworks/CoverSheet.framework/CoverSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18cbe4` | `0x18cc8c` | **`+0xa8`** |
| `__TEXT.__oslogstring` | `0x8ef6` | `0x8f34` | **`+0x3e`** |
| `__AUTH_CONST.__objc_const` | `0x3c750` | `0x3c780` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x164bc` | `0x164d4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xc688` | `0xc698` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1ba4` | `0x1ba8` | **`+0x4`** |

### Other Changes

```diff

-159.0.2.0.0
+159.0.3.0.0

-  Functions: 7943
-  Symbols:   14078
-  CStrings:  2663
+  Functions: 7945
+  Symbols:   14081
+  CStrings:  2664
Symbols:
+ -[CSCombinedListViewController hasScrolled]
+ -[CSCombinedListViewController setHasScrolled:]
+ GCC_except_table221
+ _OBJC_IVAR_$_CSCombinedListViewController._hasScrolled
- GCC_except_table220
Functions:
~ -[CSCombinedListViewController handleEvent:] : 1444 -> 1468
~ -[CSCombinedListViewController aggregateBehavior:] : 788 -> 864
+ -[CSCombinedListViewController setHasScrolled:]
~ -[CSCombinedListViewController _triggerSignificantUserInteractionIfNeeded] : 548 -> 560
+ -[CSCombinedListViewController setAllowsDNDStateService:]
CStrings:
+ "[CSCombinedList][AggBehavior] falling back to default locked"
+ "[CSCombinedList][AggBehavior] has scrolled"
- "[CSCombinedList][AggBehavior] has content"
```
