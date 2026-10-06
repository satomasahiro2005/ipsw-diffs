## skywalkctl

> `/usr/sbin/skywalkctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xc2fc` | `0xc33d` | **`+0x41`** |
| `__DATA_CONST.__const` | `0x4388` | `0x4398` | **`+0x10`** |
| `__TEXT.__text` | `0x1196c` | `0x11968` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  2092
+  CStrings:  2094
Functions:
~ sub_100004748 : 928 -> 924
CStrings:
+ "\t\t%llu dropped, flow not owned by Tx nexus port\n"
+ "TxFlowWrongPort"
```
