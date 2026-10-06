## IMFoundation

> `/System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49f20` | `0x49ed4` | **`-0x4c`** |
| `__TEXT.__unwind_info` | `0x18f8` | `0x18f0` | **`-0x8`** |
| `__TEXT.__oslogstring` | `0x3cd5` | `0x3cd3` | **`-0x2`** |

### Other Changes

```diff

-1132.100.1.0.0
+1134.100.1.0.0
Functions:
~ sub_19fdf2194 -> sub_19fcd7194 : 1100 -> 1096
~ _JWCreateXPCObjectFromInvocation : 2088 -> 2084
~ _JWCreateInvocationFromXPCObject : 3628 -> 3660
~ sub_19fdf4f70 -> sub_19fcd9f88 : 452 -> 448
~ sub_19fdf5134 -> sub_19fcda148 : 476 -> 472
~ sub_19fdf6d20 -> sub_19fcdbd30 : 1900 -> 1880
~ sub_19fdf9b00 -> sub_19fcdeafc : 248 -> 252
~ sub_19fdfb518 -> sub_19fce0518 : 528 -> 520
~ sub_19fdfb768 -> sub_19fce0760 : 316 -> 312
~ sub_19fdfcea4 -> sub_19fce1e98 : 384 -> 380
~ _IMLoggingStringForArray : 392 -> 388
~ _IMCreateSimpleComponentString : 272 -> 268
~ sub_19fdff920 -> sub_19fce4908 : 260 -> 256
~ sub_19fe04e3c -> sub_19fce9e20 : 204 -> 200
~ sub_19fe054b0 -> sub_19fcea490 : 224 -> 232
~ _IMCreateSuperFormatStringWithAppendedFileTransfers : 420 -> 416
~ sub_19fe06744 -> sub_19fceb728 : 548 -> 544
~ sub_19fe06968 -> sub_19fceb948 : 468 -> 464
~ sub_19fe06df0 -> sub_19fcebdcc : 764 -> 756
~ sub_19fe071c0 -> sub_19fcec194 : 432 -> 428
~ sub_19fe07404 -> sub_19fcec3d4 : 340 -> 336
~ sub_19fe07558 -> sub_19fcec524 : 368 -> 364
~ _ExtractURLQueries : 620 -> 616
~ _IMPathsForPlugInsWithExtension : 672 -> 668
~ __IMStatusMessageWithFormatAndVariables : 416 -> 412
~ _IMEnumerateArrayInRange : 348 -> 344
~ sub_19fe126e0 -> sub_19fcf7698 : 428 -> 424
~ _IMGetKeychainAuthToken : 424 -> 420
~ _IMSetKeychainAuthToken : 756 -> 752
~ _IMRemoveKeychainAuthToken : 408 -> 404
~ sub_19fe163b8 -> sub_19fcfb360 : 352 -> 348
~ sub_19fe1a73c -> sub_19fcff6e0 : 860 -> 852
~ sub_19fe1aa98 -> sub_19fcffa34 : 348 -> 344
~ sub_19fe1ce00 -> sub_19fd01d98 : 376 -> 372
~ sub_19fe1e518 -> sub_19fd034ac : 312 -> 308
~ sub_19fe1f54c -> sub_19fd044dc : 716 -> 712
~ __IMLogBacktraceForException : 1072 -> 1068
~ _IMLogSimulateCrashForProcess : 420 -> 440
~ _jw_string_to_uuid : 256 -> 252
~ sub_19fe27b44 -> sub_19fd0cadc : 316 -> 312
~ _IMFileLocationTrimFileName : 60 -> 76
~ _IMMMSPartCanBeSent : 1756 -> 1764
~ _IMMMSPartCombinationCanBeSent : 1680 -> 1676
~ sub_19fe33038 -> sub_19fd17fe0 : 360 -> 356
~ _IMSyncLoggingsPreferences : 2420 -> 2404
~ sub_19fe34b90 -> sub_19fd19b24 : 168 -> 180
~ sub_19fe34d10 -> sub_19fd19cb0 : 100 -> 112
~ sub_19fe34f68 -> sub_19fd19f14 : 168 -> 180
~ sub_19fe351a0 -> sub_19fd1a158 : 584 -> 580
~ sub_19fe354bc -> sub_19fd1a470 : 336 -> 332
~ sub_19fe3560c -> sub_19fd1a5bc : 100 -> 108
~ sub_19fe36b70 -> sub_19fd1bb28 : 288 -> 284
CStrings:
+ "Received one-way event in handler for service %s: %p"
- "Received unexpected event in hander for service %s: %p"
```
