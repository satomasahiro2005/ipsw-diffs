## libParallelCompression.dylib

> `/usr/lib/libParallelCompression.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55dbc` | `0x55e94` | **`+0xd8`** |
| `__TEXT.__cstring` | `0xf571` | `0xf581` | **`+0x10`** |

### Other Changes

```diff

-467.0.0.0.0
+469.0.0.0.0

-  CStrings:  2261
+  CStrings:  2262
Functions:
~ _BXPatch5InPlace : 2904 -> 3028
~ __Z13pc_array_initmm : 120 -> 188
~ _rawimg_destroy : 164 -> 172
~ _rawimg_create_with_stream : 1360 -> 1376
CStrings:
+ "array too large"
```
