## libncurses.5.4.dylib

> `/usr/lib/libncurses.5.4.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30710` | `0x30794` | **`+0x84`** |
| `__TEXT.__cstring` | `0x3c60` | `0x3c8e` | **`+0x2e`** |
| `__AUTH_CONST.__auth_got` | `0x2e8` | `0x2f0` | **`+0x8`** |

### Other Changes

```diff

-81.0.0.0.0
+85.0.0.0.0

-  Functions: 1014
-  Symbols:   1042
-  CStrings:  1681
+  Functions: 1015
+  Symbols:   1044
+  CStrings:  1682
Symbols:
+ __nc_env_access
+ _fopen$DARWIN_EXTSN
+ _issetugid
+ _select$DARWIN_EXTSN
- _fopen
- _select
Functions:
+ __nc_env_access
~ __nc_tic_dir : 124 -> 144
~ __nc_first_db : 968 -> 1000
~ __nc_home_terminfo : 124 -> 140
~ __nc_read_termcap_entry : 844 -> 864
~ __nc_set_writedir : 240 -> 252
CStrings:
+ "/usr/share/terminfo:/usr/local/share/terminfo"
```
