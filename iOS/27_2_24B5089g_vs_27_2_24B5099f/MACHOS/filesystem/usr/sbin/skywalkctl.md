## skywalkctl

> `/usr/sbin/skywalkctl`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xc33d` | `0xc390` | **`+0x53`** |
| `__DATA_CONST.__const` | `0x4398` | `0x43a8` | **`+0x10`** |
| `__TEXT.__text` | `0x11968` | `0x11964` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  2094
+  CStrings:  2096
Functions:
~ sub_100004ae4 : 2876 -> 2872
CStrings:
+ "\t%llu dropped due to wrap flag not matching ring direction\n"
+ "FilterDropBadDirection"
```
