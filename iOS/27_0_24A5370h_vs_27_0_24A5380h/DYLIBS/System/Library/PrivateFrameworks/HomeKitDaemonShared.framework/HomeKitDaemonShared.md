## HomeKitDaemonShared

> `/System/Library/PrivateFrameworks/HomeKitDaemonShared.framework/HomeKitDaemonShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb450` | `0xaee8` | **`-0x568`** |
| `__AUTH_CONST.__cfstring` | `0x820` | `0x620` | **`-0x200`** |
| `__AUTH_CONST.__objc_const` | `0x1a08` | `0x1910` | **`-0xf8`** |
| `__TEXT.__cstring` | `0x5e4` | `0x519` | **`-0xcb`** |
| `__TEXT.__objc_methlist` | `0xcb4` | `0xbec` | **`-0xc8`** |
| `__DATA.__data` | `0x638` | `0x5d8` | **`-0x60`** |
| `__DATA_CONST.__objc_selrefs` | `0x7c8` | `0x768` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x290` | `0x240` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x350` | `0x330` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x2c0` | `0x2a0` | **`-0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x88` | `0x80` | **`-0x8`** |
| `__TEXT.__const` | `0x2d8` | `0x2d0` | **`-0x8`** |

### Other Changes

```diff

-1479.0.0.1.0
+1484.2.0.0.0

-  Functions: 264
-  Symbols:   602
-  CStrings:  180
+  Functions: 252
+  Symbols:   583
+  CStrings:  164
Symbols:
- -[HMDStatusChannelManagementLogEvent amsMetricsEventProperties]
- -[HMDStatusChannelManagementLogEvent amsMetricsEventSchemaVersion]
- -[HMDStatusChannelManagementLogEvent amsMetricsEventType]
- -[HMDStatusChannelObserveLogEvent amsMetricsEventProperties]
- -[HMDStatusChannelObserveLogEvent amsMetricsEventSchemaVersion]
- -[HMDStatusChannelObserveLogEvent amsMetricsEventType]
- -[HMDStatusChannelObserveLogEvent startMilliseconds]
- -[HMDStatusChannelPublishLogEvent amsMetricsEventProperties]
- -[HMDStatusChannelPublishLogEvent amsMetricsEventSchemaVersion]
- -[HMDStatusChannelPublishLogEvent amsMetricsEventType]
- -[HMDStatusChannelPublishLogEvent endMilliseconds]
- -[HMDStatusChannelPublishLogEvent startMilliseconds]
- _OBJC_CLASS_$_HMMDatedLogEvent
- _OBJC_METACLASS_$_HMMDatedLogEvent
- __OBJC_$_PROP_LIST_HMMAMSMetricsObservable
- __OBJC_$_PROTOCOL_INSTANCE_METHODS_HMMAMSMetricsObservable
- __OBJC_$_PROTOCOL_METHOD_TYPES_HMMAMSMetricsObservable
- __OBJC_LABEL_PROTOCOL_$_HMMAMSMetricsObservable
- __OBJC_PROTOCOL_$_HMMAMSMetricsObservable
CStrings:
- "channelManagementAction"
- "clientEventId"
- "invite"
- "manage"
- "observe"
- "publish"
- "remove"
- "retryCount"
- "statusKitOperation"
- "statusObserveTime"
- "statusPublishAckTime"
- "statusPublishTime"
- "subscribe"
- "taskType"
- "undefined"
- "unsubscribe"
```
