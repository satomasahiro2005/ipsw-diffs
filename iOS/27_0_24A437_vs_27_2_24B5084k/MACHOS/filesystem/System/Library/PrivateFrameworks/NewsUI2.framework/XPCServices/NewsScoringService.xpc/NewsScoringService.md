## NewsScoringService

> `/System/Library/PrivateFrameworks/NewsUI2.framework/XPCServices/NewsScoringService.xpc/NewsScoringService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8780` | `0xbc48` | **`+0x34c8`** |
| `__TEXT.__cstring` | `0x524` | `0x6b4` | **`+0x190`** |
| `__TEXT.__auth_stubs` | `0xd50` | `0xeb0` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x16c9` | `0x17e7` | **`+0x11e`** |
| `__DATA.__objc_const` | `0xf08` | `0x1018` | **`+0x110`** |
| `__TEXT.__eh_frame` | `0xd8` | `0x1a8` | **`+0xd0`** |
| `__TEXT.__objc_methtype` | `0xb76` | `0xc31` | **`+0xbb`** |
| `__DATA_CONST.__auth_got` | `0x6b0` | `0x760` | **`+0xb0`** |
| `__DATA.__data` | `0x880` | `0x920` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x2a8` | `0x320` | **`+0x78`** |
| `__TEXT.__objc_methlist` | `0x7d4` | `0x838` | **`+0x64`** |
| `__TEXT.__swift5_typeref` | `0x215` | `0x276` | **`+0x61`** |
| `__DATA_CONST.__const` | `0x619` | `0x669` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x137` | `0x187` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x160` | `0x1a8` | **`+0x48`** |
| `__DATA.__objc_selrefs` | `0x490` | `0x4d0` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x278` | `0x2a8` | **`+0x30`** |
| `__TEXT.__const` | `0x422` | `0x452` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x168` | `0x198` | **`+0x30`** |
| `__DATA.__objc_data` | `0x2a8` | `0x2c8` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x2df` | `0x2ff` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x260` | `0x280` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x98` | `0xa8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `—` | `0xc` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `—` | `0xc` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x118` | `0x120` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `—` | `0x8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-5934.3.0.0.0
+5960.0.0.0.0

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 214
-  Symbols:   140
-  CStrings:  330
+  Functions: 251
+  Symbols:   153
+  CStrings:  353
Symbols:
+ _FCURLForTodayDropbox
+ _OBJC_CLASS_$_FCFileCoordinatedTodayDropbox
+ __swiftEmptySetSingleton
+ _bzero
+ _objc_release_x28
+ _objc_retain_x24
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _swift_beginAccess
+ _swift_endAccess
+ _swift_release_x12
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
- _OBJC_CLASS_$_OS_dispatch_queue
- _swift_release_x28
CStrings:
+ "FCSubscriptionListType"
+ "NewsScoringService For You: formed group (%llums)"
+ "NewsScoringService For You: group formation failed (%llums): %{public}@"
+ "Q24@0:8@\"NSString\"16"
+ "Q24@0:8@16"
+ "T@\"NSSet\",R,C,N"
+ "activeInterestTokens"
+ "attachedClients"
+ "autoFavoriteTagIDs"
+ "client detached, %lu clients remain attached"
+ "clientAssertion"
+ "clientLock"
+ "com.apple.news.ScoringService.clients"
+ "did free up resources and release assertion"
+ "first client attached, will acquire assertion until the last client detaches"
+ "formGroup:environment:completion:"
+ "ignoredTagIDs"
+ "initWithFileURL:"
+ "last client detached, will free up resources and release assertion"
+ "mutedTagIDs"
+ "originForTagID:"
+ "rankedAllSubscribedTagIDs"
+ "resolvedComputeService"
+ "subscribedTagIDs"
+ "v40@0:8@\"NSData\"16@\"_TtC10NewsDaemon27NDScoringServiceEnvironment\"24@?<v@?@\"NSData\"@\"NSError\">32"
- "com.apple.news.ScoringService.cooldown"
- "cooldownQueue"
```
