## Recap

> `/System/Library/PrivateFrameworks/Recap.framework/Recap`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22174` | `0x224f0` | **`+0x37c`** |
| `__AUTH_CONST.__objc_const` | `0x5438` | `0x5478` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x34f8` | `0x3530` | **`+0x38`** |
| `__AUTH_CONST.__objc_intobj` | `0x3c0` | `0x3f0` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x470` | `0x4a0` | **`+0x30`** |
| `__AUTH_CONST.__objc_dictobj` | `0x230` | `0x258` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e58` | `0x1e80` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x2080` | `0x20a0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x3c0` | `0x3e0` | **`+0x20`** |
| `__DATA.__bss` | `0x148` | `0x158` | **`+0x10`** |
| `__TEXT.__cstring` | `0x1bf1` | `0x1bff` | **`+0xe`** |
| `__TEXT.__unwind_info` | `0x9f8` | `0xa00` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3b8` | `0x3bc` | **`+0x4`** |

### Other Changes

```diff

-198.0.0.0.0
+200.0.0.0.0

-  Functions: 1026
-  Symbols:   2140
-  CStrings:  396
+  Functions: 1033
+  Symbols:   2149
+  CStrings:  397
Symbols:
+ +[RCPEventSenderProperties genericPencilGestureSender]
+ -[RCPEventStream recordedDisplayUUIDs]
+ -[RCPPlayer _senderPropertiesApplyingDisplayUUIDOverride:]
+ -[RCPPlayerPlaybackOptions displayUUIDOverride]
+ -[RCPPlayerPlaybackOptions setDisplayUUIDOverride:]
+ _OBJC_IVAR_$_RCPPlayerPlaybackOptions._displayUUIDOverride
+ ___54+[RCPEventSenderProperties genericPencilGestureSender]_block_invoke
+ _genericPencilGestureSender.onceToken
+ _genericPencilGestureSender.sender
CStrings:
+ "09:36:05"
+ "Aug  4 2026"
+ "B"
+ "pencilGesture"
- "03:28:05"
- "A"
- "Jul  8 2026"
```
