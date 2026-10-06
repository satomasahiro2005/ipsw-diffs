## IOMFB_bics_daemon

> `/usr/libexec/IOMFB_bics_daemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30868` | `0x31228` | **`+0x9c0`** |
| `__TEXT.__cstring` | `0x51fc` | `0x545c` | **`+0x260`** |
| `__TEXT.__const` | `0x5cf4` | `0x5e74` | **`+0x180`** |
| `__DATA.__bss` | `0x16a0` | `0x15a0` | **`-0x100`** |
| `__DATA_CONST.__auth_ptr` | `0x518` | `0x498` | **`-0x80`** |
| `__TEXT.__swift5_assocty` | `0x350` | `0x308` | **`-0x48`** |
| `__TEXT.__swift5_typeref` | `0x904` | `0x8be` | **`-0x46`** |
| `__DATA.__data` | `0xb80` | `0xb58` | **`-0x28`** |
| `__TEXT.__swift5_reflstr` | `0x268` | `0x248` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xd18` | `0xd38` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xb5c` | `0xb78` | **`+0x1c`** |
| `__TEXT.__auth_stubs` | `0x1370` | `0x1380` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x9d0` | `0x9d8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x238` | `0x230` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0x84` | `0x7c` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-700.50.80.0.0
+700.50.85.0.0

-  Functions: 978
-  Symbols:   511
-  CStrings:  762
+  Functions: 979
+  Symbols:   505
+  CStrings:  801
Symbols:
+ _xpc_dictionary_set_bool
- _$s17BorrowingIterators0A8SequencePTl
- _$s7Elements17BorrowingSequencePTl
- _$sSPyxGs8_PointersMc
- _$ss17BorrowingSequenceP04makeA8Iterator0aD0QzyFTq
- _$ss17BorrowingSequenceP0A8IteratorAB_s0aC8ProtocolTn
- _$ss17BorrowingSequenceP19underestimatedCountSivgTq
- _$ss17BorrowingSequenceP31_customContainsEquatableElementySbSg0F0QzFTq
CStrings:
+ "ArefFitBlue"
+ "ArefFitGreen"
+ "ArefFitRed"
+ "BetaFitBlue"
+ "BetaFitGreen"
+ "BetaFitRed"
+ "Brightness"
+ "EffNewB"
+ "EffNewBlue%d"
+ "EffNewG"
+ "EffNewGreen%d"
+ "EffNewR"
+ "EffNewRed%d"
+ "EffPeakShiftBlue"
+ "EffPeakShiftGreen"
+ "EffPeakShiftRed"
+ "Enabled"
+ "GenX: Reported 100 samples history metrics - enabled: %u"
+ "GenX: no history available for 100 sample reporting"
+ "Index"
+ "IsFailure"
+ "LthAvgB"
+ "LthAvgBlue%d"
+ "LthAvgG"
+ "LthAvgGreen%d"
+ "LthAvgR"
+ "LthAvgRed%d"
+ "LthPeakShiftBlue"
+ "LthPeakShiftGreen"
+ "LthPeakShiftRed"
+ "Lux"
+ "LuxAccum"
+ "NitsAccumBlue"
+ "NitsAccumGreen"
+ "NitsAccumRed"
+ "Temperature"
+ "com.apple.OracleGenX.History"
+ "com.apple.OracleGenX.Sample"
+ "com.apple.OracleGenX.SensingEvent"
```
