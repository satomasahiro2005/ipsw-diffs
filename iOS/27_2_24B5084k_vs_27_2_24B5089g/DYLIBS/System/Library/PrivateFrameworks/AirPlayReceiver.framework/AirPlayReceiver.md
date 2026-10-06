## AirPlayReceiver

> `/System/Library/PrivateFrameworks/AirPlayReceiver.framework/AirPlayReceiver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x17cb0` | `0x17c40` | **`-0x70`** |
| `__DATA_DIRTY.__data` | `0x310` | `0x380` | **`+0x70`** |
| `__TEXT.__text` | `0x17c374` | `0x17c39c` | **`+0x28`** |
| `__TEXT.__cstring` | `0x33200` | `0x33201` | **`+0x1`** |

### Other Changes

```diff

-1005.7.1.0.0
+1005.8.1.0.0
Symbols:
+ _APAdvertiserInfoCopyNameWithoutMDNSLabelSuffix
- __APAdvertiserInfoCopyAndRemoveMDNSLabelSuffix
Functions:
~ __APAdvertiserInfoCopyAndRemoveMDNSLabelSuffix -> _APAdvertiserInfoCopyNameWithoutMDNSLabelSuffix : 468 -> 508
CStrings:
+ "1005.8.1"
+ "APAdvertiserInfoCopyNameWithoutMDNSLabelSuffix"
- "1005.7.1"
- "_APAdvertiserInfoCopyAndRemoveMDNSLabelSuffix"
```
