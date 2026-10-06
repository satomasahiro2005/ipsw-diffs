## SampleAnalysis

> `/System/Library/PrivateFrameworks/SampleAnalysis.framework/SampleAnalysis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x230` | `0x50` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `0x2260` | `0x2440` | **`+0x1e0`** |
| `__TEXT.__text` | `0x105fc8` | `0x105ecc` | **`-0xfc`** |
| `__TEXT.__oslogstring` | `0xc4de` | `0xc4ac` | **`-0x32`** |
| `__DATA_CONST.__got` | `0x400` | `0x430` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x20614` | `0x20600` | **`-0x14`** |
| `__DATA_DIRTY.__bss` | `0x468` | `0x460` | **`-0x8`** |

### Other Changes

```diff

-436.0.0.0.0
+438.0.0.0.0

-  Functions: 2833
+  Functions: 2832

-  CStrings:  3716
+  CStrings:  3715
Symbols:
+ GCC_except_table274
+ GCC_except_table285
+ GCC_except_table556
+ GCC_except_table559
+ GCC_except_table561
+ GCC_except_table565
+ GCC_except_table569
+ GCC_except_table571
+ GCC_except_table573
+ GCC_except_table592
+ GCC_except_table597
- GCC_except_table278
- GCC_except_table557
- GCC_except_table560
- GCC_except_table563
- GCC_except_table567
- GCC_except_table570
- GCC_except_table572
- GCC_except_table575
- GCC_except_table594
- GCC_except_table598
- ___31-[SASampleStore gatherKextStat]_block_invoke_3
Functions:
~ -[SASampleStore handleNonMicrostackshotData:bufSize:statistics:] : 6724 -> 6784
~ ___SACachedNSString_block_invoke : 64 -> 72
~ ___31-[SASampleStore gatherKextStat]_block_invoke_2 : 700 -> 532
- ___31-[SASampleStore gatherKextStat]_block_invoke_3
CStrings:
- "Unable to convert kextstat output to NSString: %s"
```
