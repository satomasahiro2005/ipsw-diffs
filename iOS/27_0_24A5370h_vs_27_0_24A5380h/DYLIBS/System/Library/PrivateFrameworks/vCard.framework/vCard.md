## vCard

> `/System/Library/PrivateFrameworks/vCard.framework/vCard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `—` | `0x120` | **`+0x120`** |
| `__DATA_DIRTY.__objc_data` | `0x1bf8` | `0x1ad8` | **`-0x120`** |
| `__TEXT.__text` | `0x24804` | `0x247fc` | **`-0x8`** |

### Other Changes

```diff

-3835.100.6.0.0
+3837.100.1.0.0
Functions:
~ -[NSData(vCardAdditions) _cn_encodeVCardBase64DataWithInitialLength:] : 528 -> 520
```
