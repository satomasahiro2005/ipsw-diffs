## IntentRecommend

> `/System/Library/PrivateFrameworks/IntentRecommend.framework/IntentRecommend`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5c10` | `0x6ff4` | **`+0x13e4`** |
| `__TEXT.__eh_frame` | `0x4b0` | `0x618` | **`+0x168`** |
| `__AUTH_CONST.__const` | `0x350` | `0x418` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x1b9` | `0x259` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x268` | `0x2d8` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0x3b0` | `0x400` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x43` | `0x83` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0x90` | `0xc0` | **`+0x30`** |
| `__DATA.__data` | `0xf8` | `0xd8` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x60` | `0x80` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x68` | `0x80` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x210` | `0x220` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x50` | `0x60` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x34` | `0x44` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x34` | `0x44` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x252` | `0x25c` | **`+0xa`** |

### Other Changes

```diff

-92.0.0.0.0
+95.0.0.0.0

-  - /System/Library/Frameworks/Intents.framework/Intents

-  - /System/Library/PrivateFrameworks/LinkMetadata.framework/LinkMetadata

-  Functions: 236
-  Symbols:   110
-  CStrings:  17
+  Functions: 277
+  Symbols:   111
+  CStrings:  22
Symbols:
+ _NSClassFromString
+ _objc_release_x28
+ _swift_arrayDestroy
+ _swift_arrayInitWithCopy
+ _swift_beginAccess
+ _swift_release_n
+ _swift_retain_n
- _OBJC_CLASS_$_INImage
- _OBJC_CLASS_$_INPlayMediaIntent
- _OBJC_CLASS_$_LNAction
- _OBJC_CLASS_$_MSIntentWrapper
- _OBJC_CLASS_$_MSUnifiedMediaIntent
- _OBJC_CLASS_$_NSData
CStrings:
+ "%s Unable to resolve secure coding classes: %{public}s"
+ "(Daemon) Current Artwork Reference Fetch"
+ "begin for identifier: %{public}s"
+ "end for identifier: %{public}s"
+ "supportedSecureCodingClasses()"
```
