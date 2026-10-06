## Trial

> `/System/Library/PrivateFrameworks/Trial.framework/Trial`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6712c` | `0x67150` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x2d30` | `0x2d40` | **`+0x10`** |
| `__TEXT.__const` | `0xe1a` | `0xe22` | **`+0x8`** |
| `__TEXT.__cstring` | `0x8130` | `0x8134` | **`+0x4`** |

### Other Changes

```diff

-511.0.0.0.0
+511.1.2.0.0
Functions:
~ +[TRICCommandRunner runCommandAsync:withArgs:taskOutputOut:error:] : 460 -> 496
CStrings:
+ "TrialXP_ClientFramework-511.1.2"
- "TrialXP_ClientFramework-511"
```
