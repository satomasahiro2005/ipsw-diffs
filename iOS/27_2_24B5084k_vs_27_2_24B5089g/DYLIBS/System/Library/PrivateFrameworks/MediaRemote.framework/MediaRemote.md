## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x8700` | `0x5f00` | **`-0x2800`** |
| `__DATA_DIRTY.__objc_data` | `0x2da0` | `0x55a0` | **`+0x2800`** |
| `__TEXT.__oslogstring` | `0xeb44` | `0xebb9` | **`+0x75`** |
| `__TEXT.__text` | `0x317c84` | `0x317ca8` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x3440` | `0x3460` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xf9a0` | `0xf9b0` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2de64` | `0x2de57` | **`-0xd`** |
| `__TEXT.__objc_methlist` | `0x2c888` | `0x2c890` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xbe20` | `0xbe28` | **`+0x8`** |

### Other Changes

```diff

-4026.200.11.0.0
+4026.200.15.0.0

-  Functions: 21037
-  Symbols:   30276
-  CStrings:  6775
+  Functions: 21040
+  Symbols:   30278
+  CStrings:  6776
Symbols:
+ -[MRMediaRemoteService requestPushToStartTokenWithCompletion:]
+ -[MRNowPlayingPushTokenManager requestStartToken]
+ -[MRUserSettings remoteSessionStalenessGraceInterval]
+ ___49-[MRNowPlayingPushTokenManager requestStartToken]_block_invoke
+ ___53-[MRUserSettings remoteSessionStalenessGraceInterval]_block_invoke
+ ___62-[MRMediaRemoteService requestPushToStartTokenWithCompletion:]_block_invoke
+ _remoteSessionStalenessGraceInterval.__interval
+ _remoteSessionStalenessGraceInterval.__once
- -[MRMediaRemoteService remoteSessionAssertionsWithCompletion:]
- -[MRUserSettings remoteSessionDefaultAssertionInterval]
- ___55-[MRUserSettings remoteSessionDefaultAssertionInterval]_block_invoke
- ___62-[MRMediaRemoteService remoteSessionAssertionsWithCompletion:]_block_invoke
- _remoteSessionDefaultAssertionInterval.__interval
- _remoteSessionDefaultAssertionInterval.__once
CStrings:
+ "[MRNowPlayingPushTokenManager] requestStartToken"
+ "[MRNowPlayingPushTokenManager] requestStartToken failed: %{public}@"
+ "remoteSessionStalenessGraceInterval"
- "assertions"
- "remoteSessionDefaultAssertionInterval"
```
