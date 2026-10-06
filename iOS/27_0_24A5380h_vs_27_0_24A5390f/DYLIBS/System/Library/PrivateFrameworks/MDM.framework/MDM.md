## MDM

> `/System/Library/PrivateFrameworks/MDM.framework/MDM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58544` | `0x585d0` | **`+0x8c`** |

### Other Changes

```diff

-111.0.0.0.0
+113.0.2.0.0
Symbols:
+ +[MDMMCInterface clearPasscodeWithEscrowKeybagData:secretContext:outError:]
- +[MDMMCInterface clearPasscodeWithEscrowKeybagData:secret:outError:]
Functions:
~ -[MDMParser _clearPasscode:] : 548 -> 688
```
