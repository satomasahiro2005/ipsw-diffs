## HealthDiagnosticExtensionCore

> `/System/Library/PrivateFrameworks/HealthDiagnosticExtensionCore.framework/HealthDiagnosticExtensionCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x26bb` | `0x273b` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x2500` | `0x2540` | **`+0x40`** |
| `__TEXT.__text` | `0xb138` | `0xb158` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x810` | `0x818` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  CStrings:  334
+  CStrings:  336
Functions:
~ -[HDNotificationSyncDiagnosticOperation run] : 248 -> 260
~ ___104-[HDSummarySharingDiagnosticOperation _reportSharedSummariesForProfileIdentifier:committedTransactions:]_block_invoke : 544 -> 564
CStrings:
+ "HDNotificationSyncDiagnosticOperation:run"
+ "HDSummarySharingDiagnosticOperation:_reportSharedSummariesForProfileIdentifier"
```
