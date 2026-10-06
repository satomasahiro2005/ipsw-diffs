## ViceroyTrace

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/ViceroyTrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x50` | `0x490` | **`+0x440`** |
| `__DATA.__data` | `0x750` | `0x340` | **`-0x410`** |
| `__TEXT.__text` | `0xba098` | `0xba36c` | **`+0x2d4`** |
| `__AUTH_CONST.__objc_const` | `0x17870` | `0x17960` | **`+0xf0`** |
| `__AUTH_CONST.__cfstring` | `0xefa0` | `0xf020` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x93f0` | `0x9438` | **`+0x48`** |
| `__AUTH.__data` | `0x30` | `—` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x4750` | `0x4770` | **`+0x20`** |
| `__DATA.__bss` | `0x78` | `0x60` | **`-0x18`** |
| `__DATA.__objc_ivar` | `0x21e4` | `0x21fc` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0xa8` | `0xc0` | **`+0x18`** |
| `__TEXT.__cstring` | `0xf612` | `0xf626` | **`+0x14`** |

### Other Changes

```diff

-2260.11.1.0.0
+2260.14.1.0.0

-  Functions: 4263
-  Symbols:   6744
-  CStrings:  3373
+  Functions: 4269
+  Symbols:   6756
+  CStrings:  3377
Symbols:
+ -[CallSegment localCallID]
+ -[CallSegment remoteCallID]
+ -[CallSegment remoteDeviceType]
+ -[CallSegment setLocalCallID:]
+ -[CallSegment setRemoteCallID:]
+ -[CallSegment setRemoteDeviceType:]
+ GCC_except_table468
+ _OBJC_IVAR_$_CallSegment._localCallID
+ _OBJC_IVAR_$_CallSegment._remoteCallID
+ _OBJC_IVAR_$_CallSegment._remoteDeviceType
+ _OBJC_IVAR_$_VCAggregatorFaceTime._localCallID
+ _OBJC_IVAR_$_VCAggregatorFaceTime._remoteCallID
+ _OBJC_IVAR_$_VCAggregatorFaceTime._remoteDeviceType
- GCC_except_table462
CStrings:
+ "LCID"
+ "RCID"
+ "lcid"
+ "rcid"
```
