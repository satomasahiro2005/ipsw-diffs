## SetupKit

> `/System/Library/PrivateFrameworks/SetupKit.framework/SetupKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x28f54` | `0x28f7c` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `0xeec` | `0xef4` | **`+0x8`** |

### Other Changes

```diff

-900.58.0.0.0
+910.21.0.0.0

-  Symbols:   1841
+  Symbols:   1840
Symbols:
- _objc_unsafeClaimAutoreleasedReturnValue
Functions:
~ -[SKConnection _clientPairSetupContinueWithData:] : 892 -> 916
~ -[SKConnection _receivedHeader:encryptedObjectData:] : 640 -> 648
~ -[SKConnection _receivedHeader:unencryptedObjectData:] : 760 -> 768
```
