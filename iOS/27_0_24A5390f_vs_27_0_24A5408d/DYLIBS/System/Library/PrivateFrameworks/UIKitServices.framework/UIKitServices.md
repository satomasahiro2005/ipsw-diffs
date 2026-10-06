## UIKitServices

> `/System/Library/PrivateFrameworks/UIKitServices.framework/UIKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methlist` | `0x2f3c` | `0x2fac` | **`+0x70`** |
| `__TEXT.__text` | `0x21400` | `0x21450` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x17e0` | `0x17f0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xbe8` | `0xbf8` | **`+0x10`** |

### Other Changes

```diff

-9127.0.79.1.102
+9127.0.84.1.102

-  Functions: 1008
-  Symbols:   2380
+  Functions: 1018
+  Symbols:   2390
Symbols:
+ -[UISActivityContinuationAction abortForUsageViolation:]
+ -[UISFetchContentInBackgroundAction abortForUsageViolation:]
+ -[UISHandleApplicationShortcutAction abortForUsageViolation:]
+ -[UISHandleBackgroundURLSessionAction abortForUsageViolation:]
+ -[UISHandleCloudKitShareAction abortForUsageViolation:]
+ -[UISHandleRemoteNotificationAction abortForUsageViolation:]
+ -[UISIntentForwardingActionResponse abortForUsageViolation:]
+ -[UISNotificationResponseAction abortForUsageViolation:]
+ -[UISOpenURLAction abortForUsageViolation:]
+ -[UISSceneConnectionValueAction abortForUsageViolation:]
Functions:
+ -[UISSceneConnectionValueAction abortForUsageViolation:]
+ -[UISHandleRemoteNotificationAction abortForUsageViolation:]
+ -[UISNotificationResponseAction abortForUsageViolation:]
+ -[UISActivityContinuationAction abortForUsageViolation:]
+ -[UISHandleCloudKitShareAction abortForUsageViolation:]
+ -[UISOpenURLAction abortForUsageViolation:]
+ -[UISHandleBackgroundURLSessionAction abortForUsageViolation:]
+ -[UISIntentForwardingActionResponse abortForUsageViolation:]
+ +[UISSceneRequestOptions supportsBSXPCSecureCoding]
+ -[UISHandleApplicationShortcutAction abortForUsageViolation:]
```
