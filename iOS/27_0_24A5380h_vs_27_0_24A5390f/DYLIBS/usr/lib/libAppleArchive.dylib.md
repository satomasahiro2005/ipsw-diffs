## libAppleArchive.dylib

> `/usr/lib/libAppleArchive.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x832cc` | `0x83430` | **`+0x164`** |
| `__TEXT.__cstring` | `0x13398` | `0x133db` | **`+0x43`** |

### Other Changes

```diff

-467.0.0.0.0
+469.0.0.0.0

-  CStrings:  2902
+  CStrings:  2905
Functions:
~ _rawimg_destroy : 164 -> 172
~ _rawimg_create_with_stream : 1360 -> 1376
~ __Z13pc_array_initmm : 120 -> 188
~ _aeaOutputStreamCloseAndUpdateContext : 1088 -> 1144
~ _BXPatch5InPlace : 2904 -> 3028
~ _workerProc : 8076 -> 8160
CStrings:
+ "array too large"
+ "invalid reference entry: %s"
+ "worker reported errors"
```
