## VisualActionPredictionCore

> `/System/Library/PrivateFrameworks/VisualActionPredictionCore.framework/VisualActionPredictionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa584c` | `0xa7a50` | **`+0x2204`** |
| `__AUTH_CONST.__const` | `0x2370` | `0x2450` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x282a` | `0x289a` | **`+0x70`** |
| `__TEXT.__const` | `0x4788` | `0x47d8` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x1818` | `0x185e` | **`+0x46`** |
| `__TEXT.__swift5_fieldmd` | `0x1558` | `0x159c` | **`+0x44`** |
| `__TEXT.__swift5_reflstr` | `0x1695` | `0x16d5` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x1280` | `0x12bc` | **`+0x3c`** |
| `__DATA.__data` | `0xb58` | `0xb88` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x2948` | `0x2970` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x488` | `0x4ac` | **`+0x24`** |
| `__DATA_CONST.__got` | `0xa20` | `0xa38` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1a58` | `0x1a68` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x3b8` | `0x3c0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x394` | `0x39c` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x300` | `0x304` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x14` | `0x18` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x14c` | `0x150` | **`+0x4`** |

### Other Changes

```diff

-664.0.2.1.0
+667.0.0.0.0

-  Functions: 1816
-  Symbols:   952
-  CStrings:  308
+  Functions: 1828
+  Symbols:   957
+  CStrings:  310
Symbols:
+ ___swift_closure_destructor.44Tm
+ _symbolic $s26VisualActionPredictionCore14DataHarvestingP
+ _symbolic _____ 26VisualActionPredictionCore24SessionTransactionLedgerV
+ _symbolic ______p_____Ybc 26VisualActionPredictionCore14DataHarvestingP 10Foundation4UUIDV
+ _type_layout_string 26VisualActionPredictionCore24SessionTransactionLedgerV
CStrings:
+ "Relinquish preceded acquire; tombstoning session. (uuid = %s)"
+ "Skipping registration for already-relinquished session. (uuid = %s)"
+ "Successfully sent unseen-dismissal feedback event"
- "Unable to relinquish OS transaction because it no longer exists. (uuid = %s, count = %ld)"
```
