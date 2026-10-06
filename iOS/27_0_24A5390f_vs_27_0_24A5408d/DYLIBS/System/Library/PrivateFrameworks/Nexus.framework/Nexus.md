## Nexus

> `/System/Library/PrivateFrameworks/Nexus.framework/Nexus`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x3604` | `0x357c` | **`-0x88`** |
| `__TEXT.__text` | `0x12d624` | `0x12d5b8` | **`-0x6c`** |
| `__TEXT.__const` | `0xd120` | `0xd0c0` | **`-0x60`** |
| `__DATA.__bss` | `0x14de8` | `0x14dc8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x41f0` | `0x4208` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1558` | `0x1560` | **`+0x8`** |

### Other Changes

```diff

-900.55.0.0.0
+900.58.0.0.0

-  CStrings:  829
+  CStrings:  828
Symbols:
+ ___swift_closure_destructor.221Tm
+ ___swift_closure_destructor.311Tm
+ ___swift_closure_destructor.332Tm
- ___swift_closure_destructor.223Tm
- ___swift_closure_destructor.313Tm
- ___swift_closure_destructor.334Tm
CStrings:
- "MockA2DPActivity"
```
