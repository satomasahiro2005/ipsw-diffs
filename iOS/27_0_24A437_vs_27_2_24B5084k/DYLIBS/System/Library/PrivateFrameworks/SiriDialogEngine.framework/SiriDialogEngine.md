## SiriDialogEngine

> `/System/Library/PrivateFrameworks/SiriDialogEngine.framework/SiriDialogEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e5f0` | `0x6ec4c` | **`+0x65c`** |
| `__TEXT.__eh_frame` | `0x3070` | `0x3138` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x272c` | `0x278c` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x1082` | `0x10a4` | **`+0x22`** |
| `__TEXT.__const` | `0x5f88` | `0x5fa8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2860` | `0x2880` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xd84` | `0xd9c` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xd88` | `0xd98` | **`+0x10`** |
| `__DATA.__data` | `0xb70` | `0xb78` | **`+0x8`** |

### Other Changes

```diff

-3520.12.1.0.0
+3605.4.1.0.0

-  Functions: 5440
-  Symbols:   1110
-  CStrings:  313
+  Functions: 5448
+  Symbols:   1114
+  CStrings:  314
Symbols:
+ _objc_retain_x27
+ _symbolic So8NSObjectCSg
+ _symbolic _____Sg 13SiriUtilities0A11EnvironmentC
+ _symbolic _____XMT 16SiriDialogEngine11CATExecutorC
CStrings:
+ "No SiriEnvironment on the calling task for catID: \"%{public}s\"; running the completion unbound"
```
