## SiriUIActivation

> `/System/Library/PrivateFrameworks/SiriUIActivation.framework/SiriUIActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f780` | `0x2f7e0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x4edb` | `0x4f2b` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x2020` | `0x2028` | **`+0x8`** |

### Other Changes

```diff

-3605.30.1.0.0
+3605.31.1.11.2

-  CStrings:  631
+  CStrings:  632
Functions:
~ ___104-[SiriPresentationViewController handleButtonUpFromButtonIdentifier:deviceIdentifier:timestamp:context:]_block_invoke : 952 -> 1036
~ -[SiriPresentationViewController handleButtonTapFromButtonIdentifier:timestamp:context:] : 508 -> 520
CStrings:
+ "%s #activation #odeonProxy Not stopping requests for Odeon voice trigger"
```
