## com.apple.iokit.IOReportFamily

> `com.apple.iokit.IOReportFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__kalloc_var` | `—` | `0xa0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x216` | `0x238` | **`+0x22`** |
| `__TEXT_EXEC.__auth_stubs` | `0x1f0` | `0x210` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xf8` | `0x108` | **`+0x10`** |
| `__TEXT_EXEC.__text` | `0x2f98` | `0x2f8c` | **`-0xc`** |

### Other Changes

```diff

-111.0.0.0.0
+113.0.0.0.0

-  CStrings:  42
+  CStrings:  44
Functions:
~ __ZN18IOReportUserClient4stopEP9IOService : 264 -> 280
~ __ZL18_disableReportCallPvS_ : 192 -> 164
CStrings:
+ "111"
+ "site.DisableThreadCallContext"
```
