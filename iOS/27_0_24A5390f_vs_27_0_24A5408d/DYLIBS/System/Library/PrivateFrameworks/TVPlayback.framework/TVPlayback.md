## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/TVPlayback`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x6c60` | `0x6c80` | **`+0x20`** |
| `__TEXT.__cstring` | `0x6b00` | `0x6b1f` | **`+0x1f`** |
| `__DATA_CONST.__const` | `0x24d8` | `0x24e0` | **`+0x8`** |
| `__TEXT.__text` | `0x68e44` | `0x68e3c` | **`-0x8`** |

### Other Changes

```diff

-635.0.4.0.0
+635.0.7.0.0

-  Symbols:   4203
-  CStrings:  1448
+  Symbols:   4204
+  CStrings:  1449
Symbols:
+ _TVPPlaybackNeedsMachineAuthKey
Functions:
~ -[TVPPlayer playbackErrorFromError:forMediaItem:] : 1984 -> 1976
CStrings:
+ "TVPPlaybackNeedsMachineAuthKey"
```
