## TVRemoteCore

> `/System/Library/PrivateFrameworks/TVRemoteCore.framework/TVRemoteCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4834c` | `0x483e4` | **`+0x98`** |
| `__AUTH_CONST.__cfstring` | `0x4ac0` | `0x4aa0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x3798` | `0x3784` | **`-0x14`** |

### Other Changes

```diff

-627.0.9.0.0
+627.0.14.0.0

-  CStrings:  1301
+  CStrings:  1300
Functions:
~ -[TVRCAnalytics logConnectionStatus:type:reason:] : 312 -> 304
~ -[TVRCDevice _deviceUpdatedState:] : 3740 -> 3884
~ -[TVRCDeviceState description] : 720 -> 716
~ -[TVRCDeviceState detailedDescription] : 748 -> 744
~ -[TVRCHIDSession _commandForButtonEvent:] : 100 -> 96
~ -[TVRCHIDTouchSession _invalidateWithCompletion:] : 436 -> 452
~ -[TVRCHIDTouchSession sendTouchEvent:completion:] : 584 -> 620
~ -[TVRCMediaEventsManager _captionSettingForButtonEvent:] : 100 -> 96
~ -[TVRCRapportMediaEventsManager _captionSettingForButtonEvent:] : 100 -> 96
~ -[TVRCRPCompanionLinkClientWrapper _updateAttentionState:] : 368 -> 360
~ -[TVRCRPCompanionLinkClientWrapper _commandForButtonEvent:] : 100 -> 96
~ ___63-[TVRCRPCompanionLinkClientWrapper _handleSideEffectsForEvent:]_block_invoke : 1456 -> 1452
CStrings:
- "ActivateScreenSaver"
```
