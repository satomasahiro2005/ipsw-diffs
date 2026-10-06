## Feedback

> `/System/Library/PrivateFrameworks/Feedback.framework/Feedback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x108210` | `0x1091c4` | **`+0xfb4`** |
| `__TEXT.__cstring` | `0x42c6` | `0x43c6` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0x3ada` | `0x3baa` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x6c90` | `0x6d08` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x1ac8` | `0x1b20` | **`+0x58`** |
| `__TEXT.__swift5_capture` | `0x1340` | `0x1360` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xef0` | `0xef8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa48` | `0xa50` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xb352` | `0xb356` | **`+0x4`** |

### Other Changes

```diff

-227.0.0.0.0
+229.0.0.0.0

-  Functions: 5158
-  Symbols:   2006
-  CStrings:  652
+  Functions: 5168
+  Symbols:   2009
+  CStrings:  659
Symbols:
+ _dispatch_sync
+ _swift_isEscapingClosureAtFileLocation
+ _symbolic Ig_
CStrings:
+ "%d evaluations left"
+ "1 evaluation left"
+ "loadView called with contentViewController already set, returning early"
+ "observer did update"
+ "shouldAccept(_:) ran after loadView"
+ "shouldAccept(_:) ran ahead of loadView. forced loadViewIfNeeded() before assigning exportedObject"
+ "the count of a single evaluation the user has completed"
+ "the count of a single evaluation until they reach the next level"
+ "the user has no evaluations to rate and they should check back later; the interpolated value is the device name e.g. iPhone"
- "contentViewController is nil in ExtensionController"
- "the user has no evaluations to rate and they should check back later"
```
