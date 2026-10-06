## GameKitServices

> `/System/Library/PrivateFrameworks/GameKitServices.framework/GameKitServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76e28` | `0x77100` | **`+0x2d8`** |
| `__TEXT.__oslogstring` | `0x11809` | `0x118e9` | **`+0xe0`** |
| `__DATA_CONST.__objc_arraydata` | `0xb8` | `0xf8` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x328` | `0x358` | **`+0x30`** |
| `__TEXT.__cstring` | `0x6a55` | `0x6a7d` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x60` | `0x78` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xfb8` | `0xfc8` | **`+0x10`** |

### Other Changes

```diff

-2235.52.1.11.1
+2235.55.1.0.0

-  Functions: 1606
+  Functions: 1614

-  CStrings:  1885
+  CStrings:  1890
CStrings:
+ " [%s] %s:%d Failed to allocate NSUnarchiver"
+ " [%s] %s:%d Failed to super init instance"
+ " [%s] %s:%d GKVoiceChatDictionary decoded root is not a GKVoiceChatDictionary"
+ " [%s] %s:%d GKVoiceChatDictionary failed validateDictionary"
+ "-[GKVoiceChatDictionary initWithCoder:]"
+ "22:34:08"
+ "Jun 27 2026"
- "22:09:21"
- "Jun 18 2026"
```
