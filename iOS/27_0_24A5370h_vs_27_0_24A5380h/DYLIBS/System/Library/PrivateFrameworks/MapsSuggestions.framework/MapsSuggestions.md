## MapsSuggestions

> `/System/Library/PrivateFrameworks/MapsSuggestions.framework/MapsSuggestions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x720` | `0xd30` | **`+0x610`** |
| `__AUTH.__data` | `0x4e0` | `0x170` | **`-0x370`** |
| `__DATA.__bss` | `0xe10` | `0xb00` | **`-0x310`** |
| `__DATA_DIRTY.__bss` | `0x430` | `0x730` | **`+0x300`** |
| `__DATA.__data` | `0x2b38` | `0x28d8` | **`-0x260`** |
| `__AUTH.__objc_data` | `0x12a8` | `0x1058` | **`-0x250`** |
| `__DATA_DIRTY.__objc_data` | `0x5650` | `0x58a0` | **`+0x250`** |
| `__TEXT.__text` | `0x194040` | `0x1940a0` | **`+0x60`** |
| `__DATA.__common` | `0xa0` | `0x70` | **`-0x30`** |
| `__DATA_DIRTY.__common` | `0x1c0` | `0x1f0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2c130` | `0x2c160` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1180` | `0x1188` | **`+0x8`** |

### Other Changes

```diff

-2970.30.6.5.7
+2972.30.6.12.16

-  CStrings:  5452
+  CStrings:  5453
Symbols:
+ _swift_retain_x28
- _swift_willThrowTypedImpl
Functions:
~ ___67-[MapsSuggestionsXPCActivityTimer scheduleWithTimeInterval:leeway:]_block_invoke.132 : 1172 -> 1200
~ __ZNSt3__15dequeIU8__strongP6NSDateNS_9allocatorIS3_EEE19__add_back_capacityEv : 484 -> 472
~ __ZNK3MSg17EnumSignalEncoderI26GEOTransportTypePreferenceE6encodeEf : 132 -> 136
~ -[MapsSuggestionsShortcutAtMapItemDeduper dedupeByEnrichingEntry:withEntry:] : 980 -> 944
~ sub_226d903c8 -> sub_22b6513b8 : 704 -> 672
~ sub_226d90d34 -> sub_22b651d04 : 432 -> 428
~ sub_226daf5c4 -> sub_22b670590 : 6420 -> 6572
~ -[MapsSuggestionsBudget _q_hasBudgetLeft] : 252 -> 248
CStrings:
+ "00:25:40"
+ "Jun 28 2026"
+ "com.apple.maps.suggestions.xpc-activity-expiration"
- "22:46:49"
- "Jun 15 2026"
```
