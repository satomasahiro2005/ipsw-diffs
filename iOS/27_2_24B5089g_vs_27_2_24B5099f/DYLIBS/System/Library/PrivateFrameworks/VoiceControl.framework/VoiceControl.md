## VoiceControl

> `/System/Library/PrivateFrameworks/VoiceControl.framework/VoiceControl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f924` | `0x3fe8c` | **`+0x568`** |
| `__TEXT.__oslogstring` | `0xa8d` | `0xb0d` | **`+0x80`** |
| `__TEXT.__cstring` | `0x1b7a` | `0x1b9a` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x738` | `0x748` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x6b8` | `0x6ac` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0xb78` | `0xb80` | **`+0x8`** |
| `__DATA.__data` | `0x668` | `0x670` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xa24` | `0xa2c` | **`+0x8`** |

### Other Changes

```diff

-41.1.1.0.0
+41.1.3.0.0

+  - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit

-  Functions: 1262
-  Symbols:   507
-  CStrings:  264
+  Functions: 1265
+  Symbols:   508
+  CStrings:  267
Symbols:
+ _IOPMAssertionDeclareUserActivity
CStrings:
+ "Declared user activity from %{public}s, assertion %{public}u"
+ "Failed to declare user activity from %{public}s: %{public}d"
+ "Voice Control Command Matched"
```
