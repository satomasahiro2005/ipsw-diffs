## GenerationalStorage

> `/System/Library/PrivateFrameworks/GenerationalStorage.framework/GenerationalStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16e0c` | `0x16d34` | **`-0xd8`** |
| `__AUTH_CONST.__cfstring` | `0x1160` | `0x1140` | **`-0x20`** |
| `__TEXT.__cstring` | `0x12ba` | `0x129d` | **`-0x1d`** |
| `__AUTH_CONST.__auth_got` | `0x4b0` | `0x498` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x928` | `0x930` | **`+0x8`** |
| `__TEXT.__const` | `0x148` | `0x140` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x658` | `0x660` | **`+0x8`** |

### Other Changes

```diff

-405.0.0.0.1
+411.0.0.0.0

-  Functions: 459
-  Symbols:   882
-  CStrings:  236
+  Functions: 460
+  Symbols:   880
+  CStrings:  234
Symbols:
+ -[_CopyfileCallbackCtx doArchiveWithOwnerUID]
+ -[_CopyfileCallbackCtx setDoArchiveWithOwnerUID:]
+ _GSCloneTree
+ _OBJC_IVAR_$__CopyfileCallbackCtx._doArchiveWithOwnerUID
- -[_CopyfileCallbackCtx doArchive]
- -[_CopyfileCallbackCtx setDoArchive:]
- _OBJC_IVAR_$__CopyfileCallbackCtx._doArchive
- _objc_release_x3
- _snprintf
- _unlink
CStrings:
+ "\"%s\" is not owned by the caller"
- "%s_XXXXXX"
- "stat(%s) failed"
- "temporary path \"%s_XXXXXX\" too long"
```
