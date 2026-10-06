## CoreCaptureDaemon

> `/System/Library/PrivateFrameworks/CoreCaptureDaemon.framework/CoreCaptureDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b998` | `0x5bac0` | **`+0x128`** |
| `__TEXT.__cstring` | `0xbb5e` | `0xbbc0` | **`+0x62`** |
| `__TEXT.__oslogstring` | `0xb71b` | `0xb77d` | **`+0x62`** |

### Other Changes

```diff

-1355.42.0.0.0
+1355.44.0.0.0

-  CStrings:  1237
+  CStrings:  1238
Functions:
~ __ZN8CCLogTap11tapLoopImplEv : 3640 -> 3936
CStrings:
+ "CCLogTap::tapLoopImpl() entry:%u failed to map pipe with rc[0x%08x] ringSize[%llu]\n"
+ "CCLogTap::tapLoopImpl() entry:%u failed to unmap zero-length pipe with rc[0x%08x]\n"
- "CCLogTap::tapLoopImpl() entry:%u failed to map pipe with rc[0x%08x]\n"
```
