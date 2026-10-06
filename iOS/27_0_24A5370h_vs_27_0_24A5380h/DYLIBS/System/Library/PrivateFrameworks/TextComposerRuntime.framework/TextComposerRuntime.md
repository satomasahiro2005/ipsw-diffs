## TextComposerRuntime

> `/System/Library/PrivateFrameworks/TextComposerRuntime.framework/TextComposerRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6fc94` | `0x726ec` | **`+0x2a58`** |
| `__DATA.__bss` | `0x4500` | `0x3f80` | **`-0x580`** |
| `__DATA_DIRTY.__bss` | `0x480` | `0xa00` | **`+0x580`** |
| `__DATA_DIRTY.__data` | `0x540` | `0xa18` | **`+0x4d8`** |
| `__AUTH.__data` | `0x8b0` | `0x5f0` | **`-0x2c0`** |
| `__AUTH_CONST.__const` | `0x39a0` | `0x3c20` | **`+0x280`** |
| `__DATA.__data` | `0xc80` | `0xa78` | **`-0x208`** |
| `__TEXT.__oslogstring` | `0x2593` | `0x26b3` | **`+0x120`** |
| `__TEXT.__swift5_capture` | `0xd04` | `0xdf4` | **`+0xf0`** |
| `__TEXT.__cstring` | `0x123f7` | `0x12397` | **`-0x60`** |
| `__AUTH.__objc_data` | `0x180` | `0x130` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x120` | `0x170` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x17b5` | `0x17fd` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0x17a0` | `0x17d8` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1e00` | `0x1e38` | **`+0x38`** |
| `__DATA.__common` | `0x78` | `0x48` | **`-0x30`** |
| `__DATA_DIRTY.__common` | `0x28` | `0x58` | **`+0x30`** |
| `__TEXT.__const` | `0x3b24` | `0x3b44` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x5440` | `0x5460` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x398` | `0x3a0` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x444` | `0x43c` | **`-0x8`** |

### Other Changes

```diff

-211.13.0.0.0
+211.18.0.0.0

+  - /System/Library/PrivateFrameworks/CoreEmoji.framework/CoreEmoji

-  Functions: 2873
-  Symbols:   210
-  CStrings:  293
+  Functions: 2933
+  Symbols:   214
+  CStrings:  294
Symbols:
+ _CEMEnumerateEmojiTokensInStringWithBlock
+ _CEMStringContainsEmoji
+ _swift_retain
+ _swift_retain_x2
CStrings:
+ "Falling back to legacy flow due to non-English preferred language: %s"
+ "[RewriteProcessor] Stripped extra emoji from rewrite output (%{public}ld → %{public}ld chars)"
+ "[RewriteSessionManager] Failed to mark follow-ups as seen at index %ld since no follow-ups were generated"
- " since no follow-ups were generated"
- "Failed to mark follow-ups as seen at index "
```
