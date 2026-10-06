## libxml2.2.dylib

> `/usr/lib/libxml2.2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc6844` | `0xc6a04` | **`+0x1c0`** |
| `__AUTH_CONST.__auth_got` | `0x3b0` | `0x3b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1ba0` | `0x1ba8` | **`+0x8`** |

### Other Changes

```diff

-39.10.3.0.0
+40.1.0.0.0

-  Functions: 2629
-  Symbols:   3099
+  Functions: 2632
+  Symbols:   3103
Symbols:
+ _strstr
+ _xmlEncodingErr
+ _xmlGrowArray_type
+ _xmlParseLookupString
Functions:
~ _xmlOutputBufferWrite : 564 -> 588
~ _xmlOutputBufferFlush : 344 -> 380
~ _xmlParseTryOrFinish : 5116 -> 5036
+ _xmlEncodingErr
~ _xmlCharEncInFunc : 440 -> 456
~ _xmlCharEncOutFunc : 864 -> 876
+ _xmlParseLookupString
~ _xmlRelaxNGNewDefine : 252 -> 260
~ _xmlRelaxNGAddValidError : 540 -> 544
~ _xmlRelaxNGElemPush : 200 -> 208
~ _xmlRelaxNGFreeStates : 256 -> 260
~ _xmlRelaxNGCleanupTree : 4892 -> 4900
~ _xmlRelaxNGGetElements : 412 -> 440
~ _xmlRelaxNGAddStates : 416 -> 424
+ _xmlGrowArray_type
```
