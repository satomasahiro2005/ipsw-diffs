## com.apple.iokit.IOGameControllerFamily

> `com.apple.iokit.IOGameControllerFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1abac` | `0x1ada8` | **`+0x1fc`** |
| `__TEXT.__os_log` | `0x1c4a` | `0x1c18` | **`-0x32`** |
| `__TEXT.__cstring` | `0x101c` | `0x104c` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xd8` | `0xe0` | **`+0x8`** |

### Other Changes

```diff

-14.0.17.0.0
-  Functions: 672
+14.0.19.0.0
+  Functions: 673

-  CStrings:  298
+  CStrings:  299
CStrings:
+ "GameControllerCategory"
+ "GameControllerEligible"
+ "GameControllerSupport"
- "GameControllerClass"
- "[%#010llx] <IOHIDDevice %#010llx> already probed."
```
