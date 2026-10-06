## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Sharing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x7af8` | `0x3f10` | **`-0x3be8`** |
| `__DATA_DIRTY.__objc_data` | `0x1080` | `0x4c68` | **`+0x3be8`** |
| `__DATA_DIRTY.__data` | `0x2f0` | `0x1940` | **`+0x1650`** |
| `__AUTH.__data` | `0x5188` | `0x3c88` | **`-0x1500`** |
| `__TEXT.__text` | `0x3a8d4c` | `0x3a9488` | **`+0x73c`** |
| `__AUTH_CONST.__objc_const` | `0x3ca20` | `0x3cdf0` | **`+0x3d0`** |
| `__TEXT.__oslogstring` | `0xc553` | `0xc703` | **`+0x1b0`** |
| `__DATA.__data` | `0xd590` | `0xd4b8` | **`-0xd8`** |
| `__TEXT.__objc_methlist` | `0x15294` | `0x152fc` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x9bb0` | `0x9c08` | **`+0x58`** |
| `__TEXT.__const` | `0x264f4` | `0x26544` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x137a0` | `0x137e0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xf520` | `0xf538` | **`+0x18`** |
| `__TEXT.__cstring` | `0x3ba05` | `0x3ba15` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x25b4` | `0x25bc` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x35f0` | `0x35f8` | **`+0x8`** |

### Other Changes

```diff

-2131.20.65.2.1
+2131.20.71.0.0

-  Functions: 25380
-  Symbols:   20632
-  CStrings:  9033
+  Functions: 25391
+  Symbols:   20645
+  CStrings:  9041
Symbols:
+ -[SFAutoUnlockNotificationModel authToken]
+ -[SFAutoUnlockNotificationModel setAuthToken:]
+ -[SFCollaborationPerformer _failIfMetadataLoadFailed]
+ -[SFCollaborationPerformer _isOptionsLoadInFlightForItem:]
+ -[SFCollaborationPerformer _performAfterOptionsCheck]
+ -[SFCollaborationPerformer _stopWaitingForOptionsLoad]
+ -[SFCollaborationPerformer isWaitingForOptionsLoad]
+ -[SFCollaborationPerformer observable:didChange:]
+ -[SFCollaborationPerformer setIsWaitingForOptionsLoad:]
+ GCC_except_table65
+ _OBJC_IVAR_$_SFAutoUnlockNotificationModel._authToken
+ _OBJC_IVAR_$_SFCollaborationPerformer._isWaitingForOptionsLoad
+ __OBJC_CLASS_PROTOCOLS_$_SFCollaborationPerformer
+ ___53-[SFCollaborationPerformer _performAfterOptionsCheck]_block_invoke
+ ___53-[SFCollaborationPerformer _performAfterOptionsCheck]_block_invoke_2
+ ___54-[SFCollaborationPerformer _stopWaitingForOptionsLoad]_block_invoke
- GCC_except_table40
- ___63-[SFCollaborationPerformer _performWithAddParticipantsAllowed:]_block_invoke
- ___63-[SFCollaborationPerformer _performWithAddParticipantsAllowed:]_block_invoke_2
CStrings:
+ "%@: cannot set allowsAccessRequests:%s, share options have not loaded"
+ "%@: cannot set isPublicCollaboration:%s, share options have not loaded"
+ "Collaboration Performer for item %@ resuming after options loaded"
+ "Collaboration Performer for item %@ resuming without options after loading finished"
+ "Collaboration Performer for item %@ waiting for options to load before performing"
+ "Mac17,5"
+ "MacBookNeo"
+ "canShowShareOptions:no, the share options are read-only"
```
