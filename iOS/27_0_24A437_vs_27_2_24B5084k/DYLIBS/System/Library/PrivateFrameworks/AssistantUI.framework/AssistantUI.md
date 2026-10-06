## AssistantUI

> `/System/Library/PrivateFrameworks/AssistantUI.framework/AssistantUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65e1c` | `0x65f50` | **`+0x134`** |
| `__DATA_CONST.__objc_selrefs` | `0x53c0` | `0x53f0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x7290` | `0x72c0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x8a46` | `0x8a66` | **`+0x20`** |

### Other Changes

```diff

-3600.55.37.11.4
+3605.22.2.0.0

-  Functions: 2803
-  Symbols:   4439
-  CStrings:  1222
+  Functions: 2807
+  Symbols:   4444
+  CStrings:  1223
Symbols:
+ +[AFUICarPlayUtilities requestOptions:referToSameNotificationAs:]
+ +[AFUIUtilities overrideBuddyImage]
+ +[AFUIUtilities shouldOverrideBuddyBehavior]
+ +[SRUIFSiriFeatureFlag(SWEFeatureFlags) isContinuousConversationHomepodEnabled]
+ -[AFUISiriCarPlayView _deviceSupportsSAE]
+ -[AFUISiriCarPlayView _deviceSupportsSiriAI]
+ -[AFUISiriCompactView siriWillPresentOverVisualIntelligence]
+ GCC_except_table29
- -[AFUISiriCarPlayView _deviceSupportsAI]
- -[AFUISiriCarPlayView _showContentViews]
- -[AFUISiriCompactView siriWillPresentOverVisualIntelliengece]
CStrings:
+ "continuous_conversation_homepod"
```
