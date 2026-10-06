## CloudKit

> `/System/Library/Frameworks/CloudKit.framework/CloudKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__const` | `0x12520` | `0x11f08` | **`-0x618`** |
| `__TEXT.__cstring` | `0x20b69` | `0x21086` | **`+0x51d`** |
| `__TEXT.__swift5_capture` | `0x3d80` | `0x3b14` | **`-0x26c`** |
| `__AUTH.__objc_data` | `0x6790` | `0x66a0` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x4710` | `0x4800` | **`+0xf0`** |
| `__TEXT.__const` | `0xe490` | `0xe3b0` | **`-0xe0`** |
| `__AUTH_CONST.__objc_const` | `0x39a80` | `0x39b30` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x10654` | `0x105cc` | **`-0x88`** |
| `__AUTH_CONST.__cfstring` | `0x1de80` | `0x1df00` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x21864` | `0x218dc` | **`+0x78`** |
| `__TEXT.__text` | `0x366fa0` | `0x367004` | **`+0x64`** |
| `__TEXT.__unwind_info` | `0x11110` | `0x11158` | **`+0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0xbf68` | `0xbf98` | **`+0x30`** |
| `__DATA.__bss` | `0xe948` | `0xe968` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xabb0` | `0xabc4` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x4d0` | `0x4e0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x6bce` | `0x6bc2` | **`-0xc`** |
| `__AUTH.__data` | `0x1900` | `0x1908` | **`+0x8`** |
| `__AUTH_CONST.__auth_got` | `0x2548` | `0x2540` | **`-0x8`** |
| `__DATA.__data` | `0x6380` | `0x6378` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1974` | `0x197c` | **`+0x8`** |
| `__DATA_DIRTY.__bss` | `0xb90` | `0xb98` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0xb28` | `0xb30` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x16f51` | `0x16f52` | **`+0x1`** |

### Other Changes

```diff

-2710.114.0.0.0
+2710.116.0.0.0

-  Functions: 24303
-  Symbols:   6516
-  CStrings:  6219
+  Functions: 24283
+  Symbols:   6515
+  CStrings:  6248
Symbols:
- _$sSy10FoundationE8containsySbqd__SyRd__lF
CStrings:
+ "AssetStreamHandleInternal.inputStream Generator"
+ "BackgroundTaskPriority"
+ "CKAsyncSerialQueue Task Cancellation"
+ "CKContainer Accept Shares"
+ "CKContainer Decline Shares"
+ "CKContainer Discover User Identities for Emails"
+ "CKContainer Discover User Identities for Phone Numbers"
+ "CKContainer Discover User Identities for Record IDs"
+ "CKContainer Fetch Share Metadatas for URLs"
+ "CKContainer Fetch Share Participants for Emails"
+ "CKContainer Fetch Share Participants for Phone Numbers"
+ "CKContainer Fetch Share Participants for Record IDs"
+ "CKContainer Leave Shares"
+ "CKDatabase Fetch Database Changes"
+ "CKDatabase Fetch Record Zone Changes"
+ "CKDatabase Fetch Record Zones for IDs"
+ "CKDatabase Fetch Records for Cursor"
+ "CKDatabase Fetch Records for IDs"
+ "CKDatabase Fetch Records for Query"
+ "CKDatabase Fetch Subscriptions for IDs"
+ "CKDatabase Modify Record Zones"
+ "CKDatabase Modify Records"
+ "CKDatabase Modify Subscriptions"
+ "CKPreSharingContext Load Handler"
+ "CKScheduler Activity Handler: "
+ "ChunkReader Downloading Range "
+ "CloudCoreContainerImplementation Session Invalidation Notification Handler"
+ "Setting duetPreClearedMode CKOperationDuetPreClearedModeWithBudgeting for operation <%{public}@: %p; %{public}@> for background task %@"
+ "Someone's invoking `CKModifySubscriptionsOperation.modifySubscriptionsResultBlock` directly.  We'll invoke the underlying completion block as asked, but without any `savedSubscriptions` or `deletedSubscriptionIDs` values"
+ "ckdiscretionaryd_priority"
+ "lastPushReceivedDate"
+ "savePCSOnlyForZones"
- "&b"
- "Setting duetPreClearedMode KOperationDuetPreClearedModeWithBudgeting for operation <%{public}@: %p; %{public}@> for background task %@"
- "Someone's invoking `CKModifySubscriptionOperation.modifySubscriptionsResultBlock` directly.  We'll invoke the underlying completion block as asked, but without any `savedSubscriptions` or `deletedSubscriptionIDs` values"
```
