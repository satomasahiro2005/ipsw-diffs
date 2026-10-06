## AccessibilitySharedSupport

> `/System/Library/PrivateFrameworks/AccessibilitySharedSupport.framework/AccessibilitySharedSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1793c0` | `0x17dd90` | **`+0x49d0`** |
| `__TEXT.__eh_frame` | `0x8dec` | `0x8fe4` | **`+0x1f8`** |
| `__TEXT.__const` | `0x204e8` | `0x20698` | **`+0x1b0`** |
| `__AUTH_CONST.__const` | `0x17f48` | `0x180c8` | **`+0x180`** |
| `__DATA.__bss` | `0x3cd80` | `0x3cea0` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x50b5` | `0x51c5` | **`+0x110`** |
| `__TEXT.__swift5_reflstr` | `0x2d16` | `0x2df6` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x6a00` | `0x6ab0` | **`+0xb0`** |
| `__AUTH.__data` | `0x1790` | `0x1820` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x580c` | `0x5898` | **`+0x8c`** |
| `__AUTH_CONST.__auth_got` | `0x1ad0` | `0x1b58` | **`+0x88`** |
| `__AUTH_CONST.__objc_const` | `0x9cf0` | `0x9d70` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0xb30` | `0xbac` | **`+0x7c`** |
| `__TEXT.__constg_swiftt` | `0x5fc0` | `0x6004` | **`+0x44`** |
| `__TEXT.__swift5_typeref` | `0x69b6` | `0x69ea` | **`+0x34`** |
| `__DATA_DIRTY.__data` | `0x30` | `0x50` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x70c` | `0x724` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x21c` | `0x230` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xd48` | `0xd58` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x1b78` | `0x1b80` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `0xc0` | `0xc8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x1e44` | `0x1e4c` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x9bc` | `0x9c4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x204` | `0x20c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x4e8` | `0x4ec` | **`+0x4`** |

### Other Changes

```diff

-591.4.1.0.0
+591.4.2.0.0

-  Functions: 12054
-  Symbols:   6755
-  CStrings:  1641
+  Functions: 12116
+  Symbols:   6763
+  CStrings:  1644
Symbols:
+ -[AXImageCaptionAssetManagerWrapper initWithImageCaptionsIsEnabled:setImageCaptionsIsEnabled:imageCaptionsPreferenceWasSetByUser:shouldDownloadAsset:]
+ ___swift_closure_destructor.410Tm
+ _get_enum_tag_for_layout_string 26AccessibilitySharedSupport14AXChatProviderC9RateLimitV12RetryWordingO
+ _keypath_set.289Tm
+ _symbolic SS4time_t
+ _symbolic _____ 26AccessibilitySharedSupport14AXChatProviderC9RateLimitV
+ _symbolic _____ 26AccessibilitySharedSupport14AXChatProviderC9RateLimitV12RetryWordingO
+ _symbolic _____Sg 26AccessibilitySharedSupport14AXChatProviderC9RateLimitV
+ _symbolic _____Sg_ABt 26AccessibilitySharedSupport14AXChatProviderC9RateLimitV
+ _symbolic ______pSg So8NSObjectP
+ _type_layout_string 26AccessibilitySharedSupport14AXChatProviderC9RateLimitV12RetryWordingO
- -[AXImageCaptionAssetManagerWrapper initWithImageCaptionsIsEnabled:setImageCaptionsIsEnabled:shouldDownloadAsset:]
- ___swift_closure_destructor.337Tm
- _keypath_set.277Tm
CStrings:
+ "Audio engine reconfigured mid-session; the input tap will not resume. Ending transcription."
+ "Audio input stalled: no buffers for %fs. Ending transcription."
+ "[AXImageCaptionAssetManager]: Image descriptions were turned off by the user. Leaving the setting alone."
```
