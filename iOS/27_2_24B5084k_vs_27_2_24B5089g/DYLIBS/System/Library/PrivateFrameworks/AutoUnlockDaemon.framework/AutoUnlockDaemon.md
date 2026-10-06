## AutoUnlockDaemon

> `/System/Library/PrivateFrameworks/AutoUnlockDaemon.framework/AutoUnlockDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c2100` | `0x1c21a8` | **`+0xa8`** |
| `__DATA_DIRTY.__data` | `0x1f98` | `0x1fc8` | **`+0x30`** |
| `__TEXT.__cstring` | `0x6feb` | `0x700b` | **`+0x20`** |
| `__AUTH.__data` | `0x6b28` | `0x6b38` | **`+0x10`** |
| `__DATA.__data` | `0x2342` | `0x2332` | **`-0x10`** |
| `__TEXT.__constg_swiftt` | `0x5e38` | `0x5e40` | **`+0x8`** |

### Other Changes

```diff

-2131.20.65.2.1
+2131.20.71.0.0

-  CStrings:  1438
+  CStrings:  1439
Functions:
~ sub_259b52750 -> sub_259dba750 : 40 -> 44
~ sub_259b877e8 -> sub_259def7ec : 828 -> 980
~ sub_259b8919c -> sub_259df1238 : 352 -> 364
CStrings:
+ "unlockAccessoryPurpose"
```
