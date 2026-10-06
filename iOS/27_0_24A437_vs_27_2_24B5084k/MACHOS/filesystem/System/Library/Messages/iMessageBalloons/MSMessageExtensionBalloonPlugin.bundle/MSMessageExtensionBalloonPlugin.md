## MSMessageExtensionBalloonPlugin

> `/System/Library/Messages/iMessageBalloons/MSMessageExtensionBalloonPlugin.bundle/MSMessageExtensionBalloonPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ae8c` | `0x2b788` | **`+0x8fc`** |
| `__TEXT.__objc_methname` | `0x8b3d` | `0x8ccd` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0x2cf4` | `0x2e64` | **`+0x170`** |
| `__TEXT.__objc_stubs` | `0x6b60` | `0x6c80` | **`+0x120`** |
| `__TEXT.__objc_methlist` | `0x2eec` | `0x2f5c` | **`+0x70`** |
| `__DATA.__objc_selrefs` | `0x23a8` | `0x2408` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x794` | `0x7ec` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x1120` | `0x1170` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x1ede` | `0x1f2e` | **`+0x50`** |
| `__DATA.__objc_const` | `0x3718` | `0x3750` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0xc38` | `0xc68` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x668` | `0x678` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0xed0` | `0xee0` | **`+0x10`** |
| `__TEXT.__const` | `0x494` | `0x4a4` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x778` | `0x780` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1e4` | `0x1e8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1491.100.1.2.25
+1491.200.63.2.1

-  Functions: 1074
-  Symbols:   483
-  CStrings:  1934
+  Functions: 1082
+  Symbols:   486
+  CStrings:  1953
Symbols:
+ _IMBalloonBundleIdentifierLegacyAskToBuy
+ _IMBalloonPluginIdentifierIsReplyable
+ _OBJC_CLASS_$_IMFeatureFlags
CStrings:
+ "LiveBubble. Deferring remote view creation until on window. messageGUID: %@"
+ "LiveBubble. On window; retrying deferred remote view creation. messageGUID: %@"
+ "LiveBubble. Requesting remote view controller from extension for messageGUID: %@"
+ "LiveBubble. remoteProxy nil breakdown — remoteVC: %@ requestUUID: %@ hostContext: %@ auxConnection: %@"
+ "_addRemoteViewControllerAndConfigureExtension %@ firstResponder: %@"
+ "_needsRemoteViewCreationOnWindow"
+ "_shouldApplyMoveToWindowDeferral"
+ "_stageAppItem:replyingToMessage:skipShelf:completionHandler:"
+ "_stagePayload:skipShelf:completion:"
+ "_substituteNamesInAppItem:"
+ "balloonTailInsets"
+ "didMoveToWindow"
+ "firstResponder"
+ "isAppleCashRepliesEnabled"
+ "liveViewDidMoveToWindow:"
+ "setThreadReferenceBalloonBundleID:"
+ "setThreadReferenceMessageGUID:"
+ "sharedFeatureFlags"
+ "stageAppItem:replyingToMessage:skipShelf:completionHandler:"
+ "v44@0:8@\"MSMessage\"16@\"MSMessage\"24B32@?<v@?B@\"NSError\">36"
+ "v44@0:8@16@24B32@?36"
- "_addRemoteViewControllerAndConfigureExtension %@"
- "pluginBalloonInsetsForMessageFromMe:"
```
