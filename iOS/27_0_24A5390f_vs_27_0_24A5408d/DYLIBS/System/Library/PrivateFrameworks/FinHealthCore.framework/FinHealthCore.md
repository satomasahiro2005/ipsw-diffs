## FinHealthCore

> `/System/Library/PrivateFrameworks/FinHealthCore.framework/FinHealthCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf8218` | `0xf4424` | **`-0x3df4`** |
| `__DATA.__bss` | `0x3b20` | `0x3930` | **`-0x1f0`** |
| `__TEXT.__const` | `0x3cf8` | `0x3b78` | **`-0x180`** |
| `__TEXT.__eh_frame` | `0x5720` | `0x55c8` | **`-0x158`** |
| `__AUTH_CONST.__const` | `0x2bb0` | `0x2a88` | **`-0x128`** |
| `__TEXT.__swift5_typeref` | `0x1a52` | `0x19b2` | **`-0xa0`** |
| `__TEXT.__cstring` | `0xa2ea` | `0xa26a` | **`-0x80`** |
| `__DATA.__data` | `0xd80` | `0xd10` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0x2a68` | `0x2a30` | **`-0x38`** |
| `__DATA_CONST.__got` | `0xae8` | `0xab8` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x3f6e` | `0x3f9e` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x180` | `0x150` | **`-0x30`** |
| `__AUTH_CONST.__cfstring` | `0x6860` | `0x6880` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xc53` | `0xc33` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0xeec` | `0xed0` | **`-0x1c`** |
| `__TEXT.__swift_as_cont` | `0x394` | `0x378` | **`-0x1c`** |
| `__AUTH_CONST.__auth_got` | `0x1568` | `0x1550` | **`-0x18`** |
| `__TEXT.__constg_swiftt` | `0xfa0` | `0xf8c` | **`-0x14`** |
| `__TEXT.__swift5_proto` | `0x1dc` | `0x1cc` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x198` | `0x1a8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2108` | `0x2110` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x114` | `0x110` | **`-0x4`** |

### Other Changes

```diff

-1.9.1.28.0
+1.9.1.29.0

-  Functions: 3423
-  Symbols:   3440
-  CStrings:  1273
+  Functions: 3403
+  Symbols:   3428
+  CStrings:  1269
Symbols:
- _NSLocalizedDescriptionKey
- ___swift_deallocate_boxed_opaque_existential_1
- _associated conformance 13FinHealthCore16AnnotatableTypesOSHAASQ
- _associated conformance 13FinHealthCore16AnnotatableTypesOs12CaseIterableAA8AllCasessADP_Sl
- _symbolic Say_____G 13FinHealthCore16AnnotatableTypesO
- _symbolic _____ 10FinanceKit11TransactionV
- _symbolic _____ 13FinHealthCore16AnnotatableTypesO
- _symbolic _____y______G 10Foundation20PredicateExpressionsO8VariableV 10FinanceKit11TransactionV
- _symbolic _____y______QPG 10Foundation9PredicateV 10FinanceKit11TransactionV
- _symbolic _____y______QPGSg 10Foundation9PredicateV 10FinanceKit11TransactionV
- _symbolic _____y______y______G_____G 10Foundation20PredicateExpressionsO7KeyPathV AC8VariableV 10FinanceKit11TransactionV AA4UUIDV
- _symbolic _____y______y______y______G_____G_____y_AFGG 10Foundation20PredicateExpressionsO5EqualV AC7KeyPathV AC8VariableV 10FinanceKit11TransactionV AA4UUIDV AC5ValueV
CStrings:
+ "FinanceKitDataStore: failed to fetch annotations for account %s - %@"
+ "FinanceKitDataStore: failed to fetch annotations for transaction %s - %@"
+ "FinanceKitDataStore: failed to set annotations for account %s - %@"
+ "FinanceKitDataStore: failed to set annotations for transaction %s - %@"
+ "FinanceKitDataStore: fetching annotations for account %s"
+ "FinanceKitDataStore: fetching annotations for transaction %s"
+ "FinanceKitDataStore: setting annotations for account %s"
+ "FinanceKitDataStore: setting annotations for transaction %s"
+ "FinanceKitDataStore: successfully fetched annotations for account %s"
+ "FinanceKitDataStore: successfully fetched annotations for transaction %s"
+ "FinanceKitDataStore: successfully set annotations for account %s"
+ "FinanceKitDataStore: successfully set annotations for transaction %s"
+ "UTC"
- "Account"
- "Account not found"
- "FinanceKitDataStore"
- "FinanceKitDataStore: account not found for UUID %s"
- "FinanceKitDataStore: annotating id %s of type %s with key '%s'"
- "FinanceKitDataStore: deleting annotation for id %s of type %s with key '%s'"
- "FinanceKitDataStore: failed to annotate id %s of type %s - %@"
- "FinanceKitDataStore: failed to delete annotation for id %s of type %s - %@"
- "FinanceKitDataStore: failed to fetch annotation for id %s - %@"
- "FinanceKitDataStore: fetching annotation for id %s of type %s with key '%s'"
- "FinanceKitDataStore: no annotation found for id %s with key '%s'"
- "FinanceKitDataStore: successfully annotated id %s of type %s"
- "FinanceKitDataStore: successfully deleted annotation for id %s of type %s"
- "FinanceKitDataStore: successfully fetched annotation for id %s"
- "FinanceKitDataStore: transaction not found for UUID %s"
- "Transaction"
- "Transaction not found"
```
