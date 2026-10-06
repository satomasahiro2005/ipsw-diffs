## Recap

> `/System/Library/PrivateFrameworks/Recap.framework/Recap`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x224f0` | `0x22acc` | **`+0x5dc`** |
| `__TEXT.__objc_methlist` | `0x3530` | `0x3658` | **`+0x128`** |
| `__TEXT.__cstring` | `0x1bff` | `0x1ce7` | **`+0xe8`** |
| `__AUTH_CONST.__objc_const` | `0x5478` | `0x5500` | **`+0x88`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e80` | `0x1ef0` | **`+0x70`** |
| `__TEXT.__gcc_except_tab` | `0xc00` | `0xc24` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0xa00` | `0xa20` | **`+0x20`** |
| `__DATA_DIRTY.__bss` | `0xd0` | `0xc8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x3bc` | `0x3c0` | **`+0x4`** |

### Other Changes

```diff

-200.0.0.0.0
+201.108.0.0.0

-  Functions: 1033
-  Symbols:   2149
-  CStrings:  397
+  Functions: 1048
+  Symbols:   2164
+  CStrings:  401
Symbols:
+ -[RCPPlayerPlaybackOptions displayUUIDOverrideSpecified]
+ -[RCPPlayerPlaybackOptions setDisplayUUIDOverrideSpecified:]
+ -[RCPSyntheticEventStream _flickWithStartPoint:endPoint:duration:pressure:radius:lift:]
+ -[RCPSyntheticEventStream cancel:]
+ -[RCPSyntheticEventStream cancel:touchCount:]
+ -[RCPSyntheticEventStream cancelAtAllActivePoints]
+ -[RCPSyntheticEventStream cancelAtPoints:touchCount:]
+ -[RCPSyntheticEventStream dragAndCancelWithStartPoint:endPoint:duration:]
+ -[RCPSyntheticEventStream dragAndCancelWithStartPoint:endPoint:duration:radius:]
+ -[RCPSyntheticEventStream dragAndCancelWithStartPoint:endPoint:duration:tapAndWait:radius:]
+ -[RCPSyntheticEventStream flickAndCancelWithStartPoint:endPoint:duration:]
+ -[RCPSyntheticEventStream flickAndCancelWithStartPoint:endPoint:duration:radius:]
+ -[RCPSyntheticEventStream tapAndCancel:]
+ -[RCPSyntheticEventStream tapAndCancel:radius:]
+ _OBJC_IVAR_$_RCPPlayerPlaybackOptions._displayUUIDOverrideSpecified
+ _isTouchCancelArgument
- _supplyMissingStandardProperties:senderID:.deviceCount
CStrings:
+ "01:01:54"
+ "Canceling a %s isn't supported. Use the \"%s\" command with a trailing \"%s\" to cancel a multi-finger sequence.\n"
+ "Canceling a %s isn't supported. Use the \"%s\" command with a trailing \"%s\" to cancel an arbitrary touch sequence.\n"
+ "Sep  4 2026"
+ "cancel"
+ "pinch"
+ "stretch"
- "16:48:49"
- "Aug  8 2026"
- "recap-bus-%d"
```
