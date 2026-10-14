## AirPlayReceiverKit

> `/System/Library/PrivateFrameworks/AirPlayReceiverKit.framework/AirPlayReceiverKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26a68` | `0x26a8c` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x1350` | `0x1358` | **`+0x8`** |
| `__TEXT.__cstring` | `0x8dc1` | `0x8dc3` | **`+0x2`** |

### Other Changes

```diff

-1005.12.1.0.0
+1005.13.1.1.0

-  Symbols:   1572
+  Symbols:   1573
Symbols:
+ _APSIsHomeAccessory
Functions:
~ -[APRKMediaPlayer initWithP2PWiFiSupport:isInterstitialPlayer:playerSessionID:] : 940 -> 960
~ -[APRKMediaPlayer _insertPlayQueueItemWithDictionary:] : 2684 -> 2700
CStrings:
+ "1005.13.1.1"
- "1005.12.1"
```
