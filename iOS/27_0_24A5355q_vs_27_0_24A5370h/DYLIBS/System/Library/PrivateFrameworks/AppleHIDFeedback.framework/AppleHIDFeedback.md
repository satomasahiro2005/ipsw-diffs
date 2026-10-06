## AppleHIDFeedback

> `/System/Library/PrivateFrameworks/AppleHIDFeedback.framework/AppleHIDFeedback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b44` | `0x4b6c` | **`+0x28`** |

### Other Changes

```diff
Symbols:
+ _objc_retain_x26
- _objc_retain_x24
Functions:
~ -[AHFPencilPatternLibrary createPatternsLibraryFrom:] : 2896 -> 2960
~ -[AHFPencilPatternLibrary maybeGetExploratoryPayload:] : 604 -> 600
~ -[AHFPencilController initializeDigitizerStylusSystem] : 576 -> 572
~ -[AHFPencilController initializeOpaqueTouchSystem] : 576 -> 572
~ -[AHFPencilController initializePencilHapticsSystem] : 548 -> 544
~ -[AHFTrackpadController initializeTrackpadSystem] : 696 -> 692
~ ___66-[AHFTrackpadController playFeedback:accessoryID:timestamp:error:]_block_invoke : 440 -> 436
```
