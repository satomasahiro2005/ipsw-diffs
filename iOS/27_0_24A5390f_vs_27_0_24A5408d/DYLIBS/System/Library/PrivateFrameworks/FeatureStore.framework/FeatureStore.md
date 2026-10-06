## FeatureStore

> `/System/Library/PrivateFrameworks/FeatureStore.framework/FeatureStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25d5c` | `0x264c4` | **`+0x768`** |
| `__AUTH_CONST.__objc_const` | `0x5258` | `0x55f8` | **`+0x3a0`** |
| `__TEXT.__cstring` | `0xb69` | `0xbe9` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xae2` | `0xb62` | **`+0x80`** |
| `__DATA.__data` | `0x668` | `0x6c8` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xfd4` | `0x102c` | **`+0x58`** |
| `__DATA_CONST.__objc_selrefs` | `0x668` | `0x698` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x218` | `0x240` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xdd0` | `0xdf8` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0xa98` | `0xab8` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x1568` | `0x1588` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0xe50` | `0xe60` | **`+0x10`** |
| `__TEXT.__const` | `0x1600` | `0x1610` | **`+0x10`** |
| `__DATA.__common` | `0x58` | `0x60` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x80` | `0x88` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0xc0` | `0xc8` | **`+0x8`** |

### Other Changes

```diff

-3600.22.11.0.0
+3600.22.17.0.0

-  Functions: 1256
-  Symbols:   2768
-  CStrings:  137
+  Functions: 1281
+  Symbols:   2798
+  CStrings:  143
Symbols:
+ -[FSFCallKitUtil callObserver:callChanged:]
+ -[FSFCallKitUtil observerQueue]
+ -[FSFCallKitUtil recomputeOnCallFromCalls:]
+ -[FSFCallKitUtil setCallCenter:]
+ -[FSFCallKitUtil setObserverQueue:]
+ _$s12FeatureStore0aB7ServiceC27fcsAllowedStreamIdentifiersShySSGvMZ
+ _$s12FeatureStore0aB7ServiceC27fcsAllowedStreamIdentifiersShySSGvMZ.resume
+ _$s12FeatureStore0aB7ServiceC27fcsAllowedStreamIdentifiersShySSGvau
+ _$s12FeatureStore0aB7ServiceC27fcsAllowedStreamIdentifiersShySSGvgZ
+ _$s12FeatureStore0aB7ServiceC27fcsAllowedStreamIdentifiersShySSGvpZ
+ _$s12FeatureStore0aB7ServiceC27fcsAllowedStreamIdentifiersShySSGvsZ
+ _$s12FeatureStore0aB7ServiceC27fcsAllowedStreamIdentifiers_WZ
+ _$s12FeatureStore0aB7ServiceC28seedAllowedStreamIdentifiersShySSGvgZTm
+ _$s12FeatureStore0aB7ServiceC28seedAllowedStreamIdentifiersShySSGvsZTm
+ _FSFCallKitLog.onceToken
+ _FSFCallKitLog.sLog
+ _OBJC_IVAR_$_FSFCallKitUtil._isOnCall
+ _OBJC_IVAR_$_FSFCallKitUtil._observerQueue
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CXCallObserverDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CXCallObserverDelegate
+ __OBJC_$_PROTOCOL_REFS_CXCallObserverDelegate
+ __OBJC_CLASS_PROTOCOLS_$_FSFCallKitUtil
+ __OBJC_LABEL_PROTOCOL_$_CXCallObserverDelegate
+ __OBJC_PROTOCOL_$_CXCallObserverDelegate
+ ___22-[FSFCallKitUtil init]_block_invoke
+ ___FSFCallKitLog_block_invoke
+ ___block_descriptor_40_e8_32s_e5_v8?0ls32l8
+ _dispatch_async
+ _dispatch_queue_attr_make_with_qos_class
+ _dispatch_queue_create
+ _os_log_create
- _$s12FeatureStore0aB7ServiceC28seedAllowedStreamIdentifiers_Wz
CStrings:
+ "CXCallObserver callChanged: changedCallEnded=%{public}d isOnCall=%{public}d"
+ "CallKit"
+ "FCS-build capture decision for stream %s: %s"
+ "allowed (in fcsAllowedStreamIdentifiers)"
+ "blocked (not in fcsAllowedStreamIdentifiers)"
+ "com.apple.FeatureStore.callkit"
```
