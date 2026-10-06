## SpotlightIndex

> `/System/Library/PrivateFrameworks/SpotlightIndex.framework/SpotlightIndex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x482d88` | `0x483600` | **`+0x878`** |
| `__TEXT.__oslogstring` | `0x1ddf2` | `0x1e105` | **`+0x313`** |
| `__TEXT.__cstring` | `0x2f434` | `0x2f4a4` | **`+0x70`** |
| `__DATA.__bss` | `0x3ff0` | `0x4010` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0x9cc8` | `0x9cb8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1f30` | `0x1f38` | **`+0x8`** |

### Other Changes

```diff

-2465.1.3.0.0
+2465.1.7.0.0

-  Functions: 7755
-  Symbols:   10266
-  CStrings:  8072
+  Functions: 7757
+  Symbols:   10270
+  CStrings:  8085
Symbols:
+ GCC_except_table6757
+ _CIIndexSetCreateWithRange.sLoggedCount
+ __CIIndexSetAddRange_Bitmap_Src_SparseDst
+ __CIIndexSetSetIndexRangeWithCache.sLoggedCount
+ _repair_journal_flush
- GCC_except_table6755
CStrings:
+ "%s:%d: Parsed v2 journal entry with faulty isFromMail size %ld"
+ "%s:%d: Repair journal: could not write the %u item batch for bundle %@; those items will not be repaired"
+ "%s:%d: Repair journal: the plist builder refused a value, most likely nesting past its depth bound; dropping the whole %u item batch for bundle %@"
+ "%s:%d: Rogue accumulated position %d at docID %d off %llu. Canceling"
+ "%s:%d: Rogue nil position at docID %d off %llu size %llu(%llu), Rogue nil count %d. Canceling _CIPositionIterate_Compressed"
+ "%s:%d: Rogue position %d at docID %d off %llu size %llu(%llu), Rogue count %d. Canceling"
+ "%s:%d: Rogue position %d at docID %d off %llu. Canceling _CIPositionIterate_Compressed"
+ "%s:%d: [CIIndexSet] CIIndexSetCreateWithRange: unrepresentable range [%u, %u], clamping"
+ "%s:%d: [CIIndexSet] _CIIndexSetSetIndexRangeWithCache: refusing unrepresentable range [%u, %u]"
+ "%s:%d: unrepresentable payloadCount (%u), marking index invalid\n"
+ "2465.1.7"
+ "<si:%s> - Playback skipping sn: %lld mrsn: %lld csn: %lld mailMigration: %d"
+ "CIIndexSetCreateWithRange"
+ "_CIIndexSetSetIndexRangeWithCache"
+ "repair_journal_batch_abandoned"
+ "repair_journal_flush"
- "%s:%d: Rogue nil position at docID %d off %llu size %llu(%llu), Rogue nil count %d. Canceling"
- "%s:%d: Rogue nil position at docID %d off %llu size %llu(%llu), Rogue nil count %d. Canceling _CIPositionIterate_NewCompressed"
- "2465.1.3"
```
